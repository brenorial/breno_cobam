# 🎓 Sistema de Gestão Escolar - Reserva de Pré-Matrícula

Este projeto é a **primeira etapa** de um sistema web completo para **gestão escolar**, com foco inicial no cadastro e reserva de pré-matrícula de alunos. A aplicação está sendo construída em camadas, com frontend modular e backend com API REST utilizando Flask.

---

## 📌 Objetivo

Criar uma plataforma que permita o gerenciamento de alunos, turmas e matrículas escolares, com foco inicial no **cadastro e exclusão de alunos**, integrando futuramente recursos administrativos, relatórios e autenticação de usuários.

---

## 🧱 Tecnologias Utilizadas

### 🔹 Frontend

- **HTML5 + CSS3 (Flexbox)**
- **JavaScript Vanilla**
- **Google Fonts (Montserrat)**
- Componentes HTML reutilizáveis (navbar, sidebar, footer)
- Estrutura modular para futura integração com frameworks JS

### 🔹 Backend

- **Python 3**
- **Flask OpenAPI 3** – Geração automática de documentação (Swagger, Redoc, RapiDoc)
- **SQLAlchemy** – ORM para banco de dados
- **Flask-CORS** – Permite requisições entre domínios
- **Log Customizado** – Logs de erro e debug com controle

---

## 🗂️ Estrutura do Projeto

```

project-root/
│
├── frontend/
│ ├── index.html
│ ├── script.js
│ ├── styles/
│ │ └── style.css
│ ├── assets/
│ │ └── img/
│ │ └── cobam.png
│ └── components/
│ ├── navbar.html
│ ├── sidebar.html
│ └── footer.html
│
├── backend/
│ ├── main.py # Arquivo principal com rotas da API
│ ├── model.py # Modelo de dados com SQLAlchemy
│ ├── schemas/ # Schemas Pydantic (entrada e saída de dados)
│ ├── logger.py # Configuração de logs
│ └── requirements.txt # Dependências do backend
│
└── README.md

```

---

## 🔁 Funcionalidades Atuais

### ✅ Frontend

- Interface para visualização da lista de alunos
- Layout responsivo e estruturado
- Componentes reutilizáveis (navbar, sidebar, etc)

### ✅ Backend

- **POST `/aluno`**: Cadastra um novo aluno (valida duplicidade de CPF)
- **DELETE `/del_aluno`**: Remove um aluno com base no CPF
- Documentação automática em `/openapi`

---

## 🚀 Como Executar

### Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
python main.py
```

### Frontend

Basta abrir `frontend/index.html` em um navegador moderno.

---

## 📚 Próximas Etapas

- Integração frontend-backend via fetch/AJAX
- Tela de listagem de alunos (GET)
- Cadastro completo com validações visuais
- Autenticação (login/admin)
- Dashboard administrativo

---

## 🧠 Observações

Este projeto está sendo desenvolvido de forma incremental e modular para facilitar a manutenção e expansão. Ele pode servir como base para outros sistemas escolares com necessidades semelhantes.

---

## 👨‍💻 Desenvolvido por

Breno Almeida. Projeto educacional de sistema escolar com frontend modular e backend documentado via OpenAPI 3.
