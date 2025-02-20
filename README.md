# Salesforce Deployment Tool 

Build deployments from a salesforce project and deploy to any org. Requires the [Salesforce Extension Pack](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode).

Initially Salesforce Deployment Helper Thanks to @Greg Lovelidge, This is an update of Greg Project with Salesforce new SF CLI requirement.

## Features

The following commands are included in the extension:

### Add to Deployment

Adds a source file or directory to a deployment.
![Add to Deployment](images/add-to-deployment.gif)

### Add Multiple files from Context to Deployment

Adds multiple source files or directories from the VS Code explorer to a deployment.
![Add to Deployment](images/add-to-deployment.gif)

### Add Multiple Files to Deployment

Adds multiple source files from OS Explorer to a deployment.
![Add Multiple Files to Deployment](images/add-multiple-to-deployment.gif)

### Remove From Deployment

Removes a source file or directory from a deployment.
![Remove From Deployment](images/remove-from-deployment.gif)

### Deploy to Org

Deploys the selected metadata to a salesforce environment. You'll be prompted to select a target org from a list of your authorized environments.
![Deploy](images/deploy-metadata.gif)

### View Metadata in Deployment

Shows all of the metadata stored in the current deployment.
![Deploy](images/view-metadata.gif)

### Clear Deployment

Removes all metadata in the deployment.
![Deploy](images/clear-deployment.gif)

## Requirements

Requires the latest version of the [Salesforce Extension Pack](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode).

## Bugs and Feedback
To report issues with Salesforce Deployment Tool, open a bug on GitHub. If you would like to suggest a feature, create a feature request on GitHub.

## Release Notes

### 1.0.0

Initial release of the Salesforce Deployment Helper. Includes the following features:

-   Add to deployment
-   Remove from deployment
-   Deploy to org
-   View current deployment
-   Clear current deployment

### 1.1.0

-   WARNING! Upgrading to version 1.0 from version 1.1 will empty your current deployment.
-   Added the "Add Multiple Files to Deployment" command.
-   Fixed issue where entire object was deployed when trying to deploy a single child metadata item (i.e., a custom field)
-   The deployment command now prompts you to select from a list of authorized environments.

### 2.0.0

-   Upgrading the project specs from SFDX CLI to SF CLI
-   Added the "Add Multiple files from Context to Deployment" Explorer Menu.