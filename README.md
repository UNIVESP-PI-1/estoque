# estoque
Projeto Integrador 1 da Univesp - Curso de Engenharia da Computação

Este projeto é uma aplicação web desenvolvida em Django para o gerenciamento de estoque.

---

## 🚀 Como rodar o projeto localmente

Siga os passos abaixo para configurar o ambiente de desenvolvimento em sua máquina.

### 1. Clonar o repositório
Abra o terminal e execute:
```bash
git clone [https://github.com/SEU-USUARIO/estoque.git](https://github.com/SEU-USUARIO/estoque.git)
cd estoque
```
### 2.Crie o ambiente de desenvolvimento

* No Windows:
```bash
python -m venv venv
.\venv\Scripts\activate
```

* No Linux ou macOS:
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Instalar as dependências
```bash
pip install -r requirements.txt
```

### 4. Configurar o Banco de Dados (Migrações)
```bash
python manage.py migrate
```

### 5. Criar um usuário administrador (Opcional)
```bash
python manage.py createsuperuser
```

### 6.Criar um superusuário
```bash
python manage.py createsuperuser
```

### 7. Iniciar o servidor de desenvolvimento
```bash
python manage.py runserver
```
Agora, acesse no seu navegador: http://127.0.0.1:8000/

### 🛠️ Tecnologias Utilizadas

Linguagem: Python 3.x

Framework Web: Django

Banco de Dados: SQLite (Desenvolvimento)

Controle de Versão: Git