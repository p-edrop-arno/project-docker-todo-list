# Use a imagem do mjgargani/puppeteer:trybe1.0
FROM mjgargani/puppeteer:trybe1.0

# Definir o diretório de trabalho dentro do container
WORKDIR /app

# Copiar o arquivo node_modules.tar.gz para imagem
ADD ./node_modules.tar.gz .

# Copiar todos os arquivos da pasta tests para imagem
COPY ./tests .

# Iniciar os testes com o comando npm test
ENTRYPOINT [ "npm", "test" ]