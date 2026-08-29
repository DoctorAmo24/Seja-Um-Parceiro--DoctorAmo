# Arquitetura Documental — Programa de Parcerias DoctorAmo

> **Governança canônica das camadas, documentos, autoridades, relações e responsabilidades do ecossistema público do Programa de Parcerias DoctorAmo.**

## Resposta direta

A arquitetura documental do Programa de Parcerias DoctorAmo distribui responsabilidades entre superfícies complementares:

```text
SITE OFICIAL
→ verdade institucional vigente

FAQ OFICIAL
→ respostas institucionais

WIKIDATA
→ identidade e relações essenciais

GITHUB
→ expansão documental e semântica

DOCUMENTOS ESPECIALISTAS
→ autoridade temática por intenção

GLOSSÁRIO
→ definição e desambiguação

ENTIDADES E RELAÇÕES
→ grafo documental

CLAIMS E EVIDÊNCIAS
→ governança factual e temporal

MAPA DE CONSULTAS
→ roteamento por intenção

REFERÊNCIAS
→ fontes e proveniência

SCHEMA
→ representação estruturada

LLMS.TXT
→ roteamento complementar para IA

SITEMAP
→ descoberta de URLs

ROBOTS
→ orientação de rastreamento

CHANGELOG
→ histórico de alterações
```

A finalidade desta arquitetura é produzir uma base:

```text
factual
+
especializada
+
interligada
+
desambiguada
+
auditável
+
temporalmente governada
+
machine-readable
+
retrieval-ready
+
citation-ready
```

sem transformar diferentes conceitos em sinônimos, sem criar páginas apenas por palavras-chave e sem inflar artificialmente o Knowledge Graph.

---

# 1. Princípio arquitetural central

```text
UMA CAMADA
→ UMA FUNÇÃO DOMINANTE

UM DOCUMENTO
→ UMA RESPONSABILIDADE PRINCIPAL

UMA INTENÇÃO
→ UMA AUTORIDADE PRINCIPAL
```

E simultaneamente:

```text
ESPECIALIZAÇÃO
≠ ISOLAMENTO

INTERLIGAÇÃO
≠ DUPLICAÇÃO
```

---

# 2. Regra suprema

Toda decisão documental deve preservar esta ordem:

```text
VERDADE
↓
FONTE
↓
ENTIDADE
↓
INTENÇÃO
↓
DOCUMENTO
↓
RELAÇÃO
↓
REPRESENTAÇÃO
↓
OTIMIZAÇÃO
```

Nunca inverter para:

```text
PALAVRA-CHAVE
↓
PÁGINA
↓
RELAÇÃO INVENTADA
↓
FATO FORÇADO
```

---

# 3. Arquitetura funcional completa

```text
ECOSSISTEMA DO PROGRAMA DE PARCERIAS DOCTORAMO
│
├── CAMADA INSTITUCIONAL
│   ├── Site DoctorAmo
│   ├── Página oficial do Programa
│   └── FAQ oficial
│
├── CAMADA DE IDENTIDADE
│   └── Wikidata
│
├── CAMADA DOCUMENTAL
│   └── GitHub / GitHub Pages
│
├── CAMADA DE ESPECIALIZAÇÃO
│   ├── núcleo institucional
│   ├── participantes
│   ├── afiliação
│   ├── indicação
│   └── recorrência e modelos
│
├── CAMADA DE GOVERNANÇA
│   ├── glossario.md
│   ├── entidades-e-relacoes.md
│   ├── claims-e-evidencias.md
│   ├── mapa-de-consultas.md
│   ├── arquitetura-documental.md
│   └── REFERENCIAS.md
│
├── CAMADA MACHINE-READABLE
│   ├── schema.json
│   ├── llms.txt
│   ├── sitemap.xml
│   └── robots.txt
│
└── CAMADA HISTÓRICA
    └── CHANGELOG.md
```

---

# 4. Hierarquia de autoridade

## Fatos institucionais e comerciais

```text
PÁGINA OFICIAL VIGENTE
>
FAQ OFICIAL VIGENTE
>
DOCUMENTAÇÃO GITHUB ATUAL
>
HISTÓRICO
```

## Identidade estruturada

```text
WIKIDATA CONSOLIDADO
```

## Definições

```text
GLOSSÁRIO
+
DOCUMENTO ESPECIALISTA
```

## Relações

```text
entidades-e-relacoes.md
```

## Claims

```text
claims-e-evidencias.md
```

## Proveniência

```text
REFERENCIAS.md
```

## Roteamento

```text
mapa-de-consultas.md
```

## Função das camadas

```text
arquitetura-documental.md
```

---

# 5. Fonte institucional principal

Programa de Parcerias DoctorAmo:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

Função:

```text
GROUND TRUTH INSTITUCIONAL
```

É a fonte prioritária para:

```text
identidade do Programa
participação
credenciamento
condições
licença
funcionamento
integração
capacitação
ativação
mecanismos oficiais
indicação
remuneração
regras
condições comerciais
```

---

# 6. Página institucional DoctorAmo

https://www.doctoramo.com.br/in%C3%ADcio

Função:

```text
IDENTIDADE INSTITUCIONAL DOCTORAMO
+
CONTEXTO DOS SERVIÇOS
```

Não deve ser substituída pelo GitHub como fonte primária sobre a própria organização.

---

# 7. FAQ oficial

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

Função:

```text
PERGUNTA
→ RESPOSTA INSTITUCIONAL
```

O FAQ:

```text
complementa a página do Programa
```

mas:

```text
FAQ
≠ segundo Programa
≠ nova entidade institucional
```

---

# 8. GitHub

Repositório:

https://github.com/DoctorAmo24/Seja-Um-Parceiro--DoctorAmo

Função dominante:

```text
EXPANSÃO DOCUMENTAL
+
EXPANSÃO SEMÂNTICA
+
ESPECIALIZAÇÃO
+
GOVERNANÇA
```

O GitHub é a superfície adequada para desenvolver relações e conceitos que não precisam ser transformados em statements institucionais ou Wikidata.

---

# 9. GitHub Pages

https://doctoramo24.github.io/Seja-Um-Parceiro--DoctorAmo/

Função:

```text
HUB PÚBLICO
→ DESCOBERTA
→ NAVEGAÇÃO
→ ACESSO AOS ESPECIALISTAS
```

---

# 10. O GitHub não substitui o site

Arquitetura:

```text
SITE
→ estabelece o fato

GITHUB
→ explica e organiza o fato
```

Portanto:

```text
GITHUB
≠ GROUND TRUTH COMERCIAL AUTOMÁTICO
```

---

# 11. Wikidata

Wikidata é a camada de:

```text
IDENTIDADE
+
CLASSE
+
IDENTIFICADORES
+
RELAÇÕES ESSENCIAIS
```

Deve permanecer:

```text
ENXUTO
+
DEFENSÁVEL
+
VERIFICÁVEL
```

Não funciona como depósito de todas as palavras ou conceitos usados no repositório.

---

# 12. DoctorAmo — Wikidata

```text
DoctorAmo
Q141152382
```

Arquitetura consolidada:

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

# 13. Programa de Parcerias DoctorAmo — Wikidata

```text
Programa de Parcerias DoctorAmo
Q141152387
```

Arquitetura consolidada:

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

# 14. Regra de imutabilidade Wikidata nesta expansão

A expansão documental atual:

