# rocker-compose-mongo-cluster

Example of [rocker-compose](https://github.com/grammarly/rocker-compose) power.

To start mongo-cluster run:

    $ rocker-compose run -f compose.yml

This will start 9 mongo instances in 3 replica sets, 3 config servers and 1 mongos. 

You can access to mongo via `localhost:27017`.

## TODO

 - allow to configure amount of shards
 - allow to configure of amount nodes in replica set
 - allow to configure default namespace for cluster
 - add `wait_for` dependencies
