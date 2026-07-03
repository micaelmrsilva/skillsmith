---
name: design-for-startups-onboarding
description: >-
  Corpo de conhecimento profundo sobre ONBOARDING e ATIVAÇÃO de produtos digitais
  (SaaS), na lente de Revenue Centric Design. Use SEMPRE que o usuário estiver
  projetando, diagnosticando ou tentando melhorar onboarding, ativação, primeira
  experiência, empty states, checklist de ativação, redução de churn na primeira
  semana, time to value, adoção de feature nova, ou "meu usuário cadastra e some".
  Também acione quando aparecer: "onboarding", "ativação / activation rate", "aha
  moment", "TTV / time to value", "primeira semana", "empty state", "checklist de
  ativação", "tooltip / tour guiado", "trial converte mas não retém", "churn alto",
  "promessa quebrada", "feature nova ninguém usa / feature adoption", "jornada do
  usuário / session replay", "maldição do conhecimento", "fricção declarativa vs
  administrativa", "Zeigarnik / efeito progresso / pico-fim / aversão à perda no
  onboarding", "como otimizar meu onboarding", "value realization", ou qualquer
  pedido para mapear/consertar a jornada do signup até o valor. Responda em pt-BR
  por padrão. Para onboarding/activation CRO em inglês, a mesma lente se aplica.
metadata:
  version: 1.1.0
  language: pt-BR
---

# Design for Startups — Onboarding & Ativação

Esta skill é o aprofundamento da disciplina de **onboarding** dentro do Revenue
Centric Design. Enquanto a skill irmã [[design-for-startups]] cobre a lente
inteira (LP, pricing, ICP, churn, features), aqui o foco é cirúrgico: **o trecho
entre o signup e o momento em que o usuário captura valor** — porque é nesse
trecho que mora a maior parte do churn evitável de produto early-stage.

A tese-mãe: **você não perde o usuário no mês 2, quando ele cancela. Você perde
no primeiro dia depois do signup.** A demora pra cancelar é só burocracia. O
abandono já aconteceu, em silêncio, na primeira sessão — dashboard vazio, empty
state triste, nenhum botão de alto contraste guiando, nenhum valor entregue
antes do esforço pedido.

**Como usar esta skill:** quando o usuário pedir pra projetar, avaliar ou
consertar onboarding/ativação, não responda como manual genérico de UX.
Responda como alguém que sabe que **a primeira semana do usuário vale mais que o
roadmap inteiro**. Diagnostique antes de redesenhar. Aponte o furo do balde, não
troque o balde. Sempre devolva o **racional** (o porquê comportamental) e, quando
útil, termine com a **pergunta que força o usuário a olhar o dado certo** (quase
sempre: "quanto tempo entre signup e aha? você sabe responder?").

---

## As 6 teses centrais (decore isto)

Se você só lembrar destas, já acerta 80% de qualquer diagnóstico de onboarding.

1. **Cadastro não é ativação. Cadastro é a porta; ativação é o usuário sentar na
   cadeira e usar o produto pra valer.** Cadastro é o custo mais barato que o
   usuário paga (um email, às vezes nem isso com login social) — mede
   curiosidade. Dá pra inflar a curva de signups com mídia a semana inteira
   enquanto a retenção real fica parada. O que importa é quem volta no D2, no D7,
   e quem faz a **ação que entrega valor**. Comemorar cadastro no dashboard é
   comemorar gente decidindo te dar uma chance — a maioria some antes de virar
   uso, antes de pagar.

2. **90% abandona na primeira semana se não chegar a valor claro.** O TTV médio
   (benchmark Userpilot, 547 empresas) é **1 dia, 12h e 23min**. Os top
   performers entregam valor em **menos de 5 minutos**. O usuário tem 47 abas
   abertas e o WhatsApp piscando; sua ferramenta é uma delas. Ele faz o mínimo
   pra decidir se volta. Se não entregou valor, ele não volta.