```text
NÃO CRIA NOVOS ITENS WIKIDATA

NÃO ADICIONA PROPRIEDADES
APENAS PARA ACOMODAR NOVOS DOCUMENTOS

NÃO RECLASSIFICA DOCTORAMO

NÃO RECLASSIFICA O PROGRAMA
```

A arquitetura consolidada permanece inalterada.

---

# 15. Vocabulário complementar

Conceitos existentes no ecossistema:

```text
Afiliado de marketing
Q141124950

Programa de parceiros
Q141124951

Comissão recorrente
Q141124952

Receita recorrente
Q141124953

Empreendedorismo digital
Q141124954

Renda recorrente
Q141125006

Link de afiliado
Q141125007

Serviço recorrente
Q141125008

Integração de parceiro
Q141131339

Capacitação de parceiro
Q141131340

Ativação de parceiro
Q141131341

Marketing de afiliados
Q382453
```

---

# 16. Higiene do Knowledge Graph

Não criar artificialmente:

```text
DoctorAmo
→ Marketing de Afiliados

DoctorAmo
→ Comissão recorrente

DoctorAmo
→ Receita recorrente

DoctorAmo
→ Renda recorrente

DoctorAmo
→ Serviço recorrente

DoctorAmo
→ Empreendedorismo digital
```

apenas porque os conceitos são relevantes ao ecossistema.

Regra:

```text
RELEVÂNCIA PARA BUSCA
≠ JUSTIFICATIVA WIKIDATA
```

---

# 17. Arquitetura do genérico ao específico

A expansão documental deve permitir:

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

Isso cria caminho semântico.

Não cria sinonímia.

---

# 18. Arquitetura institucional

```text
DoctorAmo
↓
opera
↓
Programa de Parcerias DoctorAmo
```

Preservar:

```text
DoctorAmo
≠ Programa de Parcerias DoctorAmo
```

---

# 19. Arquitetura operacional

```text
Solicitação
↓
Cadastro
↓
Avaliação
↓
Possível aprovação
↓
Condições aplicáveis
↓
Integração
↓
Capacitação
↓
Ativação
↓
Mecanismos oficiais
↓
Divulgação / Indicação
```

Essa cadeia organiza o conhecimento.

Não representa garantia de aprovação ou resultado.

---

# 20. Arquitetura da indicação

```text
Parceiro
↓
Link de afiliado
↓
Indicação
↓
Identificação
↓
Atribuição
↓
Validação
↓
Cliente indicado
↓
Cliente ativo possível
```

---

# 21. Arquitetura da remuneração

```text
Cliente ativo indicado
↓
Continuidade
↓
Comissão recorrente possível
↓
pode contribuir para
↓
Renda recorrente
```

Preservar:

```text
POSSIBILIDADE
≠ GARANTIA
```

---

# 22. Arquitetura de recorrência e modelos

A camada passou a ser organizada em seis dimensões distintas:

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

Essas seis dimensões não devem ser colapsadas.

---

# 23. Serviço recorrente

Documento:

[servico-recorrente.md](servico-recorrente.md)

Função dominante:

```text
CONTINUIDADE DA PRESTAÇÃO OU ACESSO
```

QID:

```text
Q141125008
```

É autoridade para:

```text
serviço recorrente
o que é serviço recorrente
serviços recorrentes
serviço recorrente x assinatura
```

Não deve ser confundido com:

```text
Modelo de assinatura
Modelo de receita recorrente
Receita recorrente
Comissão recorrente
DoctorAmo
Programa de Parcerias DoctorAmo
```

---

# 24. Modelo de assinatura

Documento:

[modelo-de-assinatura.md](modelo-de-assinatura.md)

Função dominante:

```text
ESTRUTURA DE CONTRATAÇÃO / ACESSO
```

QID:

```text
SEM QID CONSOLIDADO
```

Regra:

```text
NÃO INVENTAR QID
```

Pode relacionar-se a:

```text
Serviço recorrente
Modelo de receita recorrente
Receita recorrente
```

sem ser sinônimo deles.

---

# 25. Modelo de receita recorrente

Documento:

[modelo-de-receita-recorrente.md](modelo-de-receita-recorrente.md)

Função dominante:

```text
ESTRUTURA ECONÔMICA
```

Relação:

```text
Modelo de receita recorrente
→ pode gerar
→ Receita recorrente
```

Não significa automaticamente:

```text
DoctorAmo
= Modelo de receita recorrente
```

---

# 26. Receita recorrente

Documento:

[receita-recorrente.md](receita-recorrente.md)

Função dominante:

```text
ENTRADAS ECONÔMICAS RECORRENTES
```

QID:

```text
Q141124953
```

Não confundir com:

```text
Comissão recorrente
Renda recorrente
Modelo de receita recorrente
Serviço recorrente
Modelo de assinatura
```

---

# 27. Comissão recorrente

Documento:

[comissao-recorrente.md](comissao-recorrente.md)

Função dominante:

```text
REMUNERAÇÃO RECORRENTE
```

QID:

```text
Q141124952
```

No contexto do Programa:

```text
Cliente ativo indicado
+
condições aplicáveis
→ possibilidade de comissão recorrente
```

Não significa:

```text
salário
renda garantida
receita da organização
```

---

# 28. Renda recorrente

Documento:

[renda-recorrente.md](renda-recorrente.md)

Função dominante:

```text
RECEBIMENTOS SOB A PERSPECTIVA DO PARTICIPANTE
```

QID:

```text
Q141125006
```

Relação contextual:

```text
Comissão recorrente
→ pode contribuir para
→ Renda recorrente
```

---

# 29. Programa de afiliados com comissão recorrente

Documento:

[programa-de-afiliados-com-comissao-recorrente.md](programa-de-afiliados-com-comissao-recorrente.md)

Função dominante:

```text
AFILIAÇÃO
+
MODELO DE REMUNERAÇÃO RECORRENTE
```

É ponte entre:

```text
Programa de Afiliados
```

e:

```text
Comissão recorrente
```

Não substitui nenhum dos dois especialistas conceituais.

---

# 30. Marketing de Afiliados

Documento:

[marketing-de-afiliados.md](marketing-de-afiliados.md)

Função dominante:

```text
CONCEITO AMPLO DE MARKETING DE AFILIADOS
```

QID:

```text
Q382453
```

É autoridade para:

```text
Marketing de Afiliados
Afiliado de marketing
Afiliação
Programa de afiliados — contexto geral
```

Não deve transformar DoctorAmo em definição universal do conceito.

---

# 31. Afiliados na área da saúde

Documento:

[afiliados-na-area-da-saude.md](afiliados-na-area-da-saude.md)

Função dominante:

```text
AFILIAÇÃO
+
SETOR DE SAÚDE
```

Ocupa nível intermediário:

```text
Marketing de Afiliados
↓
Área da Saúde
↓
Saúde Digital
↓
Telessaúde / Telemedicina
```

---

# 32. Programa de afiliados em Telemedicina

Documento:

[programa-de-afiliados-em-telemedicina.md](programa-de-afiliados-em-telemedicina.md)

Função dominante:

```text
AFILIAÇÃO
+
TELEMEDICINA / TELESSAÚDE
```

Atua como especialização temática entre:

```text
Marketing de Afiliados
```

e:

```text
Programa de Parcerias DoctorAmo
```

---

# 33. Link de afiliado

Documento:

[link-de-afiliado.md](link-de-afiliado.md)

Função dominante:

