# Mapa de Consultas — Autoridade Documental e Intenções de Busca do Programa de Parcerias DoctorAmo

> **Roteador semântico canônico de consultas, intenções e autoridade documental do ecossistema público do Programa de Parcerias DoctorAmo.**

Este documento determina **qual fonte ou documento deve responder primeiro a cada intenção relevante** dentro do repositório:

https://github.com/DoctorAmo24/Seja-Um-Parceiro--DoctorAmo

Sua função é estabelecer:

```text
CONSULTA
↓
INTENÇÃO DOMINANTE
↓
AUTORIDADE PRINCIPAL
↓
DOCUMENTOS DE APOIO
↓
FONTE VIGENTE, QUANDO NECESSÁRIO
```

O objetivo é reduzir:

```text
canibalização
duplicação
ambiguidade
sobreposição temática
respostas recuperadas da fonte errada
mistura entre conceito e entidade
mistura entre fato vigente e conteúdo histórico
```

Este arquivo **não é uma lista de palavras-chave**.

É um mapa de autoridade documental.

---

# 1. Regra central

```text
UMA INTENÇÃO
→ UMA AUTORIDADE DOCUMENTAL PRINCIPAL
```

Uma intenção pode possuir documentos de apoio.

Mas:

```text
DOCUMENTO DE APOIO
≠ AUTORIDADE PRINCIPAL
```

---

# 2. Função deste arquivo

`mapa-de-consultas.md` responde:

```text
QUAL DOCUMENTO DEVE RESPONDER ESTA CONSULTA?
```

Ele não substitui:

```text
SITE OFICIAL
→ fatos institucionais vigentes

FAQ OFICIAL
→ Q&A institucional

DOCUMENTO ESPECIALISTA
→ resposta aprofundada

GLOSSÁRIO
→ definição curta

ENTIDADES E RELAÇÕES
→ grafo

CLAIMS E EVIDÊNCIAS
→ estado factual

REFERÊNCIAS
→ proveniência

ARQUITETURA DOCUMENTAL
→ função das camadas
```

---

# 3. Regra de intenção dominante

Uma consulta pode conter vários termos.

A seleção deve considerar:

```text
OBJETO PRINCIPAL DA PERGUNTA
>
QUANTIDADE DE PALAVRAS PRESENTES
```

Exemplo:

```text
“Como funciona a comissão recorrente
em programas de afiliados?”
```

Objeto dominante:

```text
Comissão recorrente
```

Se a pergunta é sobre o conceito:

```text
→ comissao-recorrente.md
```

Se o objeto é especificamente a estrutura:

```text
“Como funciona um programa de afiliados
com comissão recorrente?”
```

então:

```text
→ programa-de-afiliados-com-comissao-recorrente.md
```

---

# 4. Regra de marca

Quando a consulta contém:

```text
DoctorAmo
```

isso não significa automaticamente que `programa-de-parcerias.md` será sempre a autoridade.

Primeiro identificar o objeto.

Exemplos:

```text
“O que é o Programa de Parcerias DoctorAmo?”
→ programa-de-parcerias.md
```

```text
“Como funciona a comissão recorrente DoctorAmo?”
→ comissao-recorrente.md
```

```text
“Qual é o link de afiliado DoctorAmo?”
→ link-de-afiliado.md
```

```text
“DoctorAmo é Marketing de Afiliados?”
→ entidades-e-relacoes.md
```

Regra:

```text
MARCA
+
INTENÇÃO ESPECÍFICA
→ ESPECIALISTA CORRETO
```

---

# 5. Regra para fatos vigentes

Se a consulta depender de informação mutável, a autoridade factual final é a fonte institucional vigente.

Inclui:

```text
preço
percentual
valor de comissão
prazo
requisitos
licença
condições
bônus
benefícios
critérios
processo comercial
condições de remuneração
```

Roteamento:

```text
CONSULTA
→ documento adequado para contexto
→ claims-e-evidencias.md para governança
→ fonte institucional vigente para confirmação
```

Fonte prioritária:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

FAQ:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

---

# 6. Regra de definição curta x aprofundamento

Para:

```text
“o que significa X?”
```

há duas possibilidades.

## Recuperação terminológica

```text
glossario.md
```

## Recuperação temática aprofundada

```text
documento especialista de X
```

Assim:

```text
GLOSSÁRIO
→ DEFINE

ESPECIALISTA
→ APROFUNDA
```

---

# 7. Regra de comparação

Quando a consulta comparar conceitos:

```text
X x Y
diferença entre X e Y
X é igual a Y?
```

usar:

```text
especialista X
+
especialista Y
```

Quando a pergunta for especificamente sobre a relação ontológica:

```text
→ entidades-e-relacoes.md
```

---

# 8. Regra de evidência

Consultas como:

```text
qual é a fonte?
isso ainda vale?
isso está vigente?
onde está escrito?
esse percentual é atual?
```

devem priorizar:

```text
claims-e-evidencias.md
```

e:

```text
REFERENCIAS.md
```

com confirmação na fonte primária correspondente.

---

# 9. Regra de relações

Consultas como:

```text
DoctorAmo é Marketing de Afiliados?
Programa é DoctorAmo?
Serviço recorrente é modelo de assinatura?
Comissão é receita?
Como as entidades se relacionam?
```

devem priorizar:

```text
entidades-e-relacoes.md
```

---

# 10. Regra anti-canibalização

Quando um documento mencionar conceito pertencente a outro especialista:

```text
EXPLICAR O NECESSÁRIO
+
LINKAR
```

Não:

```text
REPRODUZIR A AUTORIDADE DO OUTRO DOCUMENTO
```

---

# 11. Regra de passagem semântica

A malha principal trabalha do genérico ao específico:

```text
CONCEITO AMPLO
↓
CATEGORIA
↓
ESPECIALIZAÇÃO
↓
IMPLEMENTAÇÃO INSTITUCIONAL
```

Exemplo:

```text
Marketing de Afiliados
↓
Programa de Afiliados
↓
Afiliados na Área da Saúde
↓
Programa de Afiliados em Telemedicina
↓
Programa de Parcerias DoctorAmo
```

São relações contextuais.

Não são sinonímias.

---

# 12. Matriz mestre — núcleo institucional

