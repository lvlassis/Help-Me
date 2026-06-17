# Arquitetura do Assistente de Voz

## Fluxo principal

```
Microfone → Wake Word → STT → NLU/LLM → TTS → Alto-falante
```

## Componentes

### Wake Word
Detecta a palavra de ativação sem processar tudo o tempo todo.

### STT (Speech-to-Text)
Converte o áudio capturado em texto.

### NLU / LLM
Interpreta a intenção e gera uma resposta.

### TTS (Text-to-Speech)
Converte a resposta em fala.

## Decisões em aberto

- [ ] Local vs cloud para cada componente
- [ ] Latência aceitável end-to-end
- [ ] Idioma(s) suportado(s)
