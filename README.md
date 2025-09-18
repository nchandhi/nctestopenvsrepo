# Conversation knowledge mining solution accelerator

Gain actionable insights from large volumes of conversational data by identifying key themes, patterns, and relationships. Using Azure AI Foundry, Azure AI Content Understanding, Azure OpenAI Service, and Azure AI Search, this solution analyzes unstructured dialogue and maps it to meaningful, structured insights.

Capabilities such as topic modeling, key phrase extraction, speech-to-text transcription, and interactive chat enable users to explore data naturally and make faster, more informed decisions.

Analysts working with large volumes of conversational data can use this solution to extract insights through natural language interaction. It supports tasks like identifying customer support trends, improving contact center quality, and uncovering operational intelligence—enabling teams to spot patterns, act on feedback, and make informed decisions faster.

<br/>

<div align="center">
  
[**SOLUTION OVERVIEW**](#solution-overview)  \| [**QUICK DEPLOY**](#quick-deploy)  \| [**BUSINESS SCENARIO**](#business-scenario)  \| [**SUPPORTING DOCUMENTATION**](#supporting-documentation)

</div>
<br/>

<h2><img src="./documents/Images/ReadMe/solution-overview.png" width="48" />
Solution overview
</h2>

Leverages Azure AI Content Understanding, Azure AI Search, Azure OpenAI Service, Semantic Kernel, Azure SQL Database, and Cosmos DB to process large volumes of conversational data. Audio and text inputs are analyzed through event-driven pipelines to extract and vectorize key information, orchestrate intelligent responses, and power an interactive web front-end for exploring insights using natural language.

### Solution architecture
|![image](./documents/Images/ReadMe/solution-architecture.png)|
|---|

### Additional resources

[Technical Architecture](./documents/TechnicalArchitecture.md)

<br/>

### Key features
<details open>  
<summary>Click to learn more about the key features this solution enables</summary>  

- **Mined entities and relationships** <br/>  
Azure AI Content Understanding and Azure OpenAI Service extract entities and relationships from unstructured data to create a knowledge base.

- **Processed data at scale** <br/>  
Microsoft Fabric processes conversation data at scale, generating vector embeddings for efficient retrieval using the RAG (Retrieval-Augmented Generation) pattern.

- **Visualized insights** <br/>  
An interactive dashboard delivers actionable insights and trends through rich data visualizations.

- **Natural language interaction** <br/>  
Azure OpenAI Service enables contextual question-answering, conversation capabilities, and chart generation, all powered by the RAG pattern.

- **Actionable insights** <br/>  
Summarized conversations, topic generation, and key phrase extraction support faster decision-making and improved productivity.

</details>



<br /><br />
<h2><img src="./documents/Images/ReadMe/quick-deploy.png" width="48" />
Quick deploy
</h2>

### How to install or deploy
Follow the quick deploy steps on the deployment guide to deploy this solution to your own Azure subscription.

[Click here to launch the deployment guide](./documents/DeploymentGuide.md)
<br/><br/>


| [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/microsoft/Conversation-Knowledge-Mining-Solution-Accelerator) | [![Open in Dev Containers](https://img.shields.io/static/v1?style=for-the-badge&label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/microsoft/Conversation-Knowledge-Mining-Solution-Accelerator) | [![Open in Visual Studio Code Web](https://img.shields.io/static/v1?style=for-the-badge&label=Visual%20Studio%20Code%20(Web)&message=Open&color=blue&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/azure/?vscode-azure-exp=foundry&agentPayload=eyJiYXNlVXJsIjogImh0dHBzOi8vcmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbS9uY2hhbmRoaS9uY3Rlc3RvcGVudnNyZXBvL3JlZnMvaGVhZHMvbWFpbi9maWxlcyIsICJpbmRleFVybCI6ICIvbmNpbmRleC5qc29uIiwgInZhcmlhYmxlcyI6IHsiYWdlbnRJZCI6ICIiLCAiY29ubmVjdGlvblN0cmluZyI6ICIiLCAidGhyZWFkSWQiOiAiIiwgInVzZXJNZXNzYWdlIjogIiIsICJwbGF5Z3JvdW5kTmFtZSI6ICIiLCAibG9jYXRpb24iOiAiIiwgInN1YnNjcmlwdGlvbklkIjogIiIsICJyZXNvdXJjZUlkIjogIiIsICJwcm9qZWN0UmVzb3VyY2VJZCI6ICIiLCAiZW5kcG9pbnQiOiAiIn0sICJjb2RlUm91dGUiOiBbImFpLXByb2plY3RzLXNkayIsICJweXRob24iLCAiZGVmYXVsdC1henVyZS1hdXRoIiwgImVuZHBvaW50Il19) |
|---|---|---|

<br/>

> ⚠️ **Important: Check Azure OpenAI Quota Availability**
 <br/>To ensure sufficient quota is available in your subscription, please follow [quota check instructions guide](./documents/QuotaCheck.md) before you deploy the solution.

<br/>

### Prerequisites and costs
To deploy this solution accelerator, ensure you have access to an [Azure subscription](https://azure.microsoft.com/free/) with the necessary permissions to create **resource groups, resources, app registrations, and assign roles at the resource group level**. This should include Contributor role at the subscription level and  Role Based Access Control role on the subscription and/or resource group level. Follow the steps in [Azure Account Set Up](./documents/AzureAccountSetUp.md).

Here are some example regions where the services are available: East US, East US2, Australia East, UK South, France Central.

Check the [Azure Products by Region](https://azure.microsoft.com/en-us/explore/global-infrastructure/products-by-region/?products=all&regions=all) page and select a **region** where the following services are available.

Pricing varies by region and usage, so it isn't possible to predict exact costs for your usage. The majority of Azure resources used in this infrastructure are on usage-based pricing tiers. However, some services—such as Azure Container Registry, which has a fixed cost per registry per day, and others like Cosmos DB or SQL Database when provisioned—may incur baseline charges regardless of actual usage.

Use the [Azure pricing calculator](https://azure.microsoft.com/en-us/pricing/calculator) to calculate the cost of this solution in your subscription. 

Review a [sample pricing sheet](https://azure.com/e/67c83432524440d98ccb8c92ebd3e2f7) in the event you want to customize and scale usage.

_Note: This is not meant to outline all costs as selected SKUs, scaled use, customizations, and integrations into your own tenant can affect the total consumption of this sample solution. The sample pricing sheet is meant to give you a starting point to customize the estimate for your specific needs._

<br/>


