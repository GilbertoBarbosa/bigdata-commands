Authentication
```
gcloud auth application-default login
```

Init
```
gcloud init
gcloud components update
```

List storage items
```
gsutil ls
```

Copy files from local to gcloud
```
gsutil -m cp -r <local> <gs://bucket>
```

Update files from local to gcloud 
```
gsutil -m rsync -r <local> <gs://bucket>
```

Remove file
```
gsutil rm <gs://bucket/folder/file>
```

Change permissios (example)
```
gsutil acl -r ch -u AllUsers:R <gs://bucket/folder/file>
```

List instances
```
gcloud compute instances list
```

List images
```
gcloud compute images list
```

Start/Stop instance
```
gcloud compute instances start <instanceName>
gcloud compute instances stop <instanceName>
```

Create image
```
gcloud compute images create <imageName> --source-disk <instanceName>
```

gcloud Update
```
gcloud components update
```

gcloud deploy
```
gcloud functions deploy <functionName> --runtime --trigger
```

Functions logs
```
gcloud functions logs read <functionName>
```

List functions
```
gcloud functions list
```

Detail function
```
gcloud functions describe <functionName>
```

Publish message
```
gcloud pubsub topics publish <functionName> --message <message>
```

Create topic
```
gcloud pubsub topics create <topicName>
```

Generate temporary credentials docker
```
gcloud auth configure-docker
```

List containers
```
gcloud container clusters list
```

List regions
```
gcloud app regions list
```

Create app
```
gcloud app create --project=<project> --region=<region>
```
