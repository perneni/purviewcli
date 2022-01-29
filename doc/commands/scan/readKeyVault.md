# pv scan readKeyVault
[Command Reference](../../../README.md#command-reference) > [scan](./main.md) > readKeyVault

## Description
Gets key vault information

## Syntax
```
pv scan readKeyVault --keyVaultName=<val>
```

## Required Arguments
*None*

## Optional Arguments
*None*

## API Mapping
Scanning Data Plane > Key Vault Connections > [Get](https://docs.microsoft.com/en-us/rest/api/purview/scanningdataplane/key-vault-connections/get)
```
GET https://{accountName}.purview.azure.com/scan/azureKeyVaults/{keyVaultName}
```

## Examples
```powershell

```