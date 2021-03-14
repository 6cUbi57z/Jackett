FROM mcr.microsoft.com/dotnet/sdk:5.0-alpine

# Install yamllint
RUN apk add python3 py3-pip --no-cache
RUN python3 -m pip install yamllint

# Create and use a "dev" user account to avoid permissions issues
RUN addgroup -S dev && adduser -S dev -G dev -s /bin/ash
USER dev
