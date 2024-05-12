# fullstack-docker-demo

Very simple fullstack app with postgreSQL to show basic integration with docker

### Development

`docker compose up -d`
`docker compose down`

### Production

`docker compose up -f compose.prod.yaml -d`
`docker compose -f compose.prod.yaml down`

rebuild the api image between dev-prod runs
