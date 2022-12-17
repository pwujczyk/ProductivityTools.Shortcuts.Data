docker build --tag hello-world .

docker images
docker rmi [imageid] - remove image

docker run hello-world
docker ps -a - shows all images

docker container ls -a - list all containers
docker container rm [container_id]
docker container stop [container_id]
docker run -p 5000:5000 --name run1 -d x5

Python application needs to be listening on the host 0.0.0.0
   app.run(port=5000,host='0.0.0.0',debug=True)