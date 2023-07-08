# up mongodb
´´´sh
docker-compose up -d mongodb

´´´

# check

´´´sh
docker-compose ps

´´´

## Connect to container since cmd
´´´sh
docker-compose exec mongodb bash
´´´

## Connect with mongosh
´´´sh
mongosh ""
´´´

´´´sh
show dbs
show collections
´´´

´´´sh
use("platzi_store")
db.products.find()
´´´

