# PYSQL-interface
  
Sistema de Cadastro de Clientes com Python, Tkinter e SQLite

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![SQLite](https://img.shields.io/badge/Database-SQLite-lightgrey)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green)
![License](https://img.shields.io/badge/License-Educational-blue)

---

## 📖 Descrição

O **PYSQL** é uma aplicação desktop desenvolvida em Python que realiza operações de **CRUD** (Create, Read, Update e Delete) para cadastro de clientes.  
A interface gráfica é construída com **Tkinter** e os dados são persistidos utilizando **SQLite**.

Projeto ideal para fins **educacionais**, demonstrando integração entre interface gráfica e banco de dados.

---

## ✨ Funcionalidades

- ➕ Inserir novos clientes  
- 📋 Listar todos os clientes cadastrados  
- 🔍 Buscar clientes por nome, sobrenome, email ou CPF  
- ✏️ Atualizar cliente selecionado  
- 🗑️ Deletar cliente selecionado  
- 💾 Persistência automática em banco de dados SQLite  

---

## 🖥️ Interface

A aplicação possui:
- Campos de entrada de dados
- Lista de clientes com barra de rolagem
- Botões para todas as operações CRUD

---

## 📂 Estrutura do Projeto

```text
.
├── aplicacao.py    # Arquivo principal (Controller)
├── backend.py      # Camada de dados (SQLite)
├── interface.py    # Interface gráfica (Tkinter)
├── clientes.db     # Banco de dados (gerado automaticamente)
└── README.md
