FROM mcr.microsoft.com/dotnet/core/asp:3.1
WORKDIR /app
COPY bin\Release\netcoreapp3.1/publish
ENTRYPOINT["dotnet","AspNetCoreMvc.dll"]