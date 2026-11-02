# Taspy — Gerenciador de Tarefas

Taspy é uma aplicação web para organização de projetos e tarefas, desenvolvida com foco em simplicidade, produtividade e aprendizado prático de desenvolvimento web.

O projeto permitirá que usuários criem seus próprios projetos, organizem tarefas, definam prioridades e prazos e acompanhem o andamento das atividades através de um quadro Kanban.

## Status do projeto

**[Em desenvolvimento]**

O projeto está sendo construído gradualmente, começando pela estrutura da aplicação e seguindo para autenticação, gerenciamento de projetos, tarefas e Kanban.

## Funcionalidades planejadas

- Cadastro e autenticação de usuários
- Criação de projetos
- Edição e exclusão de projetos
- Criação de tarefas
- Definição de prazos
- Definição de prioridades
- Edição e exclusão de tarefas
- Organização das tarefas por status
- Quadro Kanban [A fazer, Em andamento, Concluído]
- Proteção dos dados de cada usuário

## Tecnologias

O Taspy será desenvolvido utilizando:

- **HTML5**
- **CSS3**
- **JavaScript**
- **Supabase**
  - Authentication
  - PostgreSQL
  - Row Level Security (RLS)

## Identidade visual

A interface do Taspy utiliza uma identidade visual simples e moderna, voltada para aplicações de produtividade.

| Uso                    | Cor       |

| Fundo principal        | `#F8FAFC` |
| Cards                  | `#FFFFFF` |
| Cor principal          | `#6366F1` |
| Hover                  | `#4F46E5` |
| Texto principal        | `#0F172A` |
| Texto secundário       | `#64748B` |
| Bordas                 | `#E2E8F0` |
| Sucesso                | `#22C55E` |
| Alerta                 | `#F59E0B` |
| Erro / prioridade alta | `#EF4444` |

## Estrutura inicial

```text
taspy/
│
├── index.html
│
├── pages/
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
│
├── css/
│   ├── global.css
│   ├── auth.css
│   └── dashboard.css
│
├── js/
│   ├── supabase.js
│   ├── auth.js
│   ├── projects.js
│   ├── tasks.js
│   └── dashboard.js
│
├── assets/
│   └── images/
│
├── README.md
└── .gitignore
```

## Roadmap

### Etapa 1 — Estrutura e interface
- [x] Definir nome do projeto
- [x] Criar estrutura inicial
- [x] Definir identidade visual
- [ ] Criar página inicial
- [ ] Criar estilos globais

### Etapa 2 — Autenticação
- [ ] Configurar Supabase
- [ ] Cadastro de usuário
- [ ] Login
- [ ] Logout
- [ ] Proteção das páginas privadas

### Etapa 3 — Projetos
- [ ] Criar projetos
- [ ] Listar projetos
- [ ] Editar projetos
- [ ] Excluir projetos

### Etapa 4 — Tarefas
- [ ] Criar tarefas
- [ ] Editar tarefas
- [ ] Excluir tarefas
- [ ] Definir prioridades
- [ ] Definir prazos

### Etapa 5 — Kanban
- [ ] Coluna "A fazer"
- [ ] Coluna "Em andamento"
- [ ] Coluna "Concluído"
- [ ] Movimentação de tarefas entre status

## Objetivo

O Taspy está sendo desenvolvido como um projeto prático para aplicar e aprofundar conhecimentos em desenvolvimento web, JavaScript, autenticação, banco de dados e integração com serviços externos.