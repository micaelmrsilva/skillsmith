# Padrões concretos de onboarding e ativação

Catálogo de padrões aplicáveis, o exercício de mapear a jornada real, e o
problema específico de adoção de feature nova.

## Ativo vs passivo (a decisão estrutural)

- **Passivo** — tooltips, tour, docs; o usuário aprende "se quiser". Assume que
  ele vai explorar. Ele não vai. → baixa retenção.
- **Ativo** — sequência desenhada de ações onde cada ação entrega valor e puxa a
  próxima. Você assume que sabe o caminho mais curto pro valor, remove fricção e
  garante que ele chegue. → retém muito mais.

Frame: não "qual é o mínimo que o usuário precisa fazer", e sim **"qual é a menor
ação que entrega o maior valor no menor tempo"**. (Detalhe e o princípio Slack em
`metodo-5-passos.md`.)

## Fricção declarativa vs administrativa

- **Administrativa** — coleta dado pro sistema, não compra nada pro usuário →
  **corte ou adie**.
- **Declarativa** — faz o usuário declarar o que veio fazer → compra compromisso,
  customização e direcionamento → **expanda**.

O efeito da fricção declarativa tem dois andares: (1) operacional — a jornada
seguinte fica específica (quem vende infoproduto vê um caminho, quem vende físico
vê outro; tutoriais e próximas ações viram função da declaração); (2) o que
importa de verdade — o usuário fez um **micro-compromisso com o resultado que
quer** antes de tocar no produto. Não está mais explorando uma plataforma, está
**executando um plano que ele próprio acabou de descrever**. (Case 24→2.5 dias em
`cases-e-ia.md`.)

## Os três padrões de ativação que reduzem churn (a "tríade")

Combinação que, num B2B de 900 usuários com ARPU R$300, derrubou churn ~30%:

1. **Welcome contextual** — não um "bem-vindo, aqui está a documentação", e sim
   uma boas-vindas que já direciona pra primeira ação de valor com base no
   contexto do usuário.
2. **Empty state direcionador** — empty state é **venda, não placeholder**. Quando
   o usuário entra numa tela onde a feature seria usada, o empty state mostra a
   feature e o caminho de 1 clique pra primeira vez. Responde "o que é + por que
   eu quero + como começo agora".
3. **Checklist de ativação** — Zeigarnik na prática: poucos itens, percebíveis
   como fecháveis, idealmente começando acima de zero (efeito progresso). Cada
   item com deep-link pra ação.

## Triggered onboarding / micro-onboarding

Cada feature importante merece seu **micro-onboarding**, ativado pelo
**comportamento que sinaliza necessidade** — não no login genérico.

> Ex.: usuário de CRM entrou na página de venda? É o momento de apresentar a IA
> que ajuda a quebrar objeções. (Disparo por contexto, não por calendário.)

## Tooltips direcionadas

Use tooltips em funcionalidades **ainda não exploradas**, pra depender menos do
momento inicial — que pode ter sido atropelado por um usuário com pressa.

## Onboarding declarativo no início (micro-compromisso)

