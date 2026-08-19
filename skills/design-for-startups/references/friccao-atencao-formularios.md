# Fricção, atenção e formulários

> Leia para: formulário/lead form, checkout, quantidade de campos, multi-step,
> "meu form não converte", carga cognitiva, atenção do usuário, aversão a risco,
> garantia, reescrita de modal/tela densa.

Os três maiores inimigos da conversão, provavelmente nesta ordem:
**aversão ao risco → fricção → distração.**

Decorar truque de CRO funciona por um tempo; o que sustenta é entender
**comportamento**, não a lista de táticas.

---

## 1. Aversão ao risco — o medo mora a dois centímetros do botão

Somos criaturas medrosas: medo da perda, do desconhecido, de passar vergonha na
frente do sócio. E é desproporcional — **perder um valor dói mais que o dobro do
prazer de ganhar o mesmo valor** (estimativa clássica de Kahneman). Na tela isso
não aparece como medo. Aparece como **aba fechada**.

Numa demo, o medo tem nome:
- "E se meu mecânico não souber usar?" → **adoção**
- "E se eu perder meus dados na migração?" → **reversibilidade**
- "E se eu ficar preso nisso?" → **saída**

Muito founder acha que resolve com FAQ: inventa meia dúzia de perguntas, joga no
rodapé, e pronto. **O medo não espera chegar no rodapé** — ele aparece num ponto
específico, quase sempre a dois centímetros do botão, e é ali que precisa ser
respondido.

Os três mitigadores clássicos:
- **Garantia.** Ataca a ideia de que o produto é frágil; "satisfação garantida ou
  dinheiro de volta" cobre o medo de não entregar a promessa. **Garantia em página
  separada não conta: se não está ao lado do preço, ela não existe.**
- **Teste grátis.** Útil, mas não elimina o risco: o usuário ainda investe tempo e
  entrega os dados dele — e isso pode ser o medo real. (Grátis tem custo; ver
  `precos-monetizacao.md`.)
- **Familiaridade.** Marca conhecida, cliente conhecido, cara conhecida. Produto
  novo **pega emprestada** a confiança de quem já é conhecido.

Pergunta-guia: *Na sua última call de vendas, qual foi a pergunta que o cliente
fez antes de assinar? Ela deveria estar na tela, e provavelmente não está.*

---

## 2. Fricção — atrito mata conversão, mas nem todo atrito é igual

### Quantidade de campos

Estudo da HubSpot com **mais de 40.000 landing pages**: formulários com **3
campos** passavam de **25% de conversão**, e a taxa tendia a cair conforme campos
eram adicionados. Regra geral: **mais campos = menor conversão.**

Só que o detalhe importa:
- **O tipo de input conta.** Campos de texto costumam gerar menos impacto;
  dropdowns e textareas pesam mais.
- **O tipo de informação conta mais ainda.** Pedir telefone derrubava a conversão
  pra **~13,5%**, contra **~19%** quando não pedia. Qualquer dado que aumente
  percepção de risco ou invasão gera o mesmo efeito. (É a vozinha na cabeça:
  "até CPF vocês vão querer?")

### E o porém: a curva não é uma reta

- **Contra-exemplo real:** num produto DTC, pedir WhatsApp no pré-checkout
  derrubava a conversão imediata — **mas a conta fechava**, porque ~28% de quem
  não concluía era recuperado depois num funil de carrinho abandonado. O campo a
  mais pagou o próprio custo.
- **Unbounce** encontrou algo parecido na base deles: a conversão cai até uns **4
  campos, estabiliza, e volta a subir** — às vezes um formulário de 10 campos
  converte mais que o de 3 (mais campos podem sinalizar seriedade, qualificar
  melhor e mudar quem responde).

**Não otimize pro número de campos. Otimize pro custo total do dado.**

### Esforço percebido ≠ esforço real

O usuário **não conta etapas** — ele **percebe quanto esforço ainda falta** até
chegar onde quer. Por isso:

> 5 etapas com 2 campos por tela pode converter mais que 2 telas com 7 campos
> cada, mesmo tendo mais passos.

E não são só os elementos interativos que entram na conta: tela cheia de texto,
aviso, informação secundária e enfeite visual **também** aumenta carga cognitiva.
Você pode não precisar clicar em nada, mas precisa **ler pra saber se não tem
pegadinha ali** — e isso é atrito.

A pergunta operacional: **quanto esforço eu consigo remover sem destruir o valor
que aquela informação tem pro negócio?**

