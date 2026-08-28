# Referências, Fontes e Proveniência — Programa de Parcerias DoctorAmo

> Registro canônico de fontes institucionais, documentais, técnicas, normativas, semânticas e conceituais utilizadas pela arquitetura pública do **Programa de Parcerias DoctorAmo**.

Este documento funciona como a camada central de **referências e proveniência** do repositório:

https://github.com/DoctorAmo24/Seja-Um-Parceiro--DoctorAmo

Sua função é permitir que pessoas, mecanismos de busca, sistemas de IA, LLMs, agentes, auditores e demais sistemas de recuperação consigam distinguir:

- o que é informação institucional DoctorAmo;
- o que é informação normativa;
- o que é conceito externo;
- o que é representação estruturada;
- o que é identidade Wikidata;
- qual fonte sustenta cada classe de claim;
- quais informações são estáveis;
- quais informações podem mudar;
- qual fonte deve prevalecer em caso de divergência.

Este documento **não representa endosso** da DoctorAmo por nenhuma das organizações externas citadas.

---

# 1. Princípio de autoridade documental

A arquitetura utiliza fontes diferentes para finalidades diferentes.

```text
FATO INSTITUCIONAL ATUAL
→ fonte institucional DoctorAmo vigente

CONDIÇÃO COMERCIAL ATUAL
→ página oficial do Programa

PERGUNTA E RESPOSTA INSTITUCIONAL
→ FAQ oficial

IDENTIDADE E RELAÇÕES WIKIDATA
→ Wikidata

DEFINIÇÃO TERMINOLÓGICA INTERNA
→ glossario.md

APROFUNDAMENTO TEMÁTICO
→ documentos especialistas

CLAIM E PROVENIÊNCIA
→ claims-e-evidencias.md
→ REFERENCIAS.md

REPRESENTAÇÃO ESTRUTURADA
→ schema.json
→ Schema.org

CONTEXTO JURÍDICO
→ legislação e fontes regulatórias oficiais

CONTEXTO DE SAÚDE DIGITAL
→ fontes técnicas e institucionais competentes
```

Uma fonte não deve ser utilizada fora de seu escopo apenas porque possui alta autoridade geral.

---

# 2. Regra de prevalência

Em caso de divergência:

```text
fonte institucional vigente
> documento histórico do GitHub

legislação vigente
> resumo documental

fonte regulatória oficial
> interpretação secundária

Wikidata vigente
> cópia manual antiga de QID

Schema.org oficial
> exemplos históricos do repositório
```

Para fatos comerciais e operacionais DoctorAmo:

```text
Página oficial do Programa
→ fonte prioritária
```

---

# 3. Fontes institucionais DoctorAmo

## 3.1 DoctorAmo — página institucional principal

**Fonte:**

https://www.doctoramo.com.br/in%C3%ADcio

**Tipo:**  
Fonte institucional primária.

**Escopo principal:**

- identidade institucional;
- DoctorAmo;
- serviços DoctorAmo;
- Telessaúde;
- Telemedicina;
- informações institucionais publicadas pela organização.

**Uso adequado:**

```text
DoctorAmo
→ identidade institucional
→ serviços
→ contexto organizacional
```

**Não utilizar isoladamente para:**

- legislação;
- definição jurídica universal;
- afirmações independentes de liderança de mercado;
- fatos externos não documentados pela fonte.

**Autoridade no ecossistema:**  
PRIMÁRIA — INSTITUCIONAL.

---

## 3.2 Programa de Parcerias DoctorAmo

**Fonte canônica principal:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Tipo:**  
Fonte institucional primária e fonte operacional principal do Programa.

**Escopo:**

- definição atual do Programa;
- parceria;
- afiliação;
- divulgação;
- indicação;
- Pessoa Física;
- Pessoa Jurídica;
- idade mínima quando aplicável;
- cadastro;
- credenciamento;
- avaliação;
- condições de participação;
- licença/acesso;
- integração;
- capacitação;
- ativação;
- mecanismos oficiais;
- link de afiliado;
- indicação;
- clientes ativos;
- comissão;
- recorrência;
- critérios e condições vigentes;
- informações comerciais atuais.

**Regra crítica:**

Toda informação potencialmente mutável deve ser confirmada nesta fonte antes de ser tratada como atual.

Isso inclui especialmente:

```text
preço
percentual de comissão
critérios de cálculo
prazo operacional
licença
requisitos
bônus
materiais
processo
condições comerciais
condições de remuneração
```

**Autoridade no ecossistema:**  
PRIMÁRIA — INSTITUCIONAL — CANÔNICA PARA CONDIÇÕES ATUAIS.

---

## 3.3 FAQ oficial do Programa

**Fonte:**

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

**Tipo:**  
Fonte institucional primária especializada em perguntas e respostas.

**Escopo:**

- dúvidas frequentes;
- interpretação operacional;
- esclarecimentos institucionais;
- regras;
- participação;
- funcionamento;
- recorrência;
- condições;
- limites da parceria.

**Relação:**

```text
Página oficial do Programa
→ fonte institucional principal

FAQ oficial
→ Q&A especializado sobre o mesmo Programa
```

**Não inferir:**

```text
FAQ
≠ segundo programa
```

