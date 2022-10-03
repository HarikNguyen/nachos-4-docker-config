# nachos

1. [Run docker container containing nachos](#docker)
- Run docker compose
> docker compose up
- Exec ssh
> docker compose exec -it nachos zsh
- configuring zsh shell theme
> sudo service ssh start
> type password: nachos
- Open terminal in host machine
+ type
> docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' nachos-prj
+ copy the ip address
- first of all, you must be test the ssh connection
+ type
> ssh nachos@<ip_address>
+ type "yes"
+ type password: nachos