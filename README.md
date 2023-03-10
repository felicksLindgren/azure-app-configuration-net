# Getting Started with Azure App Configuration

## Add Connectionstring to User Secrets
```bash
dotnet user-secrets init
dotnet user-secrets set ConnectionStrings:AppConfig "<your_connection_string>"
```

## Packages to install

```bash
dotnet add package Microsoft.Azure.AppConfiguration.AspNetCore
dotnet add package Microsoft.FeatureManagement.AspNetCore
```