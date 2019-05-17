
# Rodando aplicação

- `yarn dev`

# Instalando Mongo com Docker

- Tutorial: [Docker: Criando servidor MongoDB](https://medium.com/dockerbr/mongodb-no-docker-dd3b72c7efb7)

- `docker pull tutum/mongodb`

- Sem senha: `docker run -d -p 27017:27017 -p 28017:28017 -e AUTH=no tutum/mongodb`

- Com senha: `docker run -d -p 27017:27017 -p 28017:28017 -e MONGODB_PASS="mypass" tutum/mongodb`

- Listando containers: `docker ps -a`

- Rodar container pelo id listado com comando anterior: `docker start 77b903780b83`

- Instalando cliente mongo modo texto (opcional): `sudo apt install mongo-clients`

- Cliente mongo modo gráfico (opcional): `sudo apt install snapd -y && sudo snap install robomongo`
