## Installation

gcloud compontents update

## Config
# Init the env
```
gcloud init 
gcloud auth login
gcloud auth application-default login
gcloud config set project PROJECT_ID
set GOOGLE_APPLICATION_CREDENTIALS=D:\Bitbucket\all.configuration\pwujczyk1-serviceaccount.json
$env:GOOGLE_APPLICATION_CREDENTIALS="D:\Bitbucket\all.configuration\pwujczyk1-serviceaccount.json”
```
## Projects
```
gcloud projects list
```

## VM
```
gcloud compute instances list

gcloud compute ssh learning-cloud-demo
```
## SQL

gcloud sql instances list

gcloud sql users set-password root --password "PASSWORD" --instance wordpress-db

To conect to MySQL you need to setup the proxy.
My sql is working on port 3306
```
connection string (after intances) can be found on the details of the instance
.\cloud_sql_proxy.exe -instances=pwujczyklearning:us-central1:pwwordpressmysql=tcp:3306

```
