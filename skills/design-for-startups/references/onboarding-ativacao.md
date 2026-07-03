# Onboarding & Ativação

> Leia para: onboarding, ativação, first-run experience, TTV, empty states,
> "usuário cadastra e some", primeiros usuários.

## O momento onde a maioria perde o trial

Usuário cria conta, faz login e cai num **dashboard vazio**. Nenhum dado,
nenhuma orientação, só uma tela esperando que ele descubra (magicamente) o que
fazer. Ele fecha a aba e pensa "volto depois" — e nunca mais volta. Esse momento
é o pico de curiosidade do usuário (acabou de decidir testar, está disposto a
investir tempo) e você entrega uma tela em branco.

> **Trial é teste de valor. Se ele não provou, não converte.** O trial mais
> longo do mundo não salva onboarding ruim — conversão de trial quase nunca é
> problema de pricing, é problema de jornada.

As 3 razões de o usuário sumir e a correção:
1. **Caiu num dashboard vazio** → o primeiro passo tem que ser óbvio e imediato.
   Esqueça "explore nosso produto"; conduza ao valor (ou a uma micro-vitória).
2. **Se perdeu antes do valor** → instale Clarity/PostHog, observe onde ele
   travou, otimize tudo pra facilitar esse clique.
3. **Se perdeu na vida** (gostou, mas a vida aconteceu) → email que mostra o
   **progresso dele**, não "seu trial está acabando".

---

## Onboarding ativo vs passivo

- **Passivo** — tooltips, tour guiado, documentação; o usuário aprende **se
  quiser**. Pressupõe que ele vai explorar. Ele não vai: tem 47 abas abertas e o
  WhatsApp apitando, sua ferramenta é só mais uma. Ele faz o mínimo pra decidir
  se vale voltar.
- **Ativo** — você desenha uma **sequência de ações** onde cada ação entrega
  valor e cada valor gera a próxima ação. Pressupõe que **você sabe melhor que
  ele qual é o caminho mais curto pro valor** — então desenha esse caminho,
  remove a fricção e garante que ele chegue lá.

**Slack** te coloca num canal e te faz mandar mensagem: você não leu tutorial,
você **usou** o produto. Entender fazendo > entender lendo. Se seu onboarding
começa com "bem-vindo, aqui está a documentação", você está perdendo usuários
que poderiam ficar.

> Não pergunte "qual é o mínimo que o usuário precisa fazer" — pergunte "qual é a
> **menor ação que entrega o maior valor no menor tempo**".

### Onboarding que entrega valor vs. que ensina mecânica

- Mecânica (chato): "1. Crie seu primeiro projeto 2. Adicione um membro 3.
  Configure integrações."
- Valor (converte): "1. Em 2 min você vai ver seu primeiro relatório 2. Vamos
  começar com os dados que você já tem 3. Pronto — esse é o insight que seus
  concorrentes pagam consultoria pra ter."

---

## Empty state — o que fazer com a tela em branco

Dashboard vazio **parece** neutro/bom, mas gera confusão: o usuário para e
pensa. Cada segundo decidindo o que fazer é um segundo mais perto de desistir.
Quatro correções:

1. **Estado vazio com dica da próxima ação** — o CTA já direciona pra onde ele
   recebe valor (ou pro que ele precisa pra chegar lá).
2. **Estado inicial com dados de exemplo** — mostra o dashboard "funcionando";
   ele vê o destino antes de começar, o que reduz incerteza.
3. **Uma única ação clara** — "Importe sua primeira planilha" / "Conecte sua
   conta" / "Crie seu primeiro projeto". Uma, não oito, não um tour de 12 passos.
4. **Progresso visível desde o primeiro clique** — barra que começa em 20%, não
   em 0%, pra ele sentir que **já começou** (efeito progresso + Zeigarnik).

---

## Atrito: no lugar certo qualifica e retém; no lugar errado mata