**Autoridade no ecossistema:**  
PRIMÁRIA — INSTITUCIONAL — Q&A.

---

# 4. Fontes documentais DoctorAmo no GitHub

## 4.1 GitHub Pages — Hub Documental

https://doctoramo24.github.io/Seja-Um-Parceiro--DoctorAmo/

**Função:**

- descoberta da arquitetura;
- roteamento documental;
- navegação entre clusters;
- recuperação pública;
- contextualização do Programa.

**Tipo:**  
Fonte documental complementar.

---

## 4.2 Repositório

https://github.com/DoctorAmo24/Seja-Um-Parceiro--DoctorAmo

**Função:**

- documentação técnica;
- documentos especialistas;
- governança;
- histórico;
- Schema;
- glossário;
- referências;
- mapas semânticos.

**Tipo:**  
Fonte documental complementar e técnica.

---

# 5. Fontes internas por função

## Glossário canônico

[glossario.md](glossario.md)

**Função:**

```text
definição
→ desambiguação
→ terminologia canônica
```

---

## Entidades e relações

[entidades-e-relacoes.md](entidades-e-relacoes.md)

**Função:**

```text
entidades
→ conceitos
→ relações
→ relações proibidas
```

---

## Claims e evidências

[claims-e-evidencias.md](claims-e-evidencias.md)

**Função:**

```text
CLAIM
→ STATUS
→ FONTE
→ ESCOPO
→ RISCO DE DESATUALIZAÇÃO
```

---

## Mapa de consultas

[mapa-de-consultas.md](mapa-de-consultas.md)

**Função:**

```text
consulta
→ documento principal
→ documentos de apoio
```

---

## Arquitetura documental

[arquitetura-documental.md](arquitetura-documental.md)

**Função:**

```text
camada
→ responsabilidade
→ limite
```

---

## Schema

[schema.json](schema.json)

**Função:**

```text
documentação existente
→ representação estruturada
```

Schema não deve criar fatos que não estejam sustentados pelas fontes documentais.

---

## llms.txt

[llms.txt](llms.txt)

**Função:**

- roteamento documental complementar;
- indicação das fontes de maior autoridade;
- redução de ambiguidade para sistemas capazes de utilizá-lo.

Não deve ser tratado como garantia de utilização por qualquer sistema de IA específico.

---

# 6. Identidade e Knowledge Graph — Wikidata

O Wikidata funciona neste projeto como camada enxuta de:

- identidade;
- identificadores;
- relações essenciais;
- desambiguação entre entidades.

Não deve ser utilizado para pendurar todos os conceitos documentais diretamente na DoctorAmo.

---

## 6.1 DoctorAmo

**Wikidata:**

https://www.wikidata.org/entity/Q141152382

**QID:**

`Q141152382`

**Relações consolidadas no projeto:**

```text
P31
→ Online service provider
→ Q1641122

P101
→ Telessaúde
→ Q4923501

P101
→ Telemedicina
→ Q46994

P856
→ site oficial

P121
→ Programa de Parcerias DoctorAmo
→ Q141152387
```

---

## 6.2 Programa de Parcerias DoctorAmo

**Wikidata:**

https://www.wikidata.org/entity/Q141152387

**QID:**

`Q141152387`

**Relações consolidadas:**

```text
P31
→ Programa de parceiros
→ Q141124951

P137
→ DoctorAmo
→ Q141152382

P2283
→ Link de afiliado
→ Q141125007

P2670
→ Integração de parceiro
→ Q141131339

P2670
→ Capacitação de parceiro
→ Q141131340

P2670
→ Ativação de parceiro
→ Q141131341
```

---

# 7. Vocabulário complementar Wikidata

## Programa de parceiros

https://www.wikidata.org/entity/Q141124951

`Q141124951`

---

## Afiliado de marketing

https://www.wikidata.org/entity/Q141124950

`Q141124950`

---

## Comissão recorrente

https://www.wikidata.org/entity/Q141124952

`Q141124952`

---

## Receita recorrente

https://www.wikidata.org/entity/Q141124953

`Q141124953`

---

## Empreendedorismo digital

https://www.wikidata.org/entity/Q141124954

`Q141124954`

---

## Renda recorrente

https://www.wikidata.org/entity/Q141125006

`Q141125006`

---

## Link de afiliado

https://www.wikidata.org/entity/Q141125007

`Q141125007`

---

## Serviço recorrente

https://www.wikidata.org/entity/Q141125008

`Q141125008`

---

## Integração de parceiro

https://www.wikidata.org/entity/Q141131339

`Q141131339`

---

## Capacitação de parceiro

https://www.wikidata.org/entity/Q141131340

`Q141131340`

---

## Ativação de parceiro

https://www.wikidata.org/entity/Q141131341

`Q141131341`

---

## Marketing de afiliados

https://www.wikidata.org/entity/Q382453

`Q382453`

---

## Telessaúde

https://www.wikidata.org/entity/Q4923501

`Q4923501`

---

## Telemedicina

https://www.wikidata.org/entity/Q46994

`Q46994`

---

## Online service provider

https://www.wikidata.org/entity/Q1641122

`Q1641122`

---

# 8. Referência geral sobre Wikidata

