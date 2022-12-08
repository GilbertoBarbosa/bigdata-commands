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

Get permissions
```
gsutil acl get <bucket>
```

Change lifecycle bucket
```
gsutil lifecycle set <file.json> <bucket>
```

Change permissions (example)
```
gsutil acl -r ch -u AllUsers:R <gs://bucket/folder/file>
```

Change bucket for web
```
gsutil web set -m index.html -e 404.html <bucket>
```

Create bucket
```
gsutil mb gs://<bucketName>
```

Get credentials
```
gcloud container clusters get-credentials <clusterName> --zone --project
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
gcloud <functionName> services deploy  <file>.yaml
```

Functions logs
```
gcloud functions logs read <functionName>
```

List functions
```
gcloud functions list
```

List projects
```
gcloud projects list
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

Install kubernets components
```
gcloud components install kubectl
```

Apply kubernets
```
kubectl apply -f deployment.yaml
```

List kubernets services
```
kubectl get service
```
