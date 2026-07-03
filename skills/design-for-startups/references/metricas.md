# Métricas — o que medir e o que NÃO medir

> Leia para: dashboards, "minhas métricas", diagnóstico de funil, LTV/CAC, NRR,
> activation, retenção, feature adoption.

A regra mestra: **founder técnico tende a medir a coisa fácil e visível (que dá
pra comemorar) em vez da coisa que importa.** Aquisição é crescimento visível —
lead novo aparece no dashboard, dá pra postar "batemos recorde de signups".
Ativação e retenção são silenciosas. Por isso a maioria mede ao contrário de
onde o valor mora.

---

## Cadastro não é tração

Cadastro é o custo mais barato que o usuário paga: um email, uma senha, às vezes
nem isso (login social). Testar não custa quase nada → mede **curiosidade**, não
valor. A curva de signups sobe com tráfego pago e **parece** ganho de base,
enquanto a retenção real fica parada. Cadastro vale como **topo de funil** — o
problema é parar a leitura nele e nunca olhar o que acontece depois.

> "A curva de cadastro pode subir com tráfego pago, mas o uso e a ativação só
> sobem com produto bom."

Tem produto que **converte muito bem e mesmo assim não cresce**: entra gente
pela frente e some pela porta dos fundos na mesma velocidade. Quando isso
acontece, o instinto é mexer no produto pra segurar quem sai — mas o gatilho do
churn pode estar **antes**, na expectativa que a venda criou. Ver
`conversao-landing.md` (dívida de expectativa).

---

## Os 3 erros de medição mais comuns (e a correção)

1. **Mede signups → deveria medir activation rate.**
   Signup é a porta; ativação é o usuário sentar na cadeira e usar pra valer.
   - Activation rate médio de SaaS: **30-37%**. Top quartile bate **40%**.
   - **Abaixo de 20%** indica problema estrutural sério no onboarding e/ou
     produto.

2. **Mede tempo no produto (session time) → deveria medir tempo até a primeira
   ação útil e a repetição dela.**
   Session time inclui usuário perdido procurando o que fazer. Tempo até a
   primeira ação útil mede se o produto entrega valor rápido.

3. **Mede onboarding completion → deveria medir D7 retention.**
   Completar 8 passos de tour significa que o usuário foi **obediente**, não que
   entendeu o valor. D7 retention diz se ele voltou.
   - Média de SaaS: **10-15%**. Acima de **30%** é forte.

---

## Aha moment e Time to Value (TTV)

**90% dos usuários abandonam o produto na primeira semana se não chegarem a
valor claro.** O **aha moment** é o instante exato em que o usuário sente que o
produto resolve algo que ele tinha. Antes disso ele só explora; depois, começa a
integrar o produto na rotina.

- TTV médio: **1 dia, 12 horas e 23 min** (benchmark Userpilot, 547 empresas).
- Top performers: **abaixo de 5 minutos**.

**Como descobrir o SEU aha moment (não o que você acha que é):** pegue seus
clientes pagantes e olhe o que **todos** fizeram na primeira semana que os
usuários que cancelaram **não** fizeram. Isso é provavelmente seu aha moment.
Para a maioria dos SaaS, envolve fazer algo com colaborador (convite,
compartilhamento, comentário) — rede leve já cria efeito de retenção.

Exemplos canônicos:
- **Slack:** times que trocavam **2.000 mensagens** tinham 93% de probabilidade
  de continuar. Esse número virou o norte da ativação.
- **Facebook:** **7 amigos em 10 dias.** Falavam disso em todo all-hands.

Pergunta-guia: *Quanto tempo seu usuário leva entre signup e aha moment? Se não
sabe responder, não está medindo o que importa.*

---

## Churn — onde ele realmente começa

Churn alto (falando de produto com **+50% de churn no mês**) raramente é só
problema de produto. Tipos:

- **Churn de promessa quebrada** — o gatilho está na expectativa criada pela
  venda. O usuário chega esperando o que foi vendido, encontra outra coisa. Ver
  `conversao-landing.md`.
