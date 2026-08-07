![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![ES6+](https://img.shields.io/badge/ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Apache_Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Resilience4j](https://img.shields.io/badge/Resilience4j-black?style=for-the-badge)
![Build](https://img.shields.io/badge/Build-Passing-44CC11?style=for-the-badge&logo=github-actions&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-007EC6?style=for-the-badge)

# Olá, eu sou Robson Carlos 👋
### Full-Stack Java Specialist | Backend Architecture & Spring Ecosystem

Desenvolvedor Full-Stack focado na criação de aplicações robustas, escaláveis e seguras. Minha atuação principal é no ecossistema **Java**, aplicando boas práticas de arquitetura de software, padrões de projeto (Design Patterns), segurança moderna e código limpo.

---

### 🛠️ Tech Stack & Ferramentas

| Categoria | Tecnologias |
| :--- | :--- |
| **Backend & Core** | Java (8+), Spring Boot, Spring Security, Spring Data JPA, Hibernate, MapStruct |
| **Segurança & Auth** | OAuth2, JWT, OpenID Connect, Google reCAPTCHA, BCrypt |
| **Frontend** | JavaScript (Vanilla), HTML5, CSS3, Bootstrap 5 |
| **Bancos de Dados** | Oracle, PostgreSQL, MySQL, H2 Database (In-Memory) |
| **Testes & Qualidade** | JUnit 5, Mockito, AssertJ |
| **DevOps & Ferramentas** | Docker, Git, GitHub Actions (CI/CD), Maven, Postman / Insomnia |

---

### 🌟 Projetos em Destaque

#### 🚀 (https://github.com/r0bs0ncarl0s/spring_boot-h2-oauth2-captcha-mapstruct-html5-bootstrap5-js-vanilla)
> **Stack:** Java, Spring Boot, OAuth2, H2, MapStruct, reCAPTCHA, Bootstrap 5, JS Vanilla.

Aplicação full-stack desenvolvida para consolidar conceitos avançados de segurança, autenticação social via OAuth2, proteção contra bots (reCAPTCHA) e mapeamento performático de dados (MapStruct com DTOs).

* **Destaques Técnicos:**
  * Separação rigorosa de camadas (Controller, Service, Repository, Mapper, DTO).
  * Autenticação via provedores externos e segurança baseada em funções (RBAC).
  * Frontend leve e desacoplado consumindo APIs REST nativas via `fetch`.

---

#### 🚀 (https://github.com/r0bs0ncarl0s/soap_circuitbreaker_orchestrator_duckdb)
> **Stack:** Java 8, DuckDB, JAX-WS/SOAP, Log4j2 + LMAX Disruptor, Maven.

Acelerador de integração SOAP de alta performance projetado para ambientes corporativos que exigem processamento assíncrono, resiliência contra falhas de rede e persistência analítica embutida. O projeto resolve os gargalos clássicos de integrações legadas (bloqueio de threads, perda de dados em falhas de comunicação e dependência de infraestrutura externa de banco de dados) ao combinar concorrência não-bloqueante com um motor SQL colunar embarcado.

---

#### 🚀 (https://github.com/r0bs0ncarl0s/sistema_v3_backend)
> **Stack:** Java 17, Spring Boot 3.1.3, Spring Security 3 + Java JWT (jjwt 0.12.3), Spring Data JPA + PostgreSQL Driver, Lombok + Spring Boot DevTools, JavaMail / Spring Starter Mail, Spring Boot Docker Compose, SpringDoc OpenAPI (Swagger UI 2.6).

API RESTful backend construída com Spring Boot 3 e Java 17, projetada com foco em autenticação e autorização robustas via JWT, persistência relacional com PostgreSQL, documentação interativa com OpenAPI (Swagger) e suporte nativo a Docker Compose para orquestração de ambiente de desenvolvimento.

---

#### 🚀 (https://github.com/r0bs0ncarl0s/java_threads_spring_boot)
> **Stack:** Java 21, Spring Boot 3.2.0, Spring Security 6 + Auth0 Java-JWT (4.4.0), Spring Data JPA + MySQL Connector, Flyway Migration (Core + MySQL Extension), Hibernate Validator / Bean Validation, Spring Starter Mail, JUnit 5 + Spring Security Test.

API RESTful backend moderna construída com Java 21 e Spring Boot 3.2, voltada para o ecossistema e gerenciamento de e-commerce/petshop (Adopet Store). O projeto combina segurança avançada, versionamento automatizado de banco de dados, validação rigorosa de dados de entrada e envio assíncrono de e-mails para notificações do sistema.

---

### ⚙️ Boas Práticas e Engenharia de Software

* **Clean Architecture & SOLID**: Separação clara de responsabilidades entre camadas (Controllers, Services, Repositories, DTOs e Mappers), garantindo baixo acoplamento e alta coesão.
* **Segurança por Padrão (Security-First)**:
  * Autenticação Stateless (JWT) e OAuth2 com permissões refinadas via Spring Security.
  * Sanitização de dados de entrada, proteção contra CSRF/CORS e validação de requisições automatizadas (reCAPTCHA).
  * Gestão segura de credenciais usando variáveis de ambiente e arquivos `.env` (nunca expostos no controle de versão).
* **Mapeamento Performático**: Padrão DTO implementado com **MapStruct**, garantindo conversões do/para o banco em tempo de compilação sem overhead de *reflection*.
* **Resiliência & Tolerância a Falhas**: Aplicação do padrão **Circuit Breaker** (com Resilience4j) e estratégias de **Dead Letter Queue (DLQ)** para tratamento elegante de falhas em integrações externas (HTTP/SOAP).
* **Concorrência Otimizada**: Uso consciente de processamento assíncrono (`CompletableFuture`), pools de threads customizados (`ThreadPoolExecutor`) e logging não-bloqueante via Log4j2 + LMAX Disruptor.
* **Gestão e Versionamento de Banco de Dados**: Controle de evolução de schemas via **Flyway Migrations**, garantindo compilações e deploys reprodutíveis.
* **Qualidade de Código & Testes**:
  * Testes unitários e de integração utilizando **JUnit 5**, **Mockito** e **Spring Security Test**.
  * Código declarativo e conciso com suporte ao Java 17+ / Java 21 e Lombok.
* **Padronização Git & CI/CD**:
  * Histórico de commits claro usando o padrão **Conventional Commits** (`feat:`, `fix:`, `refactor:`).
  * Estruturação de `.gitignore` rigorosa para isolar binários (`target/`), arquivos de configuração local e chaves de segurança.
  * Automação de builds e testes via **GitHub Actions**. 

---

### 📫 Como me encontrar

* 💼 **LinkedIn:** [robson-carlos-figueiredo](https://www.linkedin.com/in/robson-carlos-figueiredo-b0475520/)
* ✉️ **E-mail:** [r0bs0ncarl0s@hotmail.com](mailto:r0bs0ncarl0s@hotmail.com)
