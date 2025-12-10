# 💰 FINANCE_PSW

Sistema de gestão financeira pessoal desenvolvido para auxiliar usuários a controlar contas, organizar receitas e despesas, visualizar extratos e planejar melhor sua vida financeira. 
Criado durante o curso Pythonando

---

## 🧾 Sobre o Projeto

O **FINANCE_PSW** foi criado com o objetivo de oferecer uma ferramenta simples e funcional para acompanhamento financeiro.  
Ele permite registrar transações, monitorar saldos, gerenciar contas e visualizar informações de forma organizada e acessível.

---

## 🚀 Funcionalidades

- 📌 Cadastro e gerenciamento de contas  
- 💸 Registro de despesas e receitas  
- 📊 Visualização de extratos  
- 📅 Planejamento financeiro  
- 👤 Módulo de perfil  
- 🎨 Interface organizada utilizando templates HTML e ícones  
- 🗂️ Estrutura modular para facilitar manutenção e expansão

---

## 🧰 Tecnologias Utilizadas

- **Python**  
- **Django** 
- **SQLite**  
- **HTML / CSS**  
- **Arquitetura modular**  

---

## 📁 Estrutura do Projeto

FINANCE_PSW/

├── contas/ # Gerenciamento de contas financeiras

├── core/ # Configurações principais e lógica base

├── extrato/ # Controle de extratos e transações

├── perfil/ # Informações do usuário

├── planejamento/ # Funcionalidades de planejamento financeiro

├── templates/ # Templates HTML da aplicação

├── media/icones/ # Ícones usados na interface

├── db.sqlite3 # Banco de dados SQLite

├── manage.py # Arquivo principal para rodar o projeto

└── .gitignore


---

## ▶️ Como Rodar o Projeto

1. **Clone o repositório**
   ```bash
   git clone https://github.com/NicolasWanderley98/FINANCE_PSW.git
   cd FINANCE_PSW

Crie um ambiente virtual

python -m venv .venv

Ative:

Windows: .venv\Scripts\activate

Linux/Mac: source .venv/bin/activate

Execute o servidor

python manage.py runserver

Acesse no navegador

http://127.0.0.1:8000/

Rotas principais da aplicação

http://127.0.0.1:8000/perfil/home/

http://127.0.0.1:8000/perfil/gerenciar/

http://127.0.0.1:8000/planejamento/definir_planejamento/

http://127.0.0.1:8000/planejamento/ver_planejamento/

http://127.0.0.1:8000/contas/ver_contas/

http://127.0.0.1:8000/perfil/dashboard/

http://127.0.0.1:8000/extrato/view_extrato/

🧪 Demonstração

<img width="1354" height="1378" alt="home" src="https://github.com/user-attachments/assets/02f791e0-12ca-4789-b298-acc3c3b4980d" />

<img width="1354" height="945" alt="gerenciar" src="https://github.com/user-attachments/assets/d2abfc21-3e92-407b-8d18-9f8ea1d42b44" />


