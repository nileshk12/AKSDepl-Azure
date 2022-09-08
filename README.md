# AKSDepl-Azure
Deploying AKS clusters
This file shows how we can deploy aks clusters using the command line interface
az aks create --resource-group aks-rg --name my-test-cluster --node-count 2 --generate-ssh-key 
For the command we need to provide the required resource group name and cluster name and node count according to our need
Note- this is for free-trail account in Azure, so in prod env this things may change
