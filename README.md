# 7th-LAB-Azure-Search-Index-with-Knowledge-Store
To deploy the template 
```code 
az group create --name <resource-group-name> --location eastus

```

```code
az deployment group create \
  --resource-group <resource-group-name> \
  --template-file template.json \
  --parameters uniqueSuffix=<your-suffix>

```