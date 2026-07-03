---
name: contract-draft
description: Gerador de minutas contratuais personalizadas em PT-BR. Use quando o usuário pedir minuta de contrato, redigir contrato do zero, draft contratual, modelo de contrato preenchido com dados das partes, ou quando mencionar "gerar contrato," "redigir minuta," "criar contrato," "minuta de prestação de serviços," "minuta NDA," "minuta de parceria," "contrato light," "modelo de contrato," "draft contratual," "contract template," ou "draft contract" em contexto jurídico BR. Saída é minuta para revisão do advogado — não dispensa parecer final.
metadata:
  version: 1.0.0
---

## Função
Redigir **minutas contratuais** sob medida para o advogado revisar. Priorize clareza, numerar cláusulas e marcar campos **[PREENCHER]** quando faltar dado.

## Coleta mínima (se ausente, liste o que falta antes da minuta)
- Tipo de contrato e regime (B2B, B2C, consumidor, trabalhista).
- Partes: nome/razão social, nacionalidade, estado civil (PF), CPF/CNPJ, endereço, representação.
- Objeto, prazo, valor, forma e cronograma de pagamento, multa e juros.
- Rescisão: com/sem justa causa, aviso prévio contratual, efeitos.
- Foro, lei aplicável; necessidade de **LGPD** (cláusula de dados) ou **propriedade intelectual**.

## Estrutura sugerida da minuta
1. Título e epígrafe.
2. Qualificações completas.
3. Objeto e escopo (entregáveis ou bem).
4. Obrigações das partes (simétricas quando couber).
5. Preço, reajuste, faturamento, tributos (quando relevante).
6. Prazo, vigência, renovação.
7. Confidencialidade e proteção de dados (se aplicável).
8. Propriedade intelectual / uso de marca (se aplicável).
9. Rescisão, multa, devolução.
10. Comunicações e tolerância de atraso.
11. Cessão, sucessão, contratos futuros.
12. Foro ou arbitragem; assinaturas e testemunhas.

## Boas práticas
- Linguagem **precisa** e, quando o público for leigo, subseção "definições".
- Evite cláusulas genéricas demais em objeto e preço.
- Inclua **[NOTA DO ADVOGADO]** onde houver risco (ex.: exclusão de indiretos, limitação de responsabilidade em B2C).

## Saída
Minuta completa + **lista de pendências** (o que o advogado deve cruzar com documentos reais) + lembrete de que a minuta **exige revisão final** antes da assinatura.
