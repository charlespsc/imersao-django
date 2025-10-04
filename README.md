# JJ Investimento

> Projeto desenvolvido em Django para o cliente fictício JJ Investimento, com foco em apresentação institucional e serviços.

## 📋 Descrição
Este repositório contém um site institucional desenvolvido com Django, incluindo páginas de apresentação, serviços e contato.

## 🚀 Pré-requisitos
- Python 3.10+
- pip

## ⚙️ Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/charlespsc/imersao-django.git
   cd imersao-django
   ```
2. (Opcional) Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
3. Instale as dependências:
   ```bash
   pip install django
   ```

## ▶️ Como executar
1. Execute as migrações:
   ```bash
   python manage.py migrate
   ```
2. Inicie o servidor de desenvolvimento:
   ```bash
   python manage.py runserver
   ```
3. Acesse o site em: [http://127.0.0.1:8000](http://127.0.0.1:8000)

## 🗂️ Estrutura do Projeto
- `jj_investimento/` — Configurações do projeto Django
- `page_app/` — Aplicação principal com views, templates e arquivos estáticos
- `db.sqlite3` — Banco de dados SQLite padrão

## ✉️ Contato
- Desenvolvedor: [charlespsc](https://github.com/charlespsc)

---
Projeto para fins educacionais — Imersão Django