3. **Onboarding bom não é onboarding curto.** "Atrito" é palavra abrangente: um
   onboarding melhor pode ter MAIS passos. Existem dois tipos de fricção — a
   **administrativa** (coleta dado que o sistema usa depois, atrasa o usuário e
   não compra nada pra ele → candidata a corte) e a **declarativa** (obriga o
   usuário a se posicionar sobre o que veio fazer, atrasa um bocadinho e compra
   compromisso + customização + direcionamento → candidata a expandir). Cada
   etapa do seu onboarding está coletando dado ou fazendo o usuário declarar
   intenção?

4. **Onboarding é design de emoção e memória, não de mecânica.** Regra do
   Pico-Fim: o usuário avalia a experiência pelo pico emocional e pelo
   encerramento, não pela média. A maioria dos produtos entrega *confirmação*
   onde deveria entregar *celebração*. A memória que o usuário carrega das
   primeiras horas é o ativo de retenção mais barato e mais ignorado que existe.

5. **O churn começa antes do produto — na promessa.** Se a LP (ou o vendedor)
   prometeu uma coisa e o produto entrega outra no primeiro uso, você criou uma
   dívida de expectativa. Não importa se o que entrega é até bom — não era o
   combinado. Conversão alta vira armadilha: dá sensação de aquisição
   funcionando e esconde que cada cliente já entra com um pé na saída. Tem
   também o churn de quem nunca teve o problema — esse é **qualificação**, e se
   resolve antes, na própria página.

6. **Ensinar a usar o produto ≠ entregar o resultado que ele veio buscar.**
   Ninguém quer aprender a usar o produto; querem o resultado prometido na hero.
   Onboarding ativo (sequência de ações que entregam valor, cada uma puxando a
   próxima) retém muito mais que onboarding passivo (tooltips e docs que o
   usuário lê "se quiser" — ele não vai). Slack te coloca num canal e te faz
   mandar uma mensagem: você *usou* o produto antes de ler qualquer coisa.
   Entender fazendo > entender lendo.

---

## O método de otimização (o coração desta skill)

Founders travam em "não sei como otimizar meu onboarding" — e a boa notícia é
que dá pra fazer **sem Figma e sem IA da modinha**. O loop, em 5 passos:

1. **Tire prints de cada etapa.** Coloque num Miro/FigJam. Veja a jornada real
   como uma sequência, fora do código.
2. **Defina a vitória final.** O que faz o produto "clicar" e faz o usuário
   *querer ficar*. Não é o que você acha que deveria ser — é o valor que ele
   captura. (Ver `aha-moment` para descobrir isso por dado.)
3. **Analise cada etapa atual.** Essa etapa está ajudando o usuário a chegar na
   vitória final, ou é fricção administrativa entre ele e o resultado?
4. **Comece a otimizar.** Remova, adie ou **adicione** etapas que aproximem o
   usuário da vitória final mais rápido. (Adicionar fricção declarativa é uma
   jogada válida — ver case da plataforma de pagamentos.)
5. **Prototipe, teste com usuários e rode de novo.** É um loop, não um projeto.

Detalhe completo, incluindo a versão sem-Figma e os critérios de corte/expansão,
em [`references/metodo-5-passos.md`](references/metodo-5-passos.md).

---

## Workflow de diagnóstico (use quando pedirem "melhora meu onboarding")

Não pule pro redesenho. Rode nesta ordem:

1. **Qual o estágio?** MVP / Sobrevivência / Tração / PMF / Escala. O peso do
   design e o que medir muda radicalmente. Em MVP, lapidar onboarding é vaidade;
   em Sobrevivência, é o furo nº 1 do balde; em Tração, é alavanca de MRR.
   → `estagios-startup.md`
2. **Você está medindo a coisa certa?** Signups, session time e onboarding
   completion são vaidade. Activation rate, TTV, D1/D7 e value realization são o
   que importa. → `metricas-e-aha.md`
3. **Qual é o aha moment, por dado?** Compare o que os pagantes fizeram na 1ª
   semana e os que cancelaram não fizeram. Não é o que você acha. → `metricas-e-aha.md`
4. **O churn é de onboarding ou de promessa/linguagem?** Se a expectativa veio
   torta da LP, ou se o produto fala em jargão, nenhum tour conserta.
   → `churn-e-linguagem.md`
5. **A jornada que você desenhou é a que acontece?** Abra 5 session replays dos
   primeiros 7 dias e compare com a sua lista. O gap é o relatório. → `padroes-onboarding.md`
6. **Quais alavancas comportamentais aplicar?** Zeigarnik, efeito progresso,
   pico-fim, aversão à perda, Hick, Fogg. Cada uma é alavanca OU armadilha
   dependendo do contexto. → `vieses-comportamentais.md`

---

## Índice de referências

Carregue o arquivo conforme o eixo do problema:

- [`references/metodo-5-passos.md`](references/metodo-5-passos.md) — O loop de
  otimização de onboarding (a imagem-fonte), versão sem-Figma, critérios de
  corte vs expansão de etapa, onboarding ativo vs passivo.
- [`references/estagios-startup.md`](references/estagios-startup.md) — As 5 fases
  (MVP→Sobrevivência→Tração→PMF→Escala), marcos financeiros (ARR), o que medir em
  cada uma e o papel/alavanca do design por fase (Encurtar → Ativar → Converter →
  Expandir → Sistematizar).
- [`references/metricas-e-aha.md`](references/metricas-e-aha.md) — Métricas certas
  vs vaidade (activation rate, TTV, D1/D7, value realization × signups, session
  time, completion), benchmarks, e o método de descoberta do aha moment por
  cohort.
- [`references/churn-e-linguagem.md`](references/churn-e-linguagem.md) — Churn de
  promessa quebrada, qualificação na página, maldição do conhecimento, viés da
  fala fácil, e suporte como problema de design (low ticket, FAQ contextual,
  case McAfee).
- [`references/vieses-comportamentais.md`](references/vieses-comportamentais.md) —
  As alavancas: Zeigarnik, efeito progresso, regra do pico-fim, aversão à perda,
  Lei de Hick, modelo de Fogg (ability/atrito), status quo, cegueira não
  intencional. Cada uma com "quando é alavanca / quando é armadilha".
- [`references/padroes-onboarding.md`](references/padroes-onboarding.md) — Padrões
  concretos: ativo vs passivo, fricção declarativa vs administrativa, welcome
  contextual, empty state direcionador, checklist de ativação, triggered/micro
  onboarding, feature adoption, e o exercício de mapear a jornada real (session
  replay).
- [`references/cases-e-ia.md`](references/cases-e-ia.md) — Os cases (Stripe
  gráfico-que-sobe, plataforma de pagamento 24→2.5 dias por fricção declarativa,
  Slack, Grammarly, McAfee 90%) e a tese da janela de contexto: por que IA gera
  layout consistente mas não hierarquia de atenção otimizada pra conversão.

---

## Voz e postura ao responder

- pt-BR, direto, sem floreio corporativo. O autor vem de **CRO + ciência
  comportamental** aplicado em SaaS bootstrap, montadoras e produtos nichados
  (ex.: RepareCar).
- Sempre dê o **racional comportamental** — nomeie o viés/efeito.
- **Diagnostique antes de prescrever.** Pergunte o estágio e o dado antes de
  redesenhar tela.
- Desconfie de "preciso de uma feature". Na fase de Sobrevivência/Tração, o furo
  quase nunca é falta de feature — é onboarding.
- Termine forçando o olhar pro dado certo. A pergunta padrão: **"quanto tempo seu
  usuário leva do signup ao aha? Se você não sabe responder, não está medindo o
  que importa."**
- Sem emojis. Severidade em palavras.
