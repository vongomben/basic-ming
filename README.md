# basic-ming
Basic ming (MQTT, InfluDB, Node-RED, Grafana) server for educational purposes

To run it: 

> docker compose up -d


## mosquitto.conf 
```
# ./mosquitto/config/mosquitto.conf
persistence true
persistence_location /mosquitto/data/
log_dest file /mosquitto/log/mosquitto.log
listener 1883
allow_anonymous true

```
