# Alavancas comportamentais do onboarding

A função da interface é **conduzir comportamento do usuário para atingir um KPI**.
Estética é, às vezes, subproduto disso — não o objetivo. Cada viés abaixo é
**alavanca OU armadilha** dependendo de como você usa. O maior erro financeiro do
founder técnico é contratar designer só pra deixar o software "bonito": estética
é subjetiva, não escala e não salva produto de churn alto.

Três eixos onde o design move dinheiro:

- **Conversão** via redução de carga cognitiva (Hick + Fogg).
- **Retenção** via percepção de progresso (Zeigarnik + efeito progresso + pico-fim).
- **Ascensão/expansão** via aversão à perda.

---

## Efeito Zeigarnik

Tarefas incompletas ocupam espaço mental; pessoas voltam pra fechar loops — **mas
só se o loop for pequeno o suficiente pra parecer fechável.**

- **Alavanca:** barra de progresso que cria um leve desconforto produtivo e
  incentiva o engajamento; checklist de ativação com poucos itens.
- **Armadilha:** onboarding de 14 passos. O usuário fecha a aba no passo 5 se não
  houver pequenas vitórias percebidas pelo caminho. Loop grande demais = não
  parece fechável = abandono.

## Efeito progresso (endowed progress)

Pessoas completam o que já começaram — **mas só se perceberem que começaram.**

- **Alavanca:** começar a barra acima de zero. Usuário que vê barra em 30%
  completa mais do que usuário que vê barra em 0%. Resignifique o esforço que ele
  já teve (criar conta, pagar): *"Você já fez a parte difícil, só faltam 3 passos."*
- **Armadilha:** onboarding que começa no zero absoluto — o usuário olha e enxerga
  só esforço pela frente.
- **Função de retenção:** a sensação de movimento empurra o usuário na direção do
  valor do produto.

## Regra do Pico-Fim

O usuário avalia a experiência pelo **pico emocional** e pelo **encerramento** —
raramente pela média.

- **Alavanca:** desenhar deliberadamente um momento de pico no instante de maior
  vulnerabilidade emocional do ciclo de ativação (ex.: Stripe mostra um **gráfico
  que sobe** na primeira transação, não um número — número é dado, gráfico que
  sobe é progresso → dopamina → memória emocional associada ao produto).
- **Armadilha:** a maioria entrega **confirmação** ("Pronto, configurado") onde
  deveria entregar **celebração**. Onboarding é design de emoção e memória; a
  memória das primeiras horas é o ativo de retenção mais barato e mais ignorado.

## Aversão à perda

A dor de perder pesa mais que o prazer de ganhar.

- **Alavanca (upsell):** desenhe os planos pra que o usuário **naturalmente
  esbarre nos limites de valor**, gerando sensação de perda. O upgrade acontece
  por não querer perder uma eficiência que ele acabou de descobrir — não por um
  banner que pisca no dashboard. No downgrade, **mostrar o que ele perde converte
  mais** que mostrar o que ganha no upgrade.
- **Armadilha:** banner genérico de upsell desconectado do momento de uso;
  desconto (que ancora preço pra baixo) no lugar de aversão à perda.

## Lei de Hick

Cada opção extra na tela aumenta (de forma ~exponencial) o tempo de decisão e a
taxa de abandono.

- **Alavanca:** reduzir opções no caminho crítico; pré-selecionar defaults
  inteligentes. Em vez de perguntar "qual plano você quer?", **pré-selecione o
  mais adequado** com as infos já coletadas e ofereça upsell: *"Quer mudar? Olha
  o que você leva por mais R$20/mês."*
- **Armadilha:** menu cheio, onboarding que pede decisões antes de o usuário ter
  contexto pra decidir.

## Modelo de Fogg (B = MAP: Motivação, Ability, Prompt)

Comportamento acontece quando motivação, **habilidade/facilidade** e gatilho
coincidem. O design entra principalmente na **Ability**: tornar a tarefa-alvo o
**caminho de menor resistência**.

- **Tarefa-alvo** = o que você quer que o usuário faça.
- **Alavanca:** remover atrito pra que a ação que entrega valor seja a mais fácil
  de fazer na tela.

## Viés de status quo

Mesmo quando a forma nova é objetivamente melhor, o custo de **re-aprender** pesa
mais que o benefício percebido. É um dos motivos centrais de feature nova não ser
adotada (ver `padroes-onboarding.md` → feature adoption).

## Cegueira não intencional (inattentional blindness)

**O usuário não vê o que não está procurando.** Ele entra com uma intenção
específica, faz o caminho que sempre fez e sai. Por isso o founder erra ao supor
que "se a feature está no produto, ela será encontrada" — não será.

- **Alavanca:** empty state direcionador e triggered onboarding (apresentar a
  feature no momento/tela em que ela seria usada).
- **Armadilha:** modal de "olha nossa feature nova" no login — geralmente
  ignorado.

---

## Nota sobre retenção e a falsa pista da UI

Provavelmente **nenhum usuário cancela porque a UI é feia.** Ele cancela porque
**não viu valor** — seja por não ter conseguido, seja por não ter encontrado. O
contraste e o efeito de progresso no onboarding existem pra dar sensação de
movimento e empurrar o usuário na direção do valor. Recebeu valor? Contabiliza em
TTV. Quando um produto está morrendo, o último lugar pra procurar culpado é o
design — mas, na fase certa, essas alavancas decidem entre queimar runway e
ganhar tempo.
