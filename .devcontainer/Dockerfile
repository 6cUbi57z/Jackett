FROM mcr.microsoft.com/dotnet/sdk:5.0-alpine

# Create and use a "dev" user account to avoid permissions issues
RUN addgroup -S dev && adduser -S dev -G dev -s /bin/ash
USER dev
