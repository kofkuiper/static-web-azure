# Deploy Static Web to Azure App Service with Azure Cloud Shell

### 1. Install Azure cli
```
# Mac
$ brew update && brew install azure-cli  
```

### 2. Login to Azure
```
$ az login
```

### 3. Deploy
```
$ az webapp up --location southeastasia --name nineo --html
```