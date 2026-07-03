# Conversão & Landing Pages

> Leia para: landing page, hero, CTA, copy, conversão, "página não converte",
> primeira impressão, tela de login, arquitetura de conversão.

## A conversão se decide antes da copy — 3 variáveis pré-palavra

Founders gastam semanas reescrevendo copy de home atrás de pontos de conversão.
Mas o cérebro processa **três variáveis antes de chegar nas palavras**, e elas
costumam render mais que qualquer headline.

**1. Contraste.**
"O botão deve ser vermelho, laranja ou verde?" é a pergunta errada. Um botão
vermelho em fundo laranja contrasta **menos** que um botão preto em fundo branco.
Contraste é **função do entorno** — cor isolada importa pouco. Calculadoras de
contraste resolvem o ratio mínimo de acessibilidade (4.5:1), mas o contraste
percentual vai além: envolve forma, tamanho e posição. Um botão grande, com forma
diferente do que está em volta, numa zona de respiro, é **visto antes de ser
lido** — e ser visto é condição pra ser clicado.

**2. Disposição na tela.**
- **Lei de Fitts:** o tempo pra alcançar um alvo é função da distância e do
  tamanho. Alvos maiores e mais próximos de onde o olho já está são clicados
  mais (trivial no mouse, agressivo no touch).
- **Padrão F de leitura** (Nielsen Norman, milhares de eyetrackings): o olho
  varre o topo, faz um segundo varrimento horizontal mais curto, e desce em
  coluna pela esquerda. Tudo fora do F só é capturado com contraste forte o
  suficiente pra interromper o padrão. CTA no canto inferior direito, sem
  ancoragem visual, está fora do mapa atencional — não importa o copy.

**3. Confiança.**
Confiança é desproporcional: um cadeado ao lado de "compra segura" aumenta
conversão mesmo quando o usuário não sabe o que o cadeado significa
tecnicamente. O cérebro lê **familiaridade como sinal de segurança**, em 4
camadas que se reforçam:
- rosto humano que pareça real (não banco de imagem);
- marca conhecida ou prova social específica e verificável;
- oferta que se encaixe no problema declarado pelo usuário;
- mecanismo de solução logicamente coerente com a promessa.

Quando as 4 alinham, o usuário converte sem perceber por quê. Quando uma falha,
ele inventa um motivo racional pra sair. Otimizar copy sem trabalhar contraste,
disposição e confiança é **maquiar sintoma**.

---

## O teste dos 5 segundos (hero)

Mostre o topo da landing por 5 segundos, tire da frente e pergunte: **o que esse
produto faz? Pra quem?** Se a pessoa não souber responder, a hero falhou — não
importa quão bonita ela é.

Nos primeiros segundos o cérebro faz 3 perguntas, nesta ordem:
1. O que é isso?
2. Isso é pra mim?
3. Por que eu deveria me importar agora?

A maioria das LPs de SaaS BR responde **zero** das três no hero, porque trocou
clareza por "criatividade". "Revolucione seu fluxo de trabalho" não diz o que o
produto faz. "A plataforma definitiva de produtividade" não diz pra quem.
Headline abstrata parece sofisticada e comunica nada. O princípio é **carga
cognitiva**: cada segundo decifrando o que você faz é um segundo mais perto de
desistir. **Clareza ganha de esperteza, sempre, no topo do funil.**

O que um hero precisa ter:
- Headline que diz o que o produto faz, em **linguagem do cliente** (não jargão
  interno).
- Subheadline que crava o ICP e o resultado concreto.
- Prova visual **real** (screenshot do produto funcionando, não ilustração
  genérica de gente sorrindo).
- CTA específico (ver microcopy abaixo).
- Prova social imediata (logo ou número), ainda acima da dobra.

