# Introduction 
ARM resource templates reporitory.

# Folder structure
- tempates > Ready-to-use templates
- templatesInDev > Templates still in development
- pipelines > Pipelines to deploy resouce templates
- testDeployments > Deployments to test resource templates

# Dev process
1. Create a Dev branch
2. Develop a new resource template
2. Create a params file for every Azure resource template
3. Test the deployment manually (single deployment)
4. Push Dev branch back to Azure DevOps
5. Create a pull request to merge changes into the main branch