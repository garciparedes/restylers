FROM mcr.microsoft.com/dotnet/core/sdk
RUN dotnet tool install -g dotnet-format
ENV PATH="/root/.dotnet/tools:${PATH}"
RUN mkdir -p /code
WORKDIR /code
COPY files /
CMD ["dotnet", "format", "--help"]
