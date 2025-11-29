# 🎓 Islanders Fullstack Project

[![Status](https://img.shields.io/badge/status-in%20progress-yellow)](https://github.com/goliv/islanders-fullstack)
[![Python](https://img.shields.io/badge/python-3.13-blue)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100.0-green)](https://fastapi.tiangolo.com/)
[![Angular](https://img.shields.io/badge/Angular-17-red)](https://angular.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue)](https://www.postgresql.org/)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

---

## 🔹 Sobre o Projeto

O **Islanders Fullstack Project** é uma plataforma educacional em desenvolvimento, pensada para estudantes, professores e administradores de uma instituição fictícia/real. O objetivo principal é criar um ambiente interativo onde:

- **Estudantes (Guest)** podem assistir a vídeos de cursos, realizar quizzes e receber **badges** por desempenho, que futuramente poderão gerar benefícios ou descontos na instituição.  
- **Professores** terão acesso a dashboards restritos, podendo acompanhar o progresso dos estudantes e gerir conteúdos.  
- **Administradores** terão controle total sobre usuários, cursos e dashboards da plataforma.

O projeto integra **backend em FastAPI + SQLAlchemy** e **frontend em Angular**, com foco em autenticação segura via JWT, roles e permissões diferenciadas.

---

## 🔹 Tecnologias

**Backend:**
- Python 3.13
- FastAPI
- SQLAlchemy (ORM)
- PostgreSQL (Neon - BD remota)
- JWT para autenticação

**Frontend:**
- Angular 17
- TypeScript
- HTML/CSS

**Outras ferramentas:**
- Postman para testes API

---

## 🔹 Funcionalidades (Em andamento)

- [x] Registro de usuários Guest (com valores default)
- [x] Login com autenticação JWT
- [x] Perfis de usuário com roles: Guest, Student, Professor, Admin
- [x] AuthGuard no frontend para proteger rotas
- [ ] Dashboard diferenciado por roles
- [ ] Sistema de badges
- [ ] Refresh token e logout automático
- [ ] Integração completa frontend/backend
- [ ] Testes unitários e end-to-end

---

## 🔹 Estrutura do Projeto

```text
islanders-fullstack/
│
backend/
├─ app/
│ ├─ api/v1/routers/ # Endpoints da API
│ ├─ services/ # Lógica de negócio
│ ├─ models/ # Modelos ORM
│ ├─ schemas/ # Pydantic schemas
│ └─ core/ # Config, segurança, deps
frontend/
├─ src/app/
| ├─ componnents/ #Componentes necessários
│ ├─ pages/ # Páginas, como frontoffice e backoffice
│ ├─ services/ # Serviços Angular
│ └─ guards/ # AuthGuard
etc...
```


---

## 🔹 Próximos Passos

- Implementação completa do **dashboard** por roles.  
- Sistema de **badges e conquistas** para estudantes.  
- Implementar **refresh token** e **logout automático**.  
- Melhorar testes e documentação da API.  
- Deploy para ambiente de teste.

---

## 🔹 Team

- Desenvolvedores: Gonçalo Oliveira, Lucas Morim e Ruben Teixeira  
- GitHub:

[github.com/Gonçalo Oliveira](https://github.com/goncalo-f-oliveira)

[github.com/Lucas Morim](https://github.com/lucas-morim)

[github.com/Rúben Teixeira](https://github.com/rubenfteixeira)

---

> ⚠️ Este projeto está em desenvolvimento e muitas funcionalidades ainda estão sendo implementadas.

