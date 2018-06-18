# ELK
This repo contains config for log analysis using ELK stack. Logstash acts as any ETL tool, it takes in server logs as input. We can define filter for formattihg the data and this data is then passed on elsaticsearch.
In Kibana, the log information recieved is displayed in the discover section. Futher dashboard can be created to visualise and analyse logs. 

For mac users:<br>
To install ELK: ./install<br>
Copy the config folder
Put sample logs in logstash root directory<br>
To run ELK: ./run<br>

Ports:<br>
Elasticsearch: 9200<br>
Logstash: 9600<br>
Kibana: 5601<br>

Needs Improvement:<br>
For stopping: each of the running processes has to closed separately.
