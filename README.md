# 📚 UPX 2 💻
## Equipe: ReConstrói 🍃
---
### 🌳 Desenvolvimento Sustentável ♻️

## 💡 SISTEMA DE GERENCIAMENTO DE RESÍDUOS NA GESTÃO DE OBRAS

> ✏️ Este repositório contém uma aplicação Spring Boot desenvolvida para gerenciar obras, materiais, posts e usuários. O sistema fornece uma API completa integrada com autenticação, autorização e persistência de dados.

### Tecnologias Utilizadas
- Java 17
- Spring Boot
- Spring Security (JWT)
- Spring Data JPA
- Maven
- Docker e Docker Compose
- HTML e CSS (templates com Thymeleaf)

### Principais Funcionalidades

✅ Autenticação e Autorização
- Login e cadastro de usuários
- Controle de permissões
- Configuração de segurança via SecurityConfig.java

✅ Gerenciamento de Obras
- CRUD de obras
- Relacionamento com materiais e posts

✅ Materiais
- Cadastro e listagem de materiais
- Camada de serviço e repositório dedicado

✅ Posts e Itens do Post
- Criação e gerenciamento de posts vinculados às obras
- Controle de status
- CRUD de itens internos dos posts

✅ Usuários
- Cadastro, autenticação e gerenciamento
- Entidades completas para usuário, papéis e unidades

✅ Estrutura do Projeto
- `controllers/` – Controladores REST
- `services/` – Lógica de negócios
- `repositorys/` – Interfaces JPA
- `model/` – Entidades
- `dto/` – Objetos de transferência de dados
- `config/` – Configurações de segurança
- `static/` e `templates/` – Recursos de interface

O projeto inclui um arquivo docker-compose para facilitar a execução do ambiente.
O projeto inclui um arquivo docker-compose para facilitar a execução do ambiente.
