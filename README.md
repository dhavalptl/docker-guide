# docker-guide

## Useful docker commands

1. List docker images ```docker images -a```
2. List running docker container ```docker ps -a```
3. List docker images images id : docker images -q
4. List running docker container ids : docker ps -a -q
5. Single stop running container process: docker stop <first three digit of container id | container id>
6. Single delete stopped container process: docker rm  <first three digit of container id | container id>
7. Stop all running container process: docker stop $(docker ps -a -q)
8. Delete all stopped container process: docker rm $(docker ps -a -q)
9. Delete one docker image : docker rmi <image id | first three digit of image id>
10. Delete all docker images : docker rmi $(docker images -q)

Note: First stop running docker container, then delete docker process, then delete docker image

