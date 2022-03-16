# Azure DevOps Integration Example

## 1. Connect an AzDO Project to a GitHub Repository

**A project administrator must perform this operation.**

Following these [instructions][connect], connect your GitHub repository to your Azure Devops project.

This will enable the following key features ([documented here][features]):

- Link to Azure Boards work items from GitHub commits and PRs
- Link to a GitHub commits or PRs from Azure Boards

## 2. Setup Azure Pipelines to Build from a GitHub Repository

Pipelines are setup in the same way as a Azure DevOps repository. But when creating a new pipeline, under **Where is your code?**, select **GitHub**. You will then be redirected to GitHub to authorise.

[connect]: https://docs.microsoft.com/en-us/azure/devops/boards/github/connect-to-github?view=azure-devops#open-project-settingsgithub-connections
[features]: https://docs.microsoft.com/en-us/azure/devops/boards/github/link-to-from-github?view=azure-devops
