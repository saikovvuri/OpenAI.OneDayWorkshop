# OpenAI.Workshop

Azure OpenAI Workshop companion material. The workshop is currently designed to be delivered by an trainer, providing interactive and engaging sessions. 

Stay tuned, as we are excited to announce that it will soon transition into a self-paced training format, guided by an ***avatar*** for a more flexible learning experience.

This repository uses the [.NET SDK version Beta 2](https://www.nuget.org/packages/Azure.AI.OpenAI/2.0.0-beta.2). If you're looking for Beta 1 samples, you can find them [here](https://github.com/RobertEichenseer/OpenAI.OneDayWorkshop/tree/NET-SDK-Beta-1).

## Pre-Requisites

Be sure to have the following pre-requisites installed:

### Development Environment

- [VSCode](https://code.visualstudio.com/download)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download)
- [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=winget)
- [Git](https://git-scm.com)
- [Powershell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4)

### VSCode Extensions

- [c#](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit)
- [Polyglot NB](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode)
- [Azure CLI](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azurecli)
- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

### Azure Subscription with Azure OpenAI enabled

[Azure Subscription](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUNTZBNzRKNlVQSFhZMU9aV09EVzYxWFdORCQlQCN0PWcu)

## Agenda

***09:00 - 17:00***

| Time | Topic | Content |
|------|-------|---------|
|09:00 - 10:30 | **Welcome** | An [introduction](./00_IntroWorkshop/OpenAI-Workshop.pdf) of Azure Open AI for .net developer. |
|10:30 - 11:00 | **Intro** Create Environment | [Portal](https://portal.azure.com) or [CLI](./01_CreateEnvironment/01_Environment.ipynb)  |
|11:00 - 11:30 | **RAG** Completion | [Chat Completion HTTP](./02_RAG/02_01_ChatCompletion/01_ChatCompletionText_REST.ipynb) or [Chat Completion SDK](./02_RAG/02_01_ChatCompletion/) |
|11:30 - 12:30 | **RAG** Embeddings | [Text Embeddings](./02_RAG/02_02_Embedding/01_TextEmbeddings.ipynb) or [Image Embeddings](./02_RAG/02_02_Embedding/02_ImageEmbeddings.ipynb) and [Cosine Similarity](./02_RAG/02_02_Embedding/03_CosineSimilarity.ipynb) |
|12:30 - 13:00 |Break | |
|13:00 - 13:30 | **RAG** Vector DB | [AI Search](./02_RAG/02_03_VectorDB/01_AISearch.ipynb) |
|13:30 - 14:30 | **Function Calling** OpenAI |[Tools SDK](./03_FunctionCalling/01_OpenAI/01_Tools.ipynb) or [Semantic Kernel Planner](./03_FunctionCalling/02_SemanticKernel/03_Tools.ipynb) |
|14:30 - 15:00 |Break | |
|15:00 - 16:00 | **Agent Processing** Assistants API | [Simple Run](./04_Agent/01_Assistants/01_CreateRun.ipynb) |
|16:00 - 16:30 | **Tooling** Smeantic Kernel | [Plugins](./05_Tooling/01_SemanticKernel/01_Plugin.ipynb) or [Semantic Memory](./05_Tooling/01_SemanticKernel/02_SemanticMemory.ipynb) |
|16:30 - 17:00 | Wrap Up | Questions / Knowledge Check |

