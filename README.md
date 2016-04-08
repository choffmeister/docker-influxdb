# docker-influxdb

```bash
$ docker run -d -p 8083:8083 -p 8086:8086 choffmeister/influxdb

$ docker run -d --volume=/var/influxdb:/data -p 8083:8083 -p 8086:8086 choffmeister/influxdb
```
