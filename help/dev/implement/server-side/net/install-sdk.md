---
title: Install the .NET SDK
description: Learn how t install the [!DNL Adobe Target] .NET SDK.
feature: APIs/SDKs
role: Developer
---
# Install the .NET SDK

The .NET SDK is distributed by [NuGet](https://www.nuget.org/packages/Adobe.Target.Client). To get started, add it as a dependency by installing via `Package Manage` or `.NET CLI`:

## Package Manager

>[!BEGINTABS]

>[!TAB Package Manager]

```csharp {line-numbers="true"}
Install-Package Adobe.Target.Client
```

>[!TAB .NET CLI]

```csharp {line-numbers="true"}
dotnet add package Adobe.Target.Client
```

>[!ENDTABS]

The open sourced code can be found at [https://github.com/adobe/target-dotnet-sdk](https://github.com/adobe/target-dotnet-sdk).