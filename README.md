# ELK-Logging
ELK Logging For Dockerized App

In the text File
  - Commands for starting the ELK containers one by one.
  - Also a sample docker start command for a container with syslog variable to feed data to the logstash.
  
In Docker Compose File
  - All the threecomponents are configures to start things with a docker-compose up command.
  - But sometimes i have to restart them individually once again (some wierd connectivity issues).
  
Logstash.conf file
  - Simple config to take TCP input from containers through port 5000 as syslogs
  - Output to Elasticsearch 9200 port.
