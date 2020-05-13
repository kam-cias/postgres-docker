# PostgreSQL with docker-compose.

Description | Command
------------ | -------------
Run a container in the background | docker-compose up -d
New command in a running container - process /bin/bash. | docker exec -it psql-12.2 /bin/bash
Connection psql with postgres user | psql -U postgres
