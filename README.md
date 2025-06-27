🌱 Projeto Plantio - Sistema de Gerenciamento Agrícola
Este repositório organiza a estrutura completa do sistema Plantio, uma aplicação web composta por:

Frontend: Desenvolvido em ReactJS, hospedado via Nginx

Backend: Construído com Java Spring Boot 21, integrado ao banco de dados PostgreSQL



📁 Repositórios
Este projeto é dividido em dois repositórios:

Frontend (ReactJS + Nginx):
🔗 github.com/marcelquin/Plantio-frontend

Backend (Spring Boot 21 + PostgreSQL):
🔗 github.com/marcelquin/plantio-backend



🧩 Tecnologias Utilizadas

FRONTEND

ReactJS

Axios

React Router

Gerenciado por Nginx (em produção)



BACKEND


Java 21 (Spring Boot)

Spring Web, Spring Data JPA, Spring Security (se utilizado)

PostgreSQL

Redes para Cach de métodos necessários


🚀 Como executar localmente

1. Clone os repositórios
bash
FRONTEND: git clone https://github.com/marcelquin/Plantio-frontend.git

BACKEND: git clone https://github.com/marcelquin/plantio-backend.git

3. Configure o backend
Crie um banco PostgreSQL local com as credenciais correspondentes ao application.properties ou .yml

Execute o projeto com Maven ou sua IDE favorita

bash
Copiar
Editar
cd plantio-backend
./mvnw spring-boot:run

3. Configure o frontend
Instale as dependências e inicie o projeto

bash
Copiar
Editar
cd Plantio-frontend
npm install
npm run dev

