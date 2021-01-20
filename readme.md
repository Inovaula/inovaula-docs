# Inovaula Documentação

---
## Visão Geral
Repositório base da documentação do projeto Inovaula.

---
## Tabela de Conteúdo

- Projeto
  - Produtos
  - Resources
  - Structure
  - Repositórios
  - Estrutura de arquivo
- Design
- Backend
- Frontend
  - Mobile
  - Web
    - Aplicativo Cliente
    - Painel Administrativo
    - Website    
- Infraestrutura
- Serviços

---
## Projeto

Sistema de gestão e compartilhamento de experiências de aprendizagem.
inovaula.com

### Recursos

- Documentação
- Discord
- Trello
- Figma
- Google Sheet

### Repositórios

- [inovaula-api](https://github.com/Inovaula/inovaula-api) - API principal.
- [inovaula-async](https://github.com/Inovaula/inovaula-async) - Serviço de tarefas assíncronas.
- [inovaula-chat](https://github.com/Inovaula/inovaula-chat) - Serviço de chat.
- [inovaula-docs](https://github.com/Inovaula/inovaula-docs) - Documentação do projeto.
- [inovaula-mobile](https://github.com/Inovaula/inovaula-mobile) - Aplicativos mobile.
- [inovaula-client](https://github.com/Inovaula/inovaula-client) - Aplicativo web público, principal.
- [inovaula-dashboard](https://github.com/Inovaula/inovaula-dashboard) - Aplicativo web privado, painel administrativo.
- [inovaula-landing](https://github.com/Inovaula/inovaula-landing) - Website público, principal.
- [inovaula-iac](https://github.com/Inovaula/inovaula-iac) - Infraestrutura e manutenção.

### Domínios

### Estrutura de arquivo

Estrutura de arquivo.

```
inovaula
│
├── backend
│   ├── api
│   ├── async
│   ├── cache
│   ├── chat
│   └── database
├── design
│   ├── icons
│   ├── images
│   ├── logos
│   └── references
├── docs
│   ├── backend
│   ├── design
│   ├── frontend
│   ├── iac
│   └── project
│       └── structure     <-- we are here!
├── frontend
│   ├── mobile
│   └── web
│       ├── client
│       ├── dashboard
│       └── landing
├── iac
│   ├── aws
│   ├── backend
│   ├── frontend
│   └── maintenance
└── meta
    ├── credentials
    ├── meetings
    ├── messages
    ├── proposals
    ├── reports
    └── requirements
```

### Requirements



---
## Design

Mobile first

---
## Backend

### API

Serviço escrito em Python, Django Rest Framework.

### Async

Serviço de fila de processamento assíncrono desenvolvido em Python, Celery, Redis e RabbitMQ.

### Cache

Servidor Redis.
Serviço provido pela AWS ElastiCache.

### Chat

Serviço em NodeJS, Express.

### Database

Serviço provido pela AWS RDS.
Instância t2.small

---
## Frontend

reference: https://gist.github.com/tkrotoff/b1caa4c3a185629299ec234d2314e190

---
## Infraestrutura

---
## Serviços
