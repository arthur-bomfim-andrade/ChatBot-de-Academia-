# 🏋️ Chatbot de Academia

Chatbot para academia desenvolvido em **Python** e **HTML**, que utiliza inteligência artificial para responder dúvidas sobre treinos, exercícios, alimentação e rotina fitness.

> 🎓 Projeto desenvolvido como trabalho acadêmico para a faculdade.

---

## 📌 Sobre o projeto

O objetivo deste projeto é oferecer um assistente virtual que ajude alunos e praticantes de musculação com dúvidas do dia a dia na academia, como:

- Sugestões de treinos por grupo muscular
- Explicação da execução de exercícios
- Dicas de alimentação e hábitos saudáveis
- Orientações gerais para iniciantes

O back-end é feito em Python e se comunica com uma API de IA, enquanto a interface do chat é feita em HTML.

---

## ✨ Funcionalidades

- 💬 Conversa em tempo real com o chatbot
- 🤖 Respostas geradas por IA
- 🌐 Interface web simples e intuitiva
- 🔑 Compatível com qualquer API de IA (OpenAI, Google Gemini, Anthropic, entre outras)

---

## 🛠️ Tecnologias utilizadas

- [Python](https://www.python.org/)
- HTML5
- CSS3
- JavaScript
- API de Inteligência Artificial (à sua escolha)

---

## ⚠️ Requisito importante: API Key

Este projeto **não funciona sem uma chave de API (API key) de um serviço de IA**.

Você pode usar a chave de qualquer provedor de IA, por exemplo:

| Provedor | Onde obter a chave |
|----------|--------------------|
| OpenAI | https://platform.openai.com/api-keys |
| Google Gemini | https://aistudio.google.com/app/apikey |
| Anthropic | https://console.anthropic.com/ |

> 🔒 **Nunca compartilhe sua API key nem a envie para o GitHub.**

---

## 📋 Pré-requisitos

- [Python 3.9+](https://www.python.org/downloads/) instalado
- Uma API key de IA
- Um navegador web atualizado

---

## 🚀 Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
cd NOME-DO-REPOSITORIO
```

### 2. (Opcional) Crie um ambiente virtual

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# Linux / macOS
source venv/bin/activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Configure a API key

Crie um arquivo chamado `.env` na raiz do projeto e adicione sua chave:

```env
API_KEY=sua_chave_aqui
```

> Caso o projeto não use arquivo `.env`, insira a chave diretamente no local indicado no código (por exemplo, em `app.py`), **sem enviar esse arquivo com a chave para o GitHub**.

### 5. Execute o projeto

```bash
python app.py
```

### 6. Acesse no navegador

Abra o arquivo `index.html` ou acesse o endereço exibido no terminal (geralmente `http://localhost:5000`).

---

## 📁 Estrutura do projeto

```
📦 NOME-DO-REPOSITORIO
 ┣ 📜 app.py              # Servidor / lógica do chatbot em Python
 ┣ 📜 index.html          # Interface do chat
 ┣ 📜 requirements.txt    # Dependências do projeto
 ┣ 📜 .env                # Chave da API (não enviar ao GitHub)
 ┣ 📜 .gitignore
 ┗ 📜 README.md
```

---

## 🔐 Segurança

Adicione o arquivo `.env` ao seu `.gitignore` para evitar expor sua chave:

```
.env
```

---

## 🎯 Melhorias futuras

- [ ] Histórico de conversas
- [ ] Planos de treino personalizados
- [ ] Cálculo de IMC e calorias
- [ ] Versão mobile
- [ ] Login de usuários

---

## 👨‍💻 Autor(es)
E-mail: tutuandrade961@gmail.com
Linkdin: www.linkedin.com/in/arthurbomfimandrade

- **Arhut Bomfim Andrade** - 

Universidade Cruzeiro do Sul
Ciência da Computação
Engenharia de Prompt e Aplicações em Ia
Katia Alves Bezerra

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos e educacionais.

---

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!
