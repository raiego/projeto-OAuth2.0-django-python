# Projeto OAuth2.0 Django - Python

Uma aplicação Django que implementa autenticação via **OAuth2.0 com GitHub**, ideal para aprender a integrar login social com segurança usando variáveis de ambiente.

---

## Tecnologias usadas

- Python
- Django
- OAuth2.0 com GitHub (via `django-allauth` ou semelhante)
- Variables de ambiente para segurança (`.env`)
- Estrutura modular com apps em `setup` e `tech`

---

## Funcionalidades

- Login e cadastro automatizado via GitHub
- Armazenamento seguro de credenciais com `os.getenv()`
- Organização de templates e lógica separadas por apps

---

## Como executar localmente

```
# Clonar o repositório
git clone https://github.com/raiego/projeto-OAuth2.0-django-python.git
cd projeto-OAuth2.0-django-python

# Criar e ativar ambiente virtual
python -m venv .venv
.\.venv\Scripts\activate  # Windows
source .venv/bin/activate # Linux/macOS

# Instalar dependências
pip install -r requirements.txt

# Criar .env com chaves (não commite este arquivo!)
SECRET_KEY=...
GITHUB_CLIENT_ID=...
GITHUB_SECRET=...

# Rodar o servidor
python manage.py runserver
```
