# Estratégia de Produto — ICP, Features, Redesign, PLG, Modelo

> Leia para: ICP/nicho, priorização de features, feature creep, redesign, PLG,
> "que feature construir", modelo de cobrança, comunicação com a base.

## Tenha um ICP claro (e founder fit)

ICP claro **não é** "todos que querem usar meu produto". É entender qual problema
o produto resolve e, dentro disso, escolher **deliberadamente um nicho
sub-atendido**. Seu ICP precisa:

- **Sentir a dor com peso real.** A mesma dor não vale o mesmo pra todo mundo: um
  CRM vale mais pra uma clínica de harmonização facial do que pra um barbeiro —
  perder um lead na clínica custa R$3.000, no barbeiro R$60. **A dor é
  proporcional ao que se perde quando ela não é resolvida.**
- **Ter tamanho suficiente (TAM).** Nicho pequeno demais não sustenta operação no
  médio prazo. Mas o erro mais comum em tração é o oposto: o founder abraça o
  mundo por medo de TAM pequeno e perde a especificidade que faria o produto
  vender.
- **Ter dinheiro pra pagar.** Alguns ICPs não cabem na sua precificação (B2C ou
  B2B). Valide se o ICP absorve o ticket que o unit economics exige **antes** de
  desenhar feature.
- **Ter alguma coisa com você (founder fit).** Escolher um domínio que você
  conhece (ex.: oficinas mecânicas — amo carro, cresci em oficina, trabalhei em
  montadora) dá vantagem que dinheiro não compra: linguagem nativa, rede de
  validação rápida, instinto sobre o que o cliente vai aceitar antes de
  perguntar. Founder fit define a **velocidade da curva de aprendizado** nos
  primeiros meses — e errar barato é a diferença entre tração e a morte.

**Como o nicho muda a forma de errar:**
- **Com ICP claro, errar tem diagnóstico** — "errei a comunicação, a dor real do
  meu ICP é X". Você mapeou os problemas e só está escolhendo qual comunicar.
- **Sem ICP claro, a caixa de probabilidades estoura** — não sabe se errou
  produto, copy, canal, preço ou público; cada teste fica caro e gera pouco
  aprendizado.

ERP generalista é difícil de vender; **ERP pra marcenaria** é outra conversa
(mais fácil focar comunicação, achar onde o público está, e entender problemas
que só você resolve porque o generalista não pode se dar ao luxo). Em tração,
errar faz parte; **errar sem saber por quê é o que consome o runway.**

---

## O filtro canivete — decidir se uma feature entra

Toda feature que entra, **fica, e cobra para sempre**. Duas camadas; a feature
precisa passar nas duas.

### Camada 1 — A feature merece existir? (4 critérios)
1. **Carga cognitiva** — toda feature aumenta a superfície do produto: mais
   aprendizado, mais tempo de decisão (Lei de Hick), maior chance de o usuário
   não achar o que queria, frustrar e cancelar.
2. **Especificidade ao ICP** — serve o nicho real, ou um nicho genérico que
   parece o seu? Genérico fica genérico; específico cobra 5x mais.
3. **Custo operacional** — não é o custo de construir, é o de **manter,
   suportar, documentar, treinar, atualizar quando a stack muda** — e cada
   superfície nova é mais área de ataque/invasão.
4. **Fortalece o claim principal** — se a LP promete X, toda feature precisa
   puxar pra X. Feature que dispersa **dilui o valor** e cria um problema de
   comunicação (você nunca terá espaço/tempo pra comunicar tudo).

### Camada 2 — Vale construir agora? (2 eixos)
- **É facilmente rejeitável?** Tem um "não" óbvio? Se o "não" exige reunião de 3
  horas, a feature está mal definida ou você não tem critério ainda.
- **É facilmente implementável?** Custo real até a **primeira versão que valida**
  (não a versão dos sonhos).

Cruzando os eixos aparece a zona dos **no-brainers**: passou na camada 1, é
fácil de implementar e tem decisão óbvia de seguir → **construa primeiro,
sempre**. A maioria dos times faz o contrário: constrói o difícil que parece
estratégico e ignora o no-brainer que move métrica esta semana.

> A pergunta certa não é "esta feature é boa?". É "**esta feature merece o custo
> permanente que vai cobrar do produto?**". Se falhar em qualquer um dos 4
> critérios da camada 1, mate sem culpa.

