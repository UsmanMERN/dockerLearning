# dockerLearning
dokerfile --->DockerImage -->multiple containers 
                !
                !
                v
            docker container

docker.com 

<!-- download the docker  -->

hub.docker.com

<!-- install mysql in my docker container -->

docker pull mysql

<!-- create mysql container -->
 docker run --name mysql-c1 -e MYSQL_ROOT_PASSWORD=usman -d mysql

<!-- start server on machine -->
 docker exec -it mysql-c1 mysql -u root -p

<!-- nginx server setup -->

docker pull nginx

<!-- run the container  -->
docker run --name nginx-c1 -d -p 8080:80 nginx