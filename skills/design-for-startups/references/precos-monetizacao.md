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

---

## Preço é o dinheiro mais barato

**Pricing é a maior alavanca de um SaaS, e ~90% dos produtos estão
subprecificados.** O motivo é psicológico: o founder conhece cada limitação, cada
bug, cada canto que ainda falta polir, então ancora o preço no concorrente mais
barato em vez de ancorar no valor que entrega. O comprador não vê nada disso; ele
só vê o problema resolvido. Vocês estão olhando pra coisas diferentes, e quem
define o preço é o que olha pro produto por dentro.

O mecanismo econômico: um aumento de 30% no preço não vira 30% de MRR (algum churn
acontece), mas o que sobra é quase caixa puro, não teve aquisição no meio pra
comer a margem. Crescer um canal 30% custa dinheiro, custa tempo e tem teto. Subir
preço não tem canal, não tem CAC, não tem teto de audiência: é a alavanca que
rende mais por unidade de esforço e mesmo assim é a que ninguém encosta.

Preço baixo cobra a conta depois, em três frentes:
- **Menos budget pra alcançar o ICP** (com ticket baixo você não tem margem pra
  ir buscar quem realmente precisa).
- **A armadilha da obsessão por CAC** (a métrica real não é o CAC isolado, é o
  GAP entre CAC e LTV, e o preço alarga esse gap dos dois lados ao mesmo tempo).
- **Mais churn** (barato atrai comprador descompromissado, o mesmo caçador barato
  da `distribuicao-growth.md`).

**Como aplicar:** suba em direção ao valor, não em direção ao concorrente. E lembre
o elo com design: o número precisa ser sustentado pela percepção de valor. Sua
página e o primeiro uso justificam ou destroem o preço que você pediu. Cobrar mais
sem parecer valer mais é só aumentar o preço da rejeição.

Pergunta-guia: *Você ancorou seu preço no valor que entrega ou no concorrente mais
barato, que também está com medo de cobrar?*

Fonte: @richardrx.

---

## A armadilha do freemium, em números

**Um plano grátis aumenta a conversão de signup e pode destruir a economia do
negócio ao mesmo tempo.** O número maior no topo do funil parece vitória, mas
esconde um negócio pior embaixo. A única forma de enxergar é rodar o funil inteiro.

Mesmo tráfego nos dois cenários (R$80 mil/mês), planos a partir de R$199.

**COM freemium:**
- ~8% viram signup → 800 signups.
- 80% ativam, 5% desses pagam → **32 pagantes** (R$6.368 de MRR).
- A base satura em ~160 pagantes com 20% de churn.
- Enquanto isso, 768 usuários grátis queimam tokens de IA (~US$0,08 cada um).
- CAC real ≈ **R$2.540 por pagante**, payback ~13 meses.

**SEM freemium:**
- ~3% viram pagante → **300 pagantes** = R$59.700 de MRR (~10x o cenário anterior).
- CAC ~R$275, payback ~6 semanas.
- LTV:CAC 5:1, que reinveste o próprio lucro pra crescer.

O freemium só compensa quando o grátis traz usuários orgânicos ou virais que você
não pagou pra adquirir (quando o próprio uso grátis vira canal). Fora disso, um
cenário reinveste o próprio lucro; o outro financia prejuízo até o dinheiro acabar.

Pergunta-guia: *Seu grátis está trazendo usuário que você não pagou, ou está
queimando caixa pra inflar um número de topo de funil?*

Fonte: @richardrx.

---

## Se o freemium funciona depende do custo de servir o usuário grátis

**Freemium não é bom nem ruim no abstrato; o custo do grátis é quem decide.** E
esse custo depende de duas coisas: (1) quanto custa servir quem não paga e (2)
quão longa e cara é a ativação até o valor.

**Se servir um usuário grátis custa quase nada e o TTV é curto**, o grátis vira
canal de aquisição. O Slack coloca você mandando a primeira mensagem em minutos: é
o TTV curto que sustenta o modelo, não o caixa. O usuário sente valor rápido,
custa pouco pra mantê-lo, e uma fração vira pagante.

**Se o produto roda em IA (tokens em dólar) ou a ativação é longa**, cada conta
grátis é uma aposta cara que só uma fração pequena banca. Isso exige bolso fundo
pra aguentar o prejuízo do topo até a conversão pagar, e bolso fundo é a exceção,
não o founder médio. Numa média amigável, só ~3-4% do freemium converte, o resto
é custo puro.

**Como aplicar:** se servir o grátis é barato e o TTV é curto, use o grátis como
aquisição. Caso contrário, cobre, bem e cedo. Pra um produto de IA, seu usuário
grátis nunca foi grátis.

Pergunta-guia: *Quanto te custa, em dólar de token, servir um usuário que talvez
nunca pague, e por quantos meses você aguenta bancar isso?*

Fonte: @richardrx.