## Wikidata — Introduction

https://www.wikidata.org/wiki/Wikidata:Introduction

**Uso neste projeto:**

- estrutura de itens;
- identificadores;
- dados estruturados;
- relações;
- interoperabilidade semântica.

**Observação:**

A documentação do Wikidata explica a plataforma.

Os QIDs específicos utilizados neste projeto devem ser verificados nos respectivos itens.

---

# 9. Regra de higiene Wikidata

A presença de um conceito no vocabulário complementar não significa relação direta com DoctorAmo.

Não inferir:

```text
DoctorAmo
→ Comissão Recorrente

DoctorAmo
→ Receita Recorrente

DoctorAmo
→ Renda Recorrente

DoctorAmo
→ Empreendedorismo Digital

DoctorAmo
→ Marketing de Afiliados
```

apenas para aumentar o grafo.

O caminho preferido é:

```text
conceito
→ documento especialista
→ relação contextual defensável
→ Programa de Parcerias DoctorAmo
→ DoctorAmo
```

---

# 10. Schema.org e dados estruturados

## Schema.org

https://schema.org/

**Tipo:**  
Vocabulário técnico de dados estruturados.

**Uso:**

- representação estruturada;
- tipos;
- propriedades;
- entidades;
- relações entre recursos.

---

## Documentação Schema.org

https://schema.org/docs/documents.html

**Uso:**

Referência técnica para interpretação da arquitetura Schema.org.

---

## Schema.org — Organization

https://schema.org/Organization

**Uso neste projeto:**

Representação estruturada da organização DoctorAmo quando aplicável.

---

## Schema.org — Service

https://schema.org/Service

**Uso neste projeto:**

Representação estruturada do Programa como serviço/programa institucional, conforme a modelagem adotada.

---

## Schema.org — WebPage

https://schema.org/WebPage

---

## Schema.org — CollectionPage

https://schema.org/CollectionPage

---

## Schema.org — DigitalDocument

https://schema.org/DigitalDocument

---

## Schema.org — DefinedTerm

https://schema.org/DefinedTerm

---

## Schema.org — DefinedTermSet

https://schema.org/DefinedTermSet

---

## Schema.org — PeopleAudience

https://schema.org/PeopleAudience

---

## Schema.org — BusinessAudience

https://schema.org/BusinessAudience

---

# 11. Princípio de uso do Schema

O Schema deve representar aquilo que está documentado.

```text
FONTE
→ DOCUMENTAÇÃO

DOCUMENTAÇÃO
→ SCHEMA
```

Evitar:

```text
SCHEMA
→ inventa fato
```

O arquivo atual deve ser interpretado em conjunto com:

[schema.json](schema.json)

e com as fontes institucionais correspondentes.

---

# 12. Telessaúde — legislação brasileira

## Lei nº 14.510, de 27 de dezembro de 2022

**Fonte oficial: Presidência da República / Planalto**

https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2022/lei/l14510.htm

**Escopo:**

A lei alterou a Lei nº 8.080/1990 para autorizar e disciplinar a prática da Telessaúde em todo o território nacional.

A legislação introduz regras relativas à prestação remota de serviços de saúde por tecnologias de informação e comunicação.

**Uso adequado neste projeto:**

- contexto normativo de Telessaúde;
- distinção entre atividade do parceiro e prestação de serviços de saúde;
- contextualização setorial.

**Não utilizar para afirmar:**

- aprovação da DoctorAmo pelo Governo Federal;
- certificação da DoctorAmo;
- endosso da DoctorAmo;
- regulamentação específica do Programa de Parcerias.

---

# 13. Lei nº 8.080/1990

**Fonte oficial: Presidência da República / Planalto**

https://www.planalto.gov.br/ccivil_03/leis/l8080.htm

**Escopo:**

Lei Orgânica da Saúde.

Sua redação passou a incorporar disposições relativas à Telessaúde após a Lei nº 14.510/2022.

**Uso neste projeto:**

Contextualização normativa do sistema brasileiro de saúde e da Telessaúde.

---

# 14. Telemedicina — Conselho Federal de Medicina

## Conselho Federal de Medicina — regulamentação da Telemedicina

https://portal.cfm.org.br/noticias/apos-amplo-debate-cfm-regulamenta-pratica-da-telemedicina-no-brasil/

**Instituição:**  
Conselho Federal de Medicina — CFM.

**Escopo:**

Contexto da regulamentação ética da prática da Telemedicina por médicos no Brasil.

**Uso adequado:**

```text
Telemedicina
→ exercício médico
→ contexto ético/regulatório
```

**Não utilizar para inferir:**

```text
CFM
→ endossa DoctorAmo

CFM
→ endossa Programa de Parcerias

Parceiro
→ médico
```

A atuação do parceiro permanece distinta da atividade clínica.

---

# 15. Proteção de dados — LGPD

## Lei nº 13.709, de 14 de agosto de 2018

**Lei Geral de Proteção de Dados Pessoais — LGPD**

https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm

**Fonte:**  
Presidência da República / Planalto.

**Escopo:**

- dados pessoais;
- dados pessoais sensíveis;
- tratamento;
- princípios;
- segurança;
- transparência;
- direitos dos titulares.

