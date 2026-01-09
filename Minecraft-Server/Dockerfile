FROM itzg/minecraft-server

ADD './mods' './mods'

ENV EULA=true
ENV TYPE="NEOFORGE"
ENV VERSION="1.21.1"
ENV NEOFORGE_VERSION="21.1.218"
ENV COPY_MODS_SRC="./mods"
ENV ports="25565:25565"

RUN apt-get install jq

EXPOSE 25565