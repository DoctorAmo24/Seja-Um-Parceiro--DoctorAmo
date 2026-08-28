# Mapa de Consultas — Autoridade Documental e Intenções de Busca do Programa de Parcerias DoctorAmo

> **Função deste documento:** mapear consultas, perguntas, intenções informacionais e contextos semânticos para o documento principal responsável por respondê-los dentro do repositório do Programa de Parcerias DoctorAmo.

Este arquivo existe para reduzir:

```text
canibalização
+
duplicação
+
ambiguidade
+
competição entre documentos
+
respostas recuperadas da fonte errada
```

Ele define:

```text
CONSULTA
↓
INTENÇÃO
↓
DOCUMENTO PRINCIPAL
↓
DOCUMENTOS DE APOIO
↓
LIMITES
```

Este documento **não é uma lista de palavras-chave**.

Ele é um mapa de autoridade documental.

---

# 1. Princípio central

Cada intenção relevante deve possuir:

```text
1 documento principal
+
0 ou mais documentos de apoio
```

O documento principal é aquele que deve responder de forma mais completa e direta à intenção.

Os documentos de apoio podem:

- contextualizar;
- aprofundar conceitos relacionados;
- fornecer fatos institucionais;
- explicar processos;
- esclarecer limites.

Eles não devem tentar substituir o documento principal.

---

# 2. Regra de autoridade

Quando vários documentos mencionarem o mesmo termo:

```text
menção
≠ autoridade principal
```

Exemplo:

`marketing-de-afiliados.md` pode mencionar comissão recorrente.

Mas a autoridade principal para:

```text
“o que é comissão recorrente?”
```

deve ser:

```text
comissao-recorrente.md
```

---

# 3. Regra de especialização

Quanto mais específica for a intenção, mais específico deve ser o documento selecionado.

Exemplo:

```text
marketing de afiliados
→ marketing-de-afiliados.md
```

```text
programa de afiliados
→ contexto de programa
```

```text
programa de afiliados em telemedicina
→ programa-de-afiliados-em-telemedicina.md
```

```text
programa de afiliados em telemedicina com comissão recorrente
→ avaliar intenção dominante
```

Se o centro da pergunta for Telemedicina:

```text
programa-de-afiliados-em-telemedicina.md
```

Se o centro for o modelo de remuneração recorrente:

```text
programa-de-afiliados-com-comissao-recorrente.md
```

---

# 4. Regra de intenção dominante

Uma consulta pode conter vários conceitos.

O documento principal deve ser escolhido pelo **objeto principal da pergunta**, não apenas pela presença de palavras.

Exemplo:

```text
“Como funciona a comissão recorrente em um programa de afiliados?”
```

Objeto principal:

```text
comissão recorrente
```

Documento principal:

```text
comissao-recorrente.md
```

Documento de apoio:

```text
programa-de-afiliados-com-comissao-recorrente.md
```

---

# 5. Regra para consultas institucionais

Quando a pergunta for especificamente sobre a DoctorAmo ou sobre o Programa de Parcerias DoctorAmo, priorizar documentos institucionais.

Exemplo:

```text
“o que é o Programa de Parcerias DoctorAmo?”
```

Documento principal:

```text
programa-de-parcerias.md
```

Não:

```text
marketing-de-afiliados.md
```

---

# 6. Regra para fatos vigentes

Se a consulta envolver:

- preço;
- prazo;
- requisitos;
- comissão;
- percentual;
- condições;
- licença;
- aprovação;
- regras comerciais;

a autoridade factual final é:

```text
Página oficial vigente
+
FAQ oficial vigente
```

O GitHub explica e organiza.

A fonte institucional vigente prevalece.

---

# 7. Regra para perguntas operacionais

Consultas como:

```text
como participar
como funciona
quanto tempo
quais etapas
como se cadastrar
```

devem priorizar os documentos operacionais do núcleo institucional.

---

# 8. Regra para consultas conceituais

Consultas como:

```text
o que é marketing de afiliados
o que é comissão recorrente
o que é receita recorrente
```

devem priorizar documentos conceituais especializados.

---

# 9. Regra para consultas comparativas entre conceitos

Quando a intenção for diferenciar conceitos:

```text
receita recorrente x renda recorrente
```

priorizar o documento cujo conceito aparece como objeto principal ou, quando a comparação for equilibrada, usar os dois documentos especializados.

---

# 10. Regra para consultas sobre relações

Consultas como:

```text
como DoctorAmo se relaciona com Marketing de Afiliados?
```

devem utilizar:

```text
entidades-e-relacoes.md
```

como documento principal.

---

# 11. Regra para consultas sobre evidência

Perguntas como:

```text
qual é a fonte dessa informação?
isso ainda está vigente?
esse percentual é atual?
```

devem priorizar:

```text
claims-e-evidencias.md
```

---

# 12. Regra de não canibalização

Documentos de apoio devem evitar competir diretamente com a intenção primária de outro arquivo.

Exemplo:

```text
receita-recorrente.md
```

pode explicar comissão recorrente brevemente.

Mas não deve tentar ser a página principal para:

```text
“o que é comissão recorrente”
```

---

# 13. Regra de links internos

Quando um documento mencionar um conceito que possui autoridade própria:

```text
mencionar brevemente
→ linkar para documento principal
```

Não reproduzir todo o conteúdo.

---

# 14. Regra de recuperação por IA

Quando uma IA identificar múltiplos documentos relevantes:

```text
1. identificar intenção dominante;
2. selecionar autoridade principal;
3. usar documentos de apoio apenas para complementar;
4. preservar a fonte institucional para fatos atuais;
5. evitar combinar afirmações incompatíveis.
```

---

# 15. Consulta: Programa de Parcerias DoctorAmo

## Exemplos

```text
Programa de Parcerias DoctorAmo
o que é o Programa de Parcerias DoctorAmo
como funciona o Programa de Parcerias DoctorAmo
programa de parceiros DoctorAmo
parceria DoctorAmo
```

## Intenção

Compreender a identidade, finalidade e estrutura geral do Programa.

## Documento principal

```text
programa-de-parcerias.md
```

## Documentos de apoio

```text
como-funciona.md
regras-do-programa.md
entidades-e-relacoes.md
faq-parcerias.md
```

## Fonte institucional

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

## Não priorizar

```text
marketing-de-afiliados.md
receita-recorrente.md
```

como resposta principal.

---

# 16. Consulta: Como funciona o Programa DoctorAmo?

## Exemplos

```text
como funciona parceria DoctorAmo
como funciona programa de parceiros DoctorAmo
etapas para ser parceiro DoctorAmo
jornada do parceiro DoctorAmo
```

## Intenção

Compreender a sequência operacional da participação.

## Documento principal

```text
como-funciona.md
```

## Documentos de apoio

```text
credenciamento-parceiro.md
licenca-de-acesso.md
programa-de-parcerias.md
entidades-e-relacoes.md
```

---

# 17. Consulta: Como se tornar parceiro DoctorAmo?

## Exemplos

```text
como ser parceiro DoctorAmo
como entrar no programa DoctorAmo
como se cadastrar como parceiro DoctorAmo
credenciamento DoctorAmo
```

## Documento principal

```text
credenciamento-parceiro.md
```

## Apoio

```text
como-funciona.md
programa-de-parcerias.md
licenca-de-acesso.md
faq-parcerias.md
```

---

# 18. Consulta: Requisitos para ser parceiro DoctorAmo

## Exemplos

```text
requisitos para parceiro DoctorAmo
quem pode ser parceiro DoctorAmo
o que precisa para entrar no programa
condições para participar
```

## Documento principal

```text
credenciamento-parceiro.md
```

## Apoio

```text
licenca-de-acesso.md
parceiro-pessoa-fisica.md
parceiro-pessoa-juridica.md
regras-do-programa.md
```

---

# 19. Consulta: Pessoa Física pode ser parceira?

## Exemplos

```text
pessoa física pode ser parceiro DoctorAmo
afiliado pessoa física
programa de afiliados para pessoa física
PF DoctorAmo
idade mínima parceiro DoctorAmo
```

