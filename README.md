# eventos_academicos # 🎓 Sistema de Gerenciamento de Eventos Acadêmicos (Django)

Este projeto é um sistema web desenvolvido em **Django** para gerenciar eventos acadêmicos.  
Permite cadastro e autenticação de usuários, criação e inscrição em eventos, e controle de inscritos pelo administrador.

---

## 🚀 Tecnologias utilizadas
- Python 3.x  
- Django 5.x  
- HTML5, CSS3  
- Banco de dados SQLite3 (padrão do Django)  

---

## ⚙️ Funcionalidades
- Cadastro e autenticação de usuários (nome, e-mail e senha).  
- Login/logout com gerenciamento de sessão.  
- Criação, edição e exclusão de eventos (restrito a administradores).  
- Inscrição em eventos (usuários logados).  
- Prevenção contra múltiplas inscrições no mesmo evento.  
- Área do usuário: listar eventos inscritos.  
- Administrador pode visualizar lista de inscritos por evento.  

---

## 📂 Estrutura do projeto
eventos/ # Pasta raiz do projeto
│
├── core/ # Aplicação principal
│ ├── migrations/ # Arquivos de migração do banco
│ ├── templates/ # Arquivos HTML
│ ├── static/ # Arquivos CSS e JS
│ ├── models.py # Definição das tabelas (Eventos, Inscrições)
│ ├── views.py # Lógica do sistema (controllers)
│ ├── urls.py # Rotas da aplicação
│ └── admin.py # Configuração do admin do Django
│
├── eventos/ # Configurações globais do projeto Django
│ ├── settings.py # Configurações gerais
│ ├── urls.py # Rotas principais
│ └── wsgi.py / asgi.py
│
├── db.sqlite3 # Banco de dados SQLite
├── manage.py # Arquivo principal de execução do Django
├── requirements.txt # Dependências do projeto
└── README.md # Manual do projeto
