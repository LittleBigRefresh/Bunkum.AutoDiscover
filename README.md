# Warning! This repository is no longer updated.
This project has moved development and source code to the central Bunkum repository.

You can find the new source code location under [LittleBigRefresh/Bunkum](https://github.com/LittleBigRefresh/Bunkum).

# Bunkum.AutoDiscover
An implementation of AutoDiscover for Bunkum.

See documentation here on this API here: https://littlebigrefresh.github.io/Docs/autodiscover-api

## Usage

```csharp
using Bunkum.AutoDiscover.Extensions;

server.AddAutoDiscover(serverBrand: "Refresh", baseEndpoint: "/lbp");
```
