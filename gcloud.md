Init
```
gcloud init
```

List storage items
```
gsutil ls
```

Copy files from local to gcloud
```
gsutil -m cp -r <local> <gs://bucket>
```

Remove file
```
gsutil rm <gs://bucket/folder/file>
```

Change permissios (example)
```
gsutil acl -r ch -u AllUsers:R <gs://bucket/folder/file>
```