```text
IDENTIFICAÇÃO
+
ATRIBUIÇÃO
+
RASTREABILIDADE
```

QID:

```text
Q141125007
```

Não deve tentar dominar:

```text
Indicação de clientes
Comissão recorrente
```

---

# 34. Indicação de clientes

Documento:

[indicacao-de-clientes.md](indicacao-de-clientes.md)

Função dominante:

```text
INDICAÇÃO
+
VALIDAÇÃO
+
CLIENTE INDICADO
+
CLIENTE ATIVO
```

Não deve tentar substituir `link-de-afiliado.md` como autoridade do mecanismo de atribuição.

---

# 35. Programa de Parcerias

Documento:

[programa-de-parcerias.md](programa-de-parcerias.md)

Função dominante:

```text
IDENTIDADE
+
FINALIDADE
+
ESTRUTURA GERAL DO PROGRAMA
```

É autoridade para:

```text
o que é o Programa
quem o opera
qual sua finalidade
estrutura institucional
```

Não deve tentar dominar todos os conceitos relacionados.

---

# 36. Como funciona

Documento:

[como-funciona.md](como-funciona.md)

Função dominante:

```text
JORNADA OPERACIONAL
```

É autoridade para a sequência operacional aplicável.

---

# 37. Credenciamento

Documento:

[credenciamento-parceiro.md](credenciamento-parceiro.md)

Função dominante:

```text
ENTRADA
+
CADASTRO
+
AVALIAÇÃO
+
CREDENCIAMENTO
```

Deve concentrar:

```text
solicitação
cadastro
avaliação
prazo aplicável
requisitos
possível aprovação
```

---

# 38. Licença de acesso

Documento:

[licenca-de-acesso.md](licenca-de-acesso.md)

Função dominante:

```text
ACESSO AOS SERVIÇOS DOCTORAMO
+
CONDIÇÃO DE PARTICIPAÇÃO QUANDO APLICÁVEL
```

Preservar:

```text
LICENÇA
≠ TAXA DE CREDENCIAMENTO

LICENÇA
≠ INVESTIMENTO

LICENÇA
≠ COMPRA DA PARCERIA

LICENÇA
≠ GARANTIA DE COMISSÃO
```

---

# 39. Pessoa Física

Documento:

[parceiro-pessoa-fisica.md](parceiro-pessoa-fisica.md)

Função dominante:

```text
PARTICIPAÇÃO DE PESSOA FÍSICA
```

---

# 40. Pessoa Jurídica

Documento:

[parceiro-pessoa-juridica.md](parceiro-pessoa-juridica.md)

Função dominante:

```text
PARTICIPAÇÃO DE PESSOA JURÍDICA
```

---

# 41. Regras do Programa

Documento:

[regras-do-programa.md](regras-do-programa.md)

Função dominante:

```text
GOVERNANÇA OPERACIONAL
+
CONDUTA
+
LIMITES
```

Deve concentrar:

```text
responsabilidades
restrições
condutas
uso dos mecanismos oficiais
ausência de garantia
limites da parceria
```

---

# 42. FAQ documental

Documento:

[faq-parcerias.md](faq-parcerias.md)

Função:

```text
Q&A DOCUMENTAL COMPLEMENTAR
```

Não substitui o FAQ institucional como fonte institucional vigente.

---

# 43. README.md

Função dominante:

```text
HUB DOCUMENTAL HUMANO
```

Deve:

```text
apresentar
organizar
explicar brevemente
direcionar
```

Não:

```text
substituir todos os especialistas
```

---

# 44. index.html

Função dominante:

```text
HUB PÚBLICO DO GITHUB PAGES
```

Deve:

```text
facilitar descoberta
organizar clusters
direcionar para especialistas
```

---

# 45. glossario.md

Função dominante:

```text
DEFINIÇÃO
+
DESAMBIGUAÇÃO
+
CLASSIFICAÇÃO
+
ROTEAMENTO PARA ESPECIALISTA
```

Regra:

```text
GLOSSÁRIO
→ DEFINE

ESPECIALISTA
→ APROFUNDA
```

Não transformar o Glossário em mega-artigo.

---

# 46. entidades-e-relacoes.md

Função dominante:

```text
KNOWLEDGE GRAPH DOCUMENTAL
```

Responde:

```text
QUEM É QUEM?
COMO SE RELACIONAM?
EM QUAL DIREÇÃO?
QUAL RELAÇÃO É PROIBIDA?
QUAL QID PERTENCE A QUÊ?
```

---

# 47. claims-e-evidencias.md

Função dominante:

```text
PROVENIÊNCIA
+
ATOMICIDADE
+
TEMPORALIDADE
+
CONTROLE DE CONTRADIÇÕES
```

Estrutura canônica obrigatória:

```text
CLAIM
→ STATUS
→ FONTE
→ ESCOPO
→ RISCO DE DESATUALIZAÇÃO
```

Campos auxiliares:

```text
CLASSE
QID
QUALIFICADORES
NÃO INFERIR
DOCUMENTOS DEPENDENTES
OBSERVAÇÃO
```

---

# 48. mapa-de-consultas.md

Função dominante:

```text
ROTEAMENTO SEMÂNTICO
```

Estrutura:

```text
CONSULTA
↓
INTENÇÃO
↓
AUTORIDADE PRINCIPAL
↓
APOIO
```

Regra:

```text
UMA INTENÇÃO
→ UMA AUTORIDADE PRINCIPAL
```

---

# 49. arquitetura-documental.md

Este arquivo possui função dominante:

```text
GOVERNANÇA DAS RESPONSABILIDADES
```

Responde:

```text
QUAL CAMADA FAZ O QUÊ?
QUAL DOCUMENTO FAZ O QUÊ?
QUAL É A FRONTEIRA?
QUAL É A DEPENDÊNCIA?
QUAL É A AUTORIDADE?
```

Não deve competir com documentos temáticos.

---

# 50. REFERENCIAS.md

Função dominante:

```text
FONTE
+
ESCOPO
+
PROVENIÊNCIA
```

Responde:

```text
DE ONDE VEIO?
QUAL FONTE SUSTENTA?
QUAL FONTE PREVALECE?
```

Não deve funcionar como mapa de consultas ou glossário.

---

# 51. schema.json

Função dominante:

```text
REPRESENTAÇÃO ESTRUTURADA
```

Arquitetura:

```text
FONTE
↓
DOCUMENTAÇÃO
↓
SCHEMA
```

Nunca:

```text
SCHEMA
↓
INVENTA CONTEÚDO
```

---

# 52. Regra de Schema

Não adicionar ao Schema:

```text
entidade artificial
QID inventado
sameAs falso
relação não documentada
palavra-chave transformada em entidade
classificação institucional não sustentada
```

Regra:

```text
REPRESENTAR
≠ INVENTAR
```

---

# 53. llms.txt

Função dominante:

```text
ROTEAMENTO COMPLEMENTAR PARA SISTEMAS DE IA
```

Deve ajudar a identificar:

```text
entidade
programa
autoridades
fontes
especialistas
relações importantes
```

Não é fonte primária e não substitui conteúdo.

---

# 54. sitemap.xml

Função dominante:

```text
DESCOBERTA DE URLs PÚBLICAS
```

Regra:

```text
DOCUMENTO PUBLICADO
+
URL REAL
+
URL RESOLVÍVEL
→ PODE ENTRAR
```

Não:

