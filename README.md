# 🚀 Agentes de Marketing Autônomos

Sistema completo de 6 agentes de marketing autônomos rodando em n8n com GPT-4o-mini.

## Agentes
- 🎯 **Meta Ads** — Gestor de campanhas pagas (ID: PftueZFE2aR6ywtI)
- ✍️ **Copy** — Redator persuasivo (ID: G5WalkKONYsGA8wH)
- 🎨 **Criativo** — Designer e estrategista visual (ID: 9c4gxzNMe7NO7NRb)
- 🌐 **Página Site** — Otimizador de landing pages (ID: BesYtvPoKMBKCOyi)
- 🎬 **Vídeo** — Produtor de conteúdo em vídeo (ID: ke6jKydst5d9Y76j)
- 🤖 **GitHub Skills** — Gerenciador de conhecimento (ID: x2AQxiBYbzna5DS1)

## Tecnologia
- **Plataforma:** n8n (localhost:5678)
- **IA:** GPT-4o-mini (OpenAI)
- **Automação:** n8n workflows
- **Conhecimento:** GitHub (este repositório)
- **Notificações:** Gmail

## Estrutura
Cada agente tem seu próprio arquivo SKILL.md em agents/{nome}/SKILL.md

## Como Funciona
Os agentes trabalham em equipe: Copy → Criativo → Meta Ads → Relatório.
O Agente GitHub Skills sincroniza o conhecimento entre todos.
Ver orchestrator/ORCHESTRATOR.md para o fluxo completo.

---
*Sistema desenvolvido para darlanbessa — Marketing Autônomo com IA*