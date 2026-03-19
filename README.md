# 🚀 Fundamentos Node.js (sem frameworks)

Projeto desenvolvido com o objetivo de aprender **Node.js puro**, sem o uso de frameworks como Express, baseado no desafio da Rocketseat Ignite.

Aqui a ideia foi entender **como tudo funciona por baixo dos panos**: HTTP, rotas, streams, manipulação de dados e estrutura de uma API.

---

## 📌 Sobre o projeto

Esta aplicação é uma **API REST de gerenciamento de tarefas (CRUD)** construída apenas com recursos nativos do Node.js.

Funcionalidades implementadas:

- ✅ Criar uma nova tarefa
- ✅ Listar todas as tarefas
- ✅ Buscar tarefas com filtros
- ✅ Atualizar uma tarefa
- ✅ Remover uma tarefa
- ✅ Marcar tarefa como concluída
- ✅ Importar tarefas via arquivo CSV

---

## 🧠 Conceitos aplicados

Este projeto foca nos fundamentos mais importantes do backend:

- HTTP (requests, responses, status codes)
- Métodos HTTP (GET, POST, PUT, DELETE)
- Streams no Node.js
- Manipulação de JSON
- Estruturação de rotas sem frameworks
- Persistência em memória
- Manipulação de arquivos (CSV)
- Organização de código

---

## ⚙️ Tecnologias utilizadas

- Node.js (puro)
- JavaScript
- CSV Parse (para importação de tarefas)

---

## ▶️ Como executar o projeto

### 1. Clone o repositório

```bash
# Clone com HTTPS 
git clone https://github.com/mffdeo/fundamentos-node-rocketseat.git

# Clone com SSH
git clone git@github.com:mffdeo/fundamentos-node-rocketseat.git

# Acesse a pasta
cd fundamentos-node-rocketseat

# Instale as dependências
npm install

# Rode o projeto
npm run autoserver