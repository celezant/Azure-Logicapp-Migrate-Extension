# Migrate Logic Apps for Azure Logic App Workflow Migration

## Overview
This Azure DevOps Extension simplifies the process of migrating Logic Apps Workflows from one environment to another within Azure. It streamlines the migration of your workflows, making it easy to transfer Logic Apps seamlessly.

## Pre-requisites
1. An Active Service Principle with appropriate permissions for accessing Azure Logic Apps both Source and the Destination Logic Apps.

## Supported Platforms
```
This task is compatible with Windows OS agents only. 
```
Please ensure that you have Windows agents available in your Azure DevOps environment before incorporating this task into your pipelines.

## Configure the Task
To use this extension, follow these steps:

1. Add the task to your Build or Release pipeline.
2. Select the **+ Add tasks -> Marketplace -> Migrate Logic Apps for Workflow Migration**.
3. Provide the necessary details as outlined in the table below.

## Extension Overview
This extension automates and facilitates the migration of Logic Apps Workflows between different environments within Azure.

## Task Usage
Configure the task using the following options:

| Option                           | Description                                            |
|----------------------------------|--------------------------------------------------------|
| Azure Service Connection         | Requires access to the source and destination Azure environments. |
| Source Subscription ID           | Subscription ID for the source Logic App environment. |
| Source Resource Group            | Resource Group Name for the source Logic App environment. |
| Source Logic App Name            | Name of the Logic App to be migrated. |
| Destination Subscription ID      | Subscription ID for the destination Logic App environment. |
| Destination Resource Group       | Resource Group Name for the destination Logic App environment. |
| Destination Logic App Name       | Name to be assigned to the migrated Logic App. |

## Notes
Ensure that the necessary permissions and access are granted for the Logic App migration process.
It only supports Windows OS Agent.

## Highlighted Features
1. Simplified Logic App migration.
2. Intuitive setup and execution.
3. Facilitates seamless transfer of workflows.

## Releases
- v1.0.0 (August 2023): Streamline Logic App migration between Azure environments.