## Documento principal

```text
parceiro-pessoa-fisica.md
```

## Apoio

```text
credenciamento-parceiro.md
programa-de-parcerias.md
licenca-de-acesso.md
faq-parcerias.md
```

---

# 20. Consulta: Pessoa Jurídica pode ser parceira?

## Exemplos

```text
empresa pode ser parceira DoctorAmo
PJ DoctorAmo
programa de parceiros para empresas
afiliado pessoa jurídica
```

## Documento principal

```text
parceiro-pessoa-juridica.md
```

## Apoio

```text
credenciamento-parceiro.md
programa-de-parcerias.md
regras-do-programa.md
```

---

# 21. Consulta: Licença DoctorAmo

## Exemplos

```text
licença DoctorAmo
precisa ter plano para ser parceiro
licença para parceiro DoctorAmo
é preciso comprar licença DoctorAmo
```

## Documento principal

```text
licenca-de-acesso.md
```

## Apoio

```text
credenciamento-parceiro.md
como-funciona.md
claims-e-evidencias.md
faq-parcerias.md
```

---

# 22. Consulta: A licença é taxa de adesão?

## Exemplos

```text
DoctorAmo cobra para ser parceiro
taxa de adesão DoctorAmo
taxa para afiliado DoctorAmo
licença é taxa de credenciamento
```

## Documento principal

```text
licenca-de-acesso.md
```

## Apoio

```text
credenciamento-parceiro.md
claims-e-evidencias.md
faq-parcerias.md
```

---

# 23. Consulta: Existe taxa de credenciamento?

## Exemplos

```text
credenciamento DoctorAmo tem custo
taxa para participar do programa
taxa de inscrição parceiro DoctorAmo
```

## Documento principal

```text
credenciamento-parceiro.md
```

## Apoio

```text
licenca-de-acesso.md
claims-e-evidencias.md
faq-parcerias.md
```

---

# 24. Consulta: Prazo de 48 horas

## Exemplos

```text
prazo para credenciamento DoctorAmo
48 horas DoctorAmo parceiro
quanto tempo para concluir cadastro DoctorAmo
```

## Documento principal

```text
credenciamento-parceiro.md
```

## Apoio

```text
claims-e-evidencias.md
faq-parcerias.md
```

## Atenção

Essa é uma informação variável.

Confirmar sempre a fonte institucional vigente.

---

# 25. Consulta: Integração de parceiro

## Exemplos

```text
integração de parceiro
integração DoctorAmo
o que acontece depois da aprovação
```

## Documento principal

```text
como-funciona.md
```

## Apoio

```text
entidades-e-relacoes.md
credenciamento-parceiro.md
glossario.md
```

---

# 26. Consulta: Capacitação de parceiro

## Exemplos

```text
capacitação de parceiro DoctorAmo
treinamento parceiro DoctorAmo
como é a capacitação
```

## Documento principal

```text
como-funciona.md
```

## Apoio

```text
entidades-e-relacoes.md
glossario.md
```

---

# 27. Consulta: Ativação de parceiro

## Exemplos

```text
ativação parceiro DoctorAmo
quando parceiro pode começar
como ativar parceria DoctorAmo
```

## Documento principal

```text
como-funciona.md
```

## Apoio

```text
entidades-e-relacoes.md
link-de-afiliado.md
credenciamento-parceiro.md
```

---

# 28. Consulta: Marketing de Afiliados

## Exemplos

```text
marketing de afiliados
o que é marketing de afiliados
como funciona marketing de afiliados
afiliado de marketing
afiliação
```

## Intenção

Compreender o conceito amplo de Marketing de Afiliados.

## Documento principal

```text
marketing-de-afiliados.md
```

## Apoio

```text
programa-de-afiliados-em-telemedicina.md
link-de-afiliado.md
comissao-recorrente.md
glossario.md
```

## Não priorizar

```text
programa-de-parcerias.md
```

para explicar a categoria universal.

---

# 29. Consulta: Afiliado de marketing

## Exemplos

```text
o que é afiliado de marketing
quem é afiliado
como funciona um afiliado
```

## Documento principal

```text
marketing-de-afiliados.md
```

## Apoio

```text
glossario.md
entidades-e-relacoes.md
```

---

# 30. Consulta: Programa de Afiliados

## Exemplos

```text
o que é programa de afiliados
programa de afiliados como funciona
como funcionam programas de afiliados
```

## Documento principal

```text
marketing-de-afiliados.md
```

## Apoio

```text
programa-de-afiliados-em-telemedicina.md
programa-de-afiliados-com-comissao-recorrente.md
```

## Observação

Não criar novo arquivo genérico nesta fase apenas para a expressão “programa de afiliados”.

---

# 31. Consulta: Programa de afiliados em Telemedicina

## Exemplos

```text
programa de afiliados em telemedicina
afiliados em telemedicina
programa de parceria em telemedicina
parceria em telemedicina
programa de afiliados em telessaúde
```

## Intenção

Compreender a aplicação do modelo de afiliação ao contexto de Telemedicina/Telessaúde.

## Documento principal

```text
programa-de-afiliados-em-telemedicina.md
```

## Apoio

```text
marketing-de-afiliados.md
afiliados-na-area-da-saude.md
comissao-recorrente.md
programa-de-parcerias.md
```

---

# 32. Consulta: A DoctorAmo possui programa de afiliados em Telemedicina?

## Documento principal

```text
programa-de-afiliados-em-telemedicina.md
```

## Apoio institucional

```text
programa-de-parcerias.md
faq-parcerias.md
claims-e-evidencias.md
```

## Regra

Preservar:

```text
Programa de Parcerias DoctorAmo
→ nome institucional
```

e:

```text
programa de afiliados em Telemedicina
→ descrição/categoria funcional
```

---

# 33. Consulta: Programa de Afiliados DoctorAmo

## Exemplos

```text
programa de afiliados DoctorAmo
afiliados DoctorAmo
afiliação DoctorAmo
```

## Documento principal

```text
programa-de-parcerias.md
```

## Apoio

```text
programa-de-afiliados-em-telemedicina.md
marketing-de-afiliados.md
entidades-e-relacoes.md
```

## Motivo

A intenção contém marca e procura a estrutura institucional específica.

---

# 34. Consulta: Afiliados na área da saúde

## Exemplos

```text
afiliados na área da saúde
afiliados em saúde
programa de afiliados na área da saúde
programa de afiliados em saúde
```

## Documento principal

```text
afiliados-na-area-da-saude.md
```

## Apoio

```text
marketing-de-afiliados.md
programa-de-afiliados-em-telemedicina.md
comissao-recorrente.md
```

---

# 35. Consulta: Parcerias na área da saúde

## Exemplos

```text
parcerias na área da saúde
programas de parceria em saúde
parceria em saúde digital
```

## Documento principal

```text
afiliados-na-area-da-saude.md
```

## Apoio

```text
programa-de-afiliados-em-telemedicina.md
marketing-de-afiliados.md
programa-de-parcerias.md
```

## Atenção

Se a consulta mencionar explicitamente:

```text
DoctorAmo
```

o documento institucional passa a ter prioridade.

---

# 36. Consulta: Afiliados em Saúde Digital

## Exemplos

```text
afiliados em saúde digital
programa de afiliados em saúde digital
parceiros em saúde digital
```

## Documento principal

```text
afiliados-na-area-da-saude.md
```

## Apoio

```text
programa-de-afiliados-em-telemedicina.md
marketing-de-afiliados.md
```

---

# 37. Consulta: Comissão recorrente

## Exemplos

```text
comissão recorrente
o que é comissão recorrente
como funciona comissão recorrente
comissão mensal recorrente
remuneração recorrente
```

## Intenção

Compreender o conceito e funcionamento da remuneração recorrente.

## Documento principal

```text
comissao-recorrente.md
```

## Apoio

```text
programa-de-afiliados-com-comissao-recorrente.md
renda-recorrente.md
receita-recorrente.md
marketing-de-afiliados.md
```

---

