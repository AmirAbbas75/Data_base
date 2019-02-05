# Data_base
Store user vote and details
_SERVICE db:
go to db folder 
run:
docker-compose up // up service to port 8081
open url in browesr localhost with port or docker container ip
localhost:8081/install
done each step and wait to finish install database and other setups

open url in browesr localhost with port or docker container ip
localhost:8081/cloud/public/api/db
to install api and api database

you can access api from dbapache 
you can access mysql from dbmysql 

like curl "dbapache/cloud/public/api..."


for query to database use api address below
dbapache/cloud/public/api/db/query

params : query


for create user and login use api address below
dbapache/cloud/public/api/db/login

params : email
		 pass
		 
finish 
