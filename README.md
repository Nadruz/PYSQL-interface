# 🗄️ PYSQL Interface

> Sistema de Cadastro de Clientes com **Python**, **Tkinter** e **SQLite**

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/Database-SQLite-003B57?logo=sqlite&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![License](https://img.shields.io/badge/License-Educational-blue)

---

## 📖 Sobre o Projeto

O **PYSQL Interface** é uma aplicação desktop desenvolvida em **Python**, utilizando **Tkinter** para a interface gráfica e **SQLite** como banco de dados local.

O projeto executa operações completas de **CRUD** (*Create, Read, Update e Delete*) para o cadastro de clientes, sendo ideal para **fins educacionais**, estudos de **interfaces gráficas** e **persistência de dados**.

---

## ✨ Funcionalidades

- ➕ Cadastrar clientes  
- 📋 Listar clientes cadastrados  
- 🔍 Buscar por nome, sobrenome, email ou CPF  
- ✏️ Editar cliente selecionado  
- 🗑️ Excluir cliente  
- 💾 Salvamento automático em SQLite  

---

## 🖼️ Interface Gráfica

- Campos de entrada de dados
- Lista de clientes com barra de rolagem
- Botões para todas as operações CRUD
- Interface simples e intuitiva

---

## 📂 Estrutura do Projeto

```text
PYSQL-interface/
│
├── main.py
├── database.db
├── dist/
│   └── PYSQL-interface.exe   # Executável para testes
├── README.md
└── requirements.txt
````

---

## ▶️ Como Executar o Projeto

### 🔹 Opção 1 — Executável (Recomendado para Testes)

Se você **não possui Python instalado**, basta:

1. Acessar a pasta `dist/`
2. Executar o arquivo:

   ```text
   PYSQL-interface.exe
   ```

✔️ Nenhuma instalação adicional é necessária.

> ⚠️ **Observação:** Alguns antivírus podem alertar sobre executáveis gerados por ferramentas como PyInstaller.
> O arquivo é seguro e apenas executa o código Python do projeto.

---

### 🔹 Opção 2 — Executar pelo Código Fonte

#### Pré-requisitos

* Python **3.8 ou superior**

#### Passos

```bash
git clone https://github.com/Nadruz/PYSQL-interface.git
cd PYSQL-interface
python main.py
```

---

## 🎯 Objetivo Educacional

Projeto desenvolvido para fins de aprendizado, abordando:

* CRUD com SQLite
* Interfaces gráficas com Tkinter
* Estruturação de projetos Python
* Geração de executáveis com PyInstaller

---

## 🛠️ Tecnologias Utilizadas

* Python
* Tkinter
* SQLite

---

## 👤 Autor

Desenvolvido por **Nadruz**
🔗 GitHub: [https://github.com/Nadruz](https://github.com/Nadruz)

---

## 📝 Licença

Projeto de uso **educacional**.
