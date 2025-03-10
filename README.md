# Portainer + Traefik

Colocar los siguientes comandos en orden de acuerdo a los pasos del video:

1.- ``sudo apt update``
2.- ``sudo apt upgrade -y``
3.- ``curl -fsSL https://get.docker.com -o get-docker.sh``
4.- ``sudo sh get-docker.sh``
5.- ``docker swarm init --advertise-addr=IP_SERVIDOR``
6.- ``docker network create --driver=overlay agent_network``
7.- ``docker network create --driver=overlay traefik_public``
8.- ``ls``
9.- ``mkdir portainer``
10.- ``ls``
11.- ``cd portainer/``
12.- ``nano portainer.yaml``
13.- ``docker stack deploy -c portainer.yaml portainer``
14.- ``nano portainer.yaml``
15.- ``docker stack deploy -c portainer.yaml portainer``