Heurística contraintuitiva: **founder técnico passa a vida reduzindo atrito como
se fosse universal.** Em geral, certo. Mas em 3 etapas, atrito **na medida**
aumenta conversão e LTV ao mesmo tempo. O mecanismo é **justificação de esforço**
(Aronson & Mills, 1959; primo do efeito IKEA e do efeito dotação): quando o
usuário investe esforço pra obter algo, atribui mais valor a esse algo.

1. **Trial com cartão** — opt-in (sem cartão) converte ~8,9%; com cartão ~31,4%.
   O cartão filtra intenção comercial. Ver `precos-monetizacao.md`.
2. **Onboarding obrigatório antes do dashboard** — Superhuman exige call de 30
   min; Notion empurra template inicial; Linear força nome do time e primeira
   issue. Quem completa vira power user mais rápido.
3. **Formulário de demo enterprise (6-8 campos)** — cargo, tamanho do time,
   ferramenta atual, orçamento, prazo. Volume de lead cai, mas taxa de fechamento
   sobe; o SDR para de gastar horas qualificando lead que nunca compraria.

> Atrito no **signup do trial** mata aquisição. Atrito no **onboarding do
> produto** PODE criar ativação. Atrito na **demo enterprise** qualifica o
> pipeline. Mesma ferramenta, lugares diferentes, resultados opostos.

Pergunta-guia: *Quanto esforço de qualificação seu vendedor humano está fazendo
que o produto deveria fazer antes dele entrar em cena?*

---

## Atrito declarativo vs. administrativo

Caso: plataforma de pagamentos brasileira reduziu o tempo de cadastro até a
primeira venda de **24,2 → 2,5 dias**. A intervenção **não foi cortar etapas —
foi adicionar uma**: o usuário precisa responder o que vende e qual o objetivo de
longo prazo (≈30 s, posicionado entre cadastro e produto).

Dois andares de efeito:
- **Operacional** — a jornada seguinte fica específica (quem vende infoproduto vê
  um caminho; quem vende físico, outro).
- **O que importa** — o usuário fez um **micro-compromisso** com o resultado que
  quer, antes de tocar no produto. Não está mais explorando; está executando um
  plano que ele mesmo descreveu.

Existem dois tipos de fricção no onboarding:
- **Administrativa** — coleta dado que o sistema usa depois; atrasa e não compra
  nada pro usuário → **candidata a corte**.
- **Declarativa** — obriga o usuário a se posicionar sobre o que veio fazer;
  atrasa um bocadinho e compra compromisso, customização e direcionamento →
  **candidata a expandir**.

Pergunta-guia: *Cada etapa do seu onboarding está coletando dado ou fazendo o
usuário declarar intenção?*

---

## Efeito Zeigarnik & email de progresso

Tarefas iniciadas e não concluídas geram tensão mental até fecharem. Quando o
produto abre um **loop** (complete seu perfil, convide 3 colegas, envie sua
primeira mensagem), o usuário carrega a pendência. Mas o loop precisa ser
**pequeno o suficiente pra parecer fechável** — onboarding de 14 passos faz ele
fechar a aba no passo 5 se não houver pequenas vitórias percebidas.

Resignifique o esforço já investido: "Você já fez a parte difícil (criou a
conta, pagou), só faltam 3 passos." E o email de retenção mostra acúmulo: "Você
criou 3 relatórios, seu time acessou 12 vezes, você está no top 20% dos
usuários."

---

## Onboarding como alavanca de receita (a conta)

Caso: SaaS B2B, 900 usuários, ARPU R$300, churn 6% (= 54 contas/mês = R$16.200
saindo/mês). Reestruturar onboarding (welcome contextual + empty state + checklist
de ativação) reduziu o churn em ~30% → **16 cancelamentos a menos/mês**. Com LTV
de 11 meses: **~R$52.800 recuperados** numa base que já existia — sem tráfego
novo, sem feature nova. Churn menor também melhora valuation e faz cada real de
aquisição render mais.

---

## Os primeiros 10 usuários definem a curva inteira

- **Cobre desde o início.** Pagamento é o teste mais barato de dor real;
  curiosidade é gratuita, bolso aberto exige problema concreto. O atrito de
  pagamento é parte do teste.
