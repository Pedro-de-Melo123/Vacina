# Vacina 💉
Repositório de Desenvolvimento e Postagem do Sistema Gerenciador de Vacinas para Clínicas de Vacinação na Grande Vitória.

Este sistema tem como objetivo auxiliar o Gerenciamento de Vacinas em Clínicas de Vacinação, de forma que seja possível realizar o Controle de Estoque, Agendamentos e Procedimentos. Ao fim deste projeto, pretendemos entregar um sistema plenamente funcional que seja capaz de:

## Funcionalidades 🛠️

- **Cadastrar**:
  - 👨‍💼 Funcionários
  - 🧑‍💻 Clientes
  - 💉 Vacinas
- 📅 Agendar Vacinas
- ⏰ Alertar sobre Vacinas Próximas
- 🗂️ Manter um Histórico Detalhado de cada Aplicação de Vacina realizada
- 📦 Gerenciar o Estoque, dando baixa quando uma Vacina for aplicada e atualizando o Estoque quando um novo carregamento de Vacinas chegar

## Tecnologias Usadas 🧑‍💻

### Front-End 🖥️
- 🌐 HTML
- 🎨 CSS
- 💻 JavaScript
- ⚛️ React
- 🔗 Fetch API

### Back-End 🏗️
- ⚙️ ASP.NET Core Web API Framework
- 🖊️ C#
- 📦 Entity Framework Core (EF Core)
- 🔐 JWT (JSON Web Token)
- 📚 NuGet Packages

### Banco de Dados 🗄️
- 🐬 MySQL
- 🔌 MySql.Data

### Ferramentas de Desenvolvimento 🛠️
- 💻 Visual Studio / VS Code
- 🟢 Node.js
- 📦 npm
- 🧬 Git
- 🐙 GitHub

## Fluxo de Telas

### 1. Login / Autenticação
- Tela de Login
  - Usuário + senha
  - Recuperação de senha
  - Controle de acesso baseado em permissões (admin, funcionário etc.)

---

### 2. Dashboard (Tela Inicial)
- Resumo rápido:
  - Número de clientes cadastrados
  - Estoque atual de vacinas
  - Próximas vacinas com validade próxima
  - Acesso rápido para “Novo Cadastro” (funcionário, cliente, vacina)

---

### 3. Gestão de Funcionários 👨‍💼
- **Lista de Funcionários**
  - Busca e filtros
  - Ações: Editar | Excluir | Detalhes
- **Cadastro/Edição de Funcionário**
  - Nome, CPF, contato
  - Cargo/função
  - Definição de permissões (admin, atendente, vacinador)
- **Controle de Permissões**
  - Tela para atribuir funções
  - Configuração do que cada perfil pode acessar (CRUD, relatórios, estoque etc.)

---

### 4. Gestão de Clientes 🧑‍💻
- **Lista de Clientes**
  - Busca por nome/CPF
  - Ações: Editar | Excluir | Histórico
- **Cadastro/Edição de Cliente**
  - Nome, CPF, data de nascimento, contato
  - Informações de saúde relevantes (alergias, observações)
- **Histórico de Vacinas**
  - Linha do tempo das vacinas aplicadas
  - Informações: data, lote, validade, profissional responsável

---

### 5. Gestão de Vacinas 💉
- **Lista de Vacinas**
  - Nome da vacina, fabricante, quantidade em estoque, validade mais próxima
  - Ações: Editar | Excluir | Registrar Aplicação
- **Cadastro/Edição de Vacina**
  - Nome, fabricante
  - Descrição (doença alvo, doses necessárias)
- **Gestão de Lotes**
  - Registro de novos lotes
  - Campos: lote, quantidade, data de fabricação, validade
- **Aplicação de Vacina**
  - Seleção do cliente
  - Seleção da vacina e lote
  - Atualização automática do estoque
  - Registro de profissional aplicador

---

### 6. Relatórios (Opcional 📊)
- Vacinas aplicadas por período
- Estoque atual e vacinas prestes a vencer
- Registro de funcionários ativos

---

## Objetivos / Entregas ✅

- 📝 **Documentação do Projeto**
  - [ ] Criar README detalhado com tecnologias, funcionalidades e instruções
  - [ ] Elaborar diagrama de fluxo do sistema
  - [ ] Definir modelagem do banco de dados

- 👨‍💼 **Gestão de Funcionários**
  - [ ] Cadastro, edição e exclusão de funcionários
  - [ ] Controle de permissões e acessos

- 🧑‍💻 **Gestão de Clientes**
  - [ ] Cadastro, edição e exclusão de clientes
  - [ ] Visualização de histórico de vacinas aplicadas

- 💉 **Gestão de Vacinas**
  - [ ] Cadastro, edição e exclusão de vacinas
  - [ ] Registro de lotes e validade
  - [ ] Atualização automática do estoque ao aplicar vacinas

- 📅 **Agendamento de Vacinas**
  - [ ] Criar e gerenciar agendamentos
  - [ ] Enviar notificações de lembrete aos clientes

- ⏰ **Alertas e Notificações**
  - [ ] Lembretes de vacinas próximas
  - [ ] Alertas de estoque baixo

- 🗂️ **Histórico Detalhado**
  - [ ] Registro completo de todas as aplicações
  - [ ] Filtros por cliente, vacina ou data

- 📦 **Controle de Estoque**
  - [ ] Entrada de novos lotes de vacinas
  - [ ] Baixa automática ao aplicar vacinas
  - [ ] Relatórios de estoque atual e histórico

- 🖥️ **Interface Front-End**
  - [ ] Design responsivo e intuitivo
  - [ ] Visualização clara de agendamentos e histórico
  - [ ] Funcionalidades de CRUD para todas as entidades

- 🏗️ **Back-End e API**
  - [ ] Implementação de REST API com ASP.NET Core
  - [ ] Segurança via JWT
  - [ ] Validação de dados e tratamento de erros

- 🗄️ **Banco de Dados**
  - [ ] Modelagem relacional eficiente
  - [ ] Criação de tabelas e relacionamentos
  - [ ] Integração com o back-end via EF Core

- 🛠️ **Ferramentas de Desenvolvimento**
  - [ ] Configuração de ambiente local e repositório Git
  - [ ] Integração contínua (CI/CD) se aplicável
  - [ ] Versionamento e controle de alterações no GitHub