---

## Swiss Knife Index — quantas features são realmente usadas

Liste todas as features; conte quantas são usadas por **>40% dos ativos em 30
dias**; divida. **< 0,3 = canivete suíço** (100 ferramentas, mal cabe no bolso,
demora pra achar o que precisa). Founder técnico (ainda mais com IA) ama
construir feature — cada uma parece progresso e o roadmap vira lista de desejos.
Mas cada feature aumenta a superfície (código, UI, carga cognitiva) e **dilui a
percepção de pra que serve o produto** (feature creep).

Como resolver:
1. **Audit trimestral** — lista de features vs. uso real (dado, não opinião do
   time).
2. **Esconda, não delete** — features pouco usadas vão pra "configurações
   avançadas": acessíveis pros 3% que precisam, somem pros 97%.
3. **Critério pra próxima feature** — "que feature existente vou matar pra fazer
   espaço cognitivo pra essa?".

Atalho: *que feature você mostraria primeiro se tivesse 30 segundos pra vender o
produto?* O resto deveria estar invisível até virar necessário.

### Adoção de feature é design, não comunicação
Você lança feature, faz changelog, email, post, badge "novo" — e 3 semanas
depois 9% abriram, 4% usaram mais de uma vez. O viés que mata: **cegueira não
intencional** (o usuário não vê o que não está procurando) + **status quo**
(o custo de re-aprender pesa mais que o benefício). O que funciona:
- **Empty state direcionador** na tela onde a feature seria usada.
- **Triggered onboarding** — micro-onboarding ativado pelo comportamento que
  sinaliza a necessidade (ex.: usuário de CRM foi à página de venda → apresente a
  IA que ajuda a quebrar objeção).
- **Feature adoption rate** medindo hábito (frequência apropriada), não clique.
- **Critério de continuidade** — feature que não bate o mínimo entra em revisão.

---

## O perigo do redesign — Snapchat 2018

