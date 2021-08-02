# seed-elastic-stack
This is a seed that talk about the elastic stack. In this seed we've been use elasticSearch, kibana and logstash.

## what it's needed

1. Docker compose installed.

## Steps to build the environment in Linux

1. Inside the `/etc/sysctl.conf`, edit the file putting this variable **vm.max_map_count = 262144**.
2. Exit the file and confirm with **sudo sysctl -p**.
3. Run compose to download the images. **docker-compose up**

## Inside project

1. To access kibana, go to http://localhost:5601/app/home#/
