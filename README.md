# En Vivo

##### Requisitos

- docker y docker-compose
- Solicitar un archivo *.env.local* para configurar tu entorno


```bash



git clone --init --recursive git@...

cd en-vivo-backend
yarn install en-vivo-backend
cd ..

cd en-vivo-frontend
yarn install en-vivo-backend
cd ..

cp .env.local .env
docker-compose -f docker-compose.backend.local.yml -f docker-compose.backend.frontend.yml up

```