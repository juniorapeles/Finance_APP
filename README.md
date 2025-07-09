# App Finance – API de Finanças Pessoais

API REST desenvolvida em Java 21 com Spring Boot 3 para controle financeiro pessoal. Permite cadastrar receitas, despesas, metas, fazer cálculos de projeção de saldo e acompanhar o progresso financeiro mensal.

## 🛠 Tecnologias
- Java 21
- Spring Boot 3
- Spring Security com JWT
- PostgreSQL
- JPA/Hibernate
- Docker
- Swagger/OpenAPI
- JUnit + Mockito
- GitHub Actions (CI/CD)

## 🔐 Funcionalidades
- Cadastro de usuários com autenticação via JWT
- CRUD de receitas e despesas
- Relatório mensal de saldo
- Metas financeiras
- Cálculo de juros compostos

## ▶️ Como rodar localmente
```bash
# Clone o projeto
git clone https://github.com/juniorapeles/app-finance.git
cd app-finance

# Rode com Docker Compose
docker-compose up --build
