# Churn de promessa, linguagem e suporte como design

Nem todo churn é problema de onboarding ou de feature. Antes de mexer no produto
pra segurar quem sai, cheque se o gatilho não está **antes** — na expectativa que
a venda criou, ou na linguagem que o produto usa.

## Churn de promessa quebrada (a dívida de expectativa)

Tem produto que converte muito bem e mesmo assim não cresce: entra gente pela
frente e some pela porta dos fundos na mesma velocidade. O instinto é mexer no
produto pra segurar quem sai — mas o gatilho do churn pode estar na **promessa**.

A página ou o vendedor prometeu uma coisa que o produto não entrega no primeiro
uso. O usuário chega esperando o que foi vendido, encontra outra coisa — e **não
importa se a outra coisa é até boa, não era o combinado.**

- **Conversão alta vira armadilha:** dá a sensação de que a aquisição funciona e
  esconde que cada cliente novo já entra com um pé na saída. (Caso real: produtos
  com >50% de churn no mês.)
- **O padrão "marketing bate meta, produto apaga incêndio":** comum em gente de
  marketing digital criando SaaS. Os dois times não conectam as duas coisas.
  Converter bem e reter mal = você é "melhor de palco do que de cozinha".
- **Coerência mensagem-canal-segmento é problema de design.** No estágio de
  Tração o valor é captado por estranhos que chegaram frios por um canal com uma
  expectativa criada no criativo. A LP e o onboarding têm que **bater com a
  expectativa que os anúncios criaram lá na ponta**, fechando o loop.

## Churn de não-qualificação (resolve antes, na página)

Existe o churn de quem **nunca teve o problema** que você resolve e descobriu
isso usando. Esse não é problema de produto nem de onboarding — é **qualificação**,
e se resolve antes, na própria página. Pode até parecer lucro, mas se gera
impacto no suporte e na marca, a conta chega depois.

## Churn de linguagem (maldição do conhecimento)

Às vezes o churn que parece falta de feature ou onboarding é **desalinhamento
entre discurso e entendimento**. O founder técnico escreve o produto e a página
usando jargão sem perceber. O ICP não entende a solução, mas alguns compram no
salto de fé. Dentro do produto, mais jargão — o usuário não percebe valor,
acumula pequenas decepções e cancela.

Dois vieses em jogo:

- **Maldição do conhecimento:** você sabe demais e esquece que o outro não sabe.
- **Viés da fala fácil:** linguagem simples passa mais confiança e eleva o nível
  de consciência do problema.

### O experimento dos batedores (por que isso acontece)

Grupo A bate o ritmo de uma música conhecida na mesa; grupo B só ouve as batidas
e tenta adivinhar. Resultado: acertaram **3 em 120 (2,5%)**. Quem bate escuta a
música inteira na cabeça — vocal, instrumento, tudo — enquanto quem ouve recebe
só "toc toc toc". O batedor não consegue desligar a música e acaba achando o
outro meio burro por não sacar algo "óbvio".

É exatamente o que acontece com seu produto: na sua cabeça não precisa de
onboarding porque "o produto é simples" — você está com a música toda tocando.
O usuário só tem o "toc toc toc". **Aquela dúvida que seu suporte responde toda
semana e você jura que está escrita na tela é óbvia só pra você** — que talvez
tenha literalmente escrito o texto.

**A má notícia:** não dá pra desligar a música. O que você sabe já alterou
permanentemente sua percepção. A única saída é **colher feedback de quem nunca
viu o produto**, sem direcionar, sem dar nome às coisas, observando comportamento.

### Como colher feedback de forma contínua (prática do RepareCar)

- **SAC/CX como coletor de insights:** cada problema vai pra uma tabela e é
  analisado por % de ocorrência, impacto no produto e insight.
- **Clarity/PostHog:** mapa de calor, gravação de sessão, fluxo de navegação
  "por cima".
- **Entrevistas** por amostras e grupos específicos.
- **Benchmarking:** como outros produtos endereçam o mesmo problema.

Regra: se o churn está alto e você já revisou onboarding e produto, **revise a
linguagem e a estrutura antes** de construir mais coisa.

## Suporte como problema de design

O que parece problema de suporte geralmente é problema de design. Você **reduz
volume de suporte dentro do próprio onboarding**: FAQ contextual dentro do
produto, interface que responde a dúvida antes de ela ser feita.

- **Case McAfee:** redução de **90%** do volume de suporte só implementando FAQ —
  na época sem chatbot, texto puro.
