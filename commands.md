## Docker commands

#### construir y ejecutar los contenedores
```sh
docker-compose up --build
```

#### parar todos los contenedores
```sh
docker-compose downn
```

#### construir los contenedores sin usar cache
```sh
docker-compose build --no-cache
```

## Django app

#### django app domain
`http://localhost:8000`

## Jenkins

#### jenkins domain
`http://localhost:8080`

#### obtener la constrasena de jenkins
`docker-compose exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword`



