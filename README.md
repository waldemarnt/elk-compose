# Pre configured ELK (Elasticsearch, logstash and Kibana) 
ELK orchestration using docker and docker-compose.

**Setup**
Just clone this repository and change [this line of code](https://github.com/waldemarnt/elk-compose/blob/master/docker-compose.yml#L29) to be
your log directory.

The log syncronization is done by Filbeat and the configuration is allowed by the [configuration file](https://github.com/waldemarnt/elk-compose/blob/master/filebeat/filebeat.yml), 
just change the prospectors to read your own log files.

You will just need docker and docker-compose to be able to run this ELK.

**Running docker-compose:**

```docker-compose up```

If you need help, take a look here http://walde.co/2016/07/11/configurando-elk-com-docker-e-filebeat/