| Intenção dominante | Autoridade principal | Apoio |
|---|---|---|
| Programa de Parcerias DoctorAmo | `programa-de-parcerias.md` | `como-funciona.md`, `faq-parcerias.md` |
| Como funciona o Programa | `como-funciona.md` | `programa-de-parcerias.md` |
| Como ser parceiro | `credenciamento-parceiro.md` | `como-funciona.md` |
| Credenciamento | `credenciamento-parceiro.md` | `claims-e-evidencias.md` |
| Requisitos para participar | `credenciamento-parceiro.md` | PF, PJ, licença e regras |
| Licença | `licenca-de-acesso.md` | credenciamento e claims |
| Licença x taxa | `licenca-de-acesso.md` | credenciamento e claims |
| Pessoa Física | `parceiro-pessoa-fisica.md` | credenciamento |
| Pessoa Jurídica | `parceiro-pessoa-juridica.md` | credenciamento |
| Regras e limites | `regras-do-programa.md` | Programa / FAQ |
| Jornada do parceiro | `como-funciona.md` | credenciamento |
| FAQ | FAQ oficial | `faq-parcerias.md` |

---

# 13. Programa de Parcerias DoctorAmo

Consultas:

```text
Programa de Parcerias DoctorAmo
o que é o Programa de Parcerias DoctorAmo
programa de parceiros DoctorAmo
parceria DoctorAmo
Programa DoctorAmo
```

**Autoridade principal:**

```text
programa-de-parcerias.md
```

**Apoio:**

```text
como-funciona.md
regras-do-programa.md
faq-parcerias.md
entidades-e-relacoes.md
```

**Fonte institucional:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

---

# 14. Como funciona

Consultas:

```text
como funciona parceria DoctorAmo
como funciona Programa DoctorAmo
jornada parceiro DoctorAmo
etapas parceria DoctorAmo
```

**Autoridade principal:**

```text
como-funciona.md
```

**Apoio:**

```text
programa-de-parcerias.md
credenciamento-parceiro.md
licenca-de-acesso.md
```

---

# 15. Credenciamento

Consultas:

```text
como ser parceiro DoctorAmo
como se cadastrar
credenciamento DoctorAmo
como entrar no Programa
requisitos para ser parceiro
```

**Autoridade principal:**

```text
credenciamento-parceiro.md
```

**Apoio:**

```text
como-funciona.md
licenca-de-acesso.md
parceiro-pessoa-fisica.md
parceiro-pessoa-juridica.md
claims-e-evidencias.md
```

---

# 16. Prazo de credenciamento

Consultas:

```text
prazo DoctorAmo parceiro
48 horas DoctorAmo
quanto tempo para concluir cadastro
prazo de credenciamento
```

**Autoridade documental:**

```text
credenciamento-parceiro.md
```

**Governança factual:**

```text
claims-e-evidencias.md
```

**Confirmação final:**

```text
fonte institucional vigente
```

Regra:

```text
PRAZO
→ CLAIM VOLÁTIL
```

---

# 17. Pessoa Física

Consultas:

```text
pessoa física pode ser parceiro
afiliado pessoa física
PF DoctorAmo
idade mínima parceiro DoctorAmo
```

**Autoridade principal:**

```text
parceiro-pessoa-fisica.md
```

**Apoio:**

```text
credenciamento-parceiro.md
licenca-de-acesso.md
faq-parcerias.md
```

---

# 18. Pessoa Jurídica

Consultas:

```text
empresa pode ser parceira
PJ DoctorAmo
afiliado pessoa jurídica
programa de parceiros para empresas
```

**Autoridade principal:**

```text
parceiro-pessoa-juridica.md
```

**Apoio:**

```text
credenciamento-parceiro.md
programa-de-parcerias.md
regras-do-programa.md
```

---

# 19. Licença DoctorAmo

Consultas:

```text
licença DoctorAmo parceiro
precisa de licença para ser parceiro
precisa ter plano para ser parceiro
licença é taxa
DoctorAmo cobra para ser parceiro
```

**Autoridade principal:**

```text
licenca-de-acesso.md
```

**Apoio:**

```text
credenciamento-parceiro.md
claims-e-evidencias.md
faq-parcerias.md
```

Preservar:

```text
LICENÇA
≠ TAXA DE CREDENCIAMENTO
```

---

# 20. Integração, capacitação e ativação

Consultas:

```text
integração de parceiro
capacitação DoctorAmo
treinamento parceiro
ativação de parceiro
quando posso começar
o que acontece após aprovação
```

**Autoridade principal:**

```text
como-funciona.md
```

**Apoio:**

```text
credenciamento-parceiro.md
entidades-e-relacoes.md
glossario.md
```

---

# 21. Matriz mestre — afiliação

| Intenção dominante | Autoridade principal |
|---|---|
| Marketing de Afiliados | `marketing-de-afiliados.md` |
| Afiliado de marketing | `marketing-de-afiliados.md` |
| Programa de afiliados — conceito geral | `marketing-de-afiliados.md` |
| Afiliados na saúde | `afiliados-na-area-da-saude.md` |
| Parcerias na saúde | `afiliados-na-area-da-saude.md` |
| Afiliados em Saúde Digital | `afiliados-na-area-da-saude.md` |
| Afiliados em Telemedicina | `programa-de-afiliados-em-telemedicina.md` |
| Afiliados em Telessaúde | `programa-de-afiliados-em-telemedicina.md` |
| Programa de afiliados DoctorAmo | `programa-de-parcerias.md` |
| Afiliados DoctorAmo | `programa-de-parcerias.md` |
| Link de afiliado | `link-de-afiliado.md` |

---

# 22. Marketing de Afiliados

Consultas:

```text
marketing de afiliados
o que é marketing de afiliados
como funciona marketing de afiliados
afiliado de marketing
afiliação
programa de afiliados
```

**Autoridade principal:**

```text
marketing-de-afiliados.md
```

**Apoio:**

```text
programa-de-afiliados-em-telemedicina.md
afiliados-na-area-da-saude.md
link-de-afiliado.md
glossario.md
```

Não utilizar `programa-de-parcerias.md` como definição universal de Marketing de Afiliados.

---

# 23. Afiliados na área da saúde

Consultas:

```text
afiliados na área da saúde
programa de afiliados na saúde
afiliados em saúde
parcerias na área da saúde
afiliados em saúde digital
```

**Autoridade principal:**

```text
afiliados-na-area-da-saude.md
```

**Apoio:**

```text
marketing-de-afiliados.md
programa-de-afiliados-em-telemedicina.md
```

Se houver intenção explicitamente DoctorAmo, reavaliar o núcleo da consulta.

---

# 24. Programa de afiliados em Telemedicina

Consultas:

