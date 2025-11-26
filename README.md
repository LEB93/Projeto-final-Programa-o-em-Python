<img width="862" height="731" alt="image" src="https://github.com/user-attachments/assets/39864e31-b14d-45eb-8d74-a8bc41cefdb5" /># Projeto final de Programação em Python - Senai.

📘 Sobre o projeto

Este projeto foi desenvolvido para demonstrar um CRUD completo (Create, Read, Update, Delete) utilizando Python com interface gráfica.
Ele gerencia perfis de investidores, registrando:

CPF
Nível de experiência
Objetivo financeiro
Tolerância ao risco

Tudo é armazenado localmente em um banco SQLite.

⚙ Funcionalidades

✔ Cadastrar um novo perfil
✔ Listar todos os perfis cadastrados
✔ Atualizar dados de um perfil selecionado
✔ Deletar um perfil permanentemente
✔ Interface moderna com CustomTkinter
✔ Dados persistentes armazenados em SQLite

🖼 Demonstração da interface

(Opcional — você pode adicionar uma imagem aqui)
Exemplo:

![Screenshot](image./img/interface.png)

🛠 Tecnologias utilizadas

🐍 Python 3.10
🖼 Tkinter
🎨 CustomTkinter
🗄 SQLite3
🪟 ttk Treeview

🚀 Como executar

1️⃣ Instale o Python - Versão recomendada: 3.10 ou superior
2️⃣ Instale a biblioteca CustomTkinter - pip install customtkinter
3️⃣ Baixe o projeto e execute: python main.py

Na primeira execução, o arquivo banco.db será criado automaticamente.

🗂 Estrutura do banco de dados

Tabela: perfil_investidor
Campo	        Tipo
cpf	          TEXT
experiencia	  TEXT
objetivo	    TEXT
risco	        TEXT

🪟 Interface gráfica (Tkinter + CustomTkinter)

Frames organizam a tela
Labels e Entries recebem dados
ComboBox escolhe o nível de risco
Botões chamam as funções CRUD
Treeview exibe a tabela completa
O código garante boa usabilidade e aparência moderna.

👤 Autor - Luis Eduardo (LEB93)
