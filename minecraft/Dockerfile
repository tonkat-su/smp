FROM ghcr.io/voltaire/spigot-server:1.16.4

WORKDIR /srv/
RUN echo 'eula=true' > /srv/eula.txt
ADD run /srv/run
ADD whitelist.json /srv/whitelist.json
ADD ops.json /srv/ops.json
ADD bukkit.yml /srv/bukkit.yml
ADD spigot.yml /srv/spigot.yml
ADD server.properties /srv/server.properties
ENTRYPOINT ["/bin/sh", "/srv/run"]
