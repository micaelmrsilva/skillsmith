# Métodos de Análise — como auditar um produto de verdade

> Leia para: como auditar um produto, coletar feedback, mapear a jornada real,
> rodar uma análise heurística, calcular LTV por cohort.

## A análise heurística da jornada (as bolinhas verdes e vermelhas)

O entregável final de uma análise de jornada é um gráfico onde **cada bolinha é
uma observação do produto** — da landing até a ativação. Verdes são as vitórias;
vermelhas são as **micro-decepções** que se empilham. A linha despenca não por um
erro dramático, mas por **acúmulo**: decepçãozinha sobre decepçãozinha, até o
usuário desistir sem saber explicar por quê.

**Como rodar (a ferramenta):**
1. Percorra o produto **área por área** e marque cada ponto como **OK** ou **não
   OK**.
2. Quando não está OK, tire um print e **classifique a gravidade em 4 níveis**:
   - **Estético** — feio, mas não atrapalha.
   - (níveis intermediários de fricção/usabilidade)
   - **Crítico** — onde o usuário **trava** e a conversão morre.
3. No fim, sobra um **mapa de furos**.

**A parte que quase ninguém engole:** a reação automática de todo mundo
(designer na frente da fila) é **jogar tudo fora e redesenhar do zero** — tela
nova, o prazer viciante da página em branco. Mas redesign do zero é caro, lento e
quase sempre diz mais sobre a vontade de quem desenha do que sobre a dor de quem
usa. **Em vez de refazer o balde, ache onde está pingando e vede** — quase sempre
uma fração do esforço pra maior parte do ganho.

> Origem da ferramenta: começou como uma lista de perguntas num artigo de ~12
> anos atrás, fermentou numa palestra da **Abby Covert**, e virou ferramenta
> online. Faz uma coisa só, mas bem.

---

## O gap entre a jornada do founder e a jornada do usuário

O founder médio descreve a jornada em **12 passos**; o usuário médio executa
**4**. A distância entre o diagrama no Excalidraw e o replay de sessão real é onde
mora a maior parte do **churn evitável** em early stage.

- **Jornada do founder** — construída de cima pra baixo, começa pelo que o
  produto **quer** que o usuário faça (Onboarding → Ativação → 1º projeto → 2º
  projeto → Expansão → Advocacy). Tem lógica, mas não retrata a realidade.
- **Jornada do usuário** — executada de baixo pra cima, começa pelo **problema
  específico** que ele tinha quando abriu a aba. Tudo o resto é fricção entre ele
  e o resultado que veio buscar.

O gap é invisível pro founder porque ele nunca executou a jornada como
recém-chegado — ele vive a **jornada do criador**. Para mapear (sem abrir Figma):
1. Escreva sua versão da jornada em passos numerados (papel/notes, sem
   prototipar).
2. Abra **5 gravações de sessão** de usuários reais nos primeiros 7 dias; anote o
   que cada um **efetivamente faz**, na ordem, com tempo — e o que tenta e
   desiste.
3. Coloque as duas listas lado a lado. **O relatório está nas diferenças** — cada
   divergência é uma hipótese a confirmar ou descartar.

> Jornada de usuário é o que aparece no **replay de sessão**. O que está no Figma
> e no Excalidraw é **hipótese.**

Pergunta-guia: *Qual percentual dos seus usuários executa o happy path que você
desenhou?* Se não sabe, é candidato a uma sessão de pesquisa amanhã.

---

## Stack de coleta de feedback (quanti + quali, contínuo)

Você não consegue desligar a maldição do conhecimento (ver
`vieses-comportamentais.md`) — a única saída é coletar feedback **constante** com
quem usa, sem direcionar. O que o autor faz (no RepareCar e com clientes):

- **SAC/CX como coletor de insights** — cada problema vai pra uma tabela e é
  analisado: **%**, **impacto no produto**, **insight**. (Suporte não é só
  apagar incêndio; é a fonte de pesquisa mais barata que existe.)
- **Clarity / PostHog** — mapa de calor, gravação de sessão e fluxo de navegação
  "por cima". É aqui que você vê onde o usuário se perdeu antes do valor.
- **Entrevistas** com usuários por amostras e grupos específicos. (Sem volume pra
  A/B, **5 entrevistas bem feitas valem mais que um teste sem amostra**.)
- **Benchmarking** — como outros produtos endereçam o mesmo problema, pra
  entender o que já é oferecido.

Lembrete do **1:26**: pra cada cliente que senta e reclama, há ~26 igualmente
insatisfeitos que só não tiveram saco. Cada reclamação é a ponta de um iceberg
(ver `distribuicao-growth.md`).

---

## LTV por cohort (em vez da fórmula que engana)

`ARPU / Churn` superestima LTV em **30-50%** em produto novo, porque mistura
cohorts jovens (alto churn) e maduras (baixo churn) numa média que não descreve
nenhum dos dois. Em produto com **< 18 meses**, calcule **por cohort**:

| Cohort | Churn | LTV real |
|---|---|---|
| 0-3 meses | 18% | R$1.111 |
| 3-6 meses | 10% | R$2.000 |
| 6+ meses | 5% | R$4.000 |

(ARPU R$200; a "fórmula geral" daria R$2.500 — um número que **não existe na
base**.) Use o cohort de 6+ meses pra decidir CAC com segurança. Detalhe em
`metricas.md`. Pergunta-guia: *Esse LTV vem da fórmula geral ou do cohort dos
últimos 6 meses?*

---

## Refatorar de verdade vs. repintar a parede

A cabeça do designer roda num loop: *tá incrível → dá pra melhorar → ficou melhor
→ repete pra sempre*. Refatoramos UI como refatoramos código. A regra pra não
queimar uma semana num pixel perfect que ninguém pediu:

> **Refatorar de verdade é esperar o feedback do usuário e mexer no que resolve
> um problema.** Repintar a parede porque a cor velha cansou é outra coisa — e o
> designer vive confundindo as duas.

Teste pra saber se uma mudança passou: ela ataca uma **dor real e velha** do
setor (ex.: cliente não confiar no orçamento da oficina — daí o orçamento com
peça, foto, código e preço, aprovação pelo celular, follow-up automático na
recusa), ou é só vontade de página em branco? Se ficou melhor de verdade ou só
mais bonito, **só o uso dirá** — até lá, você está vendendo o visual.
