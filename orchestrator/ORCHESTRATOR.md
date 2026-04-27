# 🧠 Orquestrador — Sistema de Agentes de Marketing

## Visão Geral
O orquestrador coordena os 6 agentes autônomos para trabalhar como uma equipe integrada.

## Agentes do Time
| Agente | ID n8n | Função |
|--------|--------|--------|
| 🎯 Meta Ads | PftueZFE2aR6ywtI | Campanhas pagas |
| ✍️ Copy | G5WalkKONYsGA8wH | Textos persuasivos |
| 🎨 Criativo | 9c4gxzNMe7NO7NRb | Conteúdo visual |
| 🌐 Página Site | BesYtvPoKMBKCOyi | Landing pages |
| 🎬 Vídeo | ke6jKydst5d9Y76j | Produção de vídeo |
| 🤖 GitHub Skills | x2AQxiBYbzna5DS1 | Gestão de conhecimento |

## Fluxo de Trabalho em Equipe

```
BRIEFING (entrada)
       ↓
[Orquestrador analisa e distribui tarefas]
       ↓
┌──────────────────────────────────┐
│  Copy → Criativo → Meta Ads      │ (campanha paga)
│  Copy → Vídeo → Meta Ads         │ (vídeo ad)
│  Copy → Página Site              │ (landing page)
│  GitHub Skills ← todos os agentes │ (aprendizado)
└──────────────────────────────────┘
       ↓
[Relatório consolidado por email]
       ↓
RESULTADO (saída)
```

## Schedule Diário
- **08:00** — Meta Ads verifica e otimiza campanhas ativas
- **09:00** — Copy gera novos textos para a semana
- **10:00** — Criativo produz assets visuais
- **14:00** — Página Site audita conversões
- **16:00** — Vídeo planeja conteúdo semanal
- **18:00** — Relatório consolidado enviado por email
- **23:00** — GitHub Skills atualiza aprendizados do dia

## Comunicação entre Agentes
Agentes se comunicam via webhooks n8n.
Cada agente tem um webhook de entrada e pode chamar outros agentes.
