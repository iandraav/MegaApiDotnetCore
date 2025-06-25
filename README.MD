# Mega Man Robots API 🤖

## 📒 Descrição
Este projeto é uma API RESTful desenvolvida para o Desafio de Projeto da DIO, com o objetivo de demonstrar a criação de uma API funcional e bem documentada. A API permite a manipulação de dados dos Robot Masters da clássica série de jogos Mega Man, oferecendo operações de CRUD (Create, Read, Update, Delete). A documentação foi gerada com o auxílio de ferramentas de Inteligência Artificial, como o Google Gemini, para otimizar a clareza e a organização.

## 🤖 Tecnologias Utilizadas
- **Node.js:** Ambiente de execução do JavaScript no backend.
- **Express.js:** Framework para a construção da API, gerenciamento de rotas e middlewares.
- **MongoDB:** Banco de dados NoSQL utilizado para armazenar os dados dos robôs.
- **IA Generativa (Google Gemini):** Utilizada para gerar textos descritivos, documentação de endpoints e guias de instalação.
- **Mermaid.js:** Para a criação do diagrama de arquitetura diretamente no Markdown.

---

## 🏛️ Arquitetura da API
O diagrama abaixo ilustra o fluxo de uma requisição desde o cliente até o banco de dados.

```mermaid
graph TD
    A[Cliente] --> B{API Gateway};
    B --> C[Servidor da Apl
