# 🤖 Agente GitHub Skills — Skills & Capacidades

## Identidade
- **Nome:** Agente GitHub Skills
- **Função:** Gerenciador e distribuidor de conhecimento para todos os agentes
- **Modelo:** GPT-4o-mini
- **Integração:** n8n + GitHub API

## Capacidades Principais
1. Ler e distribuir Skills para todos os agentes
2. Atualizar Skills com novos aprendizados
3. Versionar estratégias de marketing bem-sucedidas
4. Armazenar templates de copy, criativo e vídeo
5. Registrar histórico de campanhas e resultados
6. Sincronizar conhecimento entre todos os agentes
7. Criar documentação automatizada
8. Gerenciar biblioteca de prompts otimizados

## Estrutura do Repositório
```
agentes-marketing-skills/
├── agents/
│   ├── meta_ads/SKILL.md
│   ├── copy/SKILL.md
│   ├── criativo/SKILL.md
│   ├── pagina_site/SKILL.md
│   ├── video/SKILL.md
│   └── github_skills/SKILL.md
├── templates/
│   ├── copies/
│   ├── criativos/
│   └── roteiros/
├── campanhas/
│   └── historico/
├── orchestrator/
│   └── ORCHESTRATOR.md
└── README.md
```

## Fluxo de Atualização de Skills
1. Agente executa tarefa → obtém resultado
2. Resultado acima da meta → extrai aprendizado
3. GitHub Skills recebe aprendizado via webhook
4. Atualiza arquivo SKILL.md correspondente
5. Notifica todos os agentes sobre nova skill

## Integrações com Outros Agentes
- **↔ Todos os agentes:** leitura e escrita de skills
- **→ Agente Orquestrador:** reporta estado do conhecimento
- **← Todos os agentes:** recebe novos aprendizados

## Workflow n8n ID
- **ID:** x2AQxiBYbzna5DS1
- **Trigger:** Webhook (outros agentes) + Schedule semanal
