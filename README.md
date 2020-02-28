# API Desafio Serasa! 
Este repositório contém os dados de uma api(mock) que serve a aplicação: [__desafio serasa__](https://github.com/gu1ma/desafio-serasa)

### Instalando
Siga os passos para iniciar a aplicação no seu ambiente: 
1. Baixe o projeto com o comando `git clone https://github.com/gu1ma/desafio-serasa-api`
1. Instale as dependências `npm install`
2. Inicie o servidor :D `node src/server.js`

### Rotas
rota para busca de dados do usuário <br>
GET: `/serasa/get-user-data` <br>
POST: `/serasa/pay-debt`
parametro: 
`
{ "scoreValue": 20 }
`
<br>
POST: `/serasa/accept-credit`
parametro: 
`{ "scoreValue": 20 }
`
<br>
POST: `/serasa/accept-protection-plain`
parametro: 
`{ "scoreValue": 20 }
`
<br>

