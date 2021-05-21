
```shell
sudo docker stack deploy -c docker-compose.yml bee-1
```



```shell
sudo docker stop $(sudo docker ps -q) & sudo docker rm $(sudo docker ps -aq)
```

[bee docker](https://docs.ethswarm.org/docs/installation/docker/)