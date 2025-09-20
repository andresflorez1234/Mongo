## connect to container

```sh
docker-commpose exec mongodb bash
```

## connect with mongosh

```sh
mongosh "mongodb://localhost:27017/"
mongosh "mongodb+srv://florezandresfelipe62_db_user:JQen1cUAE60dZM2T@practica.d64z9nr.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("Produc_stores")
db.productos.find()
```