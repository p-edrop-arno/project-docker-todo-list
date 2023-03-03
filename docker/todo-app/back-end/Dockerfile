# Use a imagem do node na versão 14
FROM node:14

# Definir o diretório de trabalho dentro do container
WORKDIR /app

# Expor a porta 3001
EXPOSE 3001

# Adcionar o arquivo node_modules.tar.gz para imagem
ADD ./node_modules.tar.gz .

# Copiar todos os arquivos da pasta back-end para o diretório de trabalho
COPY ./back-end .

# Iniciar a aplicação com o comando npm start
ENTRYPOINT  [ "npm", "start" ]