- **Churn de qualificação** — quem nunca teve o problema que você resolve e
  descobriu isso usando. Isso se resolve **antes**, na própria página (ver
  `conversao-landing.md`, filtro na LP).
- **Churn de trabalho concluído** — produto que resolve um problema pontual
  (currículo, contrato, migração, pitch deck). Não é falha de produto, é de
  modelo de negócio. Ver `estrategia-produto.md` (ritual TurboTax).

Sintoma diagnóstico: **churn de 30 dias alto + NPS ok = problema de promessa,
não de produto.**

Padrão organizacional perigoso: marketing batendo meta (convertendo bem) e
produto apagando incêndio (retendo mal), e ninguém conecta as duas coisas.
**Converter bem e reter mal = ser melhor de palco do que de cozinha.**

---

## LTV — a fórmula padrão superestima em produto novo

`ARPU / Churn` funciona em produto maduro com churn estabilizado. Em produto em
tração, **superestima LTV entre 30% e 50%**, por motivo estatístico: o churn é
maior nos primeiros 90 dias e cai conforme a base se autosseleciona. Calcular com
o churn médio dos últimos 12 meses mistura cohorts jovens (alto churn) e maduras
(baixo churn) — e a média não descreve nenhum dos dois.

Exemplo:
- ARPU R$200, churn médio 8% → LTV pela fórmula = **R$2.500**.
- Por cohort:
  - 0-3 meses: churn 18% → LTV real **R$1.111**
  - 3-6 meses: churn 10% → LTV real **R$2.000**
  - 6+ meses: churn 5% → LTV real **R$4.000**
- **R$2.500 não existe na base** — é a média de coisas diferentes.

Por que importa: você usa LTV pra decidir quanto pode gastar em CAC. LTV
superestimado autoriza gasto que o negócio não suporta (LTV:CAC parece 4:1
quando o real é 2:1). Pergunta-guia: *Esse LTV vem da fórmula geral ou do cohort
dos últimos 6 meses?* Se vem da fórmula geral em produto com <18 meses, refaça
por cohort. Ver `metodos-analise.md`.

---

## CAC — quase sempre é problema de filtro, não de mídia

CAC alto raramente é problema de criativo/canal. O ponto menos óbvio: **a
landing page filtra antes do formulário.** CAC real se mede em **custo por deal
fechado** (ou por conversão $), não custo por lead. Se você fecha 1 em cada 50
leads, baixar pra 30 leads com 1 fechamento quase dobra a eficiência de mídia —
com a mesma verba. Ver `conversao-landing.md` (alavancas de filtro na LP).

---

## NRR (Net Revenue Retention)

Em SaaS B2B, **NRR acima de 110%** separa crescimento sustentável de funil
furado. Alavanca subestimada: **comunicação proativa de novas features/migrações
para a base existente** (não email de release que ninguém lê). Ver
`estrategia-produto.md` (comunicação reativa = vetor de churn).

---

## Feature adoption rate

A ideia não é medir se a feature é **clicada**, mas se ela virou **hábito** —
usada com a frequência apropriada dentro do produto, em janelas compatíveis.
Ex.: no RepareCar há OS (ordem de serviço) todo dia; se uma feature atua no nível
da OS, precisa ser usada pelo menos uma vez ao dia. Feature que não bate um
critério mínimo de adoção entra em **revisão** (mal desenhada, no lugar errado,
ou ninguém precisa dela). Ver `estrategia-produto.md` (adoção é design, não
comunicação).

---

## Swiss Knife Index (resumo — detalhe em estrategia-produto.md)

Pega todas as features, conta quantas são usadas por **>40% dos ativos em 30
dias**, divide. Resultado **< 0,3** = canivete suíço (produto que "faz tudo" e o
usuário se perde). Mais superfície = mais carga cognitiva, mais código, e diluição
da percepção de pra que serve o produto.
