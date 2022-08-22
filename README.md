# Cloud Parking


## Run database
docker run --name parking-db -p 5432:5432 -e POSTGRES_DB=parking -e POSTGRES_USER=admin -e POSTGRES_PASSWORD=root123 -d postgres:13.1-alpine

## Start and Stop

### Stop Database
docker stop parking-db

### Start Database
docker start parking-db
