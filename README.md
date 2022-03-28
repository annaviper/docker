# docker

docker pull
docker run container_name // does a pull
docker run -d container_name // detached, in background mode, you can use the terminal
docker run -d --name <name> image_name
docker run -it container_name bash // `exit` to exit

docker images // lists

docker ps // list running containers
docker ps -a // stopped and exited included
docker stop container_id_name
docker rm container_id_name // you can provide more than one at once
doker rmi image_name

docker exec container-id command // enter in the container

# docker run

docker run -it container_name
docker run -p host_port:port container_name // port mapping
docker run -v path_to_store_data:/var/lib/image_name image_name // make data persistent
docker inspect container_name
docker logs container_name
