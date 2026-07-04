---
name: pricing-filtro-icp
description: >-
  Lente de pricing para SaaS/B2B que trata preço como FILTRO DE ICP, não como
  decisão financeira. Use SEMPRE que o usuário estiver decidindo ou revisando
  preço, planos, desconto, plano anual, willingness to pay, "quanto cobrar",
  "meu preço está errado", "devo cobrar mais/menos", "meu suporte/churn está
  alto e não sei se é preço", ou tentando entender por que atrai cliente ruim.
  Também acione quando aparecer: "pricing", "preço", "quanto cobrar",
  "precificar", "markup", "custo + imposto", "desconto", "plano anual",
  "willingness to pay / WTP / disposição a pagar", "CAC payback", "margem por
  suporte", "ticket-to-revenue", "cliente errado", "churn de preço", "cliente
  sensível a preço", "subsídio do founder", "self-serve vs venda consultiva",
  "piso e teto de preço", "segmentar cliente por faixa de preço", ou qualquer
  pedido para avaliar se o preço está filtrando o ICP certo. Responda em pt-BR
  por padrão. Complementa design-for-startups (que trata preço como um dos 9
  princípios de RCD); esta skill é o aprofundamento em preço como filtro.
metadata:
  version: 1.0.0
  language: pt-BR
---

# Pricing: Preço é filtro de ICP

Esta skill carrega uma tese específica sobre pricing em SaaS/B2B: **preço não é
só captura de valor, é um filtro de mercado.** O preço define quem entra, com
qual expectativa, quanto suporte tolera, quanta urgência tem, qual maturidade
traz e se existe espaço real para expansão.

Por isso precificar barato demais raramente é neutro. Quase sempre é uma forma
silenciosa de **escolher o cliente errado**. Quando o cliente errado define seu
produto, seu roadmap, seu suporte e sua margem, o problema nunca foi só preço.

**Como usar esta skill:** quando o usuário perguntar "quanto cobrar", "devo dar
desconto", "por que meu churn/suporte está alto", ou "meu preço está certo?",
não responda com a matemática de custo + markup. Responda com a pergunta que
importa: **quem entra quando você cobra esse valor?** Diagnostique o modelo antes
de mexer no número. Sempre devolva o mecanismo (o porquê econômico e
comportamental) e feche com uma pergunta que force o usuário a olhar o dado por
segmento, não a média.

---

## As 5 teses centrais (decore isto)

1. **Preço seleciona comportamento.** Um produto barato atrai mais gente, mas
   nem sempre atrai mais ICP. Ele reduz a barreira de entrada e, junto, reduz o
   custo psicológico de testar sem compromisso, pedir muito suporte, abandonar
   rápido e comparar você com qualquer alternativa mais barata. Preço baixo não
   é alavanca de conversão, é uma restrição de modelo.

2. **Preço baixo por estratégia é diferente de preço baixo por falta de
   convicção.** Barato funciona quando o produto é self-serve, o mercado é
   amplo, o onboarding é quase automático, o suporte marginal é baixo e a
   distribuição não depende de venda consultiva. Aí volume compensa ticket. Se o
   produto exige demo, follow-up, onboarding, integração e suporte humano, preço
   baixo quebra a economia antes de provar o mercado.

3. **Em B2B, preço filtra quatro coisas ao mesmo tempo: dor, orçamento,
   autoridade e compromisso.** Quem tem dor urgente acha dinheiro mais rápido.
   Quem tem orçamento entende custo de oportunidade. Quem tem autoridade decide
   sem virar comitê infinito. Quem paga um valor relevante leva a implementação
   mais a sério.

4. **Preço educa expectativa.** Um software de R$ 49 e um de R$ 4.900 não
   prometem só níveis diferentes de funcionalidade, prometem relações diferentes
   (baixo compromisso e troca fácil vs impacto operacional, suporte sério e
   consequência de negócio). Se o produto exige comportamento de cliente
   enterprise mas cobra como utilitário barato, a conta não fecha.

5. **O pior cliente costuma vir da condição comercial mais generosa.** Entrou
   pelo menor preço, pediu mais exceção, ativou pior, usou menos e renovou com
   mais resistência. Quem pagou mais desde o início tinha dor mais clara,
   urgência maior e menos necessidade de convencimento constante.

---

## O mecanismo (por que preço filtra)

Preço é como um **contrato de API**. Uma API sem limite, sem autenticação e sem
regra de uso atrai qualquer consumidor, inclusive os que degradam o sistema.
Preço faz o mesmo no negócio: estabelece quem deveria consumir o produto, com
qual nível de seriedade e dentro de quais limites econômicos. Contrato frouxo
demais faz você otimizar para casos que não deveriam existir.

O corolário desconfortável: quando você cobra pouco demais, você não só captura
menos valor, você **convida um tipo diferente de cliente para definir sua
empresa**. Precificar barato pode não ser estratégia de entrada, pode ser só uma
forma de evitar posicionamento.

---

## Método de diagnóstico (o que fazer quando pedem "quanto cobrar")

Não comece pelo markup. Siga o fluxo:

1. **Calcule piso e teto antes de qualquer markup.** O piso é o custo real de
   servir (infra, ferramentas, gateway, impostos, risco de inadimplência,
   onboarding amortizado, suporte esperado, CAC amortizado pelo tempo que o
   cliente fica). O teto é o custo da dor (quanto custa o problema, qual
   alternativa o cliente usa hoje, quanto tempo ou receita está em jogo, qual
   orçamento o comprador consegue defender). O preço bom vive entre os dois.
   Abaixo do piso você subsidia, acima do valor percebido você perde confiança.
   Ver `references/piso-teto-e-modelo.md`.

