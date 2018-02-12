Deploys a web app with multiple slots per country

.\Deploy-AzureResourceGroup.ps1 -StorageAccountName '' -ResourceGroupName 'DemoARM' -ResourceGroupLocation 'westeurope' -TemplateFile '4_copy_loop_property/azuredeploy.json' -TemplateParametersFile '4_copy_loop_property/azuredeploy.parameters.json' -ArtifactStagingDirectory '.' -DSCSourceFolder '.\DSC'