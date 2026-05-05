# 🏥 Voll.med API

API REST para gerenciamento de uma clínica médica, desenvolvida com **Spring Boot 3** e **Java 17**. O sistema permite o cadastro, listagem, atualização e exclusão de médicos, aplicando regras de negócio e segurança avançada.

## 🚀 Tecnologias
- **Spring Boot 3** (Java 17)
- **Spring Data JPA** (Persistência)
- **MySQL** (Banco de Dados)
- **Flyway** (Migrations)
- **Spring Security** (Autenticação Stateless com JWT)
- **Lombok** (Produtividade)
- **Insomnia** (Testes da API)

## 🔑 Configuração de Segurança
Este projeto utiliza variáveis de ambiente para dados sensíveis. Defina as seguintes variáveis antes de rodar:
- `DB_USERNAME`: Usuário do banco de dados
- `DB_PASSWORD`: Senha do banco de dados

## 🛠️ Como executar
1. Clone o repositório: `git clone https://github.com/rogers-codes/API-Voll-Med.git`
2. Configure as variáveis de ambiente mencionadas acima.
3. Execute a aplicação na pasta: \src\main\java\medico\ ApiAplication
