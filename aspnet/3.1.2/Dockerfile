FROM mcr.microsoft.com/dotnet/core/aspnet:3.1.2-alpine3.11
LABEL MAINTAINER=peymanpn@yahoo.com
LABEL purpose="Set invariant culture off to use with sql server"
LABEL comments="Image for run asp.net core 3.1.2"
# Install cultures (same approach as Alpine SDK image)
RUN apk update && apk add --no-cache curl icu-libs
# Disable the invariant mode (set in base image)
ENV DOTNET_SYSTEM_GLOBALIZATION_INVARIANT=false