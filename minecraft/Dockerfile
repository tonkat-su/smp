FROM ghcr.io/voltaire/spigot-server:1.16.4
LABEL org.opencontainers.image.source https://github.com/tonkat-su/smp

WORKDIR /srv/
RUN echo 'eula=true' > /srv/eula.txt
ADD run /bin/run
ENTRYPOINT ["/bin/sh", "/bin/run"]
