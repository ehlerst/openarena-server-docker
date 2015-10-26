# openarena-server-docker
openarena server docker

# To run (with docker directly)

create /opt/openarena on the server where you run docker. Copy config/server.cfg to this folder and make your changes


docker run -d -p 27960:27960/udp -p 27950:27950/udp -v /opt/openarena:/root/.openarena/baseoa ehlers320/openarena-server-docker


# To run (with docker-compose)
Make any customizations to `config/server.cfg` you want.

Run `docker-compose up -d`

