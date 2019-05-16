# https://medium.com/dockerbr/mongodb-no-docker-dd3b72c7efb7

docker pull tutum/mongodb

# Sem senha
docker run -d -p 27017:27017 -p 28017:28017 -e AUTH=no tutum/mongodb

# Com senha
# docker run -d -p 27017:27017 -p 28017:28017 -e MONGODB_PASS="mypass" tutum/mongodb

docker ps -a

# Rodar container pelo id listado no comando anterior
# docker start 77b903780b83

# Cliente mongo no terminal
sudo apt install mongo-clients

# Cliente gráfico
sudo apt install snapd -y && sudo snap install robomongo
