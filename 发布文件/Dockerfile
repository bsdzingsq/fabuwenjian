FROM microsoft/aspnetcore:2.0 AS base
WORKDIR /app
EXPOSE 80

FROM microsoft/aspnetcore-build:2.0 AS build
WORKDIR /src
COPY . .
ENTRYPOINT ["dotnet", "ZsqApp.Core.WebApi.dll"]