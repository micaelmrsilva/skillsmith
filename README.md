# minhas-skills

Coleção de skills de Claude Code que eu criei, em PT-BR. Cada pasta em [`skills/`](skills/) é uma skill autocontida com um `SKILL.md` (e, quando faz sentido, uma pasta `references/` com o corpo de conhecimento aprofundado).

## Skills

### Produto / Growth

| Skill | O que faz |
|---|---|
| [`design-for-startups`](skills/design-for-startups) | Lente de **Revenue Centric Design** para startups e SaaS: onboarding, ativação, landing, hero, CTA, pricing, churn, retenção, escolha de ICP e priorização de features. Traz `references/` sobre RCD, o teardown de landing em 10 camadas, níveis de consciência, fricção/formulários/atenção, diferenciação na era da IA, preços, métricas, vieses e growth. |
| [`design-for-startups-onboarding`](skills/design-for-startups-onboarding) | Aprofundamento em **onboarding e ativação**: aha moment, time to value, empty states, checklist de ativação, churn na primeira semana e adoção de feature nova. `references/` com método de 5 passos, padrões de onboarding, métricas de aha e vieses comportamentais. |
| [`pricing-filtro-icp`](skills/pricing-filtro-icp) | Pricing tratado como **filtro de ICP**, não decisão financeira: preço seleciona comportamento (dor, orçamento, autoridade, compromisso). `references/` com piso e teto (custo real de servir vs custo da dor), métricas por segmento (WTP, CAC payback, margem por suporte, ticket-to-revenue) e política de desconto. |

### Jurídico

| Skill | O que faz |
|---|---|
| [`contract-draft`](skills/contract-draft) | Geração de minutas contratuais personalizadas em PT-BR (contrato do zero, modelos, drafts). |
| [`contract-review`](skills/contract-review) | Revisão e análise de risco em contratos: mapeamento de cláusulas críticas, sugestões de redação e checklist de negociação. Suporte à decisão, não substitui parecer formal. |
| [`juridico-jurisprudencia`](skills/juridico-jurisprudencia) | Estrutura pesquisa jurisprudencial: teses a favor/contra, estratégia de busca em tribunais e relatório argumentativo. |
| [`juridico-legislacao-compliance`](skills/juridico-legislacao-compliance) | Mapeia normas aplicáveis e requisitos de conformidade para um caso/setor, gerando checklist de compliance com semáforo P0/P1/P2. |
| [`juridico-lgpd`](skills/juridico-lgpd) | Diagnóstico LGPD: mapeia tratamento de dados pessoais, prioriza riscos com semáforo e sugere bases legais e documentação. Não substitui DPO nem RIPD formal. |

## Como usar

Skills de Claude Code ficam em `~/.claude/skills/`. Pra instalar qualquer uma daqui, copie a pasta correspondente:

```bash
cp -R skills/design-for-startups ~/.claude/skills/
```

O Claude Code carrega a skill automaticamente pela `description` no frontmatter do `SKILL.md` quando o contexto da conversa bate com os gatilhos.

## Licença

MIT. Veja [LICENSE](LICENSE).

**Exceção:** a skill [`design-for-startups`](skills/design-for-startups) destila
ideias de Richard ([@richardrx](https://x.com/richardrx)), via
[heliocosta-dev/revenue-centric-design](https://github.com/heliocosta-dev/revenue-centric-design).
Esse material exige atribuição e **não pode ser usado para produtos de aposta,
cassino ou jogo de azar a dinheiro real**. Termos em
[`skills/design-for-startups/LICENSE-RCD`](skills/design-for-startups/LICENSE-RCD).