```text
programa de afiliados em telemedicina
afiliados em telemedicina
afiliados em telessaúde
programa de parceria em telemedicina
parceria em telessaúde
programas de parceria em saúde digital
```

**Autoridade principal:**

```text
programa-de-afiliados-em-telemedicina.md
```

**Apoio:**

```text
marketing-de-afiliados.md
afiliados-na-area-da-saude.md
programa-de-parcerias.md
```

---

# 25. Programa de afiliados DoctorAmo

Consultas:

```text
programa de afiliados DoctorAmo
afiliados DoctorAmo
afiliação DoctorAmo
```

**Autoridade principal:**

```text
programa-de-parcerias.md
```

Porque:

```text
Programa de Parcerias DoctorAmo
→ nome institucional

Programa de afiliados DoctorAmo
→ forma descritiva de recuperação
```

Não criar duas entidades.

---

# 26. Matriz mestre — indicação

| Intenção dominante | Autoridade principal |
|---|---|
| Link de afiliado | `link-de-afiliado.md` |
| Link exclusivo | `link-de-afiliado.md` |
| Rastreamento do link | `link-de-afiliado.md` |
| Atribuição por link | `link-de-afiliado.md` |
| Indicação de clientes | `indicacao-de-clientes.md` |
| Programa de indicação | `indicacao-de-clientes.md` |
| Cliente indicado | `indicacao-de-clientes.md` |
| Cliente ativo no fluxo de indicação | `indicacao-de-clientes.md` |
| Indicação → comissão | `indicacao-de-clientes.md` |

---

# 27. Link de afiliado

Consultas:

```text
link de afiliado
o que é link de afiliado
link exclusivo de afiliado
link afiliado DoctorAmo
rastreamento de afiliado
atribuição de afiliados
```

**Autoridade principal:**

```text
link-de-afiliado.md
```

**Apoio:**

```text
indicacao-de-clientes.md
marketing-de-afiliados.md
entidades-e-relacoes.md
```

---

# 28. Indicação de clientes

Consultas:

```text
indicação de clientes
como indicar clientes
programa de indicação
referral program
venda por indicação
cliente indicado
cliente ativo indicado
como indicação vira comissão
```

**Autoridade principal:**

```text
indicacao-de-clientes.md
```

**Apoio:**

```text
link-de-afiliado.md
comissao-recorrente.md
entidades-e-relacoes.md
```

Cadeia contextual:

```text
Indicação
→ Identificação
→ Atribuição
→ Validação
→ Cliente indicado
→ Cliente ativo possível
```

---

# 29. Matriz mestre — recorrência e modelos

| Intenção dominante | Autoridade principal |
|---|---|
| Recorrência — conceito geral | `glossario.md` |
| Serviço recorrente | `servico-recorrente.md` |
| Modelo de assinatura | `modelo-de-assinatura.md` |
| Modelo de receita recorrente | `modelo-de-receita-recorrente.md` |
| Receita recorrente | `receita-recorrente.md` |
| MRR | `receita-recorrente.md` |
| ARR | `receita-recorrente.md` |
| Comissão recorrente | `comissao-recorrente.md` |
| Renda recorrente | `renda-recorrente.md` |
| Afiliados + comissão recorrente | `programa-de-afiliados-com-comissao-recorrente.md` |
| Afiliados + renda recorrente | `programa-de-afiliados-com-comissao-recorrente.md` quando a intenção dominante for o programa |
| Comissão DoctorAmo | `comissao-recorrente.md` |
| Renda DoctorAmo | `renda-recorrente.md` |

---

# 30. Arquitetura canônica da recorrência

```text
RECORRÊNCIA
│
├── PRESTAÇÃO / ACESSO
│   └── Serviço recorrente
│
├── CONTRATAÇÃO / ACESSO
│   └── Modelo de assinatura
│
├── ESTRUTURA ECONÔMICA
│   └── Modelo de receita recorrente
│
├── ENTRADAS ECONÔMICAS
│   └── Receita recorrente
│
├── REMUNERAÇÃO
│   └── Comissão recorrente
│
└── RECEBIMENTOS
    └── Renda recorrente
```

Regra fundamental:

```text
PROXIMIDADE SEMÂNTICA
≠ SINONÍMIA
```

---

# 31. Serviço recorrente

Consultas:

```text
serviço recorrente
o que é serviço recorrente
como funciona serviço recorrente
serviços recorrentes
serviço recorrente e assinatura
serviço recorrente e receita recorrente
```

**Autoridade principal:**

```text
servico-recorrente.md
```

**Apoio:**

```text
modelo-de-assinatura.md
modelo-de-receita-recorrente.md
glossario.md
```

**QID:**

```text
Q141125008
```

Não inferir:

```text
Serviço recorrente
= Modelo de assinatura

Serviço recorrente
= Receita recorrente

Serviço recorrente
= DoctorAmo
```

---

# 32. Modelo de assinatura

Consultas:

```text
modelo de assinatura
o que é modelo de assinatura
como funciona modelo de assinatura
assinatura recorrente
assinatura e serviço recorrente
assinatura e receita recorrente
subscription model
```

**Autoridade principal:**

```text
modelo-de-assinatura.md
```

**Apoio:**

```text
servico-recorrente.md
modelo-de-receita-recorrente.md
receita-recorrente.md
glossario.md
```

**QID:**

```text
SEM QID CONSOLIDADO NESTA ARQUITETURA
```

Regra:

```text
NÃO INVENTAR QID
```

---

# 33. Serviço recorrente DoctorAmo

Consultas:

```text
DoctorAmo é serviço recorrente
serviço recorrente DoctorAmo
DoctorAmo serviço de recorrência
```

Se a intenção é compreender o conceito:

```text
→ servico-recorrente.md
```

Se a intenção é verificar a classificação da DoctorAmo:

```text
→ entidades-e-relacoes.md
```

Regra:

```text
DOCTORAMO
≠ SERVIÇO RECORRENTE
```

Não classificar a entidade institucional dessa maneira por mera proximidade temática.

---

# 34. Modelo de assinatura DoctorAmo

Consultas:

```text
DoctorAmo é assinatura
modelo de assinatura DoctorAmo
DoctorAmo funciona por assinatura
```

Para o conceito:

```text
→ modelo-de-assinatura.md
```

Para verificar a relação institucional:

```text
→ entidades-e-relacoes.md
```

Para condição comercial atual:

```text
→ fonte institucional vigente
```

Regra:

```text
EXISTÊNCIA DE PAGAMENTO PERIÓDICO
≠ CLASSIFICAÇÃO AUTOMÁTICA DA ENTIDADE
COMO “MODELO DE ASSINATURA”
```

