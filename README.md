# elk

Configuration Elasticsearch, Logstash, Kibana.
1.First we need to create file docker-compose.yml
2. Second inside the folder were we create docker-compose find the folder logstash
3. Inside the folder we found file  logstash.conf which we can edit as we need. A simple example of its configuration is given in commit.
If you need to send some logs from another server we can use filebeat with custom configuration example in file filebeat.yml
