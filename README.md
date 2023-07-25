## Overview
- In this project, I will create one docker compose for pg_admin and postgis.
- Update Information about password and email if you need.

- To connect With PostGIS Database:
    - host name/ address: db > networks > gisnet > aliases
    - username: postgres (default)
    - password: db > enviroment > POSTGRES_PASSWORD
## Setup
* Create network for docker
    > docker network create gisnet
* Run docker compose
    > docker compose up