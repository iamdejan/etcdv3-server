# etcdv3-server
Docker Compose for Etcd V3.

## Quickstart

### Using Docker Compose
1) `docker-compose -f etcdv3-docker-compose.yml up`

### Using Docker Swarm
1) `docker swarm init`
2) `docker stack deploy -c etcdv3-docker-compose.yml etcd`
