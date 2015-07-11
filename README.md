# openarena-server-docker
openarena server docker

# To run

create /opt/openarena on the server where you run docker. Copy server.cfg to this folder and make your changes


docker run -d -p 27960:27960/udp -p 27950:27950/udp -p 27960:27960/tcp -v /opt/openarena:/root/.openarena/baseoa ehlers320/openarena-server-docker