**Especificidade vende.** "Software de gestão" é genérico; "Controle de comandas
pra oficina mecânica" diz exatamente o que é e pra quem — e quem é do nicho sente
que foi feito pra ele. E comece pelo **problema do visitante**, não pela feature:
"Seu time perde 6 horas por semana procurando informação" continua a conversa;
"Plataforma de gestão de projetos com IA" é meh. Um fala de si, o outro fala de
mim.

Pergunta-guia: *Se você tampasse tudo menos o hero, um estranho do seu ICP
entenderia o que você vende em 5 segundos?*

---

## CTA: microcopy + click trigger

A microcopy do CTA tem **mais impacto que cor ou formato do botão**. Founder
técnico A/B-testa cor por 3 semanas (diferença de 0,3%, nem significativa)
enquanto o botão diz "Cadastrar" sem nenhum click trigger.

Um bom CTA responde 3 perguntas que o cérebro faz antes de clicar:
- O que vai acontecer quando eu clicar?
- Quanto tempo isso vai levar?
- Quanto vai custar / comprometer?

"Cadastrar" deixa todas em aberto. "Começar agora" responde uma. "Começar grátis
em 30s" responde duas. Quanto mais (e melhor) você responde, menos esforço mental
o usuário gasta simulando o que vai acontecer. O **click trigger** (textinho
abaixo do CTA) ajuda a responder o resto e a quebrar uma objeção:

| Contexto | CTA | Click trigger |
|---|---|---|
| Trial B2B | "Começar Trial Grátis" | 14 dias sem cartão |
| Onboarding rápido | "Criar conta em 30 segundos" | Eleita melhor ferramenta do setor |
| Pricing | "Assinar e começar a usar hoje" | 25% de desconto anual |
| Checkout | "Pagar R$199 e ativar" | Entrega grátis em 3 dias |

Conceitos: **viés de resultado** (avaliamos a decisão pelo que esperamos) e
**teoria do nível de construção** (quanto mais concreto fica o que vai
acontecer, mais fácil decidir). Regra: o botão é a última coisa que o usuário lê
antes de decidir — trate como tal.

---

## Arquitetura de conversão — a decisão é tomada antes do checkout

A maioria otimiza a tela errada (checkout, botão, headline). A decisão de comprar
já foi tomada antes. **Conversão é arquitetura: o usuário converte quando o
caminho até a ação é mais curto que o caminho até a dúvida.**

- **Booking** roda 1.000+ experimentos simultâneos. Elementos como "Apenas 1
  quarto restante" e "Reservado 3 vezes na última hora" saíram disso. Eles até
  mostram hotéis esgotados junto dos disponíveis — esperavam queda de conversão,
  deu o oposto: escassez **real** fez reservas subirem. Função: **reduzir a
  janela de deliberação** (cada segundo pensando aumenta a chance de fechar a
  aba).
- **Amazon "1-Click"** comprime o tempo de decisão **removendo etapas**.

Os dois usam o mesmo princípio (**aversão à perda**, Kahneman: perder dói até 2x
mais que ganhar o equivalente) com táticas opostas: Booking pressuriza o
ambiente; Amazon remove fricção.

---

## A dívida de expectativa — o churn começa na landing page

Se a LP promete uma coisa e o produto entrega outra, você criou uma **dívida de
expectativa** que cobra juros todo dia que o usuário usa e pensa "não era isso
que eu esperava". Três desalinhamentos comuns:

- **Resultado prometido vs. ferramenta entregue** — "Aumente vendas em 30%" mas
  entrega um dashboard de métricas. Comprou resultado, recebeu planilha colorida.
- **Simplicidade prometida vs. produto complexo** — "Configure em 5 minutos" mas
  são 47 campos, 3 integrações, tutorial de 20 min.
- **Promessa pro ICP errado** — LP fala com startup de 2 pessoas, produto foi
  desenhado pra time de 15 em escala.

Nos três, o produto pode ser excelente — não importa, a expectativa foi calibrada
errada e a decepção já foi programada. **Churn de 30 dias alto + NPS ok = o
problema é o que você prometeu, não o produto.**