- Automatizar suporte (bot) resolve o **sintoma**; redesenhar a jornada resolve a
  **causa** — e pode impactar o churn. O ideal é o segundo; quem faz o segundo
  primeiro às vezes nem precisa do primeiro.

### Low ticket gera até 3x mais suporte que ticket convencional

Por três razões:

1. **Perfil de comprador diferente** — quem paga R$49 tem menos paciência pra
   resolver sozinho, menor familiaridade com produto digital e mais expectativa
   de atendimento humano que quem paga R$499.
2. **Compra impulsiva** — ticket baixo = fricção baixa = compra por impulso. O
   usuário entra sem entender o que comprou; primeira reação: buscar suporte.
3. **Custo de oportunidade invertido** — pro cliente de ticket alto, o tempo dele
   vale mais que esperar suporte, então resolve sozinho. Pro de ticket baixo,
   pedir suporte é mais fácil que procurar a resposta.

Implicação de design: em produto low ticket, FAQ contextual e auto-serviço no
onboarding não são luxo — são o que mantém a operação de pé.

## Cuidado financeiro do low ticket no suporte

O bot de suporte que só oferece opções pra selecionar (e não deixa o usuário
digitar o problema) é um anti-padrão clássico de abandono: o usuário frustrado
seleciona uma opção, duas, não fala com ninguém e vai embora — às vezes pra nunca
mais voltar, demorando 2 meses pra efetivar o cancelamento que já decidiu no
primeiro dia.

## Churn e payback são um problema só, medido em dois lugares

**Churn e payback parecem dois problemas (às vezes até com donos diferentes), mas
são o mesmo problema, decidido na primeira sessão do usuário.** A decisão mora no
vão entre o usuário entrar e sentir que o produto funciona. Um cliente que morre
antes de pagar o próprio CAC é uma conta que você pagou e nunca recebeu.

O mecanismo: consertar churn na tela de cancelamento e caçar CAC mais barato no
gerenciador de anúncios são, os dois, o lugar errado. A decisão já tinha sido
tomada antes, na primeira sessão. Por isso ativação conserta os dois de uma vez:
encurte o TTV e você retém mais E leva cada cliente pra além da linha de payback
antes de ele sumir. Um cliente que morre no mês 2 com payback de 4 meses nunca
fecha a conta, ele evapora enquanto ainda estava te devendo o custo de aquisição.

Como aplicar: pare de tratar o problema em dois times separados olhando duas telas
separadas, e ataque a primeira sessão. Ressalva honesta: nem todo churn é
ativação (preço errado e canal ruim existem de verdade). Mas antes de sair caçando
CAC mais barato, conte quantos clientes morrem antes de pagar o que custaram, esse
número costuma reordenar as prioridades.

Pergunta-guia: *dos clientes que cancelaram, quantos saíram antes de cruzar a
linha de payback?*

Fonte: @richardrx.

## Custo de troca é o que vira meses de LTV em anos

**O mesmo produto, desenhado diferente, rende meses vs anos de LTV, e a diferença
é o custo de troca.** Custo de troca é o esforço que o usuário PERCEBE em sair;
custo baixo significa histórico raso e saída fácil. Ele não aparece sozinho, você
engenheira de propósito, como um "juro composto" que aumenta o valor do produto ao
longo do tempo.

O mecanismo: custo de troca alto trava a saída pelos mesmos gatilhos que seguram um
investidor numa ação caindo (custo afundado, aversão à perda do que já acumulou).
São cinco alavancas pra construir:

- **Memória muscular:** atalhos aprendidos que doem pra reaprender (Superhuman,
  Photoshop).
- **Modelo mental:** a cabeça do usuário se molda ao seu jeito de organizar (a
  fricção de trocar Mac por Windows, os labels do Gmail).
- **Personalização acumulada:** o que o usuário construiu e não quer refazer
  (playlists do Spotify, o layout da home montado do jeito dele).
- **Efeito cofre:** dados guardados que ele não quer perder (iCloud, Drive, anos
  de conversa no WhatsApp).
- **Piloto automático / hábito:** o uso vira reflexo via loops de recompensa
  variável, e reflexo não se troca por decisão.

Como aplicar: o custo afundado segura na hora, mas o hábito é o ativo mais fundo, e
pode levar meses pra instalar. É exatamente essa instalação lenta do hábito que é a
diferença entre um LTV de meses e um LTV de anos.

Pergunta-guia: *se seu usuário quisesse sair amanhã, o que ele perderia, e você
projetou isso de propósito ou deixou o acaso decidir?*

Fonte: @richardrx.
