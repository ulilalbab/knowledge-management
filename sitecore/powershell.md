# Powershell

Script Compilation to make faster process

### Copy Content From EN to another Language

```csharp
$root ="Item-ID"
@(Get-Item -Path $root) + @(Get-ChildItem -Path $root -recurse) |
Add-ItemLanguage -Language "en" -TargetLanguage "fr-FR" -IfExist Skip
```

It will copy include children, change If Statement if needed "Overwrite"

### Convert Item ID to Tem Path

To Convert Item ID to URL Path on Sitecore

```csharp
$itemId = Get-Item "Item-ID",
"Item-ID",
"Item-ID"
$itemId.Paths.FullPath
```

