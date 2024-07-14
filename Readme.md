Comands to create a mysql database whit docker.

first step create a volume to db persistence

docker volume create volume-name 

create .env file like the template 

MYSQLDB_HOST=mysqldb
MYSQLDB_PASSWORD=database-password
MYSQLDB_DATABASE=database-name

MYSQLDB_LOCAL_PORT=3306
MYSQLDB_DOCKER_PORT=3306

next step first build

docker compose up 

to stop 

Ctrl + c

to delete 
docker compose down 

to run 
docker compose up

to rebuild 
docker compose up --build


see al compose running files 
docker compose ps -a 

view all docker volumes
docker volume list

delete an volume
docker volume rm name 