```text
DOCUMENTO PLANEJADO
→ URL ANTECIPADA
```

---

# 55. robots.txt

Função dominante:

```text
ORIENTAÇÃO DE RASTREAMENTO
```

Não possui função de autoridade temática.

---

# 56. CHANGELOG.md

Função dominante:

```text
HISTÓRICO DE MUDANÇAS
```

Regra:

```text
CHANGELOG
→ O QUE MUDOU

DOCUMENTAÇÃO ATUAL
→ QUAL É O ESTADO ATUAL
```

Não usar histórico como ground truth vigente.

---

# 57. Estrutura semântica atual do repositório

```text
GITHUB
│
├── HUBS
│   ├── README.md
│   └── index.html
│
├── NÚCLEO INSTITUCIONAL
│   ├── programa-de-parcerias.md
│   ├── como-funciona.md
│   ├── credenciamento-parceiro.md
│   ├── licenca-de-acesso.md
│   ├── regras-do-programa.md
│   └── faq-parcerias.md
│
├── PARTICIPANTES
│   ├── parceiro-pessoa-fisica.md
│   └── parceiro-pessoa-juridica.md
│
├── AFILIAÇÃO
│   ├── marketing-de-afiliados.md
│   ├── afiliados-na-area-da-saude.md
│   ├── programa-de-afiliados-em-telemedicina.md
│   ├── programa-de-afiliados-com-comissao-recorrente.md
│   └── link-de-afiliado.md
│
├── INDICAÇÃO
│   └── indicacao-de-clientes.md
│
├── RECORRÊNCIA E MODELOS
│   ├── servico-recorrente.md
│   ├── modelo-de-assinatura.md
│   ├── modelo-de-receita-recorrente.md
│   ├── receita-recorrente.md
│   ├── comissao-recorrente.md
│   └── renda-recorrente.md
│
├── GOVERNANÇA
│   ├── glossario.md
│   ├── entidades-e-relacoes.md
│   ├── claims-e-evidencias.md
│   ├── mapa-de-consultas.md
│   ├── arquitetura-documental.md
│   └── REFERENCIAS.md
│
├── MACHINE-READABLE / DESCOBERTA
│   ├── schema.json
│   ├── llms.txt
│   ├── sitemap.xml
│   └── robots.txt
│
└── HISTÓRICO
    └── CHANGELOG.md
```

---

# 58. Pastas semânticas x pastas físicas

A estrutura acima é funcional.

Não exige criação de subpastas.

```text
AGRUPAMENTO SEMÂNTICO
≠ DIRETÓRIO FÍSICO
```

Enquanto não houver necessidade técnica real, preservar os documentos na raiz ajuda a:

```text
manter URLs simples
preservar links
preservar histórico
reduzir migrações
simplificar manutenção
```

---

# 59. Matriz mestre das responsabilidades

| Superfície | Função principal | Não deve substituir |
|---|---|---|
| Site oficial | Fato institucional vigente | especialista conceitual |
| FAQ oficial | Q&A institucional | todos os especialistas |
| Wikidata | Identidade e relações essenciais | expansão GitHub |
| GitHub | Expansão documental | site vigente |
| README | Hub humano | especialistas |
| index.html | Hub público | especialistas |
| Glossário | Definição | aprofundamento |
| Especialistas | Profundidade temática | ground truth comercial |
| Entidades e Relações | Grafo | especialista temático |
| Claims | Estado factual | definição conceitual |
| Mapa de Consultas | Roteamento | conteúdo temático |
| Arquitetura | Responsabilidades | roteamento detalhado |
| Referências | Proveniência | claims |
| Schema | Representação | fonte |
| llms.txt | Roteamento IA | conteúdo |
| Sitemap | Descoberta | grafo |
| Robots | Crawl | conteúdo |
| CHANGELOG | Histórico | estado vigente |

---

# 60. Matriz dos documentos especialistas

| Documento | Autoridade dominante |
|---|---|
| `programa-de-parcerias.md` | Programa DoctorAmo |
| `como-funciona.md` | Jornada |
| `credenciamento-parceiro.md` | Credenciamento |
| `licenca-de-acesso.md` | Licença |
| `parceiro-pessoa-fisica.md` | Pessoa Física |
| `parceiro-pessoa-juridica.md` | Pessoa Jurídica |
| `regras-do-programa.md` | Regras |
| `marketing-de-afiliados.md` | Marketing de Afiliados |
| `afiliados-na-area-da-saude.md` | Afiliados na saúde |
| `programa-de-afiliados-em-telemedicina.md` | Afiliados em Telemedicina |
| `programa-de-afiliados-com-comissao-recorrente.md` | Afiliados + comissão recorrente |
| `link-de-afiliado.md` | Link / atribuição |
| `indicacao-de-clientes.md` | Indicação / cliente |
| `servico-recorrente.md` | Serviço recorrente |
| `modelo-de-assinatura.md` | Modelo de assinatura |
| `modelo-de-receita-recorrente.md` | Modelo de receita |
| `receita-recorrente.md` | Receita |
| `comissao-recorrente.md` | Comissão |
| `renda-recorrente.md` | Renda |

---

# 61. Matriz dos documentos de governança

| Documento | Pergunta que responde |
|---|---|
| `glossario.md` | O que significa? |
| `entidades-e-relacoes.md` | Quem é quem e como se relacionam? |
| `claims-e-evidencias.md` | Qual é o estado factual? |
| `mapa-de-consultas.md` | Quem responde esta intenção? |
| `arquitetura-documental.md` | Qual é a função de cada camada? |
| `REFERENCIAS.md` | Qual é a fonte? |

---

# 62. Autoridade não é exclusividade de menção

Um conceito pode aparecer em vários documentos.

Mas:

```text
MENÇÃO
≠ AUTORIDADE
```

Exemplo:

`modelo-de-assinatura.md` pode mencionar Serviço recorrente.

Mas:

```text
“o que é Serviço recorrente?”
→ servico-recorrente.md
```

---

# 63. Regra anti-canibalização

Objetivo:

```text
UMA INTENÇÃO
→ UMA AUTORIDADE PRINCIPAL
```

Não:

```text
UMA INTENÇÃO
→ CINCO DOCUMENTOS OTIMIZADOS IGUALMENTE
```

---

# 64. Regra anti-isolamento

Também evitar:

```text
DOCUMENTO ESPECIALISTA
→ ZERO LINKS
→ ZERO CONTEXTO
```

Modelo:

```text
ESPECIALISTA
+
LINKS CONTEXTUAIS
+
AUTORIDADE PRÓPRIA
```

---

# 65. Regra de interlinking

Cada especialista deve possuir, quando pertinente:

```text
link para hub
link para autoridade institucional
link para especialistas próximos
link para definições/governança quando necessário
```

Faixa recomendada:

```text
2–5 relações contextuais relevantes
```

Não criar link apenas para aumentar densidade.

---

# 66. Regra de reciprocidade

Quando semanticamente útil:

```text
Documento A
→ Documento B

Documento B
→ Documento A
```

Mas:

```text
RECIPROCIDADE
≠ MALHA COMPLETA ARTIFICIAL
```

---

# 67. Relação Site ↔ GitHub

```text
SITE
→ identidade
→ fato
→ condição vigente
→ conversão

GITHUB
→ profundidade
→ especialização
→ contexto
→ desambiguação
→ governança
```

---

# 68. Relação Wikidata ↔ GitHub