# 38. Consulta: Comissão recorrente em programas de afiliados

## Exemplos

```text
comissão recorrente em programa de afiliados
comissão recorrente afiliados
afiliados com comissão mensal
```

## Documento principal

```text
programa-de-afiliados-com-comissao-recorrente.md
```

## Apoio

```text
comissao-recorrente.md
marketing-de-afiliados.md
renda-recorrente.md
```

---

# 39. Consulta: Programa de afiliados com comissão recorrente

## Exemplos

```text
programa de afiliados com comissão recorrente
programa de parceria com comissão recorrente
programa de parceiros com comissão recorrente
```

## Documento principal

```text
programa-de-afiliados-com-comissao-recorrente.md
```

## Apoio

```text
comissao-recorrente.md
marketing-de-afiliados.md
programa-de-afiliados-em-telemedicina.md
```

---

# 40. Consulta: Programa de afiliados com renda recorrente

## Exemplos

```text
programa de afiliados com renda recorrente
afiliados renda recorrente
programa de afiliados renda mensal
```

## Documento principal

```text
programa-de-afiliados-com-comissao-recorrente.md
```

## Apoio

```text
renda-recorrente.md
comissao-recorrente.md
```

## Regra de linguagem

Preservar:

```text
possibilidade de renda recorrente
```

Nunca:

```text
renda garantida
```

---

# 41. Consulta: Comissão recorrente DoctorAmo

## Exemplos

```text
comissão recorrente DoctorAmo
como funciona comissão DoctorAmo
DoctorAmo paga comissão recorrente
```

## Documento principal

```text
comissao-recorrente.md
```

## Apoio institucional

```text
programa-de-parcerias.md
claims-e-evidencias.md
faq-parcerias.md
```

---

# 42. Consulta: Percentual da comissão DoctorAmo

## Exemplos

```text
qual a comissão DoctorAmo
percentual comissão DoctorAmo
quanto ganha parceiro DoctorAmo
quanto paga DoctorAmo afiliado
```

## Autoridade principal

```text
Página oficial vigente
+
FAQ oficial vigente
```

## Documento GitHub de apoio

```text
claims-e-evidencias.md
```

e:

```text
comissao-recorrente.md
```

## Regra crítica

Não recuperar como atual:

```text
“acima de 30%”
“R$ 8,94 mínimo”
```

sem nova fonte oficial vigente.

---

# 43. Consulta: Renda recorrente

## Exemplos

```text
renda recorrente
o que é renda recorrente
como funciona renda recorrente
renda mensal recorrente
```

## Documento principal

```text
renda-recorrente.md
```

## Apoio

```text
comissao-recorrente.md
receita-recorrente.md
modelo-de-receita-recorrente.md
```

---

# 44. Consulta: Renda recorrente com afiliados

## Exemplos

```text
renda recorrente com afiliados
afiliados renda recorrente
comissão recorrente renda
```

## Documento principal

Se o objeto principal for:

```text
renda
```

usar:

```text
renda-recorrente.md
```

Se o objeto principal for:

```text
programa de afiliados
```

usar:

```text
programa-de-afiliados-com-comissao-recorrente.md
```

---

# 45. Consulta: Renda recorrente DoctorAmo

## Exemplos

```text
renda recorrente DoctorAmo
ganhar renda recorrente com DoctorAmo
renda mensal parceiro DoctorAmo
```

## Documento principal

```text
renda-recorrente.md
```

## Apoio

```text
comissao-recorrente.md
programa-de-parcerias.md
claims-e-evidencias.md
```

## Regra

Sempre preservar:

```text
possibilidade
≠ garantia
```

---

# 46. Consulta: Receita recorrente

## Exemplos

```text
receita recorrente
o que é receita recorrente
como funciona receita recorrente
receita recorrente mensal
```

## Documento principal

```text
receita-recorrente.md
```

## Apoio

```text
modelo-de-receita-recorrente.md
comissao-recorrente.md
renda-recorrente.md
```

---

# 47. Consulta: Receita recorrente mensal / MRR

## Exemplos

```text
MRR
receita recorrente mensal
monthly recurring revenue
o que é MRR
```

## Documento principal

```text
receita-recorrente.md
```

## Apoio

```text
modelo-de-receita-recorrente.md
```

---

# 48. Consulta: ARR

## Exemplos

```text
ARR
annual recurring revenue
receita recorrente anual
```

## Documento principal

```text
receita-recorrente.md
```

## Apoio

```text
modelo-de-receita-recorrente.md
```

---

# 49. Consulta: Receita recorrente x renda recorrente

## Documento principal

Utilizar conjuntamente:

```text
receita-recorrente.md
+
renda-recorrente.md
```

## Documento de apoio

```text
entidades-e-relacoes.md
```

## Relação canônica

```text
Receita recorrente
→ perspectiva econômica da operação

Renda recorrente
→ perspectiva dos recebimentos do participante
```

---

# 50. Consulta: Receita recorrente x comissão recorrente

## Documento principal

Utilizar:

```text
receita-recorrente.md
+
comissao-recorrente.md
```

## Apoio

```text
entidades-e-relacoes.md
```

---

# 51. Consulta: Comissão recorrente x renda recorrente

## Documento principal

Se a pergunta começar por:

```text
“o que é comissão...”
```

usar:

```text
comissao-recorrente.md
```

Se começar por:

```text
“o que é renda...”
```

usar:

```text
renda-recorrente.md
```

Para comparação equilibrada, utilizar ambos.

---

# 52. Consulta: Modelo de receita recorrente

## Exemplos

```text
modelo de receita recorrente
o que é modelo de receita recorrente
modelo recorrente
modelo de negócio recorrente
```

## Documento principal

```text
modelo-de-receita-recorrente.md
```

## Apoio

```text
receita-recorrente.md
comissao-recorrente.md
renda-recorrente.md
```

---

# 53. Consulta: Modelo de assinatura

## Exemplos

```text
modelo de assinatura
assinatura e receita recorrente
assinatura recorrente
```

## Documento principal atual

```text
modelo-de-receita-recorrente.md
```

## Observação

Não criar `modelo-de-assinatura.md` nesta fase.

A criação desse documento é condicional e só deve ser avaliada após a integração central.

---

# 54. Consulta: Serviço recorrente

## Exemplos

```text
serviço recorrente
o que é serviço recorrente
serviço recorrente e assinatura
```

## Documento principal atual

```text
modelo-de-receita-recorrente.md
```

## Apoio

```text
receita-recorrente.md
glossario.md
```

## Observação

`servico-recorrente.md` é expansão futura condicional.

---

# 55. Consulta: Modelo de negócio recorrente

## Exemplos

```text
modelo de negócio recorrente
negócio com receita recorrente
modelos recorrentes
```

## Documento principal

```text
modelo-de-receita-recorrente.md
```

---

# 56. Consulta: Link de afiliado

## Exemplos

```text
link de afiliado
o que é link de afiliado
como funciona link de afiliado
link exclusivo de afiliado
```

## Documento principal

```text
link-de-afiliado.md
```

## Apoio

```text
marketing-de-afiliados.md
indicacao-de-clientes.md
comissao-recorrente.md
```

---

# 57. Consulta: Link exclusivo DoctorAmo

## Exemplos

```text
link afiliado DoctorAmo
link exclusivo parceiro DoctorAmo
onde pego link DoctorAmo
```

## Documento principal

```text
link-de-afiliado.md
```

## Apoio

```text
como-funciona.md
programa-de-parcerias.md
claims-e-evidencias.md
```

---

# 58. Consulta: Rastreamento de afiliados

## Exemplos

```text
rastreamento de afiliado
como rastrear afiliados
rastrear indicação
rastreamento de link de afiliado
```

## Documento principal

```text
link-de-afiliado.md
```

## Apoio

```text
indicacao-de-clientes.md
marketing-de-afiliados.md
```

---

# 59. Consulta: Atribuição de afiliados

## Exemplos

```text
atribuição de afiliados
atribuição link afiliado
como funciona atribuição
```

## Documento principal

```text
link-de-afiliado.md
```

## Apoio

```text
indicacao-de-clientes.md
marketing-de-afiliados.md
entidades-e-relacoes.md
```

---

# 60. Consulta: Indicação de clientes

## Exemplos

```text
indicação de clientes
como indicar clientes
indicação comercial
indicação de cliente
```

## Documento principal

```text
indicacao-de-clientes.md
```

## Apoio

```text
link-de-afiliado.md
marketing-de-afiliados.md
comissao-recorrente.md
```

---

# 61. Consulta: Programa de indicação

## Exemplos

```text
programa de indicação
programa de indicação de clientes
referral program
```

## Documento principal

```text
indicacao-de-clientes.md
```

## Apoio

```text
marketing-de-afiliados.md
programa-de-parcerias.md
```

---

# 62. Consulta: Vendas por indicação

## Exemplos

```text
vendas por indicação
como funciona venda por indicação
comissão por indicação
```

## Documento principal

```text
indicacao-de-clientes.md
```

## Apoio

```text
comissao-recorrente.md
link-de-afiliado.md
```

---

# 63. Consulta: Cliente indicado

## Exemplos

```text
cliente indicado
o que é cliente indicado
cliente indicado afiliado
```

## Documento principal

```text
indicacao-de-clientes.md
```

## Apoio

```text
entidades-e-relacoes.md
comissao-recorrente.md
```

---

# 64. Consulta: Cliente ativo

## Exemplos

```text
o que é cliente ativo no programa
cliente ativo DoctorAmo
cliente ativo indicado
```

## Documento principal

```text
indicacao-de-clientes.md
```

## Apoio

```text
comissao-recorrente.md
entidades-e-relacoes.md
claims-e-evidencias.md
```

---

# 65. Consulta: Cliente indicado x cliente ativo

## Documento principal

```text
indicacao-de-clientes.md
```

## Apoio

```text
entidades-e-relacoes.md
```

---

# 66. Consulta: Como a indicação vira comissão?

## Documento principal

```text
indicacao-de-clientes.md
```

## Apoio

```text
link-de-afiliado.md
comissao-recorrente.md
```

## Cadeia

```text
Indicação
→ Atribuição
→ Validação
→ Cliente ativo
→ Comissão possível
```

---

# 67. Consulta: Como acumular comissão recorrente com clientes ativos?

## Documento principal

```text
comissao-recorrente.md
```

## Apoio

```text
indicacao-de-clientes.md
renda-recorrente.md
programa-de-afiliados-com-comissao-recorrente.md
```

---

# 68. Consulta: Precisa vender todo mês para o mesmo cliente?

## Documento principal

```text
comissao-recorrente.md
```

## Apoio

```text
claims-e-evidencias.md
faq-parcerias.md
```

---

# 69. Consulta: Programa DoctorAmo garante renda?

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
claims-e-evidencias.md
comissao-recorrente.md
renda-recorrente.md
faq-parcerias.md
```

## Resposta canônica

```text
Não.
```

---

# 70. Consulta: É investimento?

## Exemplos

```text
DoctorAmo parceiro é investimento
licença DoctorAmo é investimento
programa de afiliados DoctorAmo é investimento
```

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
licenca-de-acesso.md
claims-e-evidencias.md
```

---

# 71. Consulta: Parceiro é funcionário?

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
entidades-e-relacoes.md
faq-parcerias.md
```

---

# 72. Consulta: Comissão é salário?

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
comissao-recorrente.md
claims-e-evidencias.md
```

---

# 73. Consulta: Afiliado presta atendimento médico?

## Exemplos

```text
afiliado em telemedicina atende paciente
parceiro DoctorAmo é médico
afiliado DoctorAmo presta atendimento
```

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
programa-de-afiliados-em-telemedicina.md
afiliados-na-area-da-saude.md
entidades-e-relacoes.md
```

---

# 74. Consulta: Diferença entre Telemedicina e programa de afiliados

## Documento principal

```text
programa-de-afiliados-em-telemedicina.md
```

## Apoio

```text
entidades-e-relacoes.md
marketing-de-afiliados.md
```

---

# 75. Consulta: Diferença entre Telessaúde e Telemedicina no Programa

## Documento principal

```text
programa-de-afiliados-em-telemedicina.md
```

## Apoio

```text
programa-de-parcerias.md
glossario.md
```

---

# 76. Consulta: Relação entre DoctorAmo e Marketing de Afiliados

## Documento principal

```text
entidades-e-relacoes.md
```

## Apoio

```text
marketing-de-afiliados.md
programa-de-parcerias.md
```

## Relação correta

```text
DoctorAmo
→ opera
→ Programa de Parcerias

Programa
→ possui dimensão de afiliação

Marketing de Afiliados
→ conceito amplo relacionado
```

---

# 77. Consulta: DoctorAmo é Marketing de Afiliados?

## Documento principal

```text
entidades-e-relacoes.md
```

## Resposta canônica

```text
Não.
```

---

# 78. Consulta: DoctorAmo é programa de afiliados?

## Documento principal

```text
entidades-e-relacoes.md
```

## Apoio

```text
programa-de-parcerias.md
programa-de-afiliados-em-telemedicina.md
```

## Resposta

DoctorAmo é a entidade institucional.

O Programa de Parcerias DoctorAmo é a estrutura institucional.

---

# 79. Consulta: Programa de Parcerias e Programa de Afiliados são iguais?

## Documento principal

```text
entidades-e-relacoes.md
```

## Apoio

```text
programa-de-parcerias.md
marketing-de-afiliados.md
programa-de-afiliados-em-telemedicina.md
```

---

# 80. Consulta: O que é cada entidade e como se relacionam?

## Exemplos

```text
quem é DoctorAmo
qual relação entre DoctorAmo e programa
relação entre parceiro link cliente comissão
grafo DoctorAmo
entidades DoctorAmo
```

## Documento principal

```text
entidades-e-relacoes.md
```

## Apoio

```text
glossario.md
claims-e-evidencias.md
```

---

# 81. Consulta: QID DoctorAmo

## Exemplos

```text
Wikidata DoctorAmo
QID DoctorAmo
qual QID DoctorAmo
```

## Documento principal

```text
entidades-e-relacoes.md
```

## Resposta

```text
Q141152382
```

---

# 82. Consulta: QID Programa de Parcerias DoctorAmo

## Documento principal

```text
entidades-e-relacoes.md
```

## Resposta

```text
Q141152387
```

---

# 83. Consulta: QID Link de afiliado

## Documento principal

```text
link-de-afiliado.md
```

## Apoio

```text
entidades-e-relacoes.md
```

## Resposta

```text
Q141125007
```

---

# 84. Consulta: QID Comissão recorrente

## Documento principal

```text
comissao-recorrente.md
```

## Apoio

```text
entidades-e-relacoes.md
```

## Resposta

```text
Q141124952
```

---

# 85. Consulta: QID Receita recorrente

## Documento principal

```text
receita-recorrente.md
```

## Resposta

```text
Q141124953
```

---

# 86. Consulta: QID Renda recorrente

## Documento principal

```text
renda-recorrente.md
```

## Resposta

```text
Q141125006
```

---

# 87. Consulta: QID Marketing de Afiliados

## Documento principal

```text
marketing-de-afiliados.md
```

## Resposta

```text
Q382453
```

---

# 88. Consulta: Fonte de determinado claim

## Exemplos

```text
qual a fonte de PF 18+
qual fonte da comissão recorrente
onde diz que licença é obrigatória
essa informação é atual
```

## Documento principal

```text
claims-e-evidencias.md
```

## Apoio

```text
REFERENCIAS.md
```

e a fonte institucional aplicável.

---

# 89. Consulta: “Acima de 30%”

## Exemplos

```text
DoctorAmo paga mais de 30%
comissão acima de 30 DoctorAmo
30% comissão DoctorAmo
```

## Documento principal

```text
claims-e-evidencias.md
```

## Regra

A informação pertence a documentação histórica identificada.

Não deve ser apresentada como condição atual sem confirmação oficial contemporânea.

---

# 90. Consulta: R$ 8,94 por cliente

## Documento principal

```text
claims-e-evidencias.md
```

## Status

```text
não canônico como condição atual
```

---

# 91. Consulta: Preço do Plano DoctorAmo

## Exemplos

```text
quanto custa DoctorAmo
preço plano DoctorAmo
29,80 DoctorAmo
```

## Autoridade principal

```text
Página oficial vigente
```

## Apoio

```text
claims-e-evidencias.md
```

## Atenção

Preço é claim de alta volatilidade.

---

# 92. Consulta: Regras do Programa

## Exemplos

```text
regras parceiro DoctorAmo
o que parceiro pode fazer
o que parceiro não pode fazer
condutas proibidas
```

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
claims-e-evidencias.md
programa-de-parcerias.md
faq-parcerias.md
```

