## Installation

gcloud compontents update

## Config
gcloud auth login

gcloud config set project PROJECT_ID

set GOOGLE_APPLICATION_CREDENTIALS=D:\Bitbucket\all.configuration\pwujczyk1-serviceaccount.json

$env:GOOGLE_APPLICATION_CREDENTIALS="D:\Bitbucket\all.configuration\pwujczyk1-serviceaccount.json”

## Projects
gcloud projects list

## VM
gcloud compute instances list

gcloud compute ssh learning-cloud-demo

## SQL

gcloud sql instances list

gcloud sql users set-password root --password "PASSWORD" --instance wordpress-db

.\cloud_sql_proxy.exe -instances=pwujczyk1:us-central1:pwwordpress-db=tcp:3306