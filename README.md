# 🐳 Docker Compose

Coinsamba docker compose

# coinsamba-api.yaml

This file will start all necessary services to develop all Coinsamba apps.

`$ docker-compose -f .\coinsamba-api.yaml up`

Services that will be start

| name            | port | internal host   |
| --------------- | ---- | --------------- |
| mysql           | 3306 | mysql           |
| redis           | 6379 | redis           |
| redis-commander | 8081 | redis-commander |
| phpmyadmin      | 8181 | phpmyadmin      |

# exchange.yaml

This file will start all necessary services to develop an exchange app with Node.js based.

`$ docker-compose -f .\exchange.yaml up`

Services that will be start

| name            | port | internal host   |
| --------------- | ---- | --------------- |
| mongo           | 27017 | mongo           |
| redis           | 6379 | redis           |
| redis-commander | 8081 | redis-commander |
| mongo-express   | 8082 | mongo-express      |
