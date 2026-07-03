# Preços & Monetização

> Leia para: pricing, planos, decoy, ancoragem, defaults, freemium, trial,
> "quanto cobrar", disposição a pagar.

## Você provavelmente deveria subir o preço

A matemática (margens típicas de SaaS, dados ProfitWell):
- **1% de melhoria no preço → 8 a 11% de aumento no lucro.**
- **1% de melhoria em aquisição → ~2% no lucro.**

O mesmo 1% de esforço paga 2% de um lado e até 11% do outro. E ainda assim,
perguntados qual alavanca de crescimento é a mais importante, **70% de 1.500
executivos escolheram aquisição** — exatamente a que rende menos. Valorizamos ao
contrário de onde o valor mora.

Por quê? **Aquisição é crescimento visível** (lead aparece no dashboard, dá pra
comemorar). **Preço dá frio na barriga** — mexer parece que vai espantar cliente,
então ninguém encosta. É **aversão à perda**: o medo de perder o que já tem grita
mais alto que a chance de ganhar mais.

**Como estruturar um aumento:**
1. Veja quando foi a última vez que subiu preço. Se passou de 1 ano e o produto
   melhorou, já há defasagem.
2. Teste o preço novo **só nos clientes novos**, sem encostar na base. Meça
   conversão. Racional: se a queda de conversão compensar o ticket extra, vale.
3. Considere o impacto no **LTV**: quem paga mais costuma gerar **menos churn**
   que quem pagou barato.
4. Suba pouco e **ancorado em valor** — comunique o que melhorou, não atire o
   aumento na cara do cliente sem contexto.
5. **Esqueça A/B test de preço** — você não tem volume. Faça por segmento e por
   pesquisa de disposição a pagar.

Pergunta-guia: *Se 1% no preço rende 5x mais que 1% em aquisição, por que quase
toda a sua energia está no topo do funil?*

---

## Efeito chamariz (decoy) — o estudo da Economist (Dan Ariely)

Três opções testadas em 100 alunos do MIT:
- A — Só online, US$59 → **16%**
- B — Só impresso, US$125 → **0%**
- C — Online + impresso, US$125 → **84%**

Removendo a opção B (que ninguém escolhia):
- A → **68%** | C → **32%**

Sem o B no meio, a Economist **perdeu mais da metade da receita do plano caro**.
O B nunca foi feito pra ser vendido — foi feito pra fazer o C parecer óbvio. É o
**boi de piranha**. Funciona porque decidimos por **comparação**. Estima-se que a
arquitetura aumentou a receita de assinaturas em ~30-43%.

**Como aplicar no SaaS sem virar pegadinha:**
- O plano que você quer vender mais é o **do meio**. Se quer vender o Pro, o
  decoy é o Premium (mais caro, mais features, mas com algo que o ICP não precisa
  de verdade).
- O chamariz precisa ser **claramente inferior** em algum atributo importante
  (no Economist, B oferecia menos pelo mesmo preço de C). Em SaaS: limite de
  usuários, sem integração crítica, sem suporte prioritário.
- **Três planos > quatro ou cinco** (quatro disparam o paradoxo da escolha; o
  usuário paralisa e fecha a aba). Três ativam o decoy de forma limpa.
- O plano mais caro existe pra **ancorar** a percepção de preço — mesmo que poucos
  comprem o Enterprise, ele faz o Pro parecer razoável.

Cuidado: se o chamariz estiver muito próximo (em preço) do mais caro, é o **mais
caro** que ganha vantagem por comparação. Pergunta: *Qual é o chamariz dos seus
planos hoje?* Se não consegue responder, provavelmente não existe — e o seu plano
alvo está brigando contra os outros sem ajudar o usuário a decidir.

---

## Defaults — a alavanca mais subestimada

Estudo clássico (Science, 2003): países com **opt-out** de doação de órgãos têm
em média **6x mais** doadores que países com opt-in. Cultura/religião não
explicam: Alemanha (opt-in) ~12% registrados; Áustria (opt-out) ~100%. A
diferença é **uma caixinha marcada por padrão**. Se isso muda uma decisão tão
grande, imagine nas triviais.

Mecanismo: **viés de status quo + redução de carga cognitiva**. Decidir é caro; o
padrão é a decisão mais fácil pro cérebro preguiçoso. **Default é o
reconhecimento de que o usuário não vai gastar energia decidindo o que pra você é
trivial.**

