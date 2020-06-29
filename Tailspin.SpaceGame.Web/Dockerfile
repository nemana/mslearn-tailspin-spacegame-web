FROM mcr.microsoft.com/dotnet/core/aspnet:3.1 AS base
WORKDIR /app
EXPOSE 80
EXPOSE 443
COPY /bin/Release/publish .
ENTRYPOINT ["dotnet", "Tailspin.SpaceGame.Web.dll"]