FROM itzg/minecraft-server

ADD './mods' './mods'
ADD './config' './config'

ENV EULA=true
ENV TYPE="FORGE"
ENV VERSION="1.20.1"
ENV FORGE_VERSION="47.4.0"
ENV COPY_MODS_SRC="./mods"

RUN apt-get install jq

EXPOSE 25565