- Saem de comunidade fechada, alcance pessoal ou guerrilha pura.
- **Caso RepareCar:** as primeiras 25 oficinas testaram o produto ainda em
  protótipo; visitava-se cada uma e no fim **cobrava-se**. Quando o dono dizia
  que não podia pagar, a pergunta era: *"O que o sistema precisa fazer pra você
  pagar agora?"* Se ele sacava o telefone pra pagar, avisava-se que ainda não era
  necessário (entrava numa lista de espera). Só se desenhou algo visual depois de
  **20 oficinas pagantes**.
- B2C app muda o método, o princípio se mantém. Pré-venda com a solução em
  progresso resolve a maioria dos cenários.

---

## Vídeo de onboarding dá boas-vindas, não ensina

**Um bom vídeo de onboarding não é manual.** Ninguém lê o manual do carro, ninguém
lê o do iPhone, e ninguém vai assistir um vídeo de 12 minutos ensinando cada botão
do seu produto. O trabalho do vídeo é outro: dar boas-vindas, criar conexão,
mostrar o produto num relance e apontar onde o valor aparece mais rápido.

**Como aplicar:** mire em cortar TTV, reduzir tickets de suporte e matar a sensação
de "e agora?", não em educar. A duração segue a urgência do seu ICP: alguém com
pressa pra resolver um problema tolera muito menos vídeo do que alguém feliz
montando um Lego. E não precisa de ator nem set chique: o Richard gravou o dele no
Screen Studio e superou o de muito produto grande.

Imagine a tela: um modal de boas-vindas escrito "Sua conta foi criada!", com o
thumbnail de um vídeo de introdução embutido no meio, e um único CTA "Próximo"
embaixo. Boas-vindas, um relance do produto, um caminho pra frente. Só isso.

Seu produto também não precisa de manual: você já leu o do seu carro?

Pergunta-guia: *Seu vídeo de onboarding está tentando ensinar o produto ou está
levando o usuário até o valor mais rápido?*

Fonte: @richardrx.

---

## MRR subindo com churn subindo: você perdeu ele no dia um

**Quando MRR e churn sobem juntos, o usuário não foi embora no mês 2, ele foi
perdido no primeiro dia.** Você o jogou num dashboard vazio e ele morreu ali, sem
nada guiando até o valor. Ele até levou dois meses pra clicar em cancelar, mas a
decisão já estava tomada no primeiro dia depois do cadastro.

**Como aplicar:** o problema não é falta de feature. Meça o **TTV (time to value)**
e fique obcecado em encurtar. E entenda a categoria certa das métricas: **CAC, LTV
e ativação são métricas de PRODUTO, não de marketing.** Com retenção fraca,
adquirir mais só enche o balde furado mais rápido, você paga CAC pra derramar
usuário pelo mesmo furo do dia um.

Pergunta-guia: *Seu churn é problema do mês 2 ou é a fatura de um primeiro dia que
você nunca desenhou?*

Fonte: @richardrx.

---

## Churn e payback são um problema só, medido em dois lugares

**Churn e payback parecem dois problemas (às vezes até com donos diferentes), mas
são o mesmo.** Os dois são decididos na primeira sessão do usuário, no vão entre
ele entrar e sentir que o produto funciona. Consertar churn na tela de
cancelamento e caçar CAC mais barato no gerenciador de anúncios ao mesmo tempo é
mirar nos dois lugares errados: a decisão foi tomada antes de qualquer um deles.

**Como aplicar:** ativação conserta os dois de uma vez. Encurte o TTV e você
retém mais **e** leva cada cliente pra além da linha de payback antes de ele
sumir. Um cliente que morre no mês 2 com payback de 4 meses nunca chega a fechar a
conta, ele já era prejuízo antes de você perceber. Ressalva honesta: nem todo
churn é ativação (preço errado e canal ruim existem). Mas antes de sair caçando
CAC mais barato, conte quantos clientes morrem antes de pagar o que custaram.

Pergunta-guia: *Quantos dos seus clientes morrem antes de repagar o próprio CAC? Se
não sabe, você está tratando churn e payback como dois problemas que na verdade são
um.*

Fonte: @richardrx.