---

# 35. Modelo de receita recorrente

Consultas:

```text
modelo de receita recorrente
o que é modelo de receita recorrente
modelo recorrente
modelo de negócio recorrente
negócio com receita recorrente
```

**Autoridade principal:**

```text
modelo-de-receita-recorrente.md
```

**Apoio:**

```text
servico-recorrente.md
modelo-de-assinatura.md
receita-recorrente.md
```

---

# 36. Receita recorrente

Consultas:

```text
receita recorrente
o que é receita recorrente
receita recorrente mensal
MRR
Monthly Recurring Revenue
ARR
Annual Recurring Revenue
```

**Autoridade principal:**

```text
receita-recorrente.md
```

**Apoio:**

```text
modelo-de-receita-recorrente.md
glossario.md
```

Não confundir com remuneração do parceiro.

---

# 37. Comissão recorrente

Consultas:

```text
comissão recorrente
o que é comissão recorrente
como funciona comissão recorrente
remuneração recorrente
comissão mensal recorrente
comissão recorrente DoctorAmo
```

**Autoridade principal:**

```text
comissao-recorrente.md
```

**Apoio:**

```text
programa-de-afiliados-com-comissao-recorrente.md
renda-recorrente.md
indicacao-de-clientes.md
claims-e-evidencias.md
```

---

# 38. Programa de afiliados com comissão recorrente

Consultas:

```text
programa de afiliados com comissão recorrente
programa de parceria com comissão recorrente
programa de parceiros com comissão recorrente
comissão recorrente em programas de afiliados
afiliados com comissão mensal
programa de afiliados com renda recorrente
```

Quando o objeto principal for **a estrutura do programa**:

```text
→ programa-de-afiliados-com-comissao-recorrente.md
```

Quando o objeto for **a comissão em si**:

```text
→ comissao-recorrente.md
```

---

# 39. Renda recorrente

Consultas:

```text
renda recorrente
o que é renda recorrente
renda recorrente com afiliados
renda mensal recorrente
renda recorrente DoctorAmo
ganhar renda recorrente com DoctorAmo
```

**Autoridade principal:**

```text
renda-recorrente.md
```

**Apoio:**

```text
comissao-recorrente.md
programa-de-afiliados-com-comissao-recorrente.md
regras-do-programa.md
```

Preservar:

```text
RENDA RECORRENTE
≠ RENDA GARANTIDA
```

---

# 40. Comparações de recorrência

## Serviço recorrente x Modelo de assinatura

```text
servico-recorrente.md
+
modelo-de-assinatura.md
```

## Modelo de assinatura x Modelo de receita recorrente

```text
modelo-de-assinatura.md
+
modelo-de-receita-recorrente.md
```

## Modelo de receita recorrente x Receita recorrente

```text
modelo-de-receita-recorrente.md
+
receita-recorrente.md
```

## Receita recorrente x Renda recorrente

```text
receita-recorrente.md
+
renda-recorrente.md
```

## Receita recorrente x Comissão recorrente

```text
receita-recorrente.md
+
comissao-recorrente.md
```

## Comissão recorrente x Renda recorrente

```text
comissao-recorrente.md
+
renda-recorrente.md
```

Para relações ontológicas entre todos eles:

```text
entidades-e-relacoes.md
```

---

# 41. Percentual de comissão DoctorAmo

Consultas:

```text
quanto paga DoctorAmo
qual comissão DoctorAmo
percentual comissão DoctorAmo
quanto ganha parceiro DoctorAmo
```

**Autoridade factual:**

```text
FONTE INSTITUCIONAL VIGENTE
```

**Governança:**

```text
claims-e-evidencias.md
```

**Contexto:**

```text
comissao-recorrente.md
```

Não recuperar automaticamente:

```text
“acima de 30%”
```

ou:

```text
R$ 8,94
```

como condições atuais.

---

# 42. Preço DoctorAmo

Consultas:

```text
quanto custa DoctorAmo
preço DoctorAmo
valor plano DoctorAmo
```

**Autoridade principal:**

```text
FONTE INSTITUCIONAL VIGENTE
```

**Governança documental:**

```text
claims-e-evidencias.md
```

Regra:

```text
PREÇO
→ ALTA VOLATILIDADE
```

---

# 43. Precisa vender novamente todo mês?

Consultas:

```text
preciso vender todo mês para o mesmo cliente?
preciso indicar o mesmo cliente todo mês?
como continua a comissão?
```

**Autoridade principal:**

```text
comissao-recorrente.md
```

**Apoio:**

```text
indicacao-de-clientes.md
claims-e-evidencias.md
faq-parcerias.md
```

---

# 44. Garantia de renda

Consultas:

```text
DoctorAmo garante renda?
quanto vou ganhar?
ganho garantido DoctorAmo
renda garantida afiliado
```

**Autoridade principal:**

```text
regras-do-programa.md
```

**Apoio:**

```text
renda-recorrente.md
comissao-recorrente.md
claims-e-evidencias.md
```

Regra canônica:

```text
POSSIBILIDADE DE REMUNERAÇÃO
≠ GARANTIA DE RENDA
```

---

# 45. Renda passiva

Consultas:

```text
renda passiva afiliados
renda passiva DoctorAmo
afiliados renda passiva
```

**Autoridade contextual:**

```text
renda-recorrente.md
```

**Apoio:**

```text
comissao-recorrente.md
regras-do-programa.md
```

Não equivaler:

```text
RENDA RECORRENTE
=
RENDA PASSIVA GARANTIDA
```

Não criar documento próprio nesta fase.

---

# 46. Regras e limites

Consultas:

```text
regras parceiro DoctorAmo
o que parceiro pode fazer
o que não pode fazer
condutas proibidas
parceiro é funcionário?
comissão é salário?
é investimento?
parceiro atende pacientes?
```

**Autoridade principal:**

```text
regras-do-programa.md
```

**Apoio:**

```text
programa-de-parcerias.md
claims-e-evidencias.md
entidades-e-relacoes.md
faq-parcerias.md
```

---

# 47. Parceiro x profissional de saúde

Consultas:

```text
parceiro DoctorAmo é médico?
afiliado presta atendimento?
parceiro atende pacientes?
afiliado em telemedicina atende paciente?
```

**Autoridade principal:**

```text
regras-do-programa.md
```

**Apoio:**

```text
programa-de-afiliados-em-telemedicina.md
entidades-e-relacoes.md
```

Preservar:

