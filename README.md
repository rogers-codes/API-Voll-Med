
# 🏥 Voll.med API - Gestão de Clínica Médica

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

A **Voll.med API** é uma solução robusta para a gestão de uma clínica médica, desenvolvida com Spring boot. A aplicação foca-se em fornecer uma API RESTful eficiente para o cadastro,listagem,atualização e exclusão de médicos aplicando o conceito CRUD para desempenho e performace.

---

## 🚀 Funcionalidades Principais

- **CRUD de Médicos:** Cadastro, listagem (paginada), atualização e exclusão lógica.
- **Segurança:** Autenticação stateless via tokens JWT (JSON Web Tokens).
- **Validações:** Uso de Bean Validation para garantir a integridade dos dados de entrada.
- **Persistência:** Migrations de base de dados automatizadas com Flyway.
- **Tratamento de Erros:** Implementação de um manipulador de exceções global para respostas HTTP amigáveis.

---

## 🛠️ Tecnologias Utilizadas

- **Java 17** (Linguagem principal)
- **Spring Boot 3** (Framework)
- **Spring Data JPA** (Camada de persistência)
- **Spring Security** (Autenticação e Autorização)
- **MySQL** (Base de Dados)
- **Flyway** (Gestão de Migrations)
- **Lombok** (Produtividade e código limpo)
- **Maven** (Gestão de dependências)
- **Insomnia** (Testes da API)

---

## 📖 Documentação da API (Endpoints)

### Médicos
| Método | Endpoint | Descrição |
| :--- | :--- | :--- |
| `POST` | `/medicos` | Cadastra um novo médico |
| `GET` | `/medicos` | Lista médicos (paginado e ordenado) |
| `PUT` | `/medicos` | Atualiza informações de um médico |
| `DELETE` | `/medicos/{id}` | Realiza a exclusão lógica do médico |

## ⚙️ Configuração do Ambiente

A aplicação utiliza variáveis de ambiente para proteger dados sensíveis. Certifique-se de configurar as seguintes variáveis no seu sistema ou na sua IDE (IntelliJ/Eclipse):


DB_HOST=localhost
DB_NAME=vollmed_api
DB_USERNAME=o_seu_usuario
DB_PASSWORD=a_sua_senha

## 🛠️ Como Executar o Projeto

### Clone o repositorio.
No seu terminal, execute o comando para baixar o projeto:
```bash
git clone [https://github.com/rogers-codes/API-Voll-Med.git](https://github.com/rogers-codes/API-Voll-Med.git)
```

### Confirgure a base de dados:
CREATE DATABASE vollmed_api;

### Rode o comando no prompt de comando:
.\mvnw.cmd spring-boot:run