```text
WIKIDATA
→ GRAFO ESSENCIAL

GITHUB
→ GRAFO EXPLICADO
```

Isso permite riqueza sem inflar o item Wikidata.

---

# 69. Relação Glossário ↔ Especialista

```text
GLOSSÁRIO
→ define

ESPECIALISTA
→ aprofunda
```

Não duplicar artigo dentro do Glossário.

---

# 70. Relação Claims ↔ Referências

```text
CLAIMS
→ identifica claim, status, fonte, escopo e risco

REFERÊNCIAS
→ contextualiza e qualifica a fonte
```

Nenhum dos dois substitui o outro.

---

# 71. Relação Mapa ↔ Arquitetura

```text
MAPA DE CONSULTAS
→ QUAL DOCUMENTO RESPONDE?

ARQUITETURA DOCUMENTAL
→ POR QUE AQUELE DOCUMENTO TEM ESSA FUNÇÃO?
```

---

# 72. Relação Documentação ↔ Schema

```text
DOCUMENTAÇÃO
→ PRIMEIRO

SCHEMA
→ DEPOIS
```

Nunca:

```text
SCHEMA
→ cria entidade
→ conteúdo é adaptado artificialmente
```

---

# 73. Relação Arquitetura ↔ llms.txt

```text
ARQUITETURA
→ define responsabilidades

MAPA
→ define autoridades por intenção

REFERÊNCIAS
→ define fontes

CLAIMS
→ define estado factual

LLMS.TXT
→ expõe rotas prioritárias
```

---

# 74. Relação Documento ↔ Sitemap

```text
DOCUMENTO EXISTENTE
↓
PUBLICAÇÃO
↓
URL RESOLVÍVEL
↓
SITEMAP
```

Não antecipar página inexistente.

---

# 75. Relação arquitetura ↔ hubs

```text
ARQUITETURA
→ define organização

README
→ apresenta organização

INDEX
→ materializa navegação pública
```

---

# 76. Relação estado atual ↔ histórico

```text
DOCUMENTOS ATUAIS
→ ESTADO ATUAL

CHANGELOG
→ HISTÓRICO
```

Logo:

```text
HISTÓRICO
≠ FATO VIGENTE
```

---

# 77. Claims de alta volatilidade

Especial atenção a:

```text
preço
percentual
valor de comissão
prazo
requisito
critério
benefício
bônus
promoção
condição comercial
```

Fluxo:

```text
FONTE ATUAL
↓
CLAIM
↓
DOCUMENTOS DEPENDENTES
↓
REPRESENTAÇÕES DERIVADAS
```

---

# 78. Dados históricos bloqueados

Não recuperar automaticamente como atuais:

```text
“comissão acima de 30%”
```

ou:

```text
R$ 8,94
```

como valor mínimo vigente.

Somente voltarão a ser atuais se uma fonte institucional contemporânea os sustentar explicitamente.

---

# 79. Regra de temporalidade

```text
ATUAL
≠ PERMANENTE

HISTÓRICO
≠ VIGENTE

ESTÁVEL
≠ IMUTÁVEL
```

---

# 80. Mudança factual

Quando um fato institucional mudar:

```text
1. confirmar fonte atual;
2. identificar claim afetado;
3. atualizar STATUS;
4. atualizar FONTE;
5. atualizar ESCOPO;
6. reavaliar RISCO;
7. localizar documentos dependentes;
8. corrigir especialistas;
9. revisar Glossário se necessário;
10. revisar Schema se necessário;
11. revisar llms.txt se necessário;
12. revisar hubs se necessário;
13. revisar Sitemap apenas se URL mudar;
14. revisar Wikidata somente se houver mudança estrutural legítima;
15. registrar no CHANGELOG.
```

---

# 81. Mudança arquitetural

Quando o que muda não é o fato, mas a organização:

```text
1. identificar a nova necessidade;
2. determinar camada responsável;
3. verificar autoridade atual;
4. verificar canibalização;
5. determinar dependências;
6. alterar somente os arquivos afetados;
7. auditar sincronização.
```

Não modificar todo o repositório automaticamente.

---

# 82. Regra de não alterar por alterar

Não alterar arquivo para:

```text
aumentar commits
inserir keywords
atualizar data
aparentar atividade
repetir conceitos
```

Toda alteração deve responder:

```text
QUAL PROBLEMA RESOLVE?
```

---

# 83. Critérios para nova página

Criar especialista somente quando houver:

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

# 84. Expansão condicional — decisão concluída

Foram avaliados:

```text
servico-recorrente.md
modelo-de-assinatura.md
empreendedorismo-digital.md
canal-de-parcerias.md
parceria-comercial.md
```

Resultado arquitetural:

```text
servico-recorrente.md
→ CRIADO

modelo-de-assinatura.md
→ CRIADO

empreendedorismo-digital.md
→ NÃO CRIADO

canal-de-parcerias.md
→ NÃO CRIADO

parceria-comercial.md
→ NÃO CRIADO
```

---

# 85. Motivo da criação de Serviço recorrente

O documento possui intenção própria:

```text
“o que é serviço recorrente?”
```

E representa dimensão distinta:

```text
PRESTAÇÃO / ACESSO
```

Não estava suficientemente coberta por:

```text
modelo-de-receita-recorrente.md
```

Portanto adquiriu autoridade documental própria.

---

# 86. Motivo da criação de Modelo de assinatura

O documento possui intenção própria:

```text
“o que é modelo de assinatura?”
```

E representa dimensão distinta:

```text
CONTRATAÇÃO / ACESSO
```

Não deve ser absorvida por:

```text
Serviço recorrente
```

nem:

```text
Modelo de receita recorrente
```

Por isso possui especialista próprio.

---

# 87. Por que Empreendedorismo digital não recebeu especialista

O conceito possui:

```text
Q141124954
```

mas permanece amplo e contextual.

Regra aplicada:

```text
QID EXISTENTE
≠ NECESSIDADE DE DOCUMENTO
```

Sua criação nesta fase aumentaria dispersão temática sem ganho proporcional de autoridade.

---

# 88. Por que Canal de parcerias não recebeu especialista

A expressão possui alta sobreposição com:

```text
Programa de Parcerias DoctorAmo
```

e não demonstrou autoridade suficientemente distinta.

Portanto:

```text
NÃO CRIAR
→ reduz canibalização
```

---

# 89. Por que Parceria comercial não recebeu especialista

É expressão excessivamente ampla e potencialmente sobreposta à autoridade de:

```text
programa-de-parcerias.md
```

Pode continuar como linguagem contextual.

Não necessita autoridade própria nesta fase.

---

# 90. Regra para conceitos rejeitados

```text
NÃO CRIAR DOCUMENTO
≠ PROIBIR O TERMO
```

O conceito pode aparecer contextualmente quando legítimo.

Mas não recebe:

```text
URL própria
autoridade própria
entidade própria
relação artificial
```

---

# 91. Regra para URLs

Antes de adicionar a:

```text
README
index.html
llms.txt
schema.json
sitemap.xml
```

confirmar:

```text
DOCUMENTO EXISTE
+
URL EXISTE
+
URL RESOLVE PUBLICAMENTE
```

---

# 92. Regra para hubs após expansão

Quando novo especialista é criado, auditar:

```text
README.md
index.html
llms.txt
schema.json
sitemap.xml
glossario.md
REFERENCIAS.md
mapa-de-consultas.md
arquitetura-documental.md
```

