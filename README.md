# En Vivo

```bash

git clone --init --recursive git@...

cd en-vivo-backend
yarn install en-vivo-backend
cd ..

cd en-vivo-frontend
yarn install en-vivo-backend
cd ..

docker-compose -f docker-compose.backend.local.yml up

```