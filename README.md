# Analisador de Dados CSV com LlamaIndex + GROQ

Este é um aplicativo simples em **Python** que permite ao usuário fazer upload de um arquivo CSV e fazer perguntas sobre os dados usando **Gradio** e **LlamaIndex + GROQ**.

---

## Funcionalidades

- Upload de arquivos CSV.
- Perguntas em linguagem natural sobre os dados.
- Respostas geradas por um modelo LLM Groq.

---

## Requisitos

- Python 3.9 ou superior
- Bibliotecas:
  - `pandas`
  - `gradio`
  - `llama-index` (versão compatível com `llama_index.llms.groq`)
- API Key do GROQ configurada na variável de ambiente `secret_key`.

---