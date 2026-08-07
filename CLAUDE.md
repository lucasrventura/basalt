# CLAUDE.md — Vault compartilhado da Basalt

Este é o **vault de contexto compartilhado da Basalt Consultoria**. Ele existe para que qualquer sessão de Claude — tanto a do Lucas quanto a do Henrique (Dilli) — trabalhe a partir do **mesmo contexto de negócio**, com a mesma linguagem, posicionamento e decisões.

> Contexto pessoal/emocional de cada sócio **não** vive aqui. Este vault é só sobre a Basalt como empresa.

## Passos obrigatórios no início de cada sessão

1. **Leia [[INDEX]] primeiro.** É a tabela de roteamento.
2. **Abra só o(s) arquivo(s) que o INDEX aponta** para a pergunta em questão — não carregue o vault inteiro. Para contexto geral, leia [[sobre-a-basalt]].
3. **Siga [[UPDATE_PROTOCOL]]** para manter tudo atualizado. Sempre que uma decisão mudar, edite o arquivo relevante no lugar (não duplique fatos).
4. **Respeite a divisão de papéis** (abaixo): Lucas = consultoria/diagnóstico; Dilli = build/configuração do agente.

## Como o sistema é organizado

- **Um tópico por arquivo.** Cada nota termina com uma seção **Relacionado** com `[[wiki links]]`.
- **[[INDEX]]** é a tabela de roteamento e o hub do grafo.
- **Nunca guarde o mesmo fato em dois lugares** — referencie com wiki links.
- Decisões têm data. Quando algo muda, marque a data da mudança.

## Fatos que nunca devem ser esquecidos

- **Basalt Consultoria** — consultoria de **agentes de IA / automação** para pequenos negócios. PM/Notion é serviço *secundário*.
- **Proposta de valor:** *"Automatizamos o que você faz todo dia. Do processo ao agente rodando."*
- **Cliente-alvo:** profissionais solo e times pequenos com um processo repetitivo claro — clínicas, consultorias, prestadores de serviço B2B (dentista, fisio, médico, consultor, coach, fundador de small-SaaS).
- **Sócios e papéis:**
  - **Lucas Ventura** — consultoria: diagnostica o processo do cliente e desenha a arquitetura do agente (o que ele decide sozinho × o que escala pra humano) antes de qualquer build.
  - **Henrique Dilli** — build: configura o agente em si. Também responsável por **vendas/outreach**.
- **Marca:** "The Bedrock System" — paleta monocromática sóbria (sem roxo, sem cor de destaque), motivo de favo de mel / hexágono, Inter + JetBrains Mono, zero `box-shadow`, peso de fonte 500 nos títulos.
- **Stack de build:** LLM via API hospedada (Claude/Anthropic, **não** self-hosted), orquestração em **n8n** (local via Docker no dev), WhatsApp via Twilio sandbox (demo) → WhatsApp Business Cloud API (produção).
- **Site:** site estático multi-página (HTML puro), GitHub Pages → basaltco.com.br.

## Relacionado

- [[INDEX]]
- [[UPDATE_PROTOCOL]]
- [[sobre-a-basalt]]
