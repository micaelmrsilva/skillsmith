# Métricas certas vs vaidade + descoberta do aha moment

O founder técnico tende a medir a coisa errada na hora de avaliar onboarding. A
regra: **cada métrica de vaidade tem uma métrica real correspondente.**

## As três trocas (vaidade → real)

1. **Mede signups → deveria medir activation rate.**
   Signup é a porta; ativação é o usuário sentar na cadeira e usar o produto pra
   valer. Cadastro é o custo mais barato que o usuário paga — um email, às vezes
   nem isso com login social. Mede curiosidade. Dá pra inflar a curva com mídia a
   semana inteira enquanto a retenção real fica parada. A curva de cadastro sobe
   com tráfego pago; **uso e ativação só sobem com produto bom**.

2. **Mede session time → deveria medir tempo até a primeira ação útil (e a
   repetição dela).**
   Tempo no produto inclui usuário *perdido* procurando o que fazer. Tempo até a
   primeira ação útil mede se o produto entrega valor rápido.

3. **Mede onboarding completion → deveria medir D7 retention.**
   Completar 8 passos de tour não significa que o usuário entendeu valor —
   significa que ele foi *obediente*. D7 retention diz se ele voltou.

## Benchmarks de referência

- **TTV médio:** 1 dia, 12h, 23min (Userpilot, 547 empresas). Top performers:
  **< 5 minutos**.
- **Activation rate:** média SaaS 30–37%; top quartile bate 40%; **abaixo de 20%
  = problema estrutural sério** no onboarding e/ou produto.
- **D7 retention:** média SaaS 10–15%; **acima de 30% é forte**.
- **Abandono:** ~90% dos usuários abandonam na 1ª semana se não chegarem a valor
  claro.

Números são referência, não meta absoluta. O verdadeiro sinal de evolução é
ativação e retenção se sustentando à medida que você abre canais, e usuários
trazendo usuários.

## Por que cadastro engana

Cadastro importa como **topo de funil** — tem valor. O problema é *parar a leitura
nele*. Quando você comemora cadastro, comemora gente decidindo te dar uma chance;
a maior parte some antes de virar uso, antes de pagar. O que importa: quantos
voltam no D2, no D7, quantos fazem a ação que entrega valor de verdade.

Em modelo freemium isso é ainda mais traiçoeiro: cadastro mede curiosidade, e dá
pra inflar a curva com mídia e *sentir* que está crescendo enquanto a retenção
real fica parada no mesmo lugar.

## value realization > feature adoption

A maioria dos SaaS mede se a feature foi *clicada*. Deveria medir se o usuário
**realizou o valor** — chegou ao resultado que a feature promete. Clique é
atividade; valor realizado é o que retém. (Recebeu valor? Contabiliza em TTV.)

---

## O aha moment

O **aha moment** é o exato instante em que o usuário sente que o produto resolve
algo que ele tinha. Antes desse instante, ele está só explorando. Depois, começa
a integrar o produto na rotina.

Cuidado com a nuance: **valor não é o aha moment em si** — é o *ponto onde o valor
é capturado*, e o aha é o momento emocional associado a essa captura. O design no
onboarding existe pra encurtar a distância até esse ponto.

### Como descobrir o SEU aha moment (por dado, não por opinião)

1. Pegue seus clientes **pagantes**.
2. Olhe **o que todos eles fizeram na primeira semana** que os usuários que
   **cancelaram não fizeram**.
3. Essa ação é, provavelmente, seu aha moment. **Não é o que você acha que
   deveria ser.**

Para a maioria dos SaaS, envolve fazer algo **com um colaborador**: convite,
compartilhamento, comentário. Uma rede leve já cria efeito de retenção (e vira
custo de troca).

### A pergunta que diagnostica tudo

> Quanto tempo seu usuário leva entre o signup e o aha moment?
> Se você não consegue responder, você não está medindo o que importa.

Use isso como fechamento padrão de qualquer diagnóstico de onboarding.

---

## MRR subindo com churn subindo: você perdeu ele no dia um

**Quando MRR e churn sobem juntos, o usuário não foi embora no mês 2, ele foi
perdido no primeiro dia.** Levou dois meses pra cancelar, mas você perdeu ele no
primeiro dia depois do cadastro: jogado num dashboard vazio e morto sem nada
guiando até o valor.

O mecanismo: o cancelamento é só o registro tardio de uma decisão que já tinha
sido tomada. O usuário que não chega ao valor na primeira sessão fica ali por
inércia, sem usar, e um dia formaliza a saída. A curva de churn no mês 2 está
descrevendo o que aconteceu (ou não aconteceu) no dia 1.

Como aplicar: o instinto de "falta feature" é quase sempre falso. Meça o TTV (time
to value) e fique obcecado em encurtar, é ele que decide se o usuário forma hábito
antes de a inércia acabar. E trate CAC, LTV e ativação como métricas de PRODUTO,
não de marketing: com retenção fraca, adquirir mais só enche o balde furado mais
rápido, e o MRR crescente vira uma ilusão que esconde a hemorragia.

Pergunta-guia: *se seu MRR e seu churn estão subindo ao mesmo tempo, o que está
acontecendo na primeira sessão do usuário que ninguém está olhando?*

Fonte: @richardrx.
