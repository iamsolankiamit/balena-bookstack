FROM linuxserver/bookstack:v0.29.3-ls99

COPY 50-config /etc/cont-init.d/50-config
RUN chmod 0755 /etc/cont-init.d/50-config

COPY 98-redis /etc/cont-init.d/98-redis
RUN chmod 0755 /etc/cont-init.d/98-redis