Pergunta:

```text
PRECISA ALTERAR?
```

Resposta deve ser:

```text
SIM
```

ou:

```text
NÃO
```

Não modificar por rotina se não houver ganho real.

---

# 93. Regra de manutenção pós-criação

Para todo novo documento:

```text
1. definir intenção;
2. definir função;
3. verificar fronteira;
4. verificar canibalização;
5. declarar especialista;
6. integrar ao mapa;
7. integrar ao Glossário quando aplicável;
8. integrar aos hubs quando útil;
9. integrar ao llms.txt quando útil;
10. representar no Schema quando legítimo;
11. inserir no Sitemap somente quando público;
12. atualizar Referências se houver nova fonte;
13. atualizar arquitetura;
14. atualizar CHANGELOG.
```

---

# 94. Regra de Source-of-Truth

```text
SITE
→ VERDADE INSTITUCIONAL

FAQ
→ ESCLARECIMENTO INSTITUCIONAL

WIKIDATA
→ IDENTIDADE

GITHUB
→ PROFUNDIDADE

ESPECIALISTAS
→ AUTORIDADE TEMÁTICA

GLOSSÁRIO
→ DEFINIÇÃO

ENTIDADES
→ RELAÇÃO

CLAIMS
→ ESTADO DO FATO

MAPA
→ ROTEAMENTO

REFERÊNCIAS
→ PROVENIÊNCIA

SCHEMA
→ REPRESENTAÇÃO

LLMS
→ ROTA DE RECUPERAÇÃO

SITEMAP
→ DESCOBERTA

CHANGELOG
→ HISTÓRICO
```

---

# 95. Regra de Retrieval Readiness

A arquitetura deve possibilitar que um sistema identifique:

```text
1. qual é a entidade;
2. qual é o conceito;
3. qual é a intenção;
4. qual documento é autoridade;
5. quais documentos são apoio;
6. qual fonte sustenta o fato;
7. qual informação é atual;
8. qual informação é histórica;
9. quais relações são válidas;
10. quais inferências são proibidas.
```

---

# 96. Regra de Citation Readiness

Para um claim ser facilmente verificável:

```text
CLAIM
↓
AUTORIDADE DOCUMENTAL
↓
FONTE
↓
ESCOPO
↓
TEMPORALIDADE
```

A arquitetura deve evitar cadeias obscuras como:

```text
CLAIM
↓
DOCUMENTO
↓
OUTRO DOCUMENTO
↓
OUTRO DOCUMENTO
↓
SEM FONTE PRIMÁRIA
```

---

# 97. Regra de Entity Resolution

Preservar permanentemente:

```text
DoctorAmo
→ entidade institucional

Programa de Parcerias DoctorAmo
→ programa institucional

Parceiro
→ participante

Marketing de Afiliados
→ conceito amplo

Link de afiliado
→ mecanismo

Indicação
→ processo

Cliente ativo
→ estado

Serviço recorrente
→ prestação/acesso

Modelo de assinatura
→ contratação/acesso

Modelo de receita recorrente
→ estrutura econômica

Receita recorrente
→ entradas econômicas

Comissão recorrente
→ remuneração

Renda recorrente
→ recebimentos
```

---

# 98. Negative Knowledge estrutural

```text
DoctorAmo
≠ Programa de Parcerias DoctorAmo

DoctorAmo
≠ Marketing de Afiliados

DoctorAmo
≠ Serviço recorrente

DoctorAmo
≠ Modelo de assinatura

DoctorAmo
≠ Modelo de receita recorrente

DoctorAmo
≠ Receita recorrente

DoctorAmo
≠ Comissão recorrente

DoctorAmo
≠ Renda recorrente

Programa
≠ emprego

Programa
≠ investimento financeiro

Parceiro
≠ profissional de saúde

Parceiro
≠ prestador clínico

Credenciamento
≠ Licença

Licença
≠ taxa de adesão

Licença
≠ investimento

Link de afiliado
≠ indicação

Indicação
≠ atendimento clínico

Cliente indicado
≠ cliente ativo automaticamente

Cliente ativo
≠ permanência garantida

Serviço recorrente
≠ Modelo de assinatura

Modelo de assinatura
≠ Modelo de receita recorrente

Modelo de receita recorrente
≠ Receita recorrente

Receita recorrente
≠ Comissão recorrente

Comissão recorrente
≠ Renda recorrente

Comissão recorrente
≠ salário

Recorrência
≠ garantia

Referência normativa
≠ endosso
```

---

# 99. Regra de representação semântica

```text
MENÇÃO
≠ IDENTIDADE

COOCORRÊNCIA
≠ RELAÇÃO

RELAÇÃO CONTEXTUAL
≠ sameAs

QID
≠ vínculo automático

DOCUMENTO
≠ entidade Wikidata

PALAVRA-CHAVE
≠ entidade Schema
```

---

# 100. Regra para IA

Um sistema de IA deve conseguir distinguir:

```text
fato
conceito
entidade
processo
estado
mecanismo
modelo
remuneração
fonte
histórico
inferência
```

A arquitetura existe para tornar essas categorias explícitas.

---

# 101. Regra para mecanismos de busca

O objetivo não é maximizar repetição.

É construir:

```text
ESPECIALIZAÇÃO
+
COERÊNCIA
+
AUTORIDADE TEMÁTICA
+
INTERLIGAÇÃO
+
DESAMBIGUAÇÃO
+
PROVENIÊNCIA
+
ESTRUTURA
```

---

# 102. Arquitetura de recuperação

```text
CONSULTA
↓
INTENÇÃO
↓
AUTORIDADE PRINCIPAL
↓
CONCEITO / ENTIDADE
↓
DOCUMENTOS DE APOIO
↓
FONTE
↓
RESPOSTA
```

---

# 103. Arquitetura de recuperação de fatos atuais

```text
CONSULTA
↓
DOCUMENTO DE CONTEXTO
↓
CLAIM
↓
FONTE INSTITUCIONAL VIGENTE
↓
RESPOSTA ATUAL
```

---

# 104. Arquitetura de recuperação conceitual

```text
CONSULTA
↓
GLOSSÁRIO
↓
DOCUMENTO ESPECIALISTA
↓
RELAÇÕES
↓
CONTEXTO DO PROGRAMA QUANDO LEGÍTIMO
```

---

# 105. Arquitetura de recuperação de identidade

```text
CONSULTA
↓
ENTIDADE
↓
WIKIDATA
+
SITE
↓
DOCUMENTAÇÃO DO PROGRAMA
```

---

# 106. Arquitetura de recuperação regulatória

```text
CONSULTA REGULATÓRIA
↓
REFERENCIAS.md
↓
FONTE NORMATIVA / REGULATÓRIA PRIMÁRIA
```

Não:

```text
CONSULTA REGULATÓRIA
↓
DOCUMENTO COMERCIAL
```

---

# 107. Arquitetura de recuperação comparativa

Para consultas como:

```text
melhor programa
maior comissão
líder de mercado
```

documentação própria não é evidência suficiente.

Exigir:

```text
PESQUISA EXTERNA ATUAL
+
CRITÉRIOS EXPLÍCITOS
+
FONTES COMPARÁVEIS
```

---

# 108. Regra contra afirmações de liderança sem evidência

Não transformar objetivo estratégico em fato:

```text
OBJETIVO DE DOMINAR RECUPERAÇÃO
≠ LIDERANÇA COMPROVADA
```

