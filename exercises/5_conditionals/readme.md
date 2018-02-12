Deploys a service plan, a web app, application insights and configures website always-on and appsettings.

.\Deploy-AzureResourceGroup.ps1 -StorageAccountName '' -ResourceGroupName 'DemoARM' -ResourceGroupLocation 'westeurope' -TemplateFile '5_conditionals/azuredeploy.json' -TemplateParametersFile '5_conditionals/azuredeploy.parameters.json' -ArtifactStagingDirectory '.' -DSCSourceFolder '.\DSC'