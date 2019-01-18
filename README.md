## Port

```bash
dotnet new webapi --language F# --output src/DotNetPort
dotnet run --project src/DotNetPort/DotNetPort.fsproj -- --urls=http://localhost:9999
open http://localhost:9999
```