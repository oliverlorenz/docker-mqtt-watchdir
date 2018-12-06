# docker-mqtt-watchdir

this is the dockerized version of [oliverlorenz/mqtt-watchdir](https://github.com/oliverlorenz/mqtt-watchdir). For detailed information have a look there.

# usage

```
docker run \ 
  -d \
  -e "MQTTHOST=test.mosquitto.org" \
  -e "MQTTWATCHDIR=/watch" \
  -v /path/to/directory:/watch
  oliverlorenz/mqtt-watchdir
```