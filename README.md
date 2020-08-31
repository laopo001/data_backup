```
docker service inspect ghost_ghost

docker stack deploy -c ghost.yml ghost

docker stack rm ghost

firewall-cmd --zone=public --permanent --add-port=3306/tcp

docker service ls

docker service logs ghost_ghost
```