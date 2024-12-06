# **App Finance** 💸

### **Gerencie suas finanças com facilidade e segurança!**

O **App Finance** é uma aplicação backend moderna, desenvolvida em **Java 17**, que fornece uma API robusta para gerenciar e calcular rendas, despesas e saldos. O projeto foi criado com foco em aprendizado e boas práticas, implementando as tecnologias mais recentes para proporcionar escalabilidade, segurança e facilidade de uso.

---

## **🌟 Objetivo do Projeto**
Criar uma API para gerenciar finanças pessoais, incluindo:
- Cálculo automático de despesas fixas, variáveis, rendas e saldo mensal.
- Sistema de autenticação e autorização (Login).
- Arquitetura robusta para aprendizado e aplicação de boas práticas no desenvolvimento backend.

---

## **⚙️ Funcionalidades**
1. **Gerenciamento Financeiro:**
   - Adicionar, editar e remover rendas fixas.
   - Gerenciar despesas fixas e variáveis por mês.
   - Obter resumos financeiros mensais.

2. **Sistema de Login:**
   - Autenticação segura com Spring Security.
   - Suporte a JWT para sessões seguras.

3. **Infraestrutura Moderna:**
   - Dockerização para fácil deploy e execução.
   - Configurações centralizadas em `application.yml`.
   - Deploy automatizado com ferramentas modernas.

---

## **🚀 Tecnologias Utilizadas**
- **Java 17**: Recursos modernos como Records, Pattern Matching e Sealed Classes.
- **Spring Boot**: Framework para criar aplicações Java robustas.
- **Spring Security**: Implementação de login e segurança.
- **PostgreSQL**: Banco de dados relacional para armazenar rendas e despesas.
- **Docker**: Empacotamento e execução do app em contêineres.
- **Hibernate/JPA**: ORM para interagir com o banco de dados.
- **YAML**: Configurações organizadas e legíveis.
- **JUnit**: Testes unitários para garantir a qualidade do código.

---

## **📦 Estrutura do Projeto**
```plaintext
src/
├── main/
│   ├── java/com/appfinance/
│   │   ├── controller/     # Controladores REST
│   │   ├── service/        # Regras de negócio
│   │   ├── repository/     # Repositórios JPA
│   │   └── model/          # Entidades
│   ├── resources/
│       ├── application.yml # Configurações
│       └── schema.sql      # Script para criação do banco
└── test/
    └── java/com/appfinance # Testes unitários e de integração


