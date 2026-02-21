# Passo a Passo de Execução

## Setup do Ollama

```bash
# 1. Instalar ollama (ollama.com)
# 2. Baixar um modelo leve
ollama pull gpt-oss

# 3. Testar se funciona
ollama run gpt-oss "Olá!"
```

## Código Completo

Todo o código-fonte está no arquivo `app.py`

## Como Rodar

```bash
# 1. Instalar dependências
pip install streamlit pandas requests

# 2. Garantir que ollama está rodando
ollama serve

# 3. Rodar o app
streamlit run .\src\app.py
```

## Evidências de Execução

<img width="1842" height="917" alt="imagem_2026-02-21_130356860" src="https://github.com/user-attachments/assets/4693df5e-4039-412e-9674-60e63e04d94a" />
