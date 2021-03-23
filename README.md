# kafka-docker-arm64

change for apple silicon use

fork from https://github.com/wurstmeister/kafka-docker

change zk docker image and glibc

## Usage

Start a cluster:

- ```docker-compose up -d```

Add more brokers:

- ```docker-compose scale kafka=3```

Destroy a cluster:

- ```docker-compose stop```