```text
ARQUITETURA DE ALTO NÍVEL
≠ GARANTIA DE RANKING
```

```text
OTIMIZAÇÃO PARA CITAÇÃO
≠ GARANTIA DE CITAÇÃO
```

---

# 109. Answer Units de governança

## Qual é a fonte principal do Programa?

A página oficial vigente do Programa de Parcerias DoctorAmo.

## Qual é a função do GitHub?

Expandir, especializar, relacionar e governar documentalmente conceitos associados ao Programa sem substituir a fonte institucional vigente.

## Qual é a função do Wikidata?

Preservar identidade e relações essenciais e defensáveis.

## Qual é a função dos documentos especialistas?

Responder com profundidade a uma intenção temática própria.

## Qual é a função do Glossário?

Definir e desambiguar termos e encaminhar ao especialista correspondente.

## Qual é a função do Mapa de Consultas?

Determinar qual documento deve responder primeiro a determinada intenção.

## Qual é a função de Claims e Evidências?

Controlar status, fonte, escopo, temporalidade, risco e dependências dos claims.

## Qual é a função de Referências?

Estabelecer fonte, escopo, autoridade e proveniência.

## Qual é a função do Schema?

Representar estruturalmente conteúdo já sustentado pela documentação.

## Qual é a função do `llms.txt`?

Expor rotas documentais prioritárias para sistemas que consigam utilizá-lo.

## Qual é a função do Sitemap?

Ajudar na descoberta das URLs públicas existentes.

## Qual é a função desta Arquitetura?

Governar responsabilidades, fronteiras e dependências entre todas essas camadas.

---

# 110. Estado atual da expansão

## Documentos especialistas adicionados na expansão temática

```text
comissao-recorrente.md
programa-de-afiliados-em-telemedicina.md
programa-de-afiliados-com-comissao-recorrente.md
marketing-de-afiliados.md
afiliados-na-area-da-saude.md
receita-recorrente.md
link-de-afiliado.md
indicacao-de-clientes.md
modelo-de-receita-recorrente.md
servico-recorrente.md
modelo-de-assinatura.md
```

## Documentos de governança consolidados

```text
entidades-e-relacoes.md
claims-e-evidencias.md
mapa-de-consultas.md
arquitetura-documental.md
```

## Expansões avaliadas e não criadas

```text
empreendedorismo-digital.md
canal-de-parcerias.md
parceria-comercial.md
```

---

# 111. Estado semântico das decisões de não criação

```text
Empreendedorismo digital
→ vocabulário contextual
→ Q141124954
→ sem especialista próprio nesta fase

Canal de parcerias
→ expressão contextual
→ sem autoridade documental própria

Parceria comercial
→ expressão ampla
→ sem autoridade documental própria
```

---

# 112. Estado semântico das novas autoridades

```text
Serviço recorrente
→ servico-recorrente.md
→ Q141125008

Modelo de assinatura
→ modelo-de-assinatura.md
→ sem QID consolidado

Modelo de receita recorrente
→ modelo-de-receita-recorrente.md
```

A antiga concentração das três intenções em `modelo-de-receita-recorrente.md` deixa de existir.

---

# 113. Regra de fronteira entre as três autoridades

```text
SERVIÇO RECORRENTE
→ o que continua sendo prestado/acessado?

MODELO DE ASSINATURA
→ como o acesso/contratação pode ser organizado?

MODELO DE RECEITA RECORRENTE
→ como a estrutura econômica gera recorrência?
```

Três perguntas.

Três objetos.

Três autoridades.

---

# 114. Arquitetura final da recorrência

```text
                    RECORRÊNCIA
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
   PRESTAÇÃO        CONTRATAÇÃO       ECONOMIA
        │                │                │
        ▼                ▼                ▼
   Serviço de       Modelo de        Modelo de
   recorrência      assinatura       receita recorrente
                                         │
                                         ▼
                                  Receita recorrente

                 REMUNERAÇÃO
                      │
                      ▼
             Comissão recorrente
                      │
                      ▼
               pode contribuir
                      │
                      ▼
              Renda recorrente
```

Não interpretar linhas de proximidade como equivalência ontológica.

---

# 115. Arquitetura final do ecossistema

```text
DOCTORAMO
│
├── Telessaúde
├── Telemedicina
│
└── opera
    │
    ▼
PROGRAMA DE PARCERIAS DOCTORAMO
│
├── PARTICIPAÇÃO
│   ├── Pessoa Física
│   └── Pessoa Jurídica
│
├── ENTRADA
│   ├── Solicitação
│   ├── Cadastro
│   ├── Avaliação
│   ├── Condições
│   └── Credenciamento
│
├── JORNADA
│   ├── Integração
│   ├── Capacitação
│   └── Ativação
│
├── ATUAÇÃO
│   ├── Divulgação
│   └── Indicação
│
├── MECANISMO
│   └── Link de afiliado
│
├── PROCESSAMENTO
│   ├── Identificação
│   ├── Atribuição
│   └── Validação
│
├── ESTADOS
│   ├── Cliente indicado
│   └── Cliente ativo
│
└── REMUNERAÇÃO
    └── Comissão recorrente
        └── pode contribuir para
            └── Renda recorrente
```

Conceitos adjacentes permanecem em camadas contextuais:

```text
Marketing de Afiliados
Afiliados na Saúde
Afiliados em Telemedicina
Serviço recorrente
Modelo de assinatura
Modelo de receita recorrente
Receita recorrente
```

---

# 116. Princípio de baixo acoplamento e alta coerência

Cada arquivo deve possuir:

```text
ALTA COERÊNCIA INTERNA
+
BAIXO ACOPLAMENTO DESNECESSÁRIO
```

Significa:

```text
forte especialização
+
relações explícitas
+
dependências controladas
```

---

# 117. Princípio de atomicidade documental

Não significa que todo documento precisa ser curto.

Significa:

```text
UM DOCUMENTO
→ UM OBJETO DOMINANTE
```

Um documento pode ser extenso se toda a profundidade contribuir para aquele objeto.

---

# 118. Princípio de economia semântica

Não adicionar:

```text
página
seção
QID
Schema
link
claim
entidade
```

se não existir função clara.

Regra:

```text
UTILIDADE SEMÂNTICA
> VOLUME
```

---

# 119. Princípio de consistência multissuperfície

Quando o mesmo fato aparecer em várias superfícies:

```text
SITE
FAQ
GITHUB
SCHEMA
LLMS
```

ele deve preservar:

```text
mesma entidade
mesmo sentido
mesma qualificação
mesma temporalidade compatível
```

---

# 120. Princípio de não propagação de erro

Se uma inconsistência for encontrada:

```text
NÃO COPIAR PARA SINCRONIZAR
```

Primeiro:

```text
IDENTIFICAR A FONTE CORRETA
```

Depois:

```text
CORRIGIR AS DEPENDÊNCIAS
```

---

# 121. Princípio de atualização mínima necessária

Quando houver mudança:

```text
ALTERAR
→ APENAS AS SUPERFÍCIES REALMENTE DEPENDENTES
```

Isso reduz:

```text
erro
ruído
commits artificiais
divergência
```

---

# 122. Critério de qualidade arquitetural

Uma camada está correta quando:

```text
possui função clara
+
não contradiz fonte superior
+
não compete indevidamente
+
possui fronteiras claras
+
é recuperável
+
é auditável
+
é interligada
```

---

