# Node.js Redis
Uses Docker to start node application and redis server together

## Node app
Exposed to port 8081

## Redis server
'visit' is used to store and show the number of times '/' is accessed.


## Docker
Use the command `docker compose up --build` to start the redis server and the node app together
`--build` argument is necessary to build the node application

