# Docker
docker image comes with file system snapshot(bin,lib files) and other default command\
1.Namespacing: islolating resources\
2.Control group:limit resources\
docker file is like readme.md file of github\
docker image is like class or contains all file as well as enviroment to run a container\
docker container is like a object or running instance of image\
docker run= docker create + docker start\
- -a to show what is running inside a container\
- -i to perform I/O operation in container\
- -t to do prettier\
`docker run image_name`all images\
`docker rmi image_name`to delete image\
`docker rm container_name`to delete container\
`docker ps` all running containers\
`docker ps -all` all running and exit containers\
`docker stop container_id` to stop container\
`docker kill container_id` to forcefully stop container\
`docker logs container_id` to see what is running inside container\
`docker exec -i -t container_id sh` helps ot write code inside container\
`docker images` helps to show all images\
`docker build .`