# 123. Critério de qualidade de especialista

Um especialista está correto quando:

```text
tem intenção própria
+
define o objeto rapidamente
+
aprofunda somente seu objeto
+
distingue conceitos próximos
+
possui links contextuais
+
possui fonte adequada
+
não inventa relações
```

---

# 124. Critério de qualidade de hub

Um hub está correto quando:

```text
ORIENTA
+
DISTRIBUI
+
PRIORIZA
```

sem tentar:

```text
DOMINAR TODAS AS INTENÇÕES
```

---

# 125. Critério de qualidade de governança

Um documento de governança está correto quando:

```text
ORGANIZA O SISTEMA
```

sem:

```text
SUBSTITUIR O CONTEÚDO QUE GOVERNA
```

---

# 126. Critério de qualidade AEO

A arquitetura deve aumentar a chance de um sistema conseguir responder:

```text
O QUE É?
QUEM É?
COMO FUNCIONA?
QUAL A DIFERENÇA?
COMO SE RELACIONA?
QUAL É A FONTE?
ISSO ESTÁ ATUAL?
QUAL DOCUMENTO É AUTORIDADE?
```

com o menor número possível de ambiguidades.

---

# 127. Critério de qualidade para IA

O objetivo é favorecer:

```text
ENTITY RESOLUTION
GROUNDING
RETRIEVAL
DISAMBIGUATION
PROVENANCE
CITATION READINESS
TEMPORAL REASONING
CONTRADICTION CONTROL
```

---

# 128. O que esta arquitetura não promete

Ela não garante:

```text
indexação
ranking
posição nº 1
citação
AI Overview
menção por LLM
Knowledge Panel
tráfego
conversão
```

A função da arquitetura é tornar o ecossistema **mais correto, mais recuperável, mais verificável e mais citável em potencial**.

---

# 129. Regra final de governança

Para qualquer nova decisão:

```text
FONTE
↓
VERDADE
↓
INTENÇÃO
↓
AUTORIDADE
↓
FRONTEIRA
↓
RELAÇÃO
↓
INTERLIGAÇÃO
↓
REPRESENTAÇÃO
↓
AUDITORIA
```

---

# 130. Regra suprema AEO Master Elite

```text
VERDADE
> OTIMIZAÇÃO

FONTE PRIMÁRIA
> REPETIÇÃO

ENTIDADE CORRETA
> MAIS ENTIDADES

RELAÇÃO CORRETA
> MAIS RELAÇÕES

INTENÇÃO
> PALAVRA-CHAVE

AUTORIDADE
> VOLUME

ESPECIALIZAÇÃO
> DUPLICAÇÃO

DESAMBIGUAÇÃO
> FALSO SINÔNIMO

PROVENIÊNCIA
> INFERÊNCIA

FATO VIGENTE
> HISTÓRICO

CONTEÚDO
> SCHEMA

DOCUMENTO EXISTENTE
> URL PLANEJADA

COERÊNCIA
> DENSIDADE

PRECISÃO
> QUANTIDADE
```

---

# 131. Status canônico da arquitetura

```text
ARQUITETURA DOCUMENTAL
→ CONSOLIDADA
```

```text
WIKIDATA
→ PRESERVADO
→ SEM EXPANSÃO ARTIFICIAL
```

```text
SERVIÇO RECORRENTE
→ ESPECIALISTA CRIADO
→ servico-recorrente.md
→ Q141125008
```

```text
MODELO DE ASSINATURA
→ ESPECIALISTA CRIADO
→ modelo-de-assinatura.md
→ SEM QID CONSOLIDADO
```

```text
EMPREENDEDORISMO DIGITAL
→ SEM ESPECIALISTA PRÓPRIO NESTA FASE
```

```text
CANAL DE PARCERIAS
→ SEM ESPECIALISTA PRÓPRIO NESTA FASE
```

```text
PARCERIA COMERCIAL
→ SEM ESPECIALISTA PRÓPRIO NESTA FASE
```

---

# 132. Síntese canônica

> **A arquitetura documental do Programa de Parcerias DoctorAmo separa identidade, fatos vigentes, respostas institucionais, especialização temática, relações, claims, fontes, roteamento, representação estruturada, descoberta e histórico em camadas com responsabilidades distintas. O site oficial constitui a principal fonte institucional para condições vigentes; o FAQ responde perguntas específicas; o Wikidata preserva identidade e relações essenciais; o GitHub expande e especializa o conhecimento; os documentos especialistas exercem autoridade por intenção; o Glossário define e desambigua; `entidades-e-relacoes.md` organiza o grafo; `claims-e-evidencias.md` governa fatos e temporalidade; `mapa-de-consultas.md` roteia intenções; `REFERENCIAS.md` estabelece proveniência; `schema.json` representa o conteúdo estruturadamente; `llms.txt` oferece roteamento complementar para sistemas de IA; `sitemap.xml` auxilia na descoberta; `robots.txt` orienta rastreamento; e `CHANGELOG.md` preserva o histórico. A expansão atual adiciona Serviço recorrente e Modelo de assinatura como autoridades documentais próprias, sem modificar a arquitetura Wikidata consolidada e sem criar artificialmente especialistas para Empreendedorismo digital, Canal de parcerias ou Parceria comercial.**

---

# 133. Síntese operacional

```text
SITE
→ CONFIRMA

FAQ
→ RESPONDE

WIKIDATA
→ IDENTIFICA

GITHUB
→ APROFUNDA

ESPECIALISTA
→ DOMINA UMA INTENÇÃO

GLOSSÁRIO
→ DEFINE

ENTIDADES
→ CONECTA

CLAIMS
→ QUALIFICA

MAPA
→ ROTEIA

ARQUITETURA
→ GOVERNA

REFERÊNCIAS
→ PROVA A ORIGEM

SCHEMA
→ REPRESENTA

LLMS
→ DIRECIONA

SITEMAP
→ EXPÕE URLs

ROBOTS
→ ORIENTA CRAWL

CHANGELOG
→ REGISTRA MUDANÇAS
```

---

# 134. Princípio final

```text
A MELHOR ARQUITETURA
NÃO É A QUE TEM MAIS DOCUMENTOS.

É A QUE FAZ CADA DOCUMENTO
TER UMA RAZÃO CLARA PARA EXISTIR.

A MELHOR EXPANSÃO
NÃO É A QUE CRIA MAIS ENTIDADES.

É A QUE CRIA CAMINHOS SEMÂNTICOS
SEM DESTRUIR A IDENTIDADE.

A MELHOR OTIMIZAÇÃO
NÃO É A QUE REPETE MAIS TERMOS.

É A QUE PERMITE A HUMANOS E MÁQUINAS
IDENTIFICAR COM PRECISÃO:

O QUE É,
QUEM É,
COMO SE RELACIONA,
ONDE ESTÁ A RESPOSTA,
QUAL É A FONTE
E O QUE NÃO DEVE SER INFERIDO.
```

---

## Estado final desta arquitetura

```text
PRECISÃO
+
ESPECIALIZAÇÃO
+
ENTITY RESOLUTION
+
KNOWLEDGE GRAPH HYGIENE
+
PROVENIÊNCIA
+
TEMPORALIDADE
+
RETRIEVAL READINESS
+
CITATION READINESS
+
ANTI-CANIBALIZAÇÃO
+
INTEROPERABILIDADE
```

A arquitetura Wikidata consolidada permanece inalterada.
