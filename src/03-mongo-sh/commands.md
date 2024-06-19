
conectarnos a un servicio corriendo en docker
* docker-compose exec mongodb bash

conectarnos con mongo sh
* mongosh "URL de conexion"
* mongosh "mongodb://root:root123@localhost:27017/?tls=false"

* show dbs
* show collections

* use("sample_training")

// busqueda normal
* db.zips.find({ state: "NY" })