FROM mcr.microsoft.com/dotnet/core/aspnet:3.1-buster-slim as base

WORKDIR /app

EXPOSE 80

COPY . .
ENTRYPOINT ["dotnet","mysql.web.dll"]