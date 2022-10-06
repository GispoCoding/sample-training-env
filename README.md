# Sample training environment
This minimal environment includes PostGIS, Geoserver and PgAdmin web client.

## Running the environment
You can change service passwords etc. in `.env` file.
```sh
docker compose up
# or if you don't want to see logs and want to detach 
```
After a while that you can access:  
**PostgreSQL**
 - host: localhost
 - port: 5432
 - database name: see `.env`
 - username: see `.env`
 - password: see `.env`

**Geoserver**
 - url: http://localhost:8080
 - username: admin
 - password: see `.env`

**PgAdmin**
 - url: http://localhost:5000
 - username/email: see `.env`
 - password: see `.env`