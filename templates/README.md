# Templates

Here are templates for creating the CosmosDB database.

```
az group create --name TestCosmosDB --location northeurope
az deployment group create --name CosmoDB --resource-group TestCosmosDB --template-file cosmodb.json --parameters cosmodb.parameters.json
```
