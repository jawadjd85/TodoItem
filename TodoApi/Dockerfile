FROM mcr.microsoft.com/dotnet/sdk:7.0

WORKDIR /app
copy . /app
EXPOSE 5001
RUN ["dotnet", "build"]
CMD ["dotnet", "run"]