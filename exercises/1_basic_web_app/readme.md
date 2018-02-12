Deploys a service plan with a web app with a slot

.\Deploy-AzureResourceGroup.ps1 -StorageAccountName '' -ResourceGroupName 'DemoARM' -ResourceGroupLocation 'westeurope' -TemplateFile '1_basic_web_app/azuredeploy.json' -TemplateParametersFile '1_basic_web_app/azuredeploy.parameters.json' -ArtifactStagingDirectory '.' -DSCSourceFolder '.\DSC'