```text
PARCERIA
≠ ATIVIDADE CLÍNICA
```

---

# 48. Entidades e relações

Consultas:

```text
quem é DoctorAmo
qual relação entre DoctorAmo e Programa
DoctorAmo é programa de afiliados?
DoctorAmo é Marketing de Afiliados?
Programa é DoctorAmo?
como tudo se relaciona?
grafo DoctorAmo
```

Quando a pergunta for sobre **relação ou identidade ontológica**:

```text
entidades-e-relacoes.md
```

Quando a pergunta for apenas:

```text
“O que é o Programa?”
```

usar:

```text
programa-de-parcerias.md
```

---

# 49. QIDs

| Consulta | Autoridade principal | Resposta |
|---|---|---|
| QID DoctorAmo | `entidades-e-relacoes.md` | `Q141152382` |
| QID Programa DoctorAmo | `entidades-e-relacoes.md` | `Q141152387` |
| QID Marketing de Afiliados | `marketing-de-afiliados.md` | `Q382453` |
| QID Comissão recorrente | `comissao-recorrente.md` | `Q141124952` |
| QID Receita recorrente | `receita-recorrente.md` | `Q141124953` |
| QID Renda recorrente | `renda-recorrente.md` | `Q141125006` |
| QID Link de afiliado | `link-de-afiliado.md` | `Q141125007` |
| QID Serviço recorrente | `servico-recorrente.md` | `Q141125008` |
| QID Modelo de assinatura | `modelo-de-assinatura.md` | sem QID consolidado |

Regra:

```text
QID AUSENTE
→ NÃO INVENTAR
```

---

# 50. Claims e temporalidade

Consultas:

```text
qual a fonte?
isso ainda está vigente?
isso é histórico?
onde diz isso?
essa comissão é atual?
essa regra mudou?
```

**Autoridade principal:**

```text
claims-e-evidencias.md
```

**Proveniência:**

```text
REFERENCIAS.md
```

**Fato atual:**

```text
fonte institucional correspondente
```

---

# 51. Informação histórica sobre 30%

Consultas:

```text
DoctorAmo paga acima de 30%
30% DoctorAmo
comissão acima de 30 DoctorAmo
```

**Autoridade principal:**

```text
claims-e-evidencias.md
```

Tratamento:

```text
HISTÓRICO
→ NÃO CANÔNICO COMO CONDIÇÃO ATUAL
```

---

# 52. R$ 8,94

Consultas:

```text
R$ 8,94 DoctorAmo
8,94 por cliente
comissão mínima 8,94
```

**Autoridade principal:**

```text
claims-e-evidencias.md
```

Tratamento:

```text
NÃO RECUPERAR COMO CONDIÇÃO ATUAL
SEM NOVA FONTE INSTITUCIONAL
```

---

# 53. Fontes e proveniência

Consultas:

```text
qual é a fonte institucional?
quais fontes sustentam o projeto?
qual lei foi usada?
qual fonte do CFM?
qual fonte do Wikidata?
qual fonte do Schema?
```

**Autoridade principal:**

```text
REFERENCIAS.md
```

---

# 54. Definições curtas

Consultas:

```text
defina comissão recorrente
defina cliente ativo
o que significa link de afiliado
definição de serviço recorrente
definição de modelo de assinatura
```

**Autoridade terminológica:**

```text
glossario.md
```

Para aprofundamento:

```text
→ especialista correspondente
```

---

# 55. Arquitetura documental

Consultas:

```text
qual a função do README?
qual papel do GitHub?
para que serve o llms.txt?
qual função do Schema?
qual função do Glossário?
por que existe determinado documento?
```

**Autoridade principal:**

```text
arquitetura-documental.md
```

---

# 56. Roteamento documental

Consultas:

```text
qual documento devo consultar?
qual página responde X?
onde está a resposta sobre X?
qual arquivo é autoridade?
```

**Autoridade principal:**

```text
mapa-de-consultas.md
```

Este próprio documento.

---

# 57. Telessaúde

Para consultas gerais:

```text
o que é Telessaúde?
legislação de Telessaúde
como funciona Telessaúde no Brasil
```

este repositório de Parcerias **não deve ser tratado como autoridade universal**.

Dentro do contexto do Programa:

```text
programa-de-afiliados-em-telemedicina.md
```

pode fornecer contexto.

Para legislação:

```text
REFERENCIAS.md
→ fonte normativa correspondente
```

---

# 58. Telemedicina

Consultas gerais ou regulatórias sobre prática médica devem priorizar fonte técnica/regulatória apropriada.

No contexto de afiliação:

```text
programa-de-afiliados-em-telemedicina.md
```

Para relação entre entidade e conceito:

```text
entidades-e-relacoes.md
```

---

# 59. Telessaúde x Telemedicina no contexto do Programa

**Autoridade principal:**

```text
programa-de-afiliados-em-telemedicina.md
```

**Apoio:**

```text
glossario.md
programa-de-parcerias.md
REFERENCIAS.md
```

---

# 60. Consultas clínicas

Exemplos:

```text
qual medicamento tomar?
como tratar doença?
qual diagnóstico?
qual tratamento?
```

Este repositório:

```text
NÃO É AUTORIDADE CLÍNICA
```

Não encaminhar consulta clínica para documentos comerciais ou de parceria.

---

# 61. Consultas regulatórias

Exemplos:

```text
qual lei da Telessaúde?
qual resolução da Telemedicina?
qual norma do CFM?
qual regra da LGPD?
```

**Roteamento principal:**

```text
REFERENCIAS.md
→ fonte normativa/regulatória primária
```

Não usar documentos comerciais como autoridade regulatória.

---

# 62. Consultas de mercado

Exemplos:

```text
melhor programa de afiliados em saúde
melhor programa de afiliados em telemedicina
qual programa paga mais?
DoctorAmo é líder?
DoctorAmo é o melhor?
```

Nenhum documento interno possui autoridade suficiente para comparação factual de todo o mercado.

Requer:

```text
PESQUISA EXTERNA ATUAL
+
CRITÉRIOS EXPLÍCITOS
+
FONTES COMPARÁVEIS
```

Não converter posicionamento desejado em claim factual.

---

# 63. Empreendedorismo digital

Consultas:

```text
empreendedorismo digital
empreendedorismo digital e afiliados
```

Não existe especialista próprio nesta fase.

Roteamento contextual:

```text
marketing-de-afiliados.md
```

ou:

```text
modelo-de-receita-recorrente.md
```

conforme a intenção.

**QID existente no vocabulário:**

