# initialize (do it only once)
docker-compose run --rm server create_db

# start redash docker 
docker-compose up -d

# stop redash docker 
docker-compose stop

# stop and remove container (warning! all db need to re initialize)
docker-compose down