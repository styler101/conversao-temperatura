# De onde estamos nos baseando na imagem
FROM node:20-alpine3.17
# esse diretório será criado dentro da imagem do container.
WORKDIR /app
# Copiar todas as alterações 
COPY  package*.json  ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]