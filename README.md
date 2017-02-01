Docker Image for Cloudera Director
=================

# **How to use it** #

### 1. Pull Docker Image ###

    docker pull andry1/cloudera-director

### 2. Run it ###

    docker run -it --name director -h director -p 7189:7189 andry1/cloudera-director

### 4. Get to a shell in the running container ###

    docker exec -it director /bin/bash

### 5. Check Docker Instance Logs ###

    docker logs director
