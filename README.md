# En Vivo

##### Requisitos

- docker y docker-compose
- Solicitar un archivo *.env.local* para configurar tu entorno


```bash



git clone --init --recursive https://github.com/federacion-de-codigo-al-vuelo/en-vivo.git

cd en-vivo-backend
yarn install en-vivo-backend
cd ..

cd en-vivo-frontend
yarn install en-vivo-backend
cd ..

cp .env.local .env
docker-compose -f docker-compose.backend.local.yml -f docker-compose.backend.frontend.yml up

```


Usando las variables default de nuestro **.env.local**, las rutas accesibles son las siguientes:


### CMS:
http://localhost:4000/admin

### Frontend:
http://localhost/

### Storybook:
http://localhost:8089/