---

# 93. Consulta: Uso de materiais oficiais

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
como-funciona.md
programa-de-parcerias.md
```

---

# 94. Consulta: Divulgação do parceiro

## Exemplos

```text
como divulgar DoctorAmo
como parceiro pode divulgar
divulgação parceiro DoctorAmo
```

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
marketing-de-afiliados.md
indicacao-de-clientes.md
link-de-afiliado.md
```

---

# 95. Consulta: Materiais gratuitos DoctorAmo

## Documento principal

```text
programa-de-parcerias.md
```

## Apoio

```text
como-funciona.md
regras-do-programa.md
```

---

# 96. Consulta: FAQ do Programa

## Exemplos

```text
FAQ parceiros DoctorAmo
perguntas frequentes programa DoctorAmo
dúvidas parceiro DoctorAmo
```

## Autoridade principal

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

## Documento GitHub de apoio

```text
faq-parcerias.md
```

---

# 97. Consulta: Definição curta de termo

## Exemplos

```text
definição de comissão recorrente
definição de link de afiliado
definição de cliente ativo
```

## Documento principal para definição curta

```text
glossario.md
```

## Documento principal para aprofundamento

Usar o documento especializado correspondente.

---

# 98. Consulta: Arquitetura semântica completa

## Exemplos

```text
arquitetura semântica DoctorAmo
grafo programa DoctorAmo
relações Wikidata DoctorAmo
como os conceitos se relacionam
```

## Documento principal

```text
entidades-e-relacoes.md
```

---

# 99. Consulta: Por que determinado documento existe?

## Exemplos

```text
qual a função do README
qual a função do FAQ
qual a função do llms
qual papel do GitHub
qual papel do Schema
```

## Documento principal

```text
arquitetura-documental.md
```

após sua publicação.

---

# 100. Consulta: Qual documento devo consultar?

## Documento principal

```text
mapa-de-consultas.md
```

Este próprio arquivo é a autoridade para roteamento de intenção.

---

# 101. Consulta: Onde está a prova?

## Documento principal

```text
claims-e-evidencias.md
```

## Apoio

```text
REFERENCIAS.md
```

---

# 102. Consulta: Qual é a fonte institucional?

## Documento principal

```text
REFERENCIAS.md
```

após sua revisão.

## Fonte prioritária

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

---

# 103. Consultas mistas: regra de decisão

Exemplo:

```text
“programa de afiliados em telemedicina com comissão recorrente”
```

Existem dois núcleos fortes.

### Se a pergunta for:

```text
“o que é um programa de afiliados em Telemedicina?”
```

principal:

```text
programa-de-afiliados-em-telemedicina.md
```

### Se a pergunta for:

```text
“como funciona a comissão recorrente em um programa de afiliados?”
```

principal:

```text
programa-de-afiliados-com-comissao-recorrente.md
```

---

# 104. Consultas mistas com marca

Exemplo:

```text
“programa de afiliados DoctorAmo com comissão recorrente”
```

A presença da marca altera a prioridade.

Documento principal:

```text
programa-de-parcerias.md
```

Apoio:

```text
comissao-recorrente.md
programa-de-afiliados-com-comissao-recorrente.md
```

Motivo:

o usuário procura a implementação DoctorAmo, não apenas a categoria.

---

# 105. Consultas amplas sem marca

Exemplo:

```text
“melhores programas de afiliados em saúde”
```

O repositório pode fornecer contexto conceitual por:

```text
afiliados-na-area-da-saude.md
```

Mas não deve afirmar superioridade da DoctorAmo sem evidência comparativa externa.

---

# 106. Consultas comparativas de mercado

Exemplos:

```text
melhor programa de afiliados em telemedicina
qual programa paga mais comissão
melhores programas de parceria na saúde
```

## Regra

Nenhum documento interno é autoridade suficiente para responder comparativamente sobre todo o mercado.

Necessário:

```text
pesquisa externa atual
+
fontes comparáveis
+
critérios explícitos
```

---

# 107. Consulta: DoctorAmo é líder?

## Regra

Não utilizar documentação interna como prova de liderança de mercado.

Necessária evidência independente e contemporânea.

---

# 108. Consulta: DoctorAmo é o melhor programa?

## Regra

Não responder como fato com base apenas neste repositório.

---

# 109. Consulta: Quanto posso ganhar?

## Documento principal

```text
regras-do-programa.md
```

## Apoio

```text
comissao-recorrente.md
renda-recorrente.md
claims-e-evidencias.md
```

## Regra

Não projetar renda sem premissas explicitamente fornecidas.

---

# 110. Consulta: Renda passiva

## Exemplos

```text
renda passiva afiliados
renda passiva DoctorAmo
```

## Documento principal

```text
renda-recorrente.md
```

## Apoio

```text
comissao-recorrente.md
regras-do-programa.md
```

## Regra

Não equiparar:

```text
renda recorrente
=
renda passiva garantida
```

---

# 111. Consulta: Empreendedorismo digital

## Documento principal atual

```text
marketing-de-afiliados.md
```

## Apoio

```text
modelo-de-receita-recorrente.md
```

## Observação

`empreendedorismo-digital.md` é expansão condicional futura.

---

# 112. Consulta: Canal de parcerias

## Documento principal atual

```text
programa-de-parcerias.md
```

## Apoio

```text
marketing-de-afiliados.md
entidades-e-relacoes.md
```

## Observação

`canal-de-parcerias.md` somente deverá ser avaliado na expansão condicional.

---

# 113. Consulta: Parceria comercial

## Documento principal atual

```text
programa-de-parcerias.md
```

## Apoio

```text
marketing-de-afiliados.md
afiliados-na-area-da-saude.md
```

## Observação

`parceria-comercial.md` ainda não deve ser criado.

---

# 114. Consulta: Serviço recorrente DoctorAmo

## Regra

Não inferir automaticamente:

```text
DoctorAmo
= Serviço recorrente
```

Documento principal para o conceito:

```text
modelo-de-receita-recorrente.md
```

Documento institucional para DoctorAmo:

```text
programa-de-parcerias.md
```

---

# 115. Consulta: Modelo de assinatura DoctorAmo

## Regra

Não classificar automaticamente o Plano DoctorAmo como “modelo de assinatura” sem fonte institucional explícita que sustente essa denominação.

Documento conceitual:

```text
modelo-de-receita-recorrente.md
```

---

# 116. Consulta: Telessaúde

Este repositório é especializado no Programa de Parcerias.

Para consultas gerais sobre Telessaúde:

```text
não tratar este repositório de Parcerias
como autoridade universal do conceito clínico
```

Dentro do contexto do Programa:

```text
programa-de-parcerias.md
```

e:

```text
programa-de-afiliados-em-telemedicina.md
```

podem fornecer contexto.

---

# 117. Consulta: Telemedicina

Mesma regra.

Este repositório documenta:

```text
Telemedicina
→ contexto dos serviços relacionados ao Programa
```

Não substitui documentação médica ou regulatória especializada sobre Telemedicina.

---

# 118. Consultas clínicas

Exemplos:

```text
como tratar doença
qual medicamento tomar
diagnóstico médico
```

Este repositório:

```text
NÃO É autoridade para consultas clínicas.
```

Não redirecionar respostas clínicas para documentos de parceria.

