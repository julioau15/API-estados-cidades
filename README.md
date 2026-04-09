# API Estados e Cidades

API REST desenvolvida com Node.js e Express para manipulação de dados de estados e cidades do Brasil.

## Tecnologias utilizadas

- Node.js  
- Express  
- CORS  
- JavaScript  

## Funcionalidades

- Listar todos os estados (UFs)  
- Buscar dados de um estado  
- Consultar capital de um estado  
- Listar cidades de um estado  
- Listar estados por região  
- Listar capitais do Brasil ao longo da história  

## Endpoints

### Listar estados

GET /v1/senai/estados

### Dados de um estado

GET /v1/senai/estado/dados/:uf

Exemplo:

GET /v1/senai/estado/dados/sp

### Capital de um estado

GET /v1/senai/estado/capital/:uf

### Cidades de um estado

GET /v1/senai/estado/cidades/:uf

### Estados por região

GET /v1/senai/regiao/estados/:regiao

Exemplo:

GET /v1/senai/regiao/estados/sudeste

### Capitais do Brasil (histórico)

GET /v1/senai/capital/brasil

### Documentação da API

GET /v1/senai/help

## Como rodar o projeto

### 1. Instalar dependências

npm install

### 2. Iniciar o servidor

node app.js

### 3. Acessar a API

http://localhost:8080/

## Estrutura do projeto

## Exemplo de uso

GET http://localhost:8080/v1/senai/estados

GET http://localhost:8080/v1/senai/estado/cidades/sp

## Próximas melhorias

- Implementar POST, PUT e DELETE  
- Integração com banco de dados

## Autor

Julio Augusto  

## Licença

Projeto desenvolvido para fins educacionais.
