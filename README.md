# Microsoft SQL Server on Google Kubernetes Engine
(NOTE: replaced CLUSTERNMAE with clustername, REGION with region cluster is deployed in, PROJECT with projectid)

TO OBTAIN CLUSTER CREDENTIALS
gcloud container clusters get-credentials CLUSTERNAME --region REGION --project PROJECT

TO CREATE mssql (using mssql.yaml)
kubectl apply -f mssql.yaml

TO REMOVE:
kubectl delete deployment mssql