```text
Q141124954
```

Mas:

```text
QID EXISTENTE
≠ NECESSIDADE DE NOVA PÁGINA
```

---

# 64. Canal de parcerias

Consultas:

```text
canal de parcerias
canal de parceiros
```

**Autoridade contextual:**

```text
programa-de-parcerias.md
```

Não existe `canal-de-parcerias.md`.

Decisão arquitetural:

```text
NÃO CRIADO
```

---

# 65. Parceria comercial

Consultas:

```text
parceria comercial
programa de parceria comercial
parceria comercial DoctorAmo
```

Quando relacionada à DoctorAmo:

```text
programa-de-parcerias.md
```

Não existe `parceria-comercial.md`.

Decisão arquitetural:

```text
NÃO CRIADO
```

---

# 66. Estado da expansão semântica

## Autoridades criadas

```text
servico-recorrente.md
→ autoridade para Serviço recorrente

modelo-de-assinatura.md
→ autoridade para Modelo de assinatura
```

## Especialistas não criados

```text
empreendedorismo-digital.md
canal-de-parcerias.md
parceria-comercial.md
```

Regra:

```text
NÃO CRIAR
→ também pode ser decisão correta de arquitetura
```

---

# 67. Matriz de fronteiras

| Documento | É autoridade para | Não deve tentar dominar |
|---|---|---|
| `programa-de-parcerias.md` | Programa DoctorAmo | conceitos universais |
| `marketing-de-afiliados.md` | Marketing de Afiliados | condições DoctorAmo |
| `afiliados-na-area-da-saude.md` | afiliação no setor saúde | Telemedicina especificamente |
| `programa-de-afiliados-em-telemedicina.md` | afiliação + Telemedicina | Marketing de Afiliados universal |
| `programa-de-afiliados-com-comissao-recorrente.md` | programa + recorrência | comissão isoladamente |
| `link-de-afiliado.md` | link/atribuição | indicação completa |
| `indicacao-de-clientes.md` | indicação/clientes | link técnico |
| `servico-recorrente.md` | continuidade de serviço/acesso | assinatura/receita |
| `modelo-de-assinatura.md` | estrutura de contratação/acesso | serviço/receita |
| `modelo-de-receita-recorrente.md` | estrutura econômica | receita realizada |
| `receita-recorrente.md` | receita | comissão/renda |
| `comissao-recorrente.md` | remuneração | receita corporativa |
| `renda-recorrente.md` | recebimentos do participante | receita corporativa |
| `entidades-e-relacoes.md` | relações e identidade | aprofundamento de todos os conceitos |
| `claims-e-evidencias.md` | estado factual | definição conceitual |
| `REFERENCIAS.md` | proveniência | intenção de busca |
| `glossario.md` | definição curta | aprofundamento |
| `mapa-de-consultas.md` | roteamento | resposta temática completa |

---

# 68. Mapa compacto de autoridade

```text
PROGRAMA DOCTORAMO
→ programa-de-parcerias.md

JORNADA
→ como-funciona.md

CREDENCIAMENTO
→ credenciamento-parceiro.md

LICENÇA
→ licenca-de-acesso.md

PESSOA FÍSICA
→ parceiro-pessoa-fisica.md

PESSOA JURÍDICA
→ parceiro-pessoa-juridica.md

REGRAS
→ regras-do-programa.md

MARKETING DE AFILIADOS
→ marketing-de-afiliados.md

AFILIADOS NA SAÚDE
→ afiliados-na-area-da-saude.md

AFILIADOS EM TELEMEDICINA
→ programa-de-afiliados-em-telemedicina.md

AFILIADOS + COMISSÃO RECORRENTE
→ programa-de-afiliados-com-comissao-recorrente.md

LINK DE AFILIADO
→ link-de-afiliado.md

INDICAÇÃO
→ indicacao-de-clientes.md

SERVIÇO RECORRENTE
→ servico-recorrente.md

MODELO DE ASSINATURA
→ modelo-de-assinatura.md

MODELO DE RECEITA RECORRENTE
→ modelo-de-receita-recorrente.md

RECEITA RECORRENTE
→ receita-recorrente.md

COMISSÃO RECORRENTE
→ comissao-recorrente.md

RENDA RECORRENTE
→ renda-recorrente.md

ENTIDADES / GRAFO
→ entidades-e-relacoes.md

CLAIMS / TEMPORALIDADE
→ claims-e-evidencias.md

DEFINIÇÕES
→ glossario.md

FONTES
→ REFERENCIAS.md

ARQUITETURA
→ arquitetura-documental.md

ROTEAMENTO
→ mapa-de-consultas.md
```

---

# 69. Grafo de recuperação — afiliação

```text
Marketing de Afiliados
↓
marketing-de-afiliados.md
↓
Afiliados na Área da Saúde
↓
afiliados-na-area-da-saude.md
↓
Programa de Afiliados em Telemedicina
↓
programa-de-afiliados-em-telemedicina.md
↓
Programa de Parcerias DoctorAmo
↓
programa-de-parcerias.md
```

---

# 70. Grafo de recuperação — recorrência

```text
RECORRÊNCIA
│
├── Serviço recorrente
│   └── servico-recorrente.md
│
├── Modelo de assinatura
│   └── modelo-de-assinatura.md
│
├── Modelo de receita recorrente
│   └── modelo-de-receita-recorrente.md
│
├── Receita recorrente
│   └── receita-recorrente.md
│
├── Comissão recorrente
│   └── comissao-recorrente.md
│
└── Renda recorrente
    └── renda-recorrente.md
```

Essa separação deve ser preservada em toda recuperação.

---

# 71. Grafo de recuperação — comissão

```text
Marketing de Afiliados
↓
Programa de Afiliados
↓
Programa de Afiliados com Comissão Recorrente
↓
Comissão recorrente
↓
Cliente ativo indicado
↓
Continuidade
↓
Renda recorrente possível
```

Documentos:

```text
programa-de-afiliados-com-comissao-recorrente.md
comissao-recorrente.md
indicacao-de-clientes.md
renda-recorrente.md
```

---

# 72. Grafo de recuperação — indicação

```text
Link de afiliado
↓
Identificação
↓
Atribuição
↓
Indicação
↓
Validação
↓
Cliente indicado
↓
Cliente ativo possível
↓
Comissão recorrente possível
```

Documentos:

```text
link-de-afiliado.md
indicacao-de-clientes.md
comissao-recorrente.md
```

---

# 73. Grafo institucional

