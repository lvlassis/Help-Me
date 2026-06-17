# Projeto: Help-me

Repositório de pesquisa e experimentação para construção de um assistente de voz.

## Estrutura

| Pasta | Conteúdo |
|-------|----------|
| `docs/` | Documentação e decisões de arquitetura |
| `data/` | Dados brutos e processados (ignorados pelo git) |
| `experiments/` | Comparativos entre tecnologias |
| `src/` | Módulos reutilizáveis |
| `prototypes/` | Protótipos integrados end-to-end |

## Experimentos planejados

- **01** — STT: Whisper vs Vosk
- **02** — LLM: Ollama (local) vs OpenAI (cloud)
- **03** — TTS: gTTS vs Coqui

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