Às vezes a solução nem está no formulário: está no espaço entre uma coisa e
outra — mais respiro, menos ruído, hierarquia mais clara, uma etapa por vez.

> O objetivo é criar um ambiente que **sinalize por onde ir em vez de explicar**,
> mesmo sem ler. Seu formulário tem que parecer mais um **corredor** que uma sala
> de interrogatório: corredor branco com tapete vermelho no centro.

### Exemplo aplicado: reescrever um modal denso

Caso típico de fricção que não é formulário — um modal de "ir para modo produção"
num gateway de pagamento.

**Antes** (6 parágrafos): explica que existem dois modos, o que é desenvolvimento,
o que é produção, que documentos serão coletados, que faz parte do processo de
segurança e conformidade, o prazo, e que ao clicar você concorda com os termos. O
usuário precisa **ler tudo** pra descobrir se tem pegadinha.

**Depois** (mesma informação, outra arquitetura):
- Título curto: "Modo Produção".
- Uma frase de consequência: a partir daqui, cobranças e pagamentos são reais.
- Um bloco escaneável **"O que acontece ao continuar"** com 3 itens (coletamos
  documentos → validamos a empresa → conta liberada pra vender).
- Uma linha de expectativa em destaque: "leva em média 1 dia útil".
- Dois botões com hierarquia visual clara (Cancelar × Continuar).

O que mudou: mesma informação, **menos leitura obrigatória**, sequência temporal
explícita, expectativa de prazo visível antes do clique e um único caminho
óbvio. É o princípio da carga cognitiva aplicado dentro do produto, não só na LP.

---

## 3. Distração — a atenção que você não controla

**Cuidado com o dado do peixinho dourado.** A frase "a atenção humana caiu de 12
para 8 segundos, menos que um peixe de aquário" é atribuída a um relatório da
Microsoft de 2015. A pesquisa nunca falou em 8 segundos nem em peixe: o número
estava num infográfico creditado a uma tal "Statistic Brain", e quando a BBC foi
puxar o dado, nenhuma das instituições citadas tinha estudo nenhum. A Microsoft
tirou o material do ar e o número colou mesmo assim — cinco anos depois do
desmentido, metade dos adultos britânicos ainda acreditava nele. **Isso é efeito
de verdade ilusória: repetição vira sensação de verdade.** (Não use esse dado.)

**O dado que existe:** Gloria Mark cronometra atenção em tela há ~20 anos. Em
2004, ~2min30 antes de a pessoa trocar de tela; em 2012, ~75 segundos; hoje, ~47
segundos.

Você perde conversão e ativação por coisas que **não controla**: notificação em
outro app, telefone tocando, outra atividade que começou antes — e, pior de todas,
**tédio**. O cérebro da maioria já se adaptou ao feed infinito, que entrega
recompensa variável e vicia igual máquina caça-níquel. Quem vive em multi-screen
perde capacidade de focar em tarefa repetitiva e chata. Tipo… sua landing page. E
seu onboarding.

### Dois princípios pra lidar com isso

**(1) A gente nota o que já está na memória ou que se repete.**
Misturar elementos da realidade do ICP faz o usuário reconhecer aquilo mais rápido
— da palavra ao componente visual (**efeito de mera exposição**). É por isso que
se abre o hero com uma dor recente e memorável, isola e contrasta a opção que se
quer influenciar, e coloca o dado **exatamente onde a objeção acontece**. Como no
click trigger:

> **CTA:** Assinar plano agora
> **Click trigger:** 2 minutos de setup, sem cartão de crédito

O click trigger ali matou a objeção do cartão. (Mais em `conversao-landing.md`.)

**(2) Coisa bizarra, engraçada, visualmente forte ou antropomórfica rouba
atenção** (efeito von Restorff / bizarrice). Na prática, quebre o padrão **dentro
da própria página** pra equilibrar: marca-texto em algumas palavras, post-it,
objeto real onde ninguém espera, quebra de seção com a cor oposta da anterior,
personagem baseado em coisa inanimada (um balde furado, uma fita adesiva, um
cérebro). Gera contraste na interface e memória de longo prazo por diferenciação.

O objetivo é **conduzir a leitura inteira sem deixar o usuário solto em momento
nenhum — mantendo a sensação de que quem manda é ele.**

Pergunta-guia: *Em 47 segundos de atenção, qual é a única coisa que o usuário
precisa entender e lembrar da sua página?*

Fonte: @richardrx.
