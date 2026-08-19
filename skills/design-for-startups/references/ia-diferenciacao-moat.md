# Diferenciação e moat na era da IA

> Leia para: "todo mundo tem o mesmo produto", commoditização, vibe coding, LP
> gerada por IA, clone/copycat, barreira de entrada, moat, por que o produto
> parece genérico, IA no fluxo de design.

Quando a barreira de entrada tende a zero, a competição tende ao infinito. A IA
derrubou a barreira: por baixo do capô, ~90% das ferramentas novas chamam as
mesmas APIs. **Código deixou de ser o ativo — virou um ingrediente.**

> Você pode ser dono de todo o cimento do mundo. Sem projeto e engenharia
> estrutural, você tem uma pilha de concreto cinza.

---

## Velocidade de build nunca foi o gargalo — ativação é

Construir ficou mais barato, e o time confunde velocidade com progresso. Só que
**entregar a mesma interface confusa mais rápido é só um jeito mais eficiente de
chegar no churn.** O gap real continua sendo o espaço entre o usuário entrar no
produto e entender o que fazer.

O que a IA não toca e você precisa atacar: **onboarding, hierarquia de atenção e
entrega de valor nas primeiras sessões (TTV)** — e agora com mais produtos
disputando a mesma atenção.

---

## Mesmo motor, UX diferente — não compita na commodity

Engenharia resolve a função base; **design e empacotamento é que diferenciam e
resistem à cópia.**

VW Up, Seat Mii e Skoda Citigo dividem exatamente a mesma plataforma — chassi,
transmissão e o mesmo motor EA211 — e mesmo assim são desenhados e empacotados
para ICPs diferentes (jovem, utilitário pragmático, confiabilidade).

UX superior compõe receita em três frentes:
1. **remove fricção inicial** → sobe conversão;
2. **encaixa no workflow do usuário** → derruba churn, sobe LTV;
3. **facilita uso contínuo/colaborativo** → habilita upsell.

> O motor pode ser idêntico; o moat é a arquitetura da experiência.

---

## Ideia validada é jogo de curto prazo — planeje o moat

Se sua única vantagem é o codebase, você construiu um MVP validado **para
concorrente melhor capitalizado executar**. Barreira estrutural é planejada, nunca
acidental. Três moats deliberados:

1. **Brand power** — identidade visual própria + UX acima da média sinaliza menos
   risco e vende segurança percebida (conversão).
2. **Custo de troca via UX** — fluxos que o usuário internalizou tornam caro
   migrar pro clone 20% mais barato, em produtividade (retenção). Detalhe das 5
   alavancas de custo de troca em `estrategia-produto.md`.
3. **Arquitetura de expansão** — efeito de rede interno (convidar pra colaborar)
   é mais difícil de copiar e traz usuário novo (LTV).

Quem percebe um ecossistema de valor prefere pagar mais a se adaptar a um produto
pior e mais barato. Evidência do contrário: ferramentas virais tipo "Roast My
Startup" foram clonadas **em uma semana**. **Clone não copia confiança.**

---

## As 4 falhas que fazem um SaaS vibe-coded parecer fraude

A IA amplifica Dunning-Kruger: você se sente onisciente sem ter base pra julgar se
a saída dela é solução ou tempo perdido. Os quatro pilares onde ela falha:

1. **Armadilha do produto genérico.** A IA foi treinada na média da internet, e
   média não constrói nada extraordinário. A saída da commoditização é ser a
   **única ferramenta possível para um nicho ignorado** — não "CRM para médicos",
   mas "CRM para clínicas de harmonização facial", com campo
   `data_ultima_toxina` e alerta de retoque em 110 dias.
2. **Entrega de valor / TTV.** O default de 99% é login → dashboard vazio.
   Construa a rampa até o valor, não o deserto. Ver `onboarding-ativacao.md`.
3. **Confiança visual.** Num mar de template V0/Tailwind, estética,
   personalidade e consistência são os últimos proxies de confiança que sobraram.
   Pixel intencional sinaliza autoridade e **derruba CAC**.
4. **Toque humano.** Código mais barato deveria comprar mais tempo pros detalhes
   memoráveis: mensagem de erro gentil, 404 que devolve o usuário ao caminho,
   regra de negócio que antecipa o erro dele, micro-interação de 200ms
   confirmando a ação. Gente é previsivelmente irracional.

---

## LPs geradas por IA: as 3 falhas recorrentes

A IA gera landing page em minutos, e ~90% delas compartilham os mesmos defeitos:
1. **estética genérica e inconsistente** (cada componente de uma cor, gradiente
   roxo/verde em fundo escuro/branco);
2. **peso demais em features** em vez do valor/dor que elas endereçam;
3. **quase não mostra o produto de verdade**.

O que perde o visitante é o hero genérico e inconsistente, não a falta de design
sofisticado. Fórmula de hero que passa no teste dos 5 segundos: headline (≤8
palavras, ataca a dor nº1), subheadline (mostra a transformação), CTA primário
(específico ao resultado), CTA secundário (baixo compromisso), barra de confiança
(5 logos ou **um** número específico).

---

## Não monte a fábrica de dívida técnica IA → Figma → código

O fluxo "Claude → Figma → código" parece velocidade e cria **dois documentos que
dessincronizam** mais componentes inconsistentes: padding aleatório de botão, cor
fora da marca, padrão de UX inconsistente. Ajuste manual não volta pro código, a
fonte de verdade regride pro canvas e os arquivos divergem. Pro dev é inútil
(V0/Lovable já cospem código); pro designer é distração que pula a arquitetura de
informação pra cuspir uma tela rápido.

---

## Desenhe para uma atenção que só encolhe

Vídeo curto age no cérebro como caça-níquel de recompensa variável, desliga o
filtro atencional e corrói autocontrole — o usuário chega com ansiedade alta e
foco baixo. (Estudo de EEG de Fabiano et al., *Frontiers in Human Neuroscience*,
liga vício em vídeo curto a menor atividade do lobo frontal.)

Se a atenção do seu usuário encolhe, o design precisa ser militarmente focado:
reduzir carga cognitiva drasticamente, direcionar de forma absoluta para a tarefa
alvo, e respeitar o teto de atenção humana. Números e táticas em
`friccao-atencao-formularios.md`.

> TikTok é o cachorro-quente das redes: hiperpalatável, pobre em nutriente.

Pergunta-guia: *Se um concorrente clonasse seu produto inteiro hoje à noite, o que
exatamente ele **não** conseguiria copiar até sexta?*

Fonte: @richardrx (via revenue-centric-design, heliocosta-dev).
