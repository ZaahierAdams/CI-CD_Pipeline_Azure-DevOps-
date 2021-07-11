# CI/CD Pipeline in Azure DevOps 
Continuous Integration/ Continuous Deployment Pipeline configuration in Azure DevOps  for Function Application. 

## About
Consists of two stages 
- Build
	- Builds package
	- Archives files
	- Publishes Archive
- Deploy 
	- Download Artifact 
 	- Deploys function app 

## Configurations 
You may decide to reconfigure the entire pipeline . 
However, if you wish to use this pipeline, change ``` azureSubscription``` and ``` appName``` is the ```Deploy``` stage. 


