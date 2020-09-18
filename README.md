# Telios2

This Project contains the following files:

1. A Dockerfile
2. An ARM Teamplate (IAC) to deploy a An Azure Container Registry, 2 Kubernetes Clusters (Dev and Prod)
3. A Kubernetes Manifest YAML file.
4. An Azure DevOps multi-stage YAML file



<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdollarpo7%2FTelios2%2Fmaster%2Fazuredeploy.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton"/>
</a>


<p> <strong> ACTION PLAN </strong> </p>

1. Deploy the ARM Template above.

2. Using Azure DevOps as our CI/CD import the repository.

3. Create Enviroments under Pipelines i.e development and production.

4. Run the multi-stage YAML pipeline using parameters fron your Infrastructure.

5. Connect to the K8s Clusters explained here: https://docs.microsoft.com/en-us/azure/aks/kubernetes-walkthrough#connect-to-the-cluster.

6. Test the Application using : <code> kubectl get service azure-vote-front --watch </code> using the PUBLIC IP address.
