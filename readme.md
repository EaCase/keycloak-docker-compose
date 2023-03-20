## Keycloak docker compose

This repository contains a docker-compose file which creates keycloak + postgres containers, and imports the keycloak realm 'Boxinator'.

The realm contains by default a single account with credentials admin:1234, which can be used to log in to the boxinator application.

### Running

1. Make sure you have docker compose installed (comes with docker desktop)
2. Clone repository, and in the root folder run command:
   `docker-compose up`
3. Navigate to localhost:8083/ to confirm everything is up and running.
