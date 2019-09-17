
rodar no docker antes de iniciar
docker-compose up hubot

criar no arquivo principal ".env" e passar o senguites coisas
export ROCKETCHAT_URL=localhost:3000    
export ROCKETCHAT_USER="nome do bot"
export ROCKETCHAT_PASSWORD=""
export ROCKETCHAT_ROOM=general
export ROCKETCHAT_USESSL=true


no terminal dar o comando source .env e dps bin/hubot
