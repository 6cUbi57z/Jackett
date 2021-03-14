# [Choice] .NET version: 5.0, 3.1, 2.1
ARG VARIANT=5.0
FROM mcr.microsoft.com/vscode/devcontainers/dotnet:0-${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
     && apt-get -y install --no-install-recommends python3 python3-pip

RUN python3 -m pip install yamllint
