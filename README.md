# Microsoft SQL Server on Google Kubernetes Engine
(NOTE: replaced CLUSTERNMAE with clustername, REGION with region cluster is deployed in, PROJECT with projectid)

gcloud container clusters get-credentials CLUSTERNAME --region REGION --project PROJECT
kubectl apply -f mssql.yaml
