# Azure Synapse SQL Pool Database Project

Example of a [SQL database project](https://learn.microsoft.com/en-us/sql/tools/sql-database-projects/sql-database-projects?view=sql-server-ver16&WT.mc_id=DP-MVP-5004032%3Fview%3Dsql-server-ver16) that deploys to Azure Synapse Dedicated SQL Pool in Azure DevOps. Based on a blog post I wrote called '[Create a dacpac for an Azure Synapse Analytics dedicated SQL Pool using Azure DevOps](https://bit.ly/3HQOfFp)'.

In addition, you can watch me demo how this can be done in the [January 2023 edition of the Azure Synapse Analytics and Microsoft MVP series](https://www.youtube.com/watch?v=Dcpd4Z783Zs).

A brief overview is below. However, there is also a [wiki for this project](https://github.com/kevchant/AzureDevOps-AzureSynapseSQLPool/wiki).

It uses a YAML pipeline, which you can find in the AzureDevOpsTemplates folder.

In order to use it in Azure Pipelines you can either import or fork this repository into another GitHub repository or into Azure Repos.

Afterwards, you can select the YAML file in Azure Pipelines and tailor the pipeline to suit your needs.

This repository is provided "as is" based on the [MIT license](https://opensource.org/licenses/MIT). Basically, I am not responsible for your use of it.