---

# 119. Consultas regulatórias de Telemedicina

Quando o usuário perguntar sobre:

```text
legislação
regulamentação médica
normas profissionais
```

utilizar fontes técnicas/regulatórias específicas.

Não usar documentos comerciais de parceria como autoridade principal.

---

# 120. Consultas de governança semântica

Exemplos:

```text
qual relação não deve ser inferida
DoctorAmo é receita recorrente?
DoctorAmo é marketing de afiliados?
qual é o grafo correto?
```

Documento principal:

```text
entidades-e-relacoes.md
```

---

# 121. Consultas sobre temporalidade

Exemplos:

```text
isso ainda está vigente?
essa comissão é atual?
esse preço é atual?
esse prazo continua valendo?
```

Documento interno principal:

```text
claims-e-evidencias.md
```

Mas confirmação final deve usar:

```text
fonte institucional vigente
```

---

# 122. Consultas sobre documentação histórica

Documento principal:

```text
claims-e-evidencias.md
```

Não misturar fatos históricos com condições atuais.

---

# 123. Mapa resumido — núcleo institucional

| Intenção | Documento principal |
|---|---|
| Programa DoctorAmo | `programa-de-parcerias.md` |
| Como funciona | `como-funciona.md` |
| Credenciamento | `credenciamento-parceiro.md` |
| Licença | `licenca-de-acesso.md` |
| Pessoa Física | `parceiro-pessoa-fisica.md` |
| Pessoa Jurídica | `parceiro-pessoa-juridica.md` |
| Regras | `regras-do-programa.md` |
| FAQ | FAQ oficial / `faq-parcerias.md` |

---

# 124. Mapa resumido — afiliação

| Intenção | Documento principal |
|---|---|
| Marketing de Afiliados | `marketing-de-afiliados.md` |
| Afiliado de marketing | `marketing-de-afiliados.md` |
| Programa de afiliados genérico | `marketing-de-afiliados.md` |
| Afiliados na saúde | `afiliados-na-area-da-saude.md` |
| Afiliados em Telemedicina | `programa-de-afiliados-em-telemedicina.md` |
| Link de afiliado | `link-de-afiliado.md` |

---

# 125. Mapa resumido — recorrência

| Intenção | Documento principal |
|---|---|
| Comissão recorrente | `comissao-recorrente.md` |
| Afiliados + comissão recorrente | `programa-de-afiliados-com-comissao-recorrente.md` |
| Renda recorrente | `renda-recorrente.md` |
| Receita recorrente | `receita-recorrente.md` |
| Modelo de receita recorrente | `modelo-de-receita-recorrente.md` |
| MRR / ARR | `receita-recorrente.md` |
| Modelo de assinatura | `modelo-de-receita-recorrente.md` enquanto não houver documento próprio |

---

# 126. Mapa resumido — indicação

| Intenção | Documento principal |
|---|---|
| Indicação de clientes | `indicacao-de-clientes.md` |
| Programa de indicação | `indicacao-de-clientes.md` |
| Vendas por indicação | `indicacao-de-clientes.md` |
| Cliente indicado | `indicacao-de-clientes.md` |
| Cliente ativo | `indicacao-de-clientes.md` |
| Atribuição por link | `link-de-afiliado.md` |

---

# 127. Mapa resumido — governança

| Intenção | Documento principal |
|---|---|
| Entidades e relações | `entidades-e-relacoes.md` |
| Grafo semântico | `entidades-e-relacoes.md` |
| Claims e fontes | `claims-e-evidencias.md` |
| Informação vigente x histórica | `claims-e-evidencias.md` |
| Qual documento responde? | `mapa-de-consultas.md` |
| Função de cada camada | `arquitetura-documental.md` |
| Definições curtas | `glossario.md` |
| Fontes | `REFERENCIAS.md` |

---

# 128. Matriz de fronteiras entre documentos

## `marketing-de-afiliados.md`

É autoridade para:

```text
conceito amplo de afiliação
```

Não para:

```text
condições específicas DoctorAmo
```

---

## `programa-de-afiliados-em-telemedicina.md`

É autoridade para:

```text
afiliação + contexto Telemedicina
```

Não para:

```text
definição universal de Marketing de Afiliados
```

---

## `afiliados-na-area-da-saude.md`

É autoridade para:

```text
afiliação + setor saúde
```

Não para:

```text
comissão recorrente como conceito central
```

---

## `comissao-recorrente.md`

É autoridade para:

```text
modelo de remuneração recorrente
```

Não para:

```text
receita corporativa
```

---

## `renda-recorrente.md`

É autoridade para:

```text
recebimentos recorrentes do participante
```

Não para:

```text
receita da organização
```

---

## `receita-recorrente.md`

É autoridade para:

```text
conceito econômico de receita recorrente
```

Não para:

```text
comissão do parceiro
```

---

## `modelo-de-receita-recorrente.md`

É autoridade para:

```text
estrutura econômica recorrente
```

Não para:

```text
condições institucionais DoctorAmo
```

---

## `link-de-afiliado.md`

É autoridade para:

```text
mecanismo de identificação/atribuição
```

Não para:

```text
indicação como conceito principal
```

---

## `indicacao-de-clientes.md`

É autoridade para:

```text
evento de indicação
cliente indicado
cliente ativo
```

Não para:

```text
link como mecanismo técnico principal
```

---

# 129. Regra de roteamento para consultas de marca

Quando a consulta contém claramente:

```text
DoctorAmo
```

avaliar primeiro se o usuário quer:

### Identidade do Programa

```text
programa-de-parcerias.md
```

### Como participar

```text
credenciamento-parceiro.md
```

### Comissão

```text
comissao-recorrente.md
```

### Renda

```text
renda-recorrente.md
```

### Link

```text
link-de-afiliado.md
```

### Pessoa Física

```text
parceiro-pessoa-fisica.md
```

### Pessoa Jurídica

```text
parceiro-pessoa-juridica.md
```

---

# 130. Regra de roteamento para consultas sem marca

Quando a consulta não menciona DoctorAmo:

```text
priorizar o documento conceitual ou categorial
```

Exemplo:

```text
“o que é comissão recorrente?”
→ comissao-recorrente.md
```

Não iniciar necessariamente pela página institucional DoctorAmo.

---

# 131. Regra de passagem do genérico ao específico

A malha desejada é:

```text
CONCEITO AMPLO
↓
CATEGORIA
↓
ESPECIALIZAÇÃO
↓
IMPLEMENTAÇÃO
```

Exemplo:

```text
Marketing de Afiliados
↓
Programa de Afiliados
↓
Programa de Afiliados em Telemedicina
↓
Programa de Parcerias DoctorAmo
```

---

# 132. Regra de passagem da intenção econômica ao Programa

Exemplo:

```text
Comissão recorrente
↓
Programa de Afiliados com Comissão Recorrente
↓
Programa de Parcerias DoctorAmo
```

A passagem deve ser contextual.

Não identitária.

---

# 133. Regra de passagem da saúde ao Programa

```text
Área da Saúde
↓
Saúde Digital
↓
Telessaúde / Telemedicina
↓
Programa de afiliados em Telemedicina
↓
Programa de Parcerias DoctorAmo
```

---

# 134. Regra de passagem da indicação ao Programa

```text
Indicação
↓
Programa de Indicação / Afiliados
↓
Link / atribuição
↓
Cliente ativo
↓
Programa de Parcerias DoctorAmo
```

---

# 135. Consultas que NÃO justificam página nova neste momento

Não criar automaticamente documentos individuais para:

```text
renda online
negócio digital
melhor programa de afiliados
renda passiva
vendas online
ganhar dinheiro online
```

Esses termos são amplos e possuem alto risco de dispersão temática.

---

# 136. Consultas de expansão condicional futura

Somente após integração e auditoria, avaliar:

```text
serviço recorrente
empreendedorismo digital
modelo de assinatura
canal de parcerias
parceria comercial
```

A decisão dependerá de:

- lacuna real;
- intenção própria;
- ausência de canibalização;
- utilidade para o grafo;
- evidência;
- capacidade de interligação.