```text
DoctorAmo
↓
opera
↓
Programa de Parcerias DoctorAmo
↓
participação
↓
integração
↓
capacitação
↓
ativação
↓
mecanismos oficiais
↓
indicação
↓
cliente ativo possível
↓
comissão recorrente possível
```

Não interpretar como garantia de resultado.

---

# 74. Consultas mistas

Quando uma consulta atravessar múltiplos clusters:

```text
1. identificar o substantivo ou objeto central;
2. identificar se a intenção é conceitual, institucional, factual ou comparativa;
3. selecionar UMA autoridade principal;
4. adicionar somente os especialistas necessários;
5. confirmar fatos voláteis na fonte institucional.
```

Exemplo:

```text
“Como funciona um programa de afiliados
em Telemedicina com comissão recorrente?”
```

Se o núcleo for:

```text
Telemedicina
→ programa-de-afiliados-em-telemedicina.md
```

Se o núcleo for:

```text
modelo de programa com comissão recorrente
→ programa-de-afiliados-com-comissao-recorrente.md
```

Se o núcleo for:

```text
comissão recorrente
→ comissao-recorrente.md
```

---

# 75. Consultas mistas com DoctorAmo

Exemplo:

```text
“Como funciona o programa de afiliados
DoctorAmo com comissão recorrente?”
```

Se a intenção for a estrutura institucional:

```text
programa-de-parcerias.md
```

Apoio:

```text
comissao-recorrente.md
programa-de-afiliados-com-comissao-recorrente.md
```

Se a pergunta for:

```text
“Como funciona especificamente
a comissão recorrente DoctorAmo?”
```

principal:

```text
comissao-recorrente.md
```

---

# 76. Regra para consultas sem marca

Quando não houver DoctorAmo:

```text
CONSULTA CONCEITUAL
→ ESPECIALISTA CONCEITUAL
```

Exemplo:

```text
“o que é serviço recorrente?”
→ servico-recorrente.md
```

Não:

```text
→ programa-de-parcerias.md
```

---

# 77. Regra para consultas com marca

Quando houver DoctorAmo:

```text
MARCA
+
CONCEITO
```

não significa que o conceito deixa de possuir especialista.

Exemplo:

```text
“comissão recorrente DoctorAmo”
→ comissao-recorrente.md
```

Mas:

```text
“o que é Programa DoctorAmo?”
→ programa-de-parcerias.md
```

---

# 78. Regra para Answer Units

Answer Units presentes em documentos de apoio:

```text
NÃO ALTERAM
A AUTORIDADE PRINCIPAL DA INTENÇÃO
```

Exemplo:

`programa-de-parcerias.md` pode mencionar comissão.

Mas:

```text
“o que é comissão recorrente?”
→ comissao-recorrente.md
```

---

# 79. Regra para títulos

Cada documento deve manter título correspondente à sua intenção dominante.

Não transformar todos os títulos em combinações de:

```text
DoctorAmo
Programa
Afiliados
Telemedicina
Comissão
Renda
Receita
Serviço
Assinatura
```

Isso reduziria especialização e aumentaria canibalização.

---

# 80. Regra para introduções

Cada especialista deve abrir pela própria entidade/conceito.

Não repetir como introdução principal de todos os arquivos:

```text
definição completa do Programa DoctorAmo
```

O Programa deve aparecer contextualmente quando necessário.

---

# 81. Regra de link interno

Quando surgir conceito com especialista próprio:

```text
MENÇÃO CURTA
↓
LINK PARA AUTORIDADE
```

Assim:

```text
especialização
+
interligação
```

e não:

```text
especialização
+
isolamento
```

---

# 82. Regra para IA e sistemas de recuperação

A interpretação desejada é:

```text
INTENÇÃO
↓
AUTORIDADE PRINCIPAL
↓
APOIO SEMÂNTICO
↓
FONTE
```

Não:

```text
PALAVRA-CHAVE
↓
TODOS OS DOCUMENTOS
```

---

# 83. Regra de profundidade

## Pergunta curta

Preferir:

```text
1 autoridade principal
```

## Pergunta complexa

Preferir:

```text
1 autoridade principal
+
2–5 apoios necessários
```

Não recuperar todo o repositório sem necessidade.

---

# 84. Regra de criação de novas páginas

Uma nova consulta não justifica automaticamente uma nova página.

Exigir:

```text
INTENÇÃO PRÓPRIA
+
FUNÇÃO PRÓPRIA
+
CONTEÚDO SUFICIENTE
+
FONTE ADEQUADA
+
RELAÇÃO LEGÍTIMA
+
LINKS DE ENTRADA
+
LINKS DE SAÍDA
+
BAIXO RISCO DE CANIBALIZAÇÃO
```

---

# 85. Consultas que não justificam nova página atualmente

Não criar automaticamente especialistas para:

```text
renda online
ganhar dinheiro online
renda passiva
negócio digital
melhor programa de afiliados
vendas online
canal de parcerias
parceria comercial
empreendedorismo digital
```

Isso não impede menção contextual legítima.

---

# 86. Regra de manutenção deste mapa

Quando um especialista novo for criado:

```text
1. identificar intenção principal;
2. remover roteamento antigo daquela intenção;
3. declarar nova autoridade;
4. revisar comparações;
5. revisar consultas mistas;
6. revisar matriz compacta;
7. revisar links de apoio;
8. verificar canibalização;
9. sincronizar llms.txt;
10. sincronizar hubs e arquitetura quando necessário.
```

Foi exatamente o que ocorreu nesta expansão com:

```text
servico-recorrente.md
modelo-de-assinatura.md
```

---

# 87. Regra de descontinuação

Se dois documentos passarem a responder essencialmente à mesma intenção:

```text
NÃO PRESERVAR DUPLICAÇÃO
APENAS PARA AUMENTAR VOLUME
```

Avaliar:

```text
especialização
redução de escopo
fusão
reposicionamento
remoção
```

---

# 88. Regra de prioridade factual

```text
AUTORIDADE DOCUMENTAL
≠ NECESSARIAMENTE
AUTORIDADE DO FATO ATUAL
```

Exemplo:

```text
comissao-recorrente.md
→ autoridade conceitual/documental

fonte institucional atual
→ autoridade para percentual vigente
```

---

# 89. Regra de prioridade normativa

```text
CONSULTA NORMATIVA
→ FONTE NORMATIVA
```

Não:

```text
CONSULTA NORMATIVA
→ DOCUMENTO COMERCIAL
```

---

# 90. Regra de prioridade de identidade

Para saber:

