# Use a imagem do node na versão 14
FROM node:14

# Definir o diretório de trabalho dentro do container
WORKDIR /app

# Expor a porta 3000
EXPOSE 3000

# Adcionar o arquivo node_modules.tar.gz para imagem
ADD ./node_modules.tar.gz .

# Copiar todos os arquivos da pasta back-end para imagem
COPY . .

# Iniciar a aplicação com o comando npm start
ENTRYPOINT  [ "npm", "start" ]