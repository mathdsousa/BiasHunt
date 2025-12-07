# 🚀 Como jogar o Bias Hunt?

Siga as instruções abaixo para rodar o projeto localmente.

---

## 📄 1. Configuração das variáveis de ambiente

Dentro da pasta **backend**, crie um arquivo chamado **`.env`** e adicione:

```bash

GPT_KEY="sua_chave_da_openai"
INFO_KEY="sua_chave_da_newsapi"

```

---

## 🖥️ 2. Executando o Backend

Entre na pasta do backend:

```bash
cd backend
````

Instale as dependências:

```bash
pip install -r requirements.txt
```

Inicie o servidor:

```bash
uvicorn main:app --reload
```

O backend estará disponível em:
➡️ [http://localhost:8000](http://localhost:8000)

---

## 🌐 3. Executando o Frontend

Volte para a raiz do projeto:

```bash
cd ..
```

Entre na pasta do frontend:

```bash
cd frontend
```

Instale as dependências:

```bash
npm install
```

Inicie o servidor:

```bash
npm run dev
```

Acesse o frontend em:
➡️ [http://localhost:8080](http://localhost:8080)

---

## ✔️ Pronto!

Com backend e frontend rodando, você já pode utilizar a aplicação localmente.

