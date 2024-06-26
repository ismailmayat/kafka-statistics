FROM mcr.microsoft.com/dotnet/core/runtime:2.1
WORKDIR /app
COPY ./bin/Release/netcoreapp2.1/publish /app
ENTRYPOINT ["dotnet", "/app/example-producer-prometheus-statistic-handler.dll"]