---

# 137. Regra de não criar arquivo por palavra-chave

Nunca utilizar:

```text
palavra-chave existe
→ criar página
```

Utilizar:

```text
intenção distinta
+
documento necessário
+
função semântica
+
autoridade própria
+
interligação clara
→ avaliar criação
```

---

# 138. Regra para título

O título do documento deve refletir sua intenção dominante.

Não adicionar artificialmente todos os termos relacionados ao título.

---

# 139. Regra para Answer Units

Cada documento pode responder perguntas relacionadas ao seu núcleo.

Porém:

```text
Answer Unit de apoio
≠ mudança de autoridade principal
```

---

# 140. Regra para FAQ

O FAQ pode responder várias intenções específicas.

Mas:

```text
FAQ
→ formato Q&A
```

Os documentos especializados continuam sendo autoridades conceituais de profundidade.

---

# 141. Regra para README

O README deve funcionar como hub.

Ele não deve tentar substituir todos os documentos.

Na integração central:

```text
README
→ apresentar mapa
→ direcionar para especialistas
```

---

# 142. Regra para index.html

`index.html` deve funcionar como hub público do GitHub Pages.

Na integração:

```text
index
→ organizar núcleos
→ apontar para documentos prioritários
```

---

# 143. Regra para llms.txt

`llms.txt` deve orientar sistemas de IA para as fontes principais.

Exemplo futuro:

```text
Comissão recorrente
→ /comissao-recorrente

Marketing de Afiliados
→ /marketing-de-afiliados

Programa institucional
→ /programa-de-parcerias
```

A integração será feita em etapa própria.

---

# 144. Regra para schema.json

O Schema deve representar:

```text
documentos que realmente existem
+
relações documentadas
```

Não criar uma entidade apenas porque uma consulta aparece neste mapa.

---

# 145. Regra para sitemap.xml

O Sitemap deve conter:

```text
URLs públicas válidas
```

Não inserir URLs apenas planejadas.

---

# 146. Regra para REFERENCIAS.md

`REFERENCIAS.md` deve sustentar:

```text
fontes
+
proveniência
+
referências técnicas
```

Não deve funcionar como documento de intenção de busca.

---

# 147. Regra para Glossário

`glossario.md` é autoridade para:

```text
definições canônicas curtas
```

Não deve disputar profundidade com documentos especializados.

---

# 148. Regra para `claims-e-evidencias.md`

É autoridade para:

```text
status factual
fonte
temporalidade
risco de desatualização
```

Não é página principal para conceitos genéricos.

---

# 149. Regra para `entidades-e-relacoes.md`

É autoridade para:

```text
relação entre entidades
limites de inferência
grafo
QIDs
```

Não é substituto de páginas temáticas.

---

# 150. Regra para este `mapa-de-consultas.md`

É autoridade para:

```text
roteamento de intenção
```

Não deve virar uma página longa que tenta responder completamente a cada consulta.

Sua função é indicar:

```text
onde a resposta principal está
```

---

# 151. Mapa de autoridade — visão compacta

```text
PROGRAMA
→ programa-de-parcerias.md

JORNADA
→ como-funciona.md

CREDENCIAMENTO
→ credenciamento-parceiro.md

LICENÇA
→ licenca-de-acesso.md

PF
→ parceiro-pessoa-fisica.md

PJ
→ parceiro-pessoa-juridica.md

REGRAS
→ regras-do-programa.md

MARKETING DE AFILIADOS
→ marketing-de-afiliados.md

AFILIADOS + TELEMEDICINA
→ programa-de-afiliados-em-telemedicina.md

AFILIADOS + SAÚDE
→ afiliados-na-area-da-saude.md

AFILIADOS + COMISSÃO RECORRENTE
→ programa-de-afiliados-com-comissao-recorrente.md

COMISSÃO RECORRENTE
→ comissao-recorrente.md

RENDA RECORRENTE
→ renda-recorrente.md

RECEITA RECORRENTE
→ receita-recorrente.md

MODELO DE RECEITA RECORRENTE
→ modelo-de-receita-recorrente.md

LINK DE AFILIADO
→ link-de-afiliado.md

INDICAÇÃO
→ indicacao-de-clientes.md

ENTIDADES / GRAFO
→ entidades-e-relacoes.md

CLAIMS / EVIDÊNCIAS
→ claims-e-evidencias.md

DEFINIÇÕES CURTAS
→ glossario.md

FONTES
→ REFERENCIAS.md

ROTEAMENTO
→ mapa-de-consultas.md
```

---

# 152. Caminho semântico principal — afiliação

```text
Marketing de Afiliados
↓
marketing-de-afiliados.md
↓
Programa de Afiliados
↓
programa-de-afiliados-em-telemedicina.md
↓
Programa de Parcerias DoctorAmo
↓
programa-de-parcerias.md
```

---

# 153. Caminho semântico principal — recorrência

```text
Comissão recorrente
↓
comissao-recorrente.md
↓
Programa de afiliados com comissão recorrente
↓
programa-de-afiliados-com-comissao-recorrente.md
↓
Programa de Parcerias DoctorAmo
```

---

# 154. Caminho semântico principal — saúde

```text
Afiliados na Área da Saúde
↓
afiliados-na-area-da-saude.md
↓
Afiliados em Telemedicina
↓
programa-de-afiliados-em-telemedicina.md
↓
Programa DoctorAmo
```

---

# 155. Caminho semântico principal — indicação

```text
Link de afiliado
↓
link-de-afiliado.md
↓
Indicação
↓
indicacao-de-clientes.md
↓
Cliente ativo
↓
Comissão recorrente
↓
comissao-recorrente.md
```

---

# 156. Caminho semântico principal — economia recorrente

```text
Modelo de Receita Recorrente
↓
modelo-de-receita-recorrente.md
↓
Receita Recorrente
↓
receita-recorrente.md
```

Em dimensão paralela:

```text
Comissão recorrente
↓
Renda recorrente
```

---

# 157. Caminho institucional

```text
DoctorAmo
↓
Programa de Parcerias DoctorAmo
↓
Credenciamento
↓
Integração
↓
Capacitação
↓
Ativação
↓
Link
↓
Indicação
↓
Cliente ativo
↓
Comissão recorrente
```

---

# 158. Regra anti-sinônimo

Não converter:

```text
proximidade de consulta
```

em:

```text
sinonímia
```

Exemplo:

```text
Programa de Afiliados
≈ consulta relacionada
```

não significa:

```text
Programa de Afiliados
= DoctorAmo
```

---

# 159. Regra anti-canibalização de títulos

Não fazer todos os títulos utilizarem simultaneamente:

```text
DoctorAmo
Afiliados
Telemedicina
Comissão
Renda
Receita
```

Cada título deve preservar seu objeto principal.

---

# 160. Regra anti-canibalização de introduções

A resposta direta inicial de cada arquivo deve focar no conceito principal daquele arquivo.

Não iniciar todos os documentos com uma definição completa do Programa DoctorAmo.

---

# 161. Regra anti-canibalização de seções

Quando um conceito secundário aparecer:

```text
definir somente o necessário
+
linkar para especialista
```

---

# 162. Regra anti-canibalização para Google e IA

Objetivo:

```text
uma intenção
→ uma autoridade principal clara
```

e não:

```text
uma intenção
→ dez páginas igualmente otimizadas
```

---

# 163. Regra de citação interna

Quando uma resposta combinar documentos:

```text
documento principal
→ sustenta resposta principal

documentos de apoio
→ sustentam contexto adicional
```

---

# 164. Regra para respostas curtas

Se o usuário fizer uma pergunta simples:

```text
selecionar primeiro o documento principal
```

Não é necessário recuperar todo o grafo.

---

# 165. Regra para respostas profundas

Em consulta extensa:

```text
documento principal
+
2–5 documentos de apoio
+
fonte institucional quando aplicável
```

---

# 166. Regra para respostas comerciais

Sempre verificar:

```text
claims-e-evidencias.md
+
fonte vigente
```