Fev/2018, maior redesign da história do Snapchat (separar conteúdo de amigos do
de marcas/creators). No papel fazia sentido; na prática foi um massacre: petição
no Change.org com **1,2 milhão** de assinaturas, Kylie Jenner ("does anyone else
not open Snapchat anymore?"), ações despencando em 24h.

Tecnicamente parecia certo; o problema era **comportamental**. Os usuários tinham
aprendido a usar o app de um jeito específico — onde cada coisa estava, qual
gesto fazia o quê. Esse **mapa cognitivo** era parte do produto, mesmo sem
ninguém tê-lo desenhado de propósito (igual o swipe do Tinder). O viés é **status
quo**: preferimos manter o estado atual quando o ganho da mudança parece pequeno
frente ao esforço de re-aprender. Redesign agressivo de um produto que funciona
pede que o usuário pague o custo de re-aprendizado **e** sinaliza que você sabe
melhor que ele o que ele deveria querer. Você vê upgrade; ele vê ameaça.

Pergunta-guia: *Que parte do produto é tão usada que mexer nela vai parecer
hostil?* Essa parte fica como está; você melhora em volta.

(Nuance honesta: o próprio autor às vezes posta uma tela nova "mais bonita". A
regra: **refatorar de verdade é esperar feedback do usuário e mexer no que
resolve um problema** — repintar a parede porque a cor velha cansou é outra
história. Só o uso dirá se ficou melhor de verdade ou só mais bonito.)

---

## As 4 condições do PLG (e por que a maioria não tem)

PLG virou padrão de pitch deck, mas é **consequência de 4 condições
estruturais** — a maioria dos SaaS B2B BR não tem nenhuma e faz pitch de PLG
assim mesmo:

1. **TTV < 10 minutos.** Se precisa de demo com consultor, suporte pra conectar
   API, freela pra implantar — não é PLG.
2. **Ticket não alto demais.** PLG escala com ticket abaixo de ~R$1.000. Muito
   acima, o comprador vira um comitê.
3. **Viralização ou colaboração nativa.** Notion, Figma, Slack cresceram porque
   um usuário arrasta outros. CRM com IA não viraliza — precisa de SDR, demo,
   follow-up (comercial caro).
4. **Mercado endereçável gigante** (TAM real, de baixo pra cima). O Brasil tem
   ~20 mil empresas com +100 funcionários; se seu produto é pra esse perfil, a
   matemática de PLG não fecha.

O Brasil tem ~uma dúzia de SaaS B2B onde PLG faz sentido econômico real; o resto
faz **sales-led com nome de PLG**. Por que insistem? Porque PLG **parece eliminar
a parte que o founder não domina: vender.**

---

## Modelo de negócio vs. produto — o churn de trabalho concluído

Produto com 4,2 estrelas, NPS positivo e **churn crescendo** não é contradição —
é desalinhamento entre **modelo de cobrança** e o trabalho que o produto foi
contratado pra fazer. O usuário que ama o produto e cancela provavelmente
**terminou o trabalho** que veio fazer. Não houve valor contínuo; o problema foi
resolvido uma vez.

Produtos contratados pra um problema **pontual** geram churn estrutural:
- currículo, contrato/documento jurídico, migração de dados entre plataformas,
  montagem de pitch deck, due diligence de aquisição.

**TurboTax** resolveu ancorando o produto a um **evento que já existe na vida do
usuário e volta todo ano sem empurrão** (imposto de renda). O produto virou
**ritual** porque o evento justifica o uso de forma inevitável.

Pergunta-guia: *Se o trabalho que seu produto faz foi concluído, qual evento na
vida do usuário justifica que ele volte?* Se não existe resposta, **não é
problema de produto — é problema de modelo de negócio.**

---

## Comunicação proativa & NRR — não espere o cancelamento

Caso real: um fornecedor só ofereceu o **produto novo (melhor)** quando o cliente
ligou pra **reclamar** de um problema técnico, já de saída. "Por que não me
ofereceram antes?" A empresa lançou versão melhor mas só comunicou pra tráfego
frio, com medo de canibalizar o produto antigo. A base ficou na versão antiga
achando que aquilo era o teto — e cancela quando aparece concorrente que parece
melhor (ou um serviço ruim, como nesse caso). Quando o suporte oferece a migração
**no momento do cancelamento**, o estrago já está feito: você converteu uma
chance limpa de **expansão de receita** em retenção emergencial.

Comunicação **reativa** de melhoria é um dos vetores de churn mais perigosos. A
alavanca afetada é o **NRR** (acima de 110% em B2B separa crescimento sustentável
de funil furado). Pergunta-guia: *Quando lançamos a última feature/versão
relevante, quantos clientes ativos foram avisados?* (E não vale email de release
que ninguém lê, nem post no Instagram.)

---

## Custo de troca é o que vira meses de LTV em anos

**O mesmo produto, desenhado de dois jeitos, rende meses ou anos de LTV.** A
diferença é o custo de troca: o esforço que o usuário PERCEBE em sair. Custo baixo
significa histórico raso e porta de saída fácil, então ele vaza no dia em que
aparece algo 10% melhor. A jogada é engenheirar custo de troca de propósito, um
"juro composto" que faz o valor do produto crescer com o tempo de uso.

Cinco alavancas pra construir isso:
- **Memória muscular:** atalhos que viram reflexo (Superhuman, Photoshop). Trocar
  significa desaprender os dedos.
- **Modelo mental:** o jeito de pensar o produto (a fricção de Mac vs Windows, os
  labels do Gmail em vez de pastas). Sair pede reconstruir o mapa da cabeça.
- **Personalização acumulada:** o que o usuário montou ao longo do tempo
  (playlists do Spotify, o layout da home). Isso não migra junto.
- **Efeito cofre:** os dados guardados que você não quer abandonar (iCloud,
  Drive, anos de conversa no WhatsApp). Sair é deixar um baú pra trás.
- **Piloto automático / hábito:** o uso vira loop de recompensa variável, a caixa
  de Skinner. Ele nem decide mais usar, só usa.

O custo afundado segura o usuário do mesmo jeito que segura o investidor numa ação
caindo: ele já colocou tanto ali que sair parece perder, não parar de perder. O
hábito pode levar meses pra se instalar, mas é exatamente ele que separa um LTV de
meses de um LTV de anos.

Pergunta-guia: *Se um concorrente idêntico surgisse amanhã de graça, o que seu
usuário perderia ao trocar, e você desenhou isso de propósito ou foi por acaso?*

Fonte: @richardrx.
