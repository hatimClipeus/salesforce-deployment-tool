# Change Log

All notable changes to the "SFDT" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

### 1.0.0 SFDH

Initial release of the Salesforce Deployment Helper. Includes the following features:

-   Add to deployment
-   Remove from deployment
-   Deploy to org
-   View current deployment
-   Clear current deployment

### 1.1.0 SFDH

-   WARNING! Upgrading to version 1.0 from version 1.1 will empty your current deployment.
-   Added the "Add Multiple Files to Deployment" command.
-   Fixed issue where entire object was deployed when trying to deploy a single child metadata item (i.e., a custom field)
-   The deployment command now prompts you to select from a list of authorized environments.

### 2.0.0 SFDT

Initial release of the Salesforce Deployment Tool. Includes the following features:

-   Upgrading the project specs from SFDX CLI to SF CLI
-   Added the "Add Multiple files from Context to Deployment" Explorer Menu.