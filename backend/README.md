# 📌 **Explicação da Lógica do sistema de Gestão Escolar**

Este sistema foi desenvolvido para facilitar o gerenciamento de uma **unidade escolar**. O primeiro módulo realizado nesse backend cadastra um novo aluno ao banco de dados, simulando uma pré-matrícula.Posteriormente, abrirá uma aba de finalização da matrícula e envio para a respectiva turma.

## 🌐 **Objetivo do Sistema**

Fornecer uma maneira atual e eficiente de gerir uma unidade escolar:

- Nome do Aluno
- Data de Nascimento
- CPF (Aluno ou Responsável)
- Nome do Responsável

---

## 📚**Funcionalidades Principais**

### **Gerenciamento de Processos**

- Cadastro de novos alunos (pré-matrícula)

- Exclusão de alunos por CPF

- Documentação interativa com Swagger, Redoc e RapiDoc

- Validação de dados com Pydantic

- Estrutura modular (models, schemas, logger, etc.)

- Suporte a CORS para integração com o frontend

---

## 🔗 Como Rodar o Sistema

**Clone o repositório:**

```bash
git clone https://github.com/seu_usuario/sistema-monitoria.git
```

2. **Instale as dependências:**

```bash
pip install -r requirements.txt
```

3. **Inicie o servidor:**

```bash
flask run --host 0.0.0.0 --port 5000 --reload
```

4. **Acesse a aplicação:**  
   [http://localhost:5000](http://localhost:5000)

---