Onde aplicar em SaaS:
- **Plano default na pricing page** — o pré-selecionado concentra **60-80%** das
  escolhas. Quer vender o mid-tier? É ele que precisa estar marcado.
- **Billing default** — anual vs mensal pré-selecionado. Mudar de mensal pra
  anual aumenta o MRR contratado sem mexer no preço.
- **Quantidade de licenças padrão** — se o ICP médio compra 5 seats, o seletor
  começa em 5 (ancoragem).
- **Reverse trial** — premium é o padrão, free é o opt-out; o usuário precisa
  **ativamente abrir mão** do que já tem.

Três regras:
1. O default precisa ser **eticamente defensável** — pegadinha de checkbox vira
   churn e ReclameAqui.
2. Padrões inteligentes batem persuasão em copy. Antes de reescrever CTA, olhe o
   que está pré-selecionado nas telas críticas.
3. Você pode passar a vida otimizando copy, ou mudar 5 defaults no fim de semana.
   (Casos reais: +60% de ticket médio; até 4x de LTV mexendo no default da
   aquisição de planos.)

---

## Trial com cartão vs. sem cartão

Dado Chartmogul 2026 (mercado US, 200 produtos):
- **Sem cartão: ~8,9%** de conversão de trial em pagante.
- **Com cartão: ~31,4%** — mais de 3x.

Parece óbvio (pede cartão, só entra quem tem intenção real), mas tem custo
escondido: **pedir cartão reduz signup.** Você converte mais trial em pagante,
mas tem menos trial.
- Sem cartão: 1.000 visitantes → 85 trials → **7,5 pagantes**.
- Com cartão: 1.000 visitantes → 30 trials → **9,4 pagantes**.

Mais um indício de que **freemium é menos efetivo do que se prega**.

**Ressalva Brasil:** isso é dado US. No BR, considere o **PIX** — mesmo no
"recorrente" tem dinâmica diferente do cartão. Na prática, **clientes de PIX
recorrente costumam ter churn maior que clientes de cartão.**

- Pedir cartão no trial é a melhor opção? **Possivelmente.**
- PIX recorrente "não presta"? **Não** — dependendo do ICP você nem tem a
  alternativa de só trabalhar com cartão.
- A pergunta certa não é "qual modelo converte mais", e sim **qual modelo atrai e
  retém o ICP certo.**

Ver `onboarding-ativacao.md` (atrito do cartão como qualificador) e
`vieses-comportamentais.md` (justificação de esforço).

---

## Por que NÃO fazer A/B test de preço (nem da maioria das coisas)

A maioria dos testes A/B em SaaS pequeno **não tem condição de provar nada**, e
mesmo assim o founder troca o produto inteiro em cima do resultado. Pra medir com
segurança uma melhora de 2% numa conversão já baixa, você precisa de **milhares
de visitantes por variação** — SaaS em tração raramente tem isso. Aí roda o teste
uma semana, vê "variante B ganhou 12%", comemora e troca tudo.

Dois vieses combinados: **lei dos pequenos números** (achar que uma amostra
pequena representa tudo) + **viés de confirmação** (favorecer o que já quer
acreditar). A ProfitWell é categórica: **não fazer A/B de preço** — nunca há
volume nem contexto suficiente.

Como tratar testes:
- Antes de rodar, **calcule o tamanho de amostra necessário** (há calculadora
  grátis). Se não atinge o chão mínimo em tempo razoável, nem comece.
- Teste **coisa grande** (headline, oferta, estrutura de pricing, onboarding) —
  efeito grande precisa de menos amostra pra aparecer.
- **Não interrompa o teste** porque o número ficou bonito no meio.
- Sem volume, decida por **pesquisa qualitativa e julgamento**: 5 entrevistas bem
  feitas valem mais que um A/B sem amostra.

Pergunta-guia: *O último teste que mudou seu produto tinha amostra pra concluir
algo, ou você trocou tudo com base numa semana de ruído?*

---

## Percepção de valor é construída (o camelô)

Vendendo eletrônicos como camelô: os produtos mais vendidos tinham margem ruim
(todos baixavam preço). A jogada foi reservar parte da grana pra comprar produtos
**mais bonitos, com caixas mais bonitas** — davam 3-4x mais margem porque
**pareciam ter mais qualidade** (sem dizer nada), e dava pra vender pelo triplo.
**Construir percepção de valor é quase um teatro de sombras.** Conecta com o
driver tático de estética em `principios-rcd.md`.
