# 📝 TaskDesk

**TaskDesk** é uma aplicação web de gerenciamento de tarefas ágil, desenvolvida com foco em simplicidade e visualização clara. Com um design moderno em modo escuro (Dark Mode), o sistema permite organizar tarefas em diferentes seções (como Sprints ou Backlogs) e categorizá-las por status e tipo.

![Status do Projeto](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![Licença](https://img.shields.io/badge/Licença-MIT-blue)

## 🚀 Funcionalidades

- **Gerenciamento de Seções (Cartões):** Crie e exclua contêineres de tarefas (ex: Sprint 1, Backlog Geral).
- **CRUD de Tarefas:**
  - **Criar:** Adicione novas tarefas com título, responsável, estimativa de tempo (SP), status e tipo.
  - **Ler:** Visualização em tabela organizada.
  - **Atualizar:** Clique em qualquer tarefa para editar seus detalhes via modal.
  - **Deletar:** Remova tarefas concluídas ou canceladas.
- **Categorização Visual:**
  - Etiquetas (Badges) coloridas para **Status** (ex: Em andamento, Feito).
  - Etiquetas coloridas para **Tipos** de tarefa (ex: Bug, Feature, Qualidade).
- **Design Responsivo:** Layout adaptável para desktop e dispositivos móveis.
- **Tema Escuro:** Interface agradável visualmente com paleta de cores moderna (`#1e1e2e`).

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica.
- **CSS3:** Estilização com variáveis (CSS Variables), Flexbox e Media Queries.
- **JavaScript (Vanilla):** Lógica de manipulação do DOM e gerenciamento de estado local.
- **Font Awesome:** Ícones para interface.

## 🎨 Sistema de Cores e Etiquetas

O sistema utiliza códigos de cores para facilitar a identificação rápida:

### Status
| Status | Cor | Significado |
| :--- | :--- | :--- |
| **Pronto para começar** | 🔵 Azul | Tarefa definida, aguardando início. |
| **Em andamento** | 🟠 Laranja | Tarefa sendo executada. |
| **Aguardando revisão** | 💠 Ciano | Aguardando QA ou aprovação. |
| **Feito** | 🟢 Verde | Tarefa concluída. |
| **Parado** | 🔴 Vermelho | Tarefa bloqueada. |

### Tipos de Tarefa
| Tipo | Cor |
| :--- | :--- |
| **Qualidade** | 🩷 Rosa |
| **Funcionalidade** | 🟢 Verde |
| **Bug** | 🔴 Vermelho |
| **Teste** | 🟣 Roxo |
| **Segurança** | 🟢 Verde Escuro |
| **Outro** | 🔵 Azul Claro |

## 📂 Estrutura do Projeto

```text
TaskDesk/
│
├── index.html      # Estrutura principal
├── style.css       # Estilos e tema escuro
├── script.js       # Lógica, dados iniciais e manipulação de eventos
└── lista.png       # Favicon da página
