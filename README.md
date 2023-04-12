## Project Title 
#### Setting up a CiCD pipeline using Azure DevOps Git and Docker to deploy a web application to Azure Container

## Project Live link
[adora-cloud-warriors-2](https://adora-coud-warriors.azurewebsites.net/)

## Project in Steps

- Create a new project in Azure DevOps and add a Git repository for your web application code.

- Set up a build pipeline in Azure DevOps to build your Docker image. The build pipeline should include the following steps:

  > - Checkout your Git repository
  > - Build your Docker image using a Dockerfile
  > - Push the Docker image to a container registry (e.g. Azure Container Registry)
  > - Set up a release pipeline in Azure DevOps to deploy your Docker image to Azure Container. The release pipeline should include the following steps:
  > - Connect to your container registry
  > - Pull the Docker image from the container registry
  > - Deploy the Docker image to Azure Container


- Set up the necessary Azure infrastructure to host your web application in a container. This may include creating an Azure Container Instance, a Kubernetes cluster, or other Azure resources.

- Configure your web application to run in the container, and make any necessary changes to your application code to ensure it can run in a containerized environment.

- Test CI/CD pipeline by making changes to your web application code and verifying that the changes are successfully built, tested, and deployed to Azure Container.

<img width="1200" alt="Screenshot 2023-03-05 at 14 45 40" src="https://raw.githubusercontent.com/pidoxy/Architecture-Diagrams/main/Azure%20DevOps%20CI/CD-Page-2.drawio.svg">
