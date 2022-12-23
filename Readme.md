## Description 
This project contains the code to enable monitoring and visualisation of logs on a search application using Elastic search, Kibana and Logstash. The ELK is a three-layered open-source tool used for storing, manipulating, and visualizing data. Adopting ELK stack in an organization can be a powerful solution for managing and analyzing large amounts of data, particularly log data.
### Dependecies
1. Docker
 
```
$ brew install docker
```
start Docker Daemon

For more on Docker see [docker](https://docs.docker.com/)

2. Git
 
install git 
For instructions on installing Git, see [git](https://git-scm.com/doc) 

### How to run
clone the repository 
```
$ git clone https://github.com/felixokpalaima/elk.git
$ cd elk
$ docker compose up
```
### Visualisation
1. visit `localhost:5601`
2. create index by uploading a csv file
3. create your dashboard 

#### ELK Reading resources 
* https://www.elastic.co/guide/en/kibana/current/dashboard.html
* https://www.elastic.co/guide/en/kibana/current/create-a-dashboard-of-panels-with-web-server-data.html