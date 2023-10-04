# Microsoft SQL Server on Google Kubernetes Engine

TO OBTAIN CLUSTER CREDENTIALS
(NOTE: replaced CLUSTERNAME with clustername, REGION with region cluster is deployed in, PROJECT with projectid)

gcloud container clusters get-credentials CLUSTERNAME --region REGION --project PROJECT

TO CREATE mssql (using mssql.yaml)
kubectl apply -f mssql.yaml

TO REMOVE:
kubectl delete deployment mssql