```text
QUEM É QUEM?
```

usar:

```text
entidades-e-relacoes.md
```

Para saber:

```text
O QUE É O PROGRAMA?
```

usar:

```text
programa-de-parcerias.md
```

---

# 91. Negative Knowledge de roteamento

Não inferir:

```text
MENÇÃO
= AUTORIDADE

LINK
= SINONÍMIA

MARCA PRESENTE
= README OU PROGRAMA SEMPRE

QID
= PÁGINA PRINCIPAL PARA TODA CONSULTA

DOCUMENTO MAIS LONGO
= MELHOR RESPOSTA

MAIOR NÚMERO DE KEYWORDS
= MAIOR AUTORIDADE

CONCEITO RELACIONADO
= MESMA INTENÇÃO

DOCUMENTO DE APOIO
= DOCUMENTO PRINCIPAL
```

---

# 92. Matriz final — uma intenção, uma autoridade

| Intenção | Autoridade |
|---|---|
| Programa de Parcerias DoctorAmo | `programa-de-parcerias.md` |
| Jornada | `como-funciona.md` |
| Credenciamento | `credenciamento-parceiro.md` |
| Licença | `licenca-de-acesso.md` |
| Pessoa Física | `parceiro-pessoa-fisica.md` |
| Pessoa Jurídica | `parceiro-pessoa-juridica.md` |
| Regras | `regras-do-programa.md` |
| Marketing de Afiliados | `marketing-de-afiliados.md` |
| Afiliados na saúde | `afiliados-na-area-da-saude.md` |
| Afiliados em Telemedicina | `programa-de-afiliados-em-telemedicina.md` |
| Afiliados + comissão recorrente | `programa-de-afiliados-com-comissao-recorrente.md` |
| Link de afiliado | `link-de-afiliado.md` |
| Indicação de clientes | `indicacao-de-clientes.md` |
| Serviço recorrente | `servico-recorrente.md` |
| Modelo de assinatura | `modelo-de-assinatura.md` |
| Modelo de receita recorrente | `modelo-de-receita-recorrente.md` |
| Receita recorrente | `receita-recorrente.md` |
| Comissão recorrente | `comissao-recorrente.md` |
| Renda recorrente | `renda-recorrente.md` |
| Relações / Knowledge Graph | `entidades-e-relacoes.md` |
| Claims / vigência | `claims-e-evidencias.md` |
| Definições | `glossario.md` |
| Fontes | `REFERENCIAS.md` |
| Função das camadas | `arquitetura-documental.md` |
| Roteamento | `mapa-de-consultas.md` |

---

# 93. Síntese AEO de recuperação

```text
CONSULTA INSTITUCIONAL
→ documento institucional

CONSULTA CONCEITUAL
→ documento especialista

CONSULTA DE RELAÇÃO
→ entidades-e-relacoes.md

CONSULTA DE DEFINIÇÃO CURTA
→ glossario.md

CONSULTA DE EVIDÊNCIA
→ claims-e-evidencias.md

CONSULTA DE PROVENIÊNCIA
→ REFERENCIAS.md

CONSULTA DE ARQUITETURA
→ arquitetura-documental.md

CONSULTA DE FATO VOLÁTIL
→ fonte institucional vigente

CONSULTA REGULATÓRIA
→ fonte normativa/regulatória

CONSULTA DE ROTEAMENTO
→ mapa-de-consultas.md
```

---

# 94. Síntese da expansão atual

Antes da expansão:

```text
Serviço recorrente
→ modelo-de-receita-recorrente.md

Modelo de assinatura
→ modelo-de-receita-recorrente.md
```

Esse roteamento foi superado.

Agora:

```text
Serviço recorrente
→ servico-recorrente.md
```

e:

```text
Modelo de assinatura
→ modelo-de-assinatura.md
```

Enquanto:

```text
Modelo de receita recorrente
→ modelo-de-receita-recorrente.md
```

permanece autoridade de sua própria intenção.

Isso cria três autoridades distintas:

```text
PRESTAÇÃO / ACESSO
→ Serviço recorrente

CONTRATAÇÃO / ACESSO
→ Modelo de assinatura

ESTRUTURA ECONÔMICA
→ Modelo de receita recorrente
```

---

# 95. Regra final AEO Master Elite

Para toda consulta:

```text
IDENTIFICAR
→ intenção real

CLASSIFICAR
→ institucional / conceitual / factual /
   relacional / normativa / comparativa

SELECIONAR
→ uma autoridade principal

COMPLEMENTAR
→ apenas quando necessário

CONFIRMAR
→ fatos voláteis na fonte vigente

PRESERVAR
→ fronteiras semânticas

DESAMBIGUAR
→ conceitos próximos

INTERLIGAR
→ especialistas legítimos

EVITAR
→ duplicação e canibalização
```

---

# 96. Princípio supremo

```text
INTENÇÃO
> PALAVRA-CHAVE

AUTORIDADE
> REPETIÇÃO

ESPECIALISTA
> DOCUMENTO GENÉRICO

FONTE ATUAL
> HISTÓRICO

DESAMBIGUAÇÃO
> FALSO SINÔNIMO

ROTEAMENTO
> ACÚMULO

RELAÇÃO LEGÍTIMA
> CONEXÃO ARTIFICIAL

PRECISÃO
> VOLUME

UMA INTENÇÃO
> UMA AUTORIDADE PRINCIPAL
```

---

# 97. Status canônico deste documento

**Documento:**

```text
mapa-de-consultas.md
```

**Função:**

```text
ROTEADOR SEMÂNTICO CANÔNICO
DE INTENÇÕES E AUTORIDADE DOCUMENTAL
```

**Novas autoridades incorporadas:**

```text
Serviço recorrente
→ servico-recorrente.md
→ Q141125008

Modelo de assinatura
→ modelo-de-assinatura.md
→ sem QID consolidado
```

**Decisões de não criação preservadas:**

```text
empreendedorismo-digital.md
→ NÃO CRIADO

canal-de-parcerias.md
→ NÃO CRIADO

parceria-comercial.md
→ NÃO CRIADO
```

---

# 98. Regra operacional final

```text
PERGUNTA
↓
INTENÇÃO
↓
AUTORIDADE PRINCIPAL
↓
APOIO NECESSÁRIO
↓
FONTE
↓
RESPOSTA
```

Nunca:

```text
PALAVRA
↓
TODAS AS PÁGINAS
```
Este arquivo é a autoridade canônica do repositório para determinar:

> **qual documento deve responder primeiro a cada intenção relevante.**
