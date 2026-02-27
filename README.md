# 🎮 Biblioteca de Jogos – Aplicação Web

Sistema web para gerenciamento e catalogação de jogos, permitindo cadastrar, visualizar, editar e remover registros através de uma interface simples e organizada.

Este projeto foi desenvolvido com foco em prática de desenvolvimento Backend utilizando Java + Spring Boot, aplicando arquitetura MVC, integração com banco de dados e operações CRUD completas.

---

## 🚀 Funcionalidades

- ✅ Cadastro de jogos
- ✅ Listagem de jogos cadastrados
- ✅ Edição de informações
- ✅ Remoção de registros
- ✅ Organização por categorias
- ✅ Interface web integrada ao backend
- ✅ Persistência em banco de dados

---

## 🧱 Arquitetura do Projeto

O sistema segue o padrão MVC (Model–View–Controller):

- Controller → Controle das requisições HTTP
- Service → Regras de negócio
- Repository → Comunicação com banco de dados
- Entity → Modelagem das entidades
- Templates (HTML) → Interface do usuário

---

## 🛠️ Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Maven
- HTML
- CSS
- Thymeleaf
- Banco de Dados Relacional (SQL)
- Docker

---

## 📂 Estrutura do Projeto

```
src
├── controller
├── service
├── repository
├── entity
├── config
└── templates
```

---

## ▶️ Como Executar o Projeto

### 1️⃣ Clonar repositório

```bash
git clone https://github.com/KauanLourenti/biblioteca-de-jogos
```

### 2️⃣ Entrar na pasta

```bash
cd biblioteca-de-jogos
```

### 3️⃣ Executar aplicação

Linux / Mac:

```bash
./mvnw spring-boot:run
```

Windows:

```bash
mvnw.cmd spring-boot:run
```

---

## 🐳 Executar com Docker

```bash
docker build -t biblioteca-jogos .
docker run -p 8080:8080 biblioteca-jogos
```

---

## 🌐 Acessar aplicação

```
http://localhost:8080
```

---

## 💡 Objetivo do Projeto

Este projeto foi desenvolvido como prática de:

- Desenvolvimento Backend com Java
- Construção de APIs e aplicações web
- Integração com banco de dados
- Organização em camadas (MVC)
- Boas práticas com Spring Boot

---

## 👨‍💻 Autor

Kauan de Pádua Lourenti

💼 LinkedIn: https://www.linkedin.com/in/kauan-lourente  
💻 GitHub: https://github.com/KauanLourenti

---

⭐ Projeto desenvolvido para fins educacionais e evolução profissional.
