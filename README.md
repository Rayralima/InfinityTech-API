## 1. Informações Gerais da API
A API Infinity-Tech é uma API RESTful desenvolvida com Java (Spring Boot). Seu
objetivo é monitorar falhas na API ExtrAI Dados da Di2win, com integração a um banco de dados PostgreSQL.
Ela cumpre os seguintes propósitos:
* Identificar e documentar falhas nas solicitações a API da Di2win.
* Ligar incidentes a clientes e modelos de Inteligência Artificial específicos.
* Produzir notificações automáticas para incidentes críticos, exibidos em um
dashboard.
* Fornece relatórios filtrados (por data, cliente, modelo de IA) exportáveis em
formato CSV ou PDF.
* Documentação: Utiliza Swagger para fornecer uma documentação interativa
de endpoints.

## Detalhes Técnicos:
* Base URL: https://api.infinity-tech.com/v1 (URL ilustrativa, pode ser alterada)
* Formato de Dados: JSON para requisições e respostas.
* Autenticação: A definir (API Key ou OAuth 2.0?)
* Códigos de status:
200 Ok: Requisição atendida com sucesso.
201 Created: Recurso criado com sucesso
400 Bad Request: Erro na requisição (por exemplo, parâmetros incorretos).
404 Not Found: Arquivo ou recurso não localizado.
500 Internal Server Error: Erro interno do servidor.