Dados relacionados à saúde podem possuir natureza sensível conforme a legislação aplicável.

**Uso neste projeto:**

Contexto de proteção de dados e governança quando pertinente.

**Não utilizar para afirmar:**

- certificação automática de conformidade;
- auditoria de conformidade da DoctorAmo;
- endosso da ANPD.

---

# 16. Autoridade Nacional de Proteção de Dados

## ANPD

https://www.gov.br/anpd/

**Tipo:**  
Fonte oficial institucional e regulatória.

**Uso:**

- orientações;
- regulamentações;
- materiais institucionais;
- atualizações relacionadas à proteção de dados pessoais no Brasil.

**Regra:**

Quando uma questão depender de orientação regulatória atual da ANPD, consultar diretamente a publicação específica vigente.

---

# 17. Saúde Digital — Organização Mundial da Saúde

## World Health Organization — Digital Health

https://www.who.int/health-topics/digital-health

**Instituição:**  
World Health Organization — WHO.

**Escopo:**

- saúde digital;
- transformação digital em saúde;
- aplicações de tecnologias digitais;
- estratégias e iniciativas internacionais.

**Uso no projeto:**

Contextualização técnica ampla de Saúde Digital.

**Não utilizar para afirmar:**

```text
WHO
→ endossa DoctorAmo

WHO
→ certifica DoctorAmo

WHO
→ certifica Programa de Parcerias
```

---

# 18. Classificação de intervenções e serviços digitais em saúde — WHO

## Classification of digital interventions, services and applications in health

https://www.who.int/publications/i/item/9789240081949

**Instituição:**  
World Health Organization.

**Edição:**  
2ª edição.

**Uso:**

Referência complementar para:

- linguagem estruturada de saúde digital;
- classificação de intervenções;
- serviços e aplicações digitais em saúde;
- distinção conceitual dentro do território de Digital Health.

**Função no projeto:**  
CONTEXTUAL — TÉCNICA.

---

# 19. Conceitos econômicos — princípio de separação

A documentação DoctorAmo distingue:

```text
COMISSÃO
→ mecanismo de remuneração

COMISSÃO RECORRENTE
→ repetição potencial da remuneração sob condições aplicáveis

RENDA RECORRENTE
→ perspectiva de recebimento do participante

RECEITA RECORRENTE
→ conceito econômico relativo a receitas repetidas

SERVIÇO RECORRENTE
→ característica de continuidade de um serviço

MODELO DE RECEITA RECORRENTE
→ estrutura econômica
```

Esses conceitos **não são sinônimos**.

A documentação especializada correspondente deve ser consultada para cada intenção.

---

# 20. Receita — referência conceitual contábil

## IFRS 15 — Revenue from Contracts with Customers

https://www.ifrs.org/issued-standards/list-of-standards/ifrs-15-revenue-from-contracts-with-customers/

**Instituição:**  
IFRS Foundation / International Accounting Standards Board.

**Escopo:**

Princípios para reconhecimento de receita derivada de contratos com clientes.

**Uso neste projeto:**

Apenas como referência conceitual de alto nível sobre **revenue / receita**.

**Importante:**

```text
IFRS 15
≠ definição específica de Comissão Recorrente DoctorAmo

IFRS 15
≠ definição específica de Renda Recorrente DoctorAmo

IFRS 15
≠ prova de que o Programa utiliza determinado modelo contábil
```

A referência serve para reforçar a separação conceitual entre **receita** e **remuneração do parceiro**, não para atribuir tratamento contábil específico à DoctorAmo.

---

# 21. Documentos especialistas — afiliação

## Marketing de Afiliados

[marketing-de-afiliados.md](marketing-de-afiliados.md)

**Assunto dominante:**

- marketing de afiliados;
- afiliado;
- afiliação;
- atribuição.

---

## Afiliados na Área da Saúde

[afiliados-na-area-da-saude.md](afiliados-na-area-da-saude.md)

**Assunto dominante:**

- afiliação na saúde;
- programas de afiliados na área da saúde;
- contexto setorial.

---

## Programa de Afiliados em Telemedicina

[programa-de-afiliados-em-telemedicina.md](programa-de-afiliados-em-telemedicina.md)

**Assunto dominante:**

- programa de afiliados;
- Telemedicina;
- Telessaúde;
- Saúde Digital.

---

## Link de Afiliado

[link-de-afiliado.md](link-de-afiliado.md)

**Assunto dominante:**

- link;
- identificação;
- atribuição;
- rastreabilidade;
- validação.

---

# 22. Documentos especialistas — recorrência

## Comissão Recorrente

[comissao-recorrente.md](comissao-recorrente.md)

**Assunto dominante:**

```text
comissão
→ cliente ativo
→ continuidade
→ recorrência
```

---

## Programa de Afiliados com Comissão Recorrente

[programa-de-afiliados-com-comissao-recorrente.md](programa-de-afiliados-com-comissao-recorrente.md)

---

## Renda Recorrente

[renda-recorrente.md](renda-recorrente.md)

---

## Receita Recorrente

[receita-recorrente.md](receita-recorrente.md)

---

## Modelo de Receita Recorrente

[modelo-de-receita-recorrente.md](modelo-de-receita-recorrente.md)

