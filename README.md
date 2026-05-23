# JARVIS Acadêmico — Trabalho 1

Assistente pessoal para estudantes universitários, com RAG, agenda,
tarefas e tool calling, usando o LLM Gemma 12B.


## Como rodar (resumo)

```bash
pip install -r requirements.txt
python main.py
```

Para o passo a passo completo, leia **TUTORIAL.md**.

## Estrutura
- `src/` — código-fonte
- `data/` — dataset acadêmico (10 documentos + README do dataset)
- `storage/` — agenda.json e tarefas.json (criados no 1º uso)
- `logs/` — logs de tool calling
- `index/` — índice vetorial do RAG
- `tests/` — testes unitários

## IAs utilizadas
- Claude (Anthropic) — revisão do código me auxiliando como ferramenta
