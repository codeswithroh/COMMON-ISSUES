# Steps to resolve the issue of Azure invalid ID or client Secret in Azure devops

1) go to the service connections inside project settings
2) create a new service connection
	- connection type: Docker Registry
	- registry type: Azure container Registry
	- authentication type: Service Principal

3) after creating just copy the name of the new service connection
4) go to edit the azure-pipelines.yml inside the repo
5) past the new service connection name in: dockerRegistryServiceConnection

## VOILA 🎉🎊