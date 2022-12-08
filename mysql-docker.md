* docker deamon run on the root
mysql 
docker pull mysql
commands :
sudo docker pull mysql/mysql-server:latest
sudo docker run --name docker_mysql -d mysql/mysql-server:latest
sudo docker run --name=[container_name] -d [image_tag_name]
docker ps   (to check if the command is running or not)
if you want  to connect db with the host 
apt-get install mysql-client
to open logs file 
sudo docker logs [container_name]

sudo docker exec -it docker_mysql bash 
# here enter : mysql -uroot -p 
enter the passowrd and enjoy to use mysql 
