# Estágios da startup e o papel do design em cada um

A alavanca do design **não é constante**. No MVP ela é quase zero; vai engordando
a cada estágio até virar decisiva na escala. Saber onde você está te diz se o
design vai mexer no caixa ou se vai ser vaidade. 90% dos founders aplicam
conselho de fase errada — leem sobre growth loop de empresa com R$10M de ARR e
tentam implementar com R$15k de MRR. Não funciona, e culpam a execução. O
problema era o mapa.

```
MVP → Sobrevivência → Tração → PMF → Escala
        (aqui mora o onboarding como furo nº 1)
```

O movimento do design ao longo das fases:

```
Encurtar → Ativar → Converter → Expandir → Sistematizar
```

A mesma disciplina alavancando coisas diferentes em cada estágio.

---

## MVP

- **Peso do design:** baixo, quase zero. Lapidar a UI de um produto que ninguém
  quer é "o erro mais bonito que existe — morre lindo".
- **Papel do design:** encurtar o caminho até o valor e **dizer não** pra feature
  que parece óbvia. Há mérito na teoria (Bruno Faggion) de que um MVP "mais ou
  menos" ajuda a encontrar oportunidades realmente abundantes.
- **Quando um produto está morrendo, o último lugar pra procurar culpado é o
  design.**

## Sobrevivência — R$0 a ~R$240k de ARR (≈ R$10k/mês MRR; B2B ~3x)

- **Objetivo único:** provar que alguém paga. Validar duas coisas ao mesmo tempo:
  (1) o problema existe e dói o suficiente pra alguém pagar; (2) sua solução
  resolve de forma que justifique o preço. Tudo que não contribui pra essas duas
  validações é distração.
- **Erro clássico do founder técnico:** excesso de produto — constrói 12 features
  quando precisava de 2.
- **Papel do design** (três frentes):
  - *Diferenciação visual* — em mercado comoditizado, parecer empresa séria (vs.
    "protótipo do Lovable") fecha negócio.
  - *Camada de confiança* — interface polida reduz percepção de risco de empresa
    desconhecida: "se caprichraram nisso, capricharam no resto".
  - *Velocidade de valor* — quanto mais rápido o usuário entende o que o produto
    faz, mais rápido decide se paga. Design ruim adiciona fricção e mata conversão.
- **O furo que mais pesa no balde aqui é o onboarding**, dificilmente falta de
  feature. A primeira semana do usuário vale mais que o roadmap inteiro.
  Consertar ativação **compra runway**, porque tira o founder de baixo de cada
  ticket de suporte.
- **O que medir** (conjunto enxuto): Ativação (% que chega ao aha) · Retenção
  D1/D7 (adapte se o produto não for diário) · TTV · $ por usuário.
- **Sinal de saída:** primeiros pagantes recorrentes voltando sozinhos + receita
  cada vez mais previsível.
- **Armadilhas:** construir features antes de ativar; escalar mídia com balde
  furado (churn alto / ativação baixa); lapidar UI cedo demais; **sair do
  operacional cedo demais** — o contato direto com usuário é sua fonte de
  conhecimento, não um custo a evitar.

## Tração — ~R$240k a R$1.2M de ARR (B2B ~3x)

- **Pergunta central:** "foi sorte ou sistema?" Validar simultaneamente:
  (1) unit economics fecha? (CAC, LTV, payback); (2) canais funcionam de forma
  previsível?; (3) retenção sustenta? Se churn não for dominado aqui, você não
  passa de fase — cada cliente novo tapa o buraco de um que saiu.
- **Papel do design: principalmente comportamental.**
  - Onboarding que entrega valor antes de pedir esforço (ex.: efeito progresso —
    barra em 30% completa mais que barra em 0%).
  - Jornada que reduz TTV — quanto mais rápido o aha real, maior conversão e
    retenção.
  - A maioria mede *feature adoption*; deveria medir *value realization*.
  - Caminho de upsell com as alavancas certas (aversão à perda > desconto;
    mostrar o que perde no downgrade converte mais que mostrar o que ganha no
    upgrade).
- **Por que pesa:** aumento de % de conversão aqui **literalmente significa mais
  MRR na mesa**. Diferença entre 5% e 3% de churn mensal pode significar até 40%
  mais receita retida em 12 meses — mesmo esforço de aquisição, margem diferente.
- **Cuidado:** público fica mais frio à medida que você abre canais. A LP precisa
  de mais confiança e o produto precisa entregar valor mais rápido. Meça
  **retenção por cohort e fonte** — diferenças gritantes aparecem só mudando
  posicionamento e canal.

## PMF — ~R$1.2M a R$6M de ARR

- **Objetivo:** provar que escala. Sinal mais claro: usuários chegam sozinhos,
  ficam e recomendam. Você para de empurrar e começa a ser puxado. Aparece
  previsibilidade (coloca X no topo, sai Y de receita) — é o que investidor quer
  ver. Teste de Sean Ellis mirando ~40% de "muito desapontado".
- **Papel do design:** profundidade e **eficiência de retenção**. O primeiro aha
  funcionou; agora projeta o **segundo aha** e a jornada inteira. Desenha o
  caminho de upgrade e a expansão de uso pra estabilizar a curva de retenção num
  ponto mais alto. Design 100% comportamental: efeito de posse sobre features
  personalizadas, custo afundado saudável em histórico acumulado.

## Escala — R$6M+ de ARR

- **A competição muda de natureza:** concorrência por **atenção**, não só por
  categoria (Netflix pensa na Steam como concorrente — ambos disputam horas do
  usuário). Pergunta: quem mais compete pelo budget e atenção do meu ICP, mesmo
  em categoria diferente?
- **Papel do design:** deixa de ser fluxo e vira **sistema**. Design system pra
  3-4 times entregarem consistente sem o founder no meio de cada decisão. Vira
  multiplicador de força do time. Otimização contínua com testes comportamentais
  — cada 0.1% de melhoria em conversão/retenção são milhões.

---

## Onde está a maioria que pede ajuda

Entre **Sobrevivência e Tração**. Founders técnicos que dominam construir
produto, código e infra, mas travam em: converter trial, reter usuário,
precificar, desenhar jornada que entrega valor antes de pedir esforço. São
**problemas de design comportamental** — que código sozinho não resolve.