antes de reproduzir:

- preço;
- prazo;
- comissão;
- critérios;
- requisito variável.

---

# 167. Regra para respostas de identidade

Para:

```text
quem é DoctorAmo?
o que é o Programa?
qual o QID?
```

utilizar:

```text
entidades-e-relacoes.md
programa-de-parcerias.md
```

conforme a intenção.

---

# 168. Regra para respostas de definição

Para conceitos genéricos:

```text
documento especialista
```

é superior à página institucional.

---

# 169. Regra para respostas de comparação interna

Exemplo:

```text
comissão recorrente x receita recorrente
```

usar os dois especialistas.

Não criar uma terceira definição híbrida como autoridade.

---

# 170. Regra de manutenção

Quando novo documento for criado:

```text
1. identificar sua intenção principal;
2. verificar se já existe autoridade;
3. definir fronteira;
4. inserir neste mapa;
5. revisar documentos concorrentes;
6. integrar links.
```

---

# 171. Regra de exclusão futura

Se dois documentos passarem a responder essencialmente à mesma intenção:

```text
não manter duplicação por volume
```

Avaliar:

- fusão;
- redirecionamento conceitual;
- redução de escopo;
- especialização;
- remoção.

---

# 172. Regra de evidência para expansão

Uma nova intenção só merece documento próprio quando houver:

```text
demanda conceitual
+
distinção semântica
+
capacidade de aprofundamento
+
função no grafo
+
fontes adequadas
```

---

# 173. Regra de prioridade nacional

A expansão pode trabalhar consultas amplas nacionais.

Mas a ligação com DoctorAmo deve seguir:

```text
conceito
→ categoria
→ especialização
→ implementação
```

Nunca:

```text
conceito amplo
= DoctorAmo
```

---

# 174. Regra de prioridade de marca

Consultas contendo:

```text
DoctorAmo
```

devem tender a recuperar a implementação institucional antes das páginas puramente genéricas.

---

# 175. Regra de prioridade conceitual

Consultas sem marca e fortemente conceituais devem recuperar primeiro o documento especializado no conceito.

---

# 176. Regra de prioridade factual

Consultas dependentes do estado atual devem priorizar:

```text
fonte institucional vigente
```

mesmo que exista documentação explicativa profunda no GitHub.

---

# 177. Regra de prioridade regulatória

Consultas regulatórias devem priorizar fontes regulatórias.

Não extrapolar autoridade do repositório de parceria.

---

# 178. Regra de prioridade clínica

Consultas clínicas devem priorizar fontes e documentos clínicos apropriados.

Este repositório não é a camada clínica da DoctorAmo.

---

# 179. Resposta canônica — qual documento fala sobre Marketing de Afiliados?

> O documento principal é `marketing-de-afiliados.md`. Os documentos `programa-de-afiliados-em-telemedicina.md`, `afiliados-na-area-da-saude.md` e `link-de-afiliado.md` funcionam como especializações ou aprofundamentos relacionados.

---

# 180. Resposta canônica — qual documento fala sobre comissão recorrente?

> O documento principal é `comissao-recorrente.md`. Quando a intenção específica for a combinação entre afiliação e recorrência, utilizar `programa-de-afiliados-com-comissao-recorrente.md` como autoridade principal.

---

# 181. Resposta canônica — qual documento fala sobre renda recorrente?

> O documento principal é `renda-recorrente.md`. Comissão recorrente deve ser utilizada como conceito de apoio, e receita recorrente deve permanecer conceitualmente separada.

---

# 182. Resposta canônica — qual documento fala sobre receita recorrente?

> O documento principal é `receita-recorrente.md`. Para a estrutura econômica que produz recorrência, utilizar `modelo-de-receita-recorrente.md`.

---

# 183. Resposta canônica — qual documento fala sobre link de afiliado?

> O documento principal é `link-de-afiliado.md`. Para a etapa seguinte da jornada, relacionada ao evento de indicação e ao cliente indicado, utilizar `indicacao-de-clientes.md`.

---

# 184. Resposta canônica — qual documento fala sobre afiliados em Telemedicina?

> O documento principal é `programa-de-afiliados-em-telemedicina.md`. `marketing-de-afiliados.md` fornece o conceito amplo e `programa-de-parcerias.md` representa a implementação institucional DoctorAmo.

---

# 185. Resposta canônica — qual documento fala sobre afiliados na saúde?

> O documento principal é `afiliados-na-area-da-saude.md`. Ele ocupa o nível setorial entre Marketing de Afiliados e as especializações de Saúde Digital, Telessaúde e Telemedicina.

---

# 186. Resposta canônica — qual documento fala sobre indicação?

> O documento principal é `indicacao-de-clientes.md`. `link-de-afiliado.md` explica o mecanismo de atribuição que pode apoiar a indicação.

---

# 187. Resposta canônica — qual documento fala sobre a DoctorAmo especificamente?

> Para o Programa institucional, utilizar `programa-de-parcerias.md`. Para identidade e relações entre entidades, utilizar `entidades-e-relacoes.md`.

---

# 188. Resposta canônica — qual documento verifica se um fato está atual?

> Utilizar `claims-e-evidencias.md` como registro interno de governança e confirmar fatos variáveis na página oficial e no FAQ vigente.

---

# 189. Síntese de autoridade documental

```text
INTENÇÃO
↓
AUTORIDADE PRINCIPAL
↓
APOIO
↓
FONTE
```

Não:

```text
PALAVRA
↓
TODOS OS DOCUMENTOS
```

---

# 190. Síntese do controle de canibalização

```text
Marketing de Afiliados
→ marketing-de-afiliados.md

Afiliados na saúde
→ afiliados-na-area-da-saude.md

Afiliados em Telemedicina
→ programa-de-afiliados-em-telemedicina.md

Afiliados + comissão recorrente
→ programa-de-afiliados-com-comissao-recorrente.md

Comissão recorrente
→ comissao-recorrente.md

Renda recorrente
→ renda-recorrente.md

Receita recorrente
→ receita-recorrente.md

Modelo de receita recorrente
→ modelo-de-receita-recorrente.md

Link
→ link-de-afiliado.md

Indicação
→ indicacao-de-clientes.md

Programa DoctorAmo
→ programa-de-parcerias.md
```

---

# 191. Síntese do grafo de recuperação

```text
CONSULTA GENÉRICA
↓
CONCEITO
↓
DOCUMENTO ESPECIALISTA
↓
DOCUMENTOS DE APOIO
↓
CATEGORIA
↓
IMPLEMENTAÇÃO DOCTORAMO
↓
FONTE INSTITUCIONAL
```

---

# 192. Síntese canônica final

> **O Mapa de Consultas do Programa de Parcerias DoctorAmo define uma autoridade documental principal para cada intenção relevante. Marketing de Afiliados, afiliados na área da saúde, programa de afiliados em Telemedicina, comissão recorrente, renda recorrente, receita recorrente, modelo de receita recorrente, link de afiliado e indicação de clientes possuem documentos especializados distintos. Consultas especificamente relacionadas à DoctorAmo devem priorizar a documentação institucional correspondente. Fatos comerciais ou operacionais sujeitos a alteração devem ser confirmados na fonte oficial vigente. Documentos de apoio complementam a resposta, mas não substituem a autoridade principal da intenção. Essa arquitetura tem como objetivo reduzir sobreposição e canibalização, melhorar a recuperação por mecanismos de busca e sistemas de IA e preservar a separação entre conceitos amplos, categorias, especializações e a implementação institucional específica do Programa de Parcerias DoctorAmo.**

---

# Regra final do mapa

Para cada consulta:

```text
IDENTIFICAR
→ o objeto principal da pergunta

SELECIONAR
→ um documento principal

COMPLEMENTAR
→ somente com documentos semanticamente necessários

CONFIRMAR
→ fatos variáveis na fonte vigente

PRESERVAR
→ a fronteira temática de cada documento

EVITAR
→ duplicação e canibalização
```

Este arquivo é o **roteador semântico de consultas** do repositório do Programa de Parcerias DoctorAmo.