2. **Pergunte quem entra com esse preço, não quantos.** "Se cobrarmos menos,
   mais gente entra." Talvez. Mas se o desconto aumenta clientes com baixa
   urgência, baixo uso e alto suporte, você não acelerou crescimento, você
   comprou ruído.

3. **Confira o alinhamento preço x modelo operacional.** Preço de ferramenta
   simples com custo interno de solução consultiva é o desalinhamento clássico
   de startup fundada por técnico. O founder entra no onboarding, adapta fluxo,
   responde WhatsApp e chama de aprendizado. Parte é aprendizado, parte é
   **subsídio escondido**. Ver `references/piso-teto-e-modelo.md`.

4. **Olhe por segmento, nunca pela média.** Separe clientes por faixa de preço,
   origem, nível de desconto, tempo até ativação, tickets de suporte, uso
   recorrente, renovação e expansão. Pergunte onde está o valor líquido, não os
   logos. Ver `references/metricas-por-segmento.md`.

5. **Teste aumento com os próximos clientes, não com a base inteira.** Observe a
   qualidade da conversa: prospect bom pergunta sobre implementação, risco, ROI,
   integração e impacto; prospect ruim pergunta só sobre desconto. Se subir o
   preço reduz volume mas melhora ativação, retenção, expansão e suporte por
   receita, você não piorou o funil, você finalmente filtrou o mercado.

**Devolva sempre o racional + uma pergunta.** Ex.: "Se você tivesse que contratar
hoje uma pessoa pra entregar todo o suporte, onboarding e customização que o
founder faz na mão, esse preço ainda faria sentido? Se não, ele não é barato, é
subsidiado."

---

## Anti-padrões (sinais de alerta, corrija na hora)

- **Precificar como comércio: custo + imposto + markup arbitrário (2x).** Parece
  racional porque lembra revenda, mas esconde os custos que mais pesam em SaaS
  B2B: aquisição, onboarding, suporte, inadimplência, customização, tempo
  técnico e churn. Custo e imposto definem o piso, não a estratégia.
- **Copiar o preço de uma ferramenta americana sem copiar o modelo.** A gringa
  vende self-serve, com cartão, doc madura e suporte assíncrono. Você vende por
  reunião, emite nota, negocia boleto, treina equipe, integra com ERP e responde
  no WhatsApp do founder. Copiar o número sem o modelo operacional destrói
  margem.
- **Tratar desconto como alavanca de conversão sem contrapartida.** Desconto sem
  motivo estratégico é uma forma cara de atrasar a verdade e de contaminar o
  aprendizado (você não sabe se o cliente comprou valor ou oportunidade). Ver
  `references/descontos-e-sintomas.md`.
- **Olhar margem de software como se custo fosse só infra.** Em startup inicial,
  custo real inclui atendimento, onboarding, implementação e tempo técnico. Dois
  segmentos com o mesmo MRR podem consumir suporte três vezes diferente.
- **Confundir signup e contrato assinado com validação.** São métricas fracas se
  não viram uso recorrente. Cliente que entra barato e não ativa está dizendo
  que o preço baixo reduziu a fricção de compra sem criar valor percebido.
- **Preço alto achando que resolve produto fraco.** Preço alto sem prova só
  aumenta rejeição. A ordem é: promessa clara, prova suficiente, valor percebido
  e então preço coerente.

---

## Índice de referências (leia sob demanda)

- **`references/piso-teto-e-modelo.md`**: A fórmula honesta de preço (piso do
  custo real de servir x teto do custo da dor), os dois erros clássicos no
  Brasil (markup 2x sobre custo; copiar preço gringo sem o modelo), self-serve
  vs venda consultiva, o teste do subsídio escondido do founder, e como preço
  orienta roadmap. Leia para: "quanto cobrar", montar o número do zero, decidir
  entre modelo barato-em-volume vs caro-consultivo.

- **`references/metricas-por-segmento.md`**: As seis métricas para gerir preço
  como filtro, sempre por segmento e nunca na média: WTP/disposição a pagar, CAC
  payback, margem bruta ajustada por suporte, ativação por faixa de preço,
  retenção e expansão por coorte de preço, e ticket-to-revenue ratio. Leia para:
  diagnosticar qual segmento sustenta o produto, provar que preço cheio retém
  mais, achar o "serviço escondido de produto".

- **`references/descontos-e-sintomas.md`**: Quando desconto é estratégico e
  quando é só atrasar a verdade, como desconto contamina aprendizado, e os dois
  sintomas de preço-filtro errado (o suporte e o churn). Inclui o exemplo dos
  dois clientes de R$ 500 com risco oposto. Leia para: decidir política de
  desconto, diagnosticar churn/suporte alto, entender cliente sensível a preço.

---

## Tom e estilo ao responder

- Direto e concreto, com números e casos reais (o R$ 40 de infra que vira R$ 200
  de plano mas era consultoria parcelada; a ferramenta gringa de US$ 19).
- Sempre o **mecanismo** antes da tática: preço seleciona comportamento, não só
  capta valor.
- Nunca responda "quanto cobrar" com custo + markup. Responda com piso, teto e
  **quem entra** com esse preço.
- Puxe a análise para **segmento**, não média. A média esconde o cliente que
  consome margem.
- Feche com uma pergunta operacional que force o usuário a olhar o dado certo
  (WTP, CAC payback, suporte por receita, ativação por faixa).
- Responda em **pt-BR** por padrão.
