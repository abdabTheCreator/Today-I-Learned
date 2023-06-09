
# Docker volumes: 

Volumes are the preferred mechanism for persisting data generated by and used by Docker containers. While bind mounts are dependent on the directory structure and OS of the host machine, volumes are completely managed by Docker. 

`docker volume ls`
- lists the volumes that have been created

`docker volume create <name>`
  - creates a new named volume

 `docker volume rm <name>`
  -removes the volume aslong as it not connected to a container
  

`docker volume inspect <name>`
  - inspect volume to view the state 
  
`docker prune` 
  - prune a volume with confirmation 

 
> State data lives on the host machine 
- [Docker volumes](https://docs.docker.com/storage/volumes/)
