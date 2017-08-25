FROM microsoft/aspnetcore
ENV ASPNETCORE_URLS=http://+:80
WORKDIR /app
COPY ./dist /app
ENTRYPOINT ["dotnet", "netcore-api.dll"]