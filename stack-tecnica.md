---
type: topic
updated: 2026-06-24
---

# Stack técnica

Decisões tomadas em 2026-06-23 para evitar paralisia de análise na infra.

## LLM

**API hospedada (Claude / Anthropic), NÃO self-hosted Llama.** Self-hosting é a armadilha do MVP — overhead de GPU/ops, qualidade pior. API é barata em volume de demo, melhor qualidade, zero ops. Llama só depois, se privacidade/custo-de-escala exigir.

## Orquestração

**n8n**, rodando local via Docker no dev (grátis). Migra para nuvem só quando houver cliente real. Tem nós prontos para WhatsApp, calendário, CRM e um nó de LLM.

## WhatsApp (a parte realmente difícil — não o modelo)

- **Demo rápida:** Twilio WhatsApp sandbox (funciona em minutos, sem aprovação da Meta).
- **Produção:** WhatsApp Business Cloud API (verificação da Meta, número dedicado).

## CRM + Agenda

Google Calendar + Google Sheets ou Notion (já usado). n8n tem nós prontos para todos.

## Segurança

Nunca commitar tokens/chaves no repo. Usar variáveis de ambiente.

## Relacionado

- [[mvp-whatsapp]]
- [[sobre-a-basalt]]