---

## O teste de honestidade do tráfego frio

Caso de mentoria: founder triplicou investimento em ads num mês; receita subiu só
11%. A conversão pré-investimento era ~3% (ótimo pra muitos nichos), mas vinha de
**público quente** (seguidores que chegavam meio decididos). Ao aumentar o
orçamento, entrou público frio: os 3% não se sustentaram e a conversão despencou
pra **0,5%**. A página **sempre teve** essa capacidade real de conversão; os 2,5
pontos extras eram a audiência perdoando os defeitos. Arrumado o óbvio, a conversão
pulou pra 2% (quadruplicou em cima do número real), mas no dashboard ainda parecia
queda, porque ele comparava com os 3% que nunca foi performance real.

> Escalar verba em público frio é um teste de honestidade: mostra quanto da sua
> conversão é a **sua página** e quanto é **confiança emprestada** pela audiência.

---

## A primeira tela é uma landing (ex.: tela de login/convite)

"É só uma tela de login" — mas é a **primeira impressão do produto**; faz o
trabalho de uma landing sem ser uma. Estudo de credibilidade da Stanford: **46%
das pessoas julgam a confiabilidade de algo pela aparência do design**, e esse
peso sobe quando há dado sensível ou dinheiro (ex.: plataforma de benefício que
pede email da empresa, CPF, senha). Em B2B, **parecer seguro pesa mais que
parecer grande**. Detalhes que sinalizam segurança: os requisitos de senha não
são só segurança real, são **sinal** de segurança ("esse povo leva proteção a
sério"); o contexto de quem convidou; a prova social do número de empresas. A
primeira tela seta o tom da jornada inteira.

Pergunta-guia: *Que parte da sua primeira tela está dizendo "confia em mim" antes
do usuário clicar em qualquer coisa?*

---

## Cargo cult — copiar a página sem a pesquisa

Duas páginas 95% iguais visualmente: uma converte 4%, a outra 0,6% (mesmo nicho,
mesma oferta, quase tudo na mesma ordem). A de 0,6% foi clonada da de 4% mudando
o mínimo. **Página de conversão é só o lado visível de um sistema invisível.** O
que converte fica embaixo da casca:
- vocabulário extraído do cliente real em pesquisa;
- ordem das objeções alinhada ao medo específico do ICP;
- prova social escolhida a dedo pra ressoar com o perfil;
- promessa central ajustada ao desejo declarado em entrevista.

Quem copia o layout copia o que é **barato de produzir**; o que custou caro é
invisível e passa despercebido na clonagem. O erro tem nome: **cargo cult** —
replicar o ritual visível esperando invocar o resultado, sem entender o mecanismo
causal. Pergunta: *O que nessa página é função do produto, e o que é função da
pesquisa do cliente feita antes de escrever cada frase e posicionar cada
elemento?* Se não sabe responder, copiar a página é só experimento de
aprendizado.

---

## Prova social que converte

- Avaliação **perfeita (5,0) converte menos** — parece falsa. A probabilidade de
  compra atinge o pico entre **4,2 e 4,5 estrelas** (Northwestern). Consumidores
  desconfiam de unanimidade; críticas construtivas parecem mais autênticas.
- Depoimentos em LP aumentam conversão em até **34%** (VWO).
- Produtos com **5+ reviews** têm **270%** mais probabilidade de compra (Yotpo).
- **93%** leem reviews antes de comprar (BrightLocal).
- A combinação que mais converte: case study com ROI quantificável + vídeo de
  depoimento de marca reconhecível pelo ICP + logos.
- Erro mais comum não é falta de prova social, é **prova social mal feita**: card
  tudo igual, só primeiro nome, só 5 estrelas, ícone genérico em vez de foto
  real. (Vale testar até linkar pro post original — review cru + foto + logo da
  empresa + título com número de compras.)
