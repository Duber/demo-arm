Deploys a web app with multiple slots per country

.\Deploy-AzureResourceGroup.ps1 -StorageAccountName '' -ResourceGroupName 'DemoARM' -ResourceGroupLocation 'westeurope' -TemplateFile '3_copy_loop_top_level/azuredeploy.json' -TemplateParametersFile '3_copy_loop_top_level/azuredeploy.parameters.json' -ArtifactStagingDirectory '.' -DSCSourceFolder '.\DSC'