# Cases concretos + a tese da janela de contexto (IA)

Estudos de caso pra ancorar os princípios, e o argumento de por que um designer
experiente ainda importa numa era de interface gerada por IA.

## Stripe — o gráfico que sobe (Regra do Pico-Fim)

No momento em que a primeira transação é processada, o dashboard **não mostra um
número — mostra um gráfico que sobe.** Visualmente a diferença é pequena;
comportamentalmente é absurda. **Número é dado; gráfico que sobe é progresso.**
Progresso → dopamina → memória emocional associada ao produto.

O usuário técnico já tinha superado a fricção da integração (geralmente de
madrugada). O momento seguinte era crítico: ou o produto entregava uma sensação
**proporcional ao esforço investido**, ou virava mais uma ferramenta na lista. Um
número teria cumprido a função; o gráfico **criou um cliente**. É design de
momento de pico aplicado no exato segundo de maior vulnerabilidade emocional do
ciclo de ativação. A maioria entrega confirmação onde deveria entregar celebração.

## Plataforma de pagamentos BR — 24 → 2.5 dias (fricção declarativa)

Tempo do cadastro até a primeira venda caiu de **24,2 para 2,5 dias**. A
intervenção **não foi cortar etapas — foi adicionar uma.**

Antes, o fluxo era enxuto: cadastro → aprovação → dashboard. O usuário entrava
sem declarar nada sobre si. A etapa adicionada (parece administrativa, não é):
**o usuário responde o que vende e qual seu objetivo de longo prazo** — ~30
segundos, posicionada entre cadastro e produto, no momento em que ele ainda
decide se vale o esforço.

Dois andares de efeito:

1. **Operacional** — a jornada seguinte fica específica: quem vende infoproduto vê
   um caminho, quem vende físico vê outro. Recomendações, tutoriais e próximas
   ações viram função da declaração inicial.
2. **O que importa** — o usuário fez um **micro-compromisso com o resultado que
   quer** antes de tocar no produto. Deixou de explorar uma plataforma e passou a
   **executar um plano que ele próprio acabou de descrever.**

Lição: a heurística "onboarding bom = onboarding curto, toda fricção atrasa o
aha" está **incompleta**. Existe fricção administrativa (corte) e declarativa
(expanda). Pergunte de cada etapa: está coletando dado ou fazendo declarar
intenção?

## SaaS B2B — a matemática da tríade de ativação

Base de 900 usuários, ARPU R$300, churn 6% (54 contas/mês saindo = R$16.200/mês).
Intervenção: **welcome contextual + empty state + checklist de ativação**.
Resultado: churn ~30% menor → 16 contas a menos cancelando/mês. Com LTV médio de
11 meses, **R$52.800 recuperados** numa base que já existia — sem tráfego novo,
sem feature nova. E o efeito estrutural pesa mais que o caixa imediato: churn
menor melhora valuation e faz cada real de aquisição render mais. (Faixa típica
de recuperação em ARR: R$40k–R$120k só reestruturando onboarding.)

## Slack — entender fazendo

Primeira coisa: te colocam num canal e te fazem **mandar uma mensagem**. Não te
mandam ler tutorial — você já usou o produto, e ao usar, entendeu. **Entender
fazendo > entender lendo.** Modelo do onboarding ativo.

## Grammarly — valor percebido recorrente

Mostra **quantas palavras já te ajudou** num dashboard simples. Transforma valor
entregue (invisível) em valor percebido (visível e cumulativo), reforçando
retenção. Provocação aplicável: imagina a Meta mostrando isso na central de
anúncios, ou o LinkedIn dando dicas constantes pra subir seu SSI.

## McAfee — FAQ derruba 90% do suporte

Redução de **90%** do volume de suporte só com FAQ — na época, sem chatbot, texto
puro. Prova de que **suporte é, em boa parte, problema de design**: redesenhar a
jornada resolve a causa; automatizar o bot só trata o sintoma.

---

## A tese da janela de contexto (por que IA não substitui o designer sênior)

Direcionada a founder técnico em Tração/PMF que usa IA ou template pra interface.
O argumento é técnico de propósito — gera credibilidade com dev e é verificável.

**O ponto:** o limite não é capacidade de gerar pixels — é **janela de contexto**.
Um design system é um manual de instruções **incompleto**: define componentes,
espaçamentos, cores, tipografia. **Não define quando usar o quê pra atingir qual
objetivo.** IA absorve o manual e gera interface consistente a partir dele. O que
ela **não** carrega na mesma janela:

- Pra onde o contraste direciona a atenção — se o olho vai pro lugar certo ou se
  dispersa.
- Se a copy informa ou converte, e pra qual nível de consciência do problema está
  calibrada.
- Se a arquitetura de informação está estruturada pra consumo linear ou pra
  decisão.
- Se os padrões visuais ativam **confiança** ou acionam **detector de golpe**.
- Décadas de padrões de LP/pricing que falharam e por quê; milhares de horas de
  mapa de calor (onde o olho realmente vai vs. onde o designer achava que ia);
  cases de churn onde a interface era polida mas o onboarding destruía retenção
  em silêncio; uma biblioteca de vieses cognitivos e quando cada um é alavanca ou
  armadilha.

Isso é **heurística validada em prática**, não cabe em contexto.

> Design system diz "use esse botão". Designer experiente pergunta "esse botão
> está competindo com o CTA principal ou direcionando pra ele?". IA gera layout
> consistente; não gera **hierarquia de atenção otimizada pra conversão**.

**Importa na prática? Depende da fase.** Em MVP, pouco — consistência visual
basta. Em Tração, começa a importar — a diferença entre 2% e 4% de conversão é a
diferença entre queimar runway e ganhar tempo. Depois do PMF, vira alavanca de
margem — cada ponto de conversão é receita sem CAC adicional.

**A pegadinha (genérico ativa desconfiança):** à medida que interfaces geradas por
IA viram commodity, certos padrões passam a ser percebidos como genéricos — e
genérico aciona desconfiança ("isso parece template" → produto amador ou golpe).
O cérebro mistura o que enxerga com o valor que atribui. Analogia: um Audi S8 2006
com motor V10 divide powertrain com o Lamborghini Gallardo, mas pra maioria é "só
um Audi velho". **A interface do seu produto está sendo percebida como Gallardo
ou como Audi usado?**
