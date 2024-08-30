# Localiza - Gerenciamento de Locadora de Veículos

## Descrição
Este projeto é uma aplicação full stack para o gerenciamento de uma locadora de veículos, composta por um backend em Java Spring Boot e um frontend em React JS.

## Estrutura do Projeto
A estrutura do projeto é organizada da seguinte forma:

```plaintext
/localiza
├── backend (localiza-api)
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   └── resources
│   │   └── test
│   ├── pom.xml (ou build.gradle)
│   └── README.md
├── frontend (localiza-app)
│   ├── public
│   ├── src
│   ├── package.json
│   └── README.md
└── README.md

Tecnologias Utilizadas
Backend: Java, Spring Boot, JPA,H2 DataBase Hibernate, Maven
Frontend: React JS, Axios, UseQuery, Bootstrap
Como Configurar e Executar
Backend
Navegue até a pasta localiza-api:
cd localiza-api

Compile e execute o projeto Spring Boot:
./mvnw spring-boot:run

Frontend
Navegue até a pasta frontend:
cd localiza-app

Instale as dependências e execute o projeto React:
npm install
npm start

Funcionalidades
Cadastro de veículos
Gerenciamento de clientes
Controle de reservas
Relatórios de locações
Contribuição
Sinta-se à vontade para contribuir com este projeto. Para isso, siga os passos abaixo:

Faça um fork do repositório.
Crie uma branch para sua feature:
git checkout -b minha-feature

Faça commit das suas alterações:
git commit -m "Adiciona minha feature"

Envie para o repositório remoto:
git push origin minha-feature

Abra um Pull Request.
Licença
Este projeto está licenciado sob a MIT License.