# 🍰 DoceLab — Diagnóstico de Receitas para Confeiteiros

**DoceLab** é um assistente inteligente e lúdico criado para ajudar confeiteiros iniciantes (e curiosos da confeitaria) a identificar e corrigir erros comuns em massas, recheios, coberturas e muito mais!

Com uma abordagem divertida e acolhedora, o chatbot usa inteligência artificial para diagnosticar "sintomas" de receitas que deram errado e sugere soluções práticas, técnicas e fáceis de aplicar.

---

## 🧁 Como funciona?

O fluxo de interação é simples, como uma consulta com um "médico da confeitaria":

1. **Você informa o erro** (ex: *"Meu bolo afundou no meio"*).
2. **O DoceLab investiga a causa provável**, consultando fontes confiáveis e seu próprio banco de conhecimento.
3. **Recebe um diagnóstico técnico** + uma **"receita de correção"** com dicas, ajustes e orientações.
4. **Tudo isso com emojis 🍩, hashtags #confeitando e linguagem acessível!**

---

## 💻 Tecnologias usadas

- 🤖 [Google ADK Agents](https://developers.google.com/agents) (Agentes multimodais com Gemini)
- 🌐 Integração com Google Search para coleta de causas e soluções atualizadas
- 🐍 Python + Google Colab
- ✨ Estrutura modular com múltiplos agentes (buscador, diagnósticos, correções, revisão)

---

## 🚀 Objetivos do projeto

- Democratizar o acesso a conhecimento técnico de confeitaria
- Usar IA para auxiliar em processos criativos e técnicos na cozinha
- Criar um ambiente seguro e divertido para aprender com os erros

---

## 📸 Exemplos de uso

```text
🎂 Usuário: Fiz um bolo e ele afundou no meio!
🤖 DoceLab: Isso pode ser fermento demais, forno muito quente ou falta de estrutura na massa. Bora corrigir isso juntos? 👨‍🍳
#bolofail #fornoamigo

---

# 📁 Estrutura do projeto
doce-lab/
├── agentes/
│   ├── buscador_de_erros.py
│   ├── diagnostico.py
│   ├── correcoes.py
│   └── revisor_respostas.py
├── main.ipynb         # Notebook principal para rodar o fluxo
├── README.md
└── requisitos.txt

---

# 🔧 Como rodar
1. Clone este repositório:
git clone https://github.com/seuusuario/doce-lab.git

2. Instale as dependências:
pip install -r requisitos.txt

3. Configure sua API Key do Google ADK

4. Rode o notebook main.ipynb no Google Colab

---

# 💡 Contribua!
Ideias doces são sempre bem-vindas! Sinta-se à vontade para abrir uma issue, enviar um pull request ou compartilhar sugestões de melhorias.

---

# ✨ Créditos
Criado com muito açúcar, código e afeto por [Luana Silva] 🍓
Inspirado nos erros reais de confeitaria e nas delícias que surgem com aprendizado.

---

#📜 Licença
MIT License
