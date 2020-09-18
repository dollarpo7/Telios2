# Telios2

This Project contains the following files:

1. A Dockerfile
2. An ARM Teamplate (IAC) to deploy a An Azure Container Registry, 2 Kubernetes Clusters (Dev and Prod)
3. An Azure DevOps multi-stage YAML file
4. Conncet to the Clusteras explained here: https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough#connect-to-the-cluster
5. Test the Application: kubectl get service azure-vote-front --watch using the PUBLIC IP address 


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdollarpo7%2FTelios2%2Fmaster%2Fazuredeploy.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton"/>
</a>
