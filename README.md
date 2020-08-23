# ntopng-influxdb-grafana

## Requirements

- Docker
- Docker-Compose

## Deploy

```
docker-compose up -d
```

## Switch to Influxdb as Time Series DB

1. Login to Ntopng via http://localhost:3000

2. Go to preferences

3. Select Time Series

4. Set Influxdb URL to http://localhost:8086

5. Login to Grafan via http://localhost:3333

6. Add Influxdb as data source. URL is http://influxdb:8086 with DB name ntopng and no username nor password.

7. Create your Ntopng dashbaords in Grafana. 

