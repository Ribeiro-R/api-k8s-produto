FROM node:14.16.1-alpine3.13
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "app.js"]

# Criar a imagem
# Caminho do Dockerfile
# Diretorio de contexto
# docker build -t namespace/api-produto:v1 -f ./src/Dockerfile ./src/
# docker tag namespace/api-produto:v1 namespace/api-produto:latest
# docker push namespace/api-produto:v1
# docker push namespace/api-produto:latest
