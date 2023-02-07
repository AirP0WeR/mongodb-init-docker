This is baisic instructions to run docker compose MosgoDB + Mongo Express.

Add .env file to the path with example

```
MONGO_ROOT_USER="rootUser"
MONGO_ROOT_PASSWORD="password"

MONGOEXPRESS_LOGIN="rootUser"
MONGOEXPRESS_PASSWORD="password"
```

To start
WLS2
```
docker-compose -f docker-compose.yml up
```
Ubuntu 
```
docker compose -f docker-compose.yml up

```