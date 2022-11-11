# My Resume on Azure.

## Frontend resources

The front-end is a static site with HTML, CSS, and JavaScript. It's static and has a visitor counter. The visitor counter data fetched via an API call to an Azure Function.
- This article explains how to make an API call with JavaScript and in a simple way how to use it to make an API call.
- Azure storage explorer is a handy tool to use when working with Storage Accounts
- This is how you can deploy static site to blob storage.

## Backend resources
The back-end is an HTTP triggered Azure Functions with Cosmos DB input and output binding. The Function is triggered, it retrieves the CosmosDB item, add +1 to it, and saves it and returns its value to the caller.
- Prerequisites for developing functions with visual code locally.
- Create a Cosmos DB account via command line or from the portal.
- Create an HTTP triggered Azure Function in Visual Studio Code.
- Azure Functions Cosmos DB bindings
- Retrieve a Cosmos DB item with Functions binding.
- Write to a Cosmos DB item with Functions binding.
- You'll have to enable CORS with Azure Functions locally and once it's deployed to Azure for you website to be able to call it.

## Testing Resources
- Testing Azure Functions.

## CI/CD Resources
- This is how you can deploy a blob storage static site with GitHub actions. Used in frontend.main.yml.
- This is how you can deploy an Azure Function to Azure with GitHub Actions. Used in backend.main.yml
- Implement .NET testing in GitHub Actions.
