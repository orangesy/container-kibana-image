# container-kibana-image
kibana docker buildfile 


## command
```
docker build -t local/kibana:4.4.2 .
docker run -e KIBANA_ES_URL="http://127.0.0.1:9200" -p 5601:5601 -d --name kibana local/kibana:4.4.2
```



## source
[pires/docker-kibana](https://github.com/pires/docker-kibana)
