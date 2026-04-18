# 🧪 Automação de Testes E2E com Cypress

## 📌 Sobre o projeto
Este projeto tem como objetivo demonstrar a automação de testes end-to-end (E2E) em aplicações web utilizando o Cypress.

Os testes simulam o comportamento do usuário em cenários reais, validando funcionalidades críticas da aplicação.

---

## 🚀 Tecnologias utilizadas

- Cypress
- JavaScript
- Node.js

---

## 🧪 Cenários testados

- Gerenciamento de tarefas (CRUD)
- Validação de regras de negócio
- Testes end-to-end (E2E)
- Validação de interface e comportamento

## 🔍 Cenários de teste detalhados

### 📝 Cadastro de tarefas

**Cenário: Cadastrar nova tarefa**
- Informar nome da tarefa
- Criar nova tarefa
- Validar exibição na lista

**Cenário: Não permitir tarefa duplicada**
- Criar uma tarefa existente
- Tentar cadastrar novamente
- Validar mensagem de erro: "Task already exists!"

**Cenário: Campo obrigatório**
- Tentar criar tarefa sem nome
- Validar mensagem de campo obrigatório

---

### 🔄 Atualização de tarefas

**Cenário: Concluir tarefa**
- Criar uma tarefa pendente
- Marcar como concluída
- Validar alteração visual (texto riscado)

---

### ❌ Exclusão de tarefas

**Cenário: Remover tarefa**
- Criar uma tarefa
- Remover tarefa
- Validar que não está mais visível na lista

---

### 🌐 Validação da aplicação

**Cenário: Aplicação online**
- Acessar a aplicação
- Validar título da página

---

## 📂 Estrutura do projeto

```
cypress/
├── e2e/
├── fixtures/
├── support/
```
---

## ▶️ Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/WeslenFurtado/cypress_eXpress.git
```
### 2. Instalar dependências

```bash
npm install
```
### 3. Executar os testes

```bash
npx cypress open
```
ou

```bash
npx cypress run
```
---

## 📊 Objetivo

Demonstrar boas práticas em automação de testes, incluindo organização de código, reutilização de comandos e validação de cenários críticos.

---

## 💡 Observações

Este projeto foi desenvolvido com foco em aprendizado e evolução na área de Qualidade de Software.
