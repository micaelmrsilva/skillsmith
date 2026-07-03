# O método de otimização de onboarding (o loop)

> Fonte direta: o funil "Como vencer: 'Não sabemos como otimizar nosso
> onboarding'". É o coração operacional desta skill.

A maior trava do founder não é falta de talento de design — é não saber por onde
começar. "Ah, eu não sei como melhorar meu onboarding" é a frase mais repetida.
A resposta: dá pra fazer **sem Figma e sem IA da modinha**. É um loop barato e
manual.

## Os 5 passos

1. **Tire capturas de tela de cada etapa.** Coloque tudo num Miro ou FigJam.
   Objetivo: ver a jornada real como uma sequência visível, fora do código, onde
   dá pra raciocinar sobre ela como um todo. Você vive a jornada do *criador*;
   precisa forçar a si mesmo a ver a do recém-chegado.

2. **Defina a vitória final.** O que faz o produto "clicar" para o usuário e faz
   com que ele *queira ficar*. Esse é o destino de toda a jornada. Atenção: a
   vitória final **não é o que você acha que deveria ser** — é o ponto onde o
   valor é de fato capturado pelo usuário. Descubra por dado (ver
   `metricas-e-aha.md`), não por opinião.

3. **Analise as etapas atuais.** Para cada etapa pergunte: *essa etapa está
   ajudando o usuário a alcançar a vitória final?* Se a resposta é "ela coleta um
   dado que eu uso depois", desconfie — pode ser fricção administrativa pura.

4. **Comece a otimizar.** Três movimentos possíveis por etapa: **remova**, **adie**
   ou **adicione**. O objetivo é que cada etapa aproxime o usuário da vitória
   final mais rápido. Adicionar é contraintuitivo mas válido — ver critério
   abaixo.

5. **Prototipe, teste com usuários e rode de novo.** Ferramentas como Figma,
   Replit ou Cursor servem pra construir e testar o protótipo com usuários
   reais. É um **loop contínuo**, não um projeto com fim.

## A versão sem-Figma (founder pode fazer hoje)

1. Tirar prints de todo o processo.
2. Definir quais são as **pequenas vitórias que grudam** ao longo do caminho.
3. Analisar cada passo procurando barreiras e fricções.
4. Começar a otimizar (remover/adiar/adicionar).
5. Prototipar, testar e rodar de novo.

Não precisa de tooling sofisticado. Precisa de disciplina de olhar a sequência
real e de testar com gente que nunca viu o produto.

## Critério de corte vs expansão de etapa (a regra de ouro)

Toda etapa de onboarding faz uma de duas coisas. Saber qual decide se você corta
ou expande:

- **Fricção administrativa** → coleta dado que o sistema vai usar depois. Atrasa
  o usuário e **não compra nada pra ele**. É **candidata a corte / adiamento**
  (peça o dado mais tarde, quando ele já viu valor).

- **Fricção declarativa** → obriga o usuário a se posicionar sobre o que ele veio
  fazer. Atrasa um bocadinho, mas **compra compromisso, customização e
  direcionamento de jornada**. É **candidata a expansão**.

Pergunta operacional para cada etapa: *está coletando dado ou fazendo o usuário
declarar intenção?* Se está só coletando dado, corte. Se está fazendo declarar
intenção, considere expandir. (Case completo: plataforma de pagamentos que
**adicionou** uma etapa declarativa e caiu de 24 para 2.5 dias até a 1ª venda —
em `cases-e-ia.md`.)

## Onboarding ativo vs passivo (a escolha estrutural)

A forma do onboarding importa mais que a quantidade de passos.

**Onboarding passivo** — você cria tooltips, tour guiado, documentação. O usuário
aprende *se quiser*. O problema: ele assume que o usuário vai explorar. **Ele não
vai.** Está ocupado tentando entender o que está acontecendo, com 47 abas
abertas. Vai fazer o mínimo pra decidir se volta — e se não viu valor, não volta.

**Onboarding ativo** — você desenha uma sequência de ações que o usuário
completa. Cada ação entrega valor; cada valor gera a próxima ação. Você assume
que **sabe melhor que ele qual é o caminho mais curto pro valor**, desenha esse
caminho, remove fricção e garante que ele chegue lá.

O princípio do Slack: a primeira coisa é te colocar num canal e te fazer mandar
uma mensagem. Não te mandam ler tutorial — você já *usou* o produto, e ao usar,
entendeu. **Entender fazendo é mais poderoso que entender lendo.**

A pergunta que troca o frame: não é "qual é o **mínimo** que o usuário precisa
fazer", é **"qual é a menor ação que entrega o maior valor no menor tempo"**.

## Ensinar mecânica vs entregar resultado

Ninguém quer aprender a usar o produto. O usuário quer o resultado prometido na
hero da landing page.

```
Onboarding de dev (ensina mecânica):
  1. Clique aqui para criar seu primeiro projeto
  2. Agora adicione um membro ao time
  3. Configure suas integrações
  → Boooring.

Onboarding que converte (entrega valor antes de pedir esforço):
  1. Em 2 minutos você vai ver seu primeiro relatório
  2. Vamos começar com os dados que você já tem
  3. Pronto. Esse é o insight que seus concorrentes pagam consultoria pra ter.
```

O primeiro ensina mecânica. O segundo entrega valor antes de pedir esforço. A
diferença entre 5% e 15% de conversão de trial está aí — não em features, não em
preço. Está na sequência de micro-decisões que você desenhou sem perceber que
estava desenhando.
