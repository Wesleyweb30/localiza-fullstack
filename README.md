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
````

## Tecnologias Utilizadas

### Backend (localiza-api)
- **Java:** Linguagem de programação principal para desenvolvimento do backend.
- **Spring Boot:** Framework que simplifica o desenvolvimento de aplicações Java com configuração mínima.
- **JPA (Java Persistence API):** API para a gestão de persistência e acesso a dados relacionais.
- **H2 Database:** Banco de dados em memória utilizado para desenvolvimento e testes.
- **Hibernate:** Framework ORM (Object-Relational Mapping) que facilita o mapeamento entre objetos Java e bancos de dados relacionais.
- **Maven:** Ferramenta de gerenciamento de dependências e construção do projeto.

### Frontend (localiza-app)
- **React JS:** Biblioteca para construção de interfaces de usuário interativas e dinâmicas.
- **Axios:** Cliente HTTP para realizar requisições ao backend e gerenciar respostas.
- **React Query (useQuery):** Biblioteca para gerenciamento de estado e cache de dados de forma eficiente.
- **Bootstrap:** Framework CSS para criar layouts responsivos e estilizar a aplicação com componentes prontos.

### Compile e execute o projeto Spring Boot:
- ./mvnw spring-boot:run

Frontend
Navegue até a pasta frontend:
cd localiza-app

### Instale as dependências e execute o projeto React:
- npm install
- npm start

### Funcionalidades
- Cadastro de veículos
- Gerenciamento de clientes
- Controle de reservas
- Relatórios de locações

# Contribuição
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

![image](https://github.com/user-attachments/assets/a5e55999-75d5-4108-b07a-443bbb23e0ae)
![image](https://github.com/user-attachments/assets/61ff1a8c-3731-4a05-b58a-0e2307eb2d11)