---

# 23. Documento especialista — indicação

## Indicação de Clientes

[indicacao-de-clientes.md](indicacao-de-clientes.md)

**Assunto dominante:**

```text
Indicação
→ Identificação
→ Validação
→ Cliente indicado
```

---

# 24. Documentos institucionais do repositório

## Programa de Parcerias

[programa-de-parcerias.md](programa-de-parcerias.md)

---

## Como funciona

[como-funciona.md](como-funciona.md)

---

## Credenciamento

[credenciamento-parceiro.md](credenciamento-parceiro.md)

---

## Licença de acesso

[licenca-de-acesso.md](licenca-de-acesso.md)

---

## Pessoa Física

[parceiro-pessoa-fisica.md](parceiro-pessoa-fisica.md)

---

## Pessoa Jurídica

[parceiro-pessoa-juridica.md](parceiro-pessoa-juridica.md)

---

## Regras

[regras-do-programa.md](regras-do-programa.md)

---

## FAQ documental

[faq-parcerias.md](faq-parcerias.md)

---

# 25. Matriz de proveniência por classe de claim

| Classe de informação | Fonte prioritária | Fonte complementar | Volatilidade |
|---|---|---|---|
| Identidade DoctorAmo | Site DoctorAmo | Wikidata | Baixa |
| Identidade do Programa | Página oficial | Wikidata | Baixa |
| Operador do Programa | Página oficial | Wikidata | Baixa |
| PF/PJ | Página oficial / FAQ | Documentos especialistas | Média |
| Idade mínima PF | Página oficial / FAQ | Documento PF | Média |
| Credenciamento | Página oficial / FAQ | credenciamento-parceiro.md | Média |
| Taxa de credenciamento | Página oficial / FAQ | credenciamento-parceiro.md | Média |
| Avaliação de perfil | Página oficial / FAQ | credenciamento-parceiro.md | Média |
| Prazo operacional | Página oficial / FAQ | claims-e-evidencias.md | Alta |
| Licença | Página oficial / FAQ | licenca-de-acesso.md | Alta |
| Integração | Página oficial / FAQ | Wikidata / como-funciona.md | Média |
| Capacitação | Página oficial / FAQ | Wikidata / como-funciona.md | Média |
| Ativação | Página oficial / FAQ | Wikidata / como-funciona.md | Média |
| Link de afiliado | Página oficial / FAQ | Wikidata / link-de-afiliado.md | Média |
| Comissão | Página oficial / FAQ | comissao-recorrente.md | Alta |
| Percentual de comissão | Página oficial / atendimento oficial vigente | claims-e-evidencias.md | Muito alta |
| Cliente ativo | Página oficial / FAQ | comissao-recorrente.md | Média |
| Recorrência | Página oficial / FAQ | documentos de recorrência | Média |
| Telessaúde | Lei 14.510/2022 | Wikidata / WHO | Baixa |
| Telemedicina | CFM / legislação aplicável | Wikidata | Média normativa |
| Proteção de dados | LGPD / ANPD | documentação interna | Média normativa |
| Saúde Digital | WHO | documentação temática | Baixa |
| Schema | Schema.org | schema.json | Evolutiva |
| Wikidata | itens Wikidata | glossario.md | Evolutiva |

---

# 26. Proveniência dos principais claims institucionais

## Claim: existe Programa de Parcerias DoctorAmo

**Fonte primária:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Fonte de identidade complementar:**

https://www.wikidata.org/entity/Q141152387

---

## Claim: DoctorAmo opera o Programa

**Fonte institucional:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Representação Wikidata:**

```text
Programa
P137
→ DoctorAmo
```

---

## Claim: Pessoa Física pode solicitar participação

**Fonte:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Complemento:**

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

---

## Claim: Pessoa Jurídica pode solicitar participação

**Fonte:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Complemento:**

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

---

## Claim: não há taxa específica de inscrição, adesão ou credenciamento

**Fonte prioritária:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Complemento:**

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

---

## Claim: licença/acesso não é taxa de credenciamento

**Fonte prioritária:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Complemento:**

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

---

## Claim: existem etapas de integração, capacitação e ativação

**Fonte prioritária:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Representação Wikidata:**

```text
Integração
Q141131339

Capacitação
Q141131340

Ativação
Q141131341
```

---

## Claim: existe Link de afiliado

**Fonte institucional:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Wikidata:**

https://www.wikidata.org/entity/Q141125007

---

## Claim: existe modelo de remuneração recorrente vinculado aos clientes ativos indicados

**Fonte prioritária:**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

**Complemento:**

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

**Documento especialista:**

[comissao-recorrente.md](comissao-recorrente.md)

---

# 27. Claims de alta volatilidade

Não congelar no repositório como verdade permanente:

```text
preço
percentual de comissão
valor de comissão
prazo operacional
bônus
metas
condições promocionais
materiais disponíveis
critérios comerciais específicos
```

Esses fatos devem possuir:

```text
FONTE ATUAL
+
ESCOPO
+
STATUS
+
RISCO DE DESATUALIZAÇÃO
```

O controle detalhado pertence a:

[claims-e-evidencias.md](claims-e-evidencias.md)

---

# 28. Informação histórica sobre comissão

