# stack-docker
Meta-project for the Elastic Docker images.

## Pre-requisites
Download MySQL connector from and place it on `lib/`:
- https://dev.mysql.com/downloads/connector/j/

Place the DDL script for the source DB in `scripts/`.


## Quick Demo
To create a demonstration Elastic stack with
Elasticsearch, Kibana, and Logstash, execute:

`ELASTIC_VERSION=5.5.2 TAG=5.5.2 docker-compose up` 

Point a browser at `http://localhost:5601` to see the results.

Log in with `elastic` / `changeme`.
