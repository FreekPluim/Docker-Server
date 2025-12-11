FROM itzg/minecraft-server

WORKDIR /app

ENV EULA=true
ENV TYPE="FORGE"
ENV VERSION="1.20.1"
ENV FORGE_VERSION="47.4.0"

COPY mods/* /data/mods

RUN apt-get install jq

EXPOSE 25565