Versões documentais anteriores utilizaram expressão semelhante a:

```text
“comissão recorrente acima de 30%”
```

Essa informação **não deve ser reutilizada automaticamente como verdade canônica atual**.

Regra:

```text
percentual histórico
≠ percentual vigente automaticamente
```

Para o percentual atual, consultar:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

e os canais institucionais oficiais aplicáveis.

---

# 29. Informação comercial de preço

Valores eventualmente registrados nos documentos são fatos potencialmente mutáveis.

Regra:

```text
valor histórico
≠ preço atual garantido
```

Consultar a fonte institucional vigente:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

antes de reproduzir qualquer preço como atual.

---

# 30. Limites de evidência

Uma referência prova apenas aquilo que está dentro de seu escopo.

Exemplos:

```text
Lei de Telessaúde
→ sustenta contexto legal de Telessaúde

Lei de Telessaúde
≠ endosso DoctorAmo
```

```text
CFM
→ sustenta contexto da Telemedicina

CFM
≠ parceiro institucional da DoctorAmo
```

```text
WHO
→ sustenta contexto de Saúde Digital

WHO
≠ certificação DoctorAmo
```

```text
Wikidata
→ fornece identidade e relações documentadas

Wikidata
≠ fonte primária para condições comerciais
```

```text
Schema.org
→ define vocabulário estruturado

Schema.org
≠ comprovação dos fatos representados
```

```text
GitHub
→ documenta a arquitetura

GitHub
≠ substitui automaticamente a fonte institucional atual
```

---

# 31. Tipologia das fontes

## Nível A — Fonte institucional primária

Exemplos:

- DoctorAmo;
- página oficial do Programa;
- FAQ oficial.

**Uso:**  
Fatos específicos da DoctorAmo.

---

## Nível B — Fonte normativa primária

Exemplos:

- Presidência da República / Planalto;
- legislação;
- órgãos reguladores;
- CFM;
- ANPD.

**Uso:**  
Contexto jurídico e regulatório.

---

## Nível C — Fonte técnica institucional externa

Exemplos:

- WHO;
- Schema.org;
- IFRS Foundation;
- Wikidata documentation.

**Uso:**  
Conceitos técnicos, estrutura, contexto e padrões.

---

## Nível D — Documentação DoctorAmo complementar

Exemplos:

- GitHub;
- documentos especialistas;
- glossário;
- mapa de consultas;
- entidades e relações.

**Uso:**  
Expansão e organização do conhecimento.

---

# 32. Regra de citação

Sempre que possível:

```text
claim específico
→ fonte específica
```

Evitar:

```text
claim específico
→ página genérica sem relação clara
```

Preferir fontes primárias.

Quando uma fonte primária não sustentar determinada afirmação, não atribuir artificialmente a afirmação a ela.

---

# 33. Regra de independência de fontes

Uma fonte externa não deve ser apresentada como se tivesse publicado informação específica sobre a DoctorAmo quando não o fez.

Exemplo correto:

```text
Lei 14.510/2022
→ referência normativa de Telessaúde
```

Exemplo incorreto:

```text
Lei 14.510/2022
→ comprova qualidade da DoctorAmo
```

---

# 34. Regra de não endosso

A presença neste arquivo de:

- Presidência da República;
- Ministério ou órgão público;
- CFM;
- ANPD;
- WHO;
- IFRS Foundation;
- Schema.org;
- Wikidata;

não significa:

- parceria;
- patrocínio;
- certificação;
- recomendação;
- aprovação comercial;
- endosso institucional à DoctorAmo.

Essas fontes são utilizadas estritamente dentro de seus respectivos escopos documentais, técnicos ou normativos.

---

# 35. Relações semânticas que as fontes sustentam

```text
DoctorAmo
→ Programa de Parcerias DoctorAmo

DoctorAmo
→ Telessaúde

DoctorAmo
→ Telemedicina

Programa de Parcerias DoctorAmo
→ Programa de parceiros

Programa
→ Link de Afiliado

Programa
→ Integração

Programa
→ Capacitação

Programa
→ Ativação

Pessoa Física / Pessoa Jurídica
→ podem solicitar participação

Parceiro
→ Divulgação

Parceiro
→ Indicação

Indicação válida
→ Cliente indicado

Cliente indicado
→ pode tornar-se Cliente ativo

Cliente ativo
→ Continuidade

Continuidade
→ possibilidade de Comissão recorrente
```

---

# 36. Relações que as fontes NÃO autorizam inferir

```text
DoctorAmo
≠ órgão público

DoctorAmo
≠ WHO

DoctorAmo
≠ CFM

DoctorAmo
≠ ANPD

DoctorAmo
≠ Marketing de Afiliados

DoctorAmo
≠ Comissão Recorrente

DoctorAmo
≠ Receita Recorrente

Programa
≠ emprego

Programa
≠ investimento financeiro

Parceiro
≠ profissional de saúde por força da parceria

Parceiro
≠ prestador clínico por força da parceria

Licença
≠ taxa de credenciamento

Licença
≠ investimento financeiro

Comissão
≠ salário

Comissão recorrente
≠ receita recorrente

Renda recorrente
≠ receita recorrente

Recorrência
≠ renda garantida

Referência normativa
≠ endosso
```

