# Baixa a imagem padrão do node.js
FROM node:16

# Especifica o diretório base da imagem
WORKDIR /usr/src/app

# Copia os pacotes e instala o as dependências
COPY package*.json ./
RUN npm install
RUN npm install express

# Copia os programas para a imagem
COPY . .

# Informa qual comando deve ser executado na carga do container
CMD [ "npm", "start" ]
