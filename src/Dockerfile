FROM mcr.microsoft.com/dotnet/aspnet:5.0
COPY bin/Release/net5.0/publish/ src/
WORKDIR /src
EXPOSE 80
ENTRYPOINT ["dotnet", "k8s-tryouts.dll"]
