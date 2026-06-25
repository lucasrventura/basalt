---
type: protocol
updated: 2026-06-24
---

# UPDATE_PROTOCOL — Como manter o vault da Basalt

Regras simples para que o contexto compartilhado não apodreça.

## Princípios

1. **Um fato, um lugar.** Se um fato já existe em outra nota, referencie com `[[wiki link]]` em vez de copiar.
2. **Edite no lugar.** Quando uma decisão muda, atualize a nota existente — não crie nota nova nem deixe a versão antiga.
3. **Datar decisões.** Mudanças relevantes levam a data: `(decidido 2026-06-24)`. Atualize o campo `updated:` do frontmatter.
4. **Um tópico por arquivo.** Se uma nota está crescendo demais com dois assuntos, separe e cruze com links.
5. **Termine cada nota com `## Relacionado`** listando wiki links.

## Quando criar uma nota nova

- Surgiu um tópico que não cabe em nenhuma nota existente → crie o arquivo, adicione ao [[INDEX]] (tabela de roteamento + lista) e linke nas notas relacionadas.

## O que NÃO entra aqui

- Contexto pessoal, emocional, financeiro individual de cada sócio. Isso fica no vault pessoal de cada um.
- Segredos/credenciais (tokens, chaves de API). Use variáveis de ambiente / gerenciador de segredos, nunca o repo.

## Relacionado

- [[INDEX]]
- [[CLAUDE]]