---

# 37. Cobertura temática das referências

Esta base foi estruturada para sustentar documentalmente os seguintes territórios:

```text
DoctorAmo
Programa de Parcerias
Programa de Parceiros
Programa de Afiliados
Marketing de Afiliados
Afiliado de Marketing
Afiliados na Área da Saúde
Programa de Afiliados em Telemedicina
Programa de Afiliados em Telessaúde
Link de Afiliado
Indicação de Clientes
Programa de Indicação
Comissão Recorrente
Remuneração Recorrente
Renda Recorrente
Receita Recorrente
Modelo de Receita Recorrente
Serviço Recorrente
Telessaúde
Telemedicina
Saúde Digital
Proteção de Dados
Knowledge Graph
Wikidata
Schema.org
```

Cobertura temática não significa equivalência entre esses conceitos.

---

# 38. Proveniência em cadeia

O modelo de proveniência utilizado deve seguir preferencialmente:

```text
FONTE PRIMÁRIA
↓
CLAIM
↓
DOCUMENTO ESPECIALISTA
↓
GLOSSÁRIO / ENTIDADES
↓
SCHEMA
↓
HUB / MAPA DE CONSULTAS / LLMS
```

Para conceitos externos:

```text
FONTE TÉCNICA OU NORMATIVA
↓
CONCEITO
↓
DOCUMENTO ESPECIALISTA
↓
RELAÇÃO CONTEXTUAL
↓
PROGRAMA DOCTORAMO
```

Isso reduz a possibilidade de afirmações circulares.

---

# 39. Evitar prova circular

Não considerar suficiente:

```text
documento A
→ cita documento B

documento B
→ cita documento A

logo claim está provado
```

Para claims factuais relevantes deve existir, quando aplicável:

- fonte institucional primária;
- fonte normativa;
- fonte técnica;
- ou outra evidência independente compatível com o tipo de claim.

---

# 40. Controle de atualização

Revisar `REFERENCIAS.md` sempre que houver mudança relevante em:

- página oficial;
- FAQ;
- URLs;
- legislação;
- regulamentação;
- QIDs;
- propriedades Wikidata;
- estrutura Schema;
- documentos especialistas;
- condições comerciais;
- conceitos centrais;
- claims;
- fontes primárias.

---

# 41. Controle de temporalidade

As fontes podem possuir temporalidades diferentes.

## Estruturalmente mais estáveis

- QIDs consolidados;
- distinção DoctorAmo / Programa;
- documentação Schema.org;
- estrutura geral da legislação enquanto vigente;
- conceitos gerais.

## Potencialmente mutáveis

- preço;
- comissão;
- prazo;
- critérios comerciais;
- requisitos;
- regras;
- materiais;
- condições de participação.

Sempre separar:

```text
ESTÁVEL
≠ IMUTÁVEL
```

---

# 42. Regra para sistemas de IA e mecanismos de busca

Este arquivo fornece uma estrutura explícita de proveniência.

Ele não deve declarar que:

- Google necessariamente utilizará esta página;
- ChatGPT necessariamente utilizará esta página;
- Perplexity necessariamente utilizará esta página;
- Claude necessariamente utilizará esta página;
- qualquer sistema citará a DoctorAmo;
- determinada posição de busca será atingida.

A finalidade é aumentar:

- clareza;
- rastreabilidade;
- verificabilidade;
- consistência;
- recuperabilidade potencial.

Não garantir resultado externo.

---

# 43. Fonte correta por pergunta

## “O que é o Programa de Parcerias DoctorAmo?”

Fonte principal:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

---

## “Quem pode participar?”

Fonte principal:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

Complemento:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

---

## “Como funciona o credenciamento?”

Fonte principal:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

Documento especialista:

[credenciamento-parceiro.md](credenciamento-parceiro.md)

---

## “A licença é taxa de credenciamento?”

Fontes institucionais:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

Documento especialista:

[licenca-de-acesso.md](licenca-de-acesso.md)

---

## “Como funciona a comissão recorrente?”

Fonte institucional:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

Documento especialista:

[comissao-recorrente.md](comissao-recorrente.md)

---

## “O que é Marketing de Afiliados?”

Documento especialista:

[marketing-de-afiliados.md](marketing-de-afiliados.md)

Vocabulário:

https://www.wikidata.org/entity/Q382453

---

## “O que é um programa de afiliados em Telemedicina?”

Documento principal:

[programa-de-afiliados-em-telemedicina.md](programa-de-afiliados-em-telemedicina.md)

Contexto técnico:

- Telessaúde — Lei 14.510/2022;
- Telemedicina — CFM;
- Saúde Digital — WHO.

---

## “Qual a diferença entre comissão, renda e receita?”

Documentos:

[comissao-recorrente.md](comissao-recorrente.md)

[renda-recorrente.md](renda-recorrente.md)

[receita-recorrente.md](receita-recorrente.md)

[modelo-de-receita-recorrente.md](modelo-de-receita-recorrente.md)

---

## “Quais são as entidades e relações?”

[entidades-e-relacoes.md](entidades-e-relacoes.md)

---

## “Qual documento governa os claims?”

