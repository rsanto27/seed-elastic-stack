# seed-elastic-stack
This is a seed that talk about the elastic stack. In this seed we've been use elasticSearch, kibana and logstash.

## what it's needed

1. Docker compose installed.

## Steps to build the environment in Linux

1. inside the `/etc/sysctl.conf`, edit the file putting this variable **vm.max_map_count = 262144**. Exit the file and confirm with **sudo sysctl -p**