Posicione uma pergunta declarativa ("o que você vende? qual seu objetivo de longo
prazo?") **entre o cadastro e o produto**, no momento em que o usuário ainda está
decidindo se aquilo vale o esforço. 30 segundos que compram compromisso e
personalizam toda a jornada.

---

## Adoção de feature nova (por que features morrem)

Padrão típico: você lança feature, faz changelog, email pra base, post no
Twitter, badge "novo". 3 semanas depois: **9% dos ativos abriram, 4% usaram mais
de uma vez.**

O founder técnico parte da suposição de que **se a feature está no produto, será
encontrada. Não será.** Dois vieses matam:

- **Cegueira não intencional** — o usuário não vê o que não está procurando. Entra
  com intenção específica, faz o caminho de sempre, sai.
- **Status quo** — mesmo quando a feature nova é objetivamente melhor, o custo de
  re-aprender pesa mais que o benefício percebido.

A maioria dos lançamentos falha porque trata adoção como **problema de
comunicação**, quando é **problema de design**. O que funciona:

- **Anúncio contextual** (não modal no login, que é ignorado).
- **Empty state direcionador** na tela onde a feature seria usada.
- **Triggered onboarding** disparado pelo comportamento que sinaliza necessidade.
- **Feature adoption rate como hábito** — não medir se foi clicada, mas se virou
  hábito, usada na frequência apropriada dentro de janelas compatíveis. (Ex.:
  RepareCar tem OS todo dia; feature no nível da OS precisa ser usada ≥1x/dia.)
- **Critério de continuidade** — feature que não bate o limite de adoption rate
  entra em revisão: foi mal desenhada, está no lugar errado, ou ninguém precisa
  dela. Lançar feature é fácil; fazer ser usada são outros 500.

---

## Mapear a jornada REAL (founder vs usuário)

> O founder médio descreve a jornada em 12 passos; o usuário médio executa 4. A
> distância entre o diagrama no Excalidraw e o replay de sessão real é onde mora
> a maior parte do churn evitável em produto early-stage.

Duas jornadas que raramente coincidem:

- **Jornada do founder** (top-down): começa pelo que o produto quer que o usuário
  faça. *Onboarding → Ativação → 1º projeto → 2º projeto → Expansão → Advocacy.*
  Tem lógica, mas não retrata a realidade.
- **Jornada do usuário** (bottom-up): começa pelo **problema específico** que ele
  tinha quando abriu a aba. Ele quer resolver aquilo; todo o resto é fricção
  entre ele e o resultado.

O gap é invisível pro founder porque ele **nunca executou a jornada como
recém-chegado** — vive a jornada do criador.

### Exercício em 3 passos (sem abrir o Figma)

1. **Escreva sua versão** da jornada em passos numerados — o que você *acha* que
   ele faz, na ordem que você *acha*. No papel ou notes, sem prototipar.
2. **Abra 5 gravações de sessão** de usuários reais nos primeiros 7 dias. Anote o
   que cada um **efetivamente faz**, na ordem, com tempo — e também **o que ele
   tenta e desiste**.
3. **Coloque as duas listas lado a lado.** O relatório está nas diferenças. Cada
   divergência é uma hipótese a confirmar ou descartar.

Pergunta de fechamento: **qual percentual dos seus usuários executa o happy path
que você desenhou?** Se você não sabe, é candidato a uma sessão de pesquisa
amanhã. Jornada de usuário é o que aparece no replay; o que está no Figma é
hipótese.

---

## Vídeo de onboarding dá boas-vindas, não ensina

**Um bom vídeo de onboarding não é manual. Ele dá boas-vindas, cria conexão,
mostra o produto num relance e aponta onde o valor vem mais rápido.** Ninguém lê o
manual do carro nem o do iPhone, e ninguém vai assistir seu vídeo esperando aula.
Seu produto também não precisa de manual, você já leu o do seu carro?

O mecanismo: o vídeo que tenta *educar* compete com a pressa do usuário e perde. O
que retém é o vídeo que reduz a sensação de estar perdido e cria vínculo no
primeiro contato, deixando o aprendizado de verdade pra dentro do próprio fluxo
(ativo, empty state, triggered onboarding). Educação é trabalho do produto; o
vídeo é o aperto de mão.

Como aplicar: mire em cortar TTV, tickets de suporte e a sensação de perdido, não
em ensinar feature por feature. A duração segue a urgência do seu ICP (alguém com
pressa pra resolver uma dor quer 40 segundos; alguém feliz montando o Lego dele
aguenta mais). Não precisa de ator nem set chique: dá pra gravar no Screen Studio e
superar o vídeo de muito produto grande (foi o que o Richard fez com o dele).

Visualmente, pense num modal de boas-vindas "Sua conta foi criada!" com o
thumbnail do vídeo intro embutido no próprio modal e um único CTA "Próximo", sem
distração e sem menu de opções.

Pergunta-guia: *seu vídeo está dando boas-vindas ao usuário ou tentando ensinar o
que o produto deveria ensinar sozinho?*

Fonte: @richardrx.