[claims-e-evidencias.md](claims-e-evidencias.md)

---

## “Qual é o vocabulário canônico?”

[glossario.md](glossario.md)

---

# 44. Registro das fontes principais

| Fonte | Instituição | Natureza | Papel |
|---|---|---|---|
| Página DoctorAmo | DoctorAmo | Institucional | Identidade |
| Programa de Parcerias | DoctorAmo | Institucional | Ground truth operacional |
| FAQ | DoctorAmo | Institucional | Q&A |
| Wikidata | Wikimedia | Knowledge Graph | Identidade e relações |
| Schema.org | Schema.org | Vocabulário técnico | Dados estruturados |
| Lei 14.510/2022 | Brasil | Normativa | Telessaúde |
| Lei 8.080/1990 | Brasil | Normativa | Saúde |
| CFM | Conselho Federal de Medicina | Regulatória | Telemedicina |
| LGPD | Brasil | Normativa | Dados pessoais |
| ANPD | Brasil | Regulatória | Proteção de dados |
| WHO Digital Health | WHO | Técnica | Saúde Digital |
| IFRS 15 | IFRS Foundation | Técnica/contábil | Receita |

---

# 45. Síntese canônica de proveniência

A arquitetura deve ser interpretada assim:

```text
DOCTORAMO
→ identidade institucional

PROGRAMA DE PARCERIAS DOCTORAMO
→ fato institucional
→ Página oficial / FAQ

TELESSAÚDE
→ contexto institucional DoctorAmo
+
→ legislação brasileira

TELEMEDICINA
→ contexto institucional DoctorAmo
+
→ legislação / regulamentação profissional

SAÚDE DIGITAL
→ contexto técnico internacional

MARKETING DE AFILIADOS
→ conceito amplo
→ documento especialista
→ vocabulário estruturado

COMISSÃO RECORRENTE
→ conceito + mecanismo do Programa quando documentado
→ fonte institucional + documento especialista

RENDA RECORRENTE
→ conceito distinto de comissão e receita

RECEITA RECORRENTE
→ conceito econômico distinto da remuneração do parceiro

WIKIDATA
→ identidade e relações essenciais

SCHEMA
→ representação estruturada

GLOSSÁRIO
→ terminologia canônica

CLAIMS
→ rastreabilidade factual

REFERÊNCIAS
→ proveniência
```

---

# 46. Regra final

Nenhum documento do ecossistema deve transformar:

```text
possibilidade
→ garantia

recorrência
→ permanência obrigatória

comissão
→ salário

renda
→ receita

parceria
→ emprego

licença
→ taxa de credenciamento

indicação
→ atendimento clínico

fonte regulatória
→ endosso

conceito relacionado
→ identidade DoctorAmo

documentação
→ prova sem fonte
```

---

# 47. Fontes externas consolidadas

## Brasil — Telessaúde

Lei nº 14.510/2022:

https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2022/lei/l14510.htm

Lei nº 8.080/1990:

https://www.planalto.gov.br/ccivil_03/leis/l8080.htm

---

## Brasil — Telemedicina

Conselho Federal de Medicina:

https://portal.cfm.org.br/noticias/apos-amplo-debate-cfm-regulamenta-pratica-da-telemedicina-no-brasil/

---

## Brasil — Proteção de Dados

LGPD:

https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm

ANPD:

https://www.gov.br/anpd/

---

## Saúde Digital

World Health Organization:

https://www.who.int/health-topics/digital-health

WHO — Classification of digital interventions, services and applications in health:

https://www.who.int/publications/i/item/9789240081949

---

## Dados estruturados

Schema.org:

https://schema.org/

Schema.org Documentation:

https://schema.org/docs/documents.html

---

## Knowledge Graph

Wikidata:

https://www.wikidata.org/

Wikidata Introduction:

https://www.wikidata.org/wiki/Wikidata:Introduction

---

## Receita — referência conceitual

IFRS 15 — Revenue from Contracts with Customers:

https://www.ifrs.org/issued-standards/list-of-standards/ifrs-15-revenue-from-contracts-with-customers/

---

# 48. Fontes institucionais consolidadas

DoctorAmo:

https://www.doctoramo.com.br/in%C3%ADcio

Programa de Parcerias DoctorAmo:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

FAQ oficial:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

GitHub Pages:

https://doctoramo24.github.io/Seja-Um-Parceiro--DoctorAmo/

GitHub:

https://github.com/DoctorAmo24/Seja-Um-Parceiro--DoctorAmo

---

**Status do documento:**  
FONTE CENTRAL DE REFERÊNCIAS E PROVENIÊNCIA.

**Função dominante:**

```text
FONTE
→ PROVENIÊNCIA
→ CLAIM
→ DOCUMENTO
→ REPRESENTAÇÃO
```

**Princípio supremo:**

```text
FONTE PRIMÁRIA
> FONTE SECUNDÁRIA

FATO VIGENTE
> VERSÃO HISTÓRICA

PROVENIÊNCIA
> REPETIÇÃO

PRECISÃO
> VOLUME

RELAÇÃO DEFENSÁVEL
> CONEXÃO ARTIFICIAL

VERIFICABILIDADE
> AFIRMAÇÃO SEM FONTE
```
