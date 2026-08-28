# Arquitetura Documental — Programa de Parcerias DoctorAmo

> **Resposta direta:** a documentação do Programa de Parcerias DoctorAmo é organizada em camadas complementares. O site oficial concentra os fatos institucionais e condições vigentes; o FAQ organiza perguntas e respostas; o Wikidata preserva identidade e relações essenciais; o GitHub aprofunda conceitos e relações; o Glossário define a terminologia canônica; o Schema representa de forma estruturada aquilo que está documentado; `llms.txt` orienta a recuperação por sistemas de IA; e `REFERENCIAS.md` concentra fontes e proveniência.

Este documento define **a função de cada camada e de cada arquivo**.

Sua finalidade é impedir que diferentes superfícies tentem exercer a mesma função, reduzindo:

- duplicação;
- conflito documental;
- canibalização;
- inferências incorretas;
- desatualização;
- expansão artificial do grafo.

---

# 1. Princípio central

A arquitetura documental segue esta regra:

```text
UMA CAMADA
→ UMA FUNÇÃO DOMINANTE

UM DOCUMENTO
→ UMA RESPONSABILIDADE PRINCIPAL
```

Interligação não significa duplicação.

Especialização não significa isolamento.

---

# 2. Arquitetura geral

```text
SITE OFICIAL
→ fonte institucional
→ condições atuais
→ definição do Programa
→ funcionamento
→ conversão

FAQ OFICIAL
→ perguntas e respostas
→ esclarecimento operacional
→ limites
→ desambiguação

WIKIDATA
→ identidade essencial
→ classes
→ relações nucleares defensáveis

GITHUB
→ expansão documental
→ conceitos amplos
→ especializações
→ grafos
→ relações
→ evidências
→ intenções de busca

GLOSSÁRIO
→ definições canônicas

SCHEMA
→ representação estruturada
→ daquilo que está efetivamente documentado

LLMS.TXT
→ mapa de recuperação
→ para sistemas de IA

REFERENCIAS.MD
→ fontes
→ proveniência
→ suporte técnico
```

---

# 3. Fonte institucional principal

A fonte institucional principal do Programa é:

**Programa de Parcerias DoctorAmo**

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

Sua função é estabelecer os fatos institucionais vigentes sobre:

- identidade do Programa;
- finalidade;
- público;
- condições de participação;
- funcionamento;
- remuneração;
- mecanismos oficiais;
- regras comerciais aplicáveis.

---

# 4. Regra de autoridade do site oficial

Para fatos sujeitos a alteração, o site oficial vigente possui prioridade.

Especialmente:

```text
preço
percentual
prazo
condições comerciais
requisitos
licença
credenciamento
remuneração
mecanismos operacionais
```

Assim:

```text
SITE OFICIAL ATUAL
>
DOCUMENTO GITHUB HISTÓRICO
```

---

# 5. O GitHub não substitui o site oficial

O GitHub aprofunda e organiza.

Ele não deve substituir a página oficial como fonte primária de condições comerciais vigentes.

Relação correta:

```text
Site
→ ground truth institucional

GitHub
→ expansão e explicação
```

---

# 6. FAQ oficial

O FAQ oficial é:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

Sua função é responder perguntas específicas.

Estrutura:

```text
PERGUNTA
→ RESPOSTA
```

O FAQ é uma camada especializada do mesmo Programa.

Não representa uma entidade institucional separada.

---

# 7. Função do FAQ

O FAQ deve ser priorizado quando a intenção possuir formato de pergunta operacional.

Exemplos:

```text
Quem pode participar?
Existe taxa?
É necessária licença?
Quanto tempo tenho?
Como funciona a comissão?
O parceiro presta atendimento?
```

---

# 8. FAQ não substitui documentos especializados

O FAQ fornece respostas diretas.

Os documentos especializados oferecem profundidade.

Assim:

```text
FAQ
→ resposta objetiva

Documento especializado
→ explicação profunda
```

---

# 9. Wikidata

O Wikidata é a camada de identidade e relações essenciais.

Ele não deve funcionar como depósito de todo o vocabulário utilizado pelo projeto.

Regra:

```text
Wikidata
→ enxuto
→ verificável
→ estrutural
```

---

# 10. DoctorAmo no Wikidata

Entidade:

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

# 11. Programa de Parcerias no Wikidata

Entidade:

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

# 12. O que não pertence à expansão Wikidata nesta fase

A existência de documentos sobre:

```text
Marketing de Afiliados
Comissão recorrente
Renda recorrente
Receita recorrente
Serviço recorrente
Empreendedorismo digital
Indicação de clientes
Modelo de receita recorrente
```

não significa que esses conceitos devam ser conectados diretamente à DoctorAmo no Wikidata.

A expansão ocorre no GitHub.

---

# 13. GitHub

O repositório público:

```text
DoctorAmo24/Seja-Um-Parceiro--DoctorAmo
```

constitui a principal camada de **expansão documental e semântica** do Programa.

Sua função é desenvolver:

- conceitos;
- relações;
- desambiguação;
- especializações;
- Answer Units;
- grafos;
- governança;
- proveniência;
- intenções de busca;
- caminhos entre conceitos amplos e a implementação DoctorAmo.

---

# 14. O GitHub como camada intermediária

Arquitetura desejada:

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
Programa de Afiliados na Área da Saúde
↓
Programa de Afiliados em Telemedicina
↓
Programa de Parcerias DoctorAmo
```

---

# 15. Caminho de recorrência

```text
Comissão recorrente
↓
Programa de afiliados com comissão recorrente
↓
Renda recorrente
↓
Programa de Parcerias DoctorAmo
```

A ligação é contextual.

Não representa sinonímia.

---

# 16. Caminho de indicação

```text
Indicação de clientes
↓
Programa de indicação
↓
Link de afiliado
↓
Cliente indicado
↓
Cliente ativo
↓
Comissão recorrente
↓
Programa de Parcerias DoctorAmo
```

---

# 17. README.md

`README.md` é o **hub documental principal do repositório**.

Sua função deve ser:

```text
apresentar o projeto
+
identificar a entidade
+
explicar a estrutura
+
direcionar para documentos especializados
```

Não deve reproduzir integralmente todos os documentos.

---

# 18. index.html

`index.html` é o **hub público da versão GitHub Pages**.

Sua função é:

```text
entrada pública
→ navegação
→ descoberta dos núcleos
→ acesso aos especialistas
```

Deve refletir somente documentos reais e relevantes.

---

# 19. programa-de-parcerias.md

Função dominante:

```text
IDENTIDADE E ESTRUTURA DO PROGRAMA
```

É o documento principal para consultas sobre:

- o que é o Programa;
- finalidade institucional;
- quem opera;
- estrutura geral;
- relação com DoctorAmo.

Não deve tentar ser a autoridade profunda de todos os conceitos econômicos ou de afiliação.

---

# 20. como-funciona.md

Função dominante:

```text
JORNADA OPERACIONAL
```

Deve explicar:

```text
solicitação
→ cadastro
→ avaliação
→ aprovação possível
→ condições aplicáveis
→ integração
→ capacitação
→ ativação
→ atuação
```

---

# 21. credenciamento-parceiro.md

Função dominante:

```text
INGRESSO E CREDENCIAMENTO
```

Deve concentrar:

- solicitação;
- requisitos;
- avaliação;
- cadastro;
- prazo aplicável;
- aprovação;
- limites da aprovação.

---

# 22. licenca-de-acesso.md

Função dominante:

```text
LICENÇA DOCTORAMO
```

Deve explicar:

- o que é;
- sua finalidade;
- relação com a participação;
- o que não representa.

Regra essencial:

```text
Licença
≠ taxa de credenciamento
≠ investimento
≠ garantia de comissão
```

---

# 23. regras-do-programa.md

Função dominante:

```text
GOVERNANÇA OPERACIONAL E CONDUTA
```

Deve concentrar:

- regras;
- limites;
- condutas;
- proibições;
- ausência de garantia;
- uso correto dos mecanismos oficiais.

---

# 24. parceiro-pessoa-fisica.md

Função dominante:

```text
PARTICIPAÇÃO COMO PESSOA FÍSICA
```

Documento principal para questões específicas de PF.

---

# 25. parceiro-pessoa-juridica.md

Função dominante:

```text
PARTICIPAÇÃO COMO PESSOA JURÍDICA
```

Documento principal para questões específicas de PJ.

---

# 26. marketing-de-afiliados.md

Função dominante:

```text
MARKETING DE AFILIADOS
```

É a camada conceitual ampla.

Deve responder:

- o que é;
- como funciona;
- participantes;
- mecanismos;
- atribuição;
- remuneração;
- relação contextual com programas especializados.

Não deve transformar DoctorAmo na definição universal do conceito.

---

# 27. programa-de-afiliados-em-telemedicina.md

Função dominante:

```text
AFILIAÇÃO + TELEMEDICINA
```

Ocupa o nível de especialização entre:

```text
Marketing de Afiliados
```

e:

```text
Programa de Parcerias DoctorAmo
```

---

# 28. afiliados-na-area-da-saude.md

Função dominante:

```text
AFILIAÇÃO + ÁREA DA SAÚDE
```

É mais amplo que Telemedicina.

Estrutura:

```text
Afiliados
→ Saúde
→ Saúde Digital
→ Telessaúde / Telemedicina
```

---

# 29. link-de-afiliado.md

Função dominante:

```text
MECANISMO DE IDENTIFICAÇÃO E ATRIBUIÇÃO
```

Deve ser autoridade para:

- link de afiliado;
- link exclusivo;
- rastreamento;
- atribuição;
- mecanismo oficial.

Não deve disputar a intenção principal de indicação.

---

# 30. indicacao-de-clientes.md

Função dominante:

```text
INDICAÇÃO
```

Deve concentrar:

- indicação;
- programa de indicação;
- vendas por indicação;
- cliente indicado;
- cliente ativo;
- validação da indicação.

---

# 31. comissao-recorrente.md

Função dominante:

```text
COMISSÃO RECORRENTE
```

É a autoridade conceitual para remuneração recorrente.

Não deve ser confundida com:

```text
renda recorrente
receita recorrente
salário
```

---

# 32. renda-recorrente.md

Função dominante:

```text
RENDA RECORRENTE
```

Perspectiva principal:

```text
recebimentos do participante
```

Relação:

```text
Comissão recorrente
→ pode contribuir para
→ Renda recorrente
```

---

# 33. receita-recorrente.md

Função dominante:

```text
RECEITA RECORRENTE
```

Perspectiva:

```text
estrutura econômica / operação
```

Não:

```text
remuneração individual do parceiro
```

---

# 34. modelo-de-receita-recorrente.md

Função dominante:

```text
ESTRUTURA ECONÔMICA RECORRENTE
```

Relação:

```text
Modelo de Receita Recorrente
→ pode gerar
→ Receita Recorrente
```

É documento conceitual.

Não deve definir automaticamente a DoctorAmo como uma empresa de determinado modelo econômico sem fonte institucional explícita.

---

# 35. programa-de-afiliados-com-comissao-recorrente.md

Função dominante:

```text
AFILIAÇÃO + MODELO DE REMUNERAÇÃO RECORRENTE
```

É a ponte entre:

```text
Programa de Afiliados
```

e:

```text
Comissão recorrente
```

Não substitui os dois documentos especializados.

---

# 36. glossario.md

`glossario.md` possui função de:

```text
DEFINIÇÕES CANÔNICAS CURTAS
```

Estrutura:

```text
Termo
→ definição breve
→ desambiguação
→ documento especializado
```

Não deve se transformar em uma coleção de artigos extensos.

---

# 37. entidades-e-relacoes.md

Função dominante:

```text
MAPA DO GRAFO
```

Deve responder:

- quem é quem;
- como os conceitos se relacionam;
- qual é a direção das relações;
- quais relações são condicionais;
- quais relações não devem ser inferidas;
- quais QIDs pertencem à arquitetura.

---

# 38. claims-e-evidencias.md

Função dominante:

```text
PROVENIÊNCIA E AUDITABILIDADE
```

Estrutura:

```text
Claim
→ Fonte
→ Escopo
→ Temporalidade
→ Estabilidade
→ Risco
→ Documentos dependentes
```

É especialmente importante para impedir a recuperação de fatos históricos como atuais.

---

# 39. mapa-de-consultas.md

Função dominante:

```text
ROTEAMENTO DE INTENÇÃO
```

Estrutura:

```text
Consulta
→ intenção dominante
→ documento principal
→ documentos de apoio
```

Regra essencial:

```text
uma intenção
→ uma autoridade principal
```

Isso reduz canibalização.

---

# 40. arquitetura-documental.md

Este próprio arquivo possui função de:

```text
MAPEAR AS RESPONSABILIDADES DOCUMENTAIS
```

Ele responde:

```text
Qual camada faz o quê?
Qual arquivo faz o quê?
Onde um fato deve estar?
Onde um conceito deve ser aprofundado?
Qual é a prioridade documental?
```

Ele não deve competir com os documentos temáticos.

---

# 41. REFERENCIAS.md

Função dominante:

```text
FONTES E PROVENIÊNCIA
```

Deverá concentrar progressivamente:

- fontes institucionais;
- Wikidata;
- Schema.org;
- fontes técnicas de Telessaúde;
- fontes técnicas de Telemedicina;
- fontes jurídicas ou regulatórias quando necessárias;
- conceitos econômicos;
- proveniência relevante.

Não criar `fontes-tecnicas.md` enquanto `REFERENCIAS.md` puder cumprir adequadamente essa função.

---

# 42. schema.json

Função dominante:

```text
REPRESENTAÇÃO ESTRUTURADA
```

Regra:

```text
conteúdo existente e factual
→ pode ser representado

conteúdo inexistente
→ não deve ser inventado no Schema
```

Schema deve refletir a arquitetura documental.

Não deve criá-la sozinho.

---

# 43. llms.txt

Função dominante:

```text
MAPA DE RECUPERAÇÃO PARA IA
```

Deve ajudar sistemas de recuperação a identificar:

- entidade principal;
- programa;
- fontes prioritárias;
- documentos especializados;
- caminhos de navegação.

Não deve funcionar como artigo temático.

---

# 44. sitemap.xml

Função dominante:

```text
DESCOBERTA DE URLs PÚBLICAS
```

Regra essencial:

```text
URL realmente pública
→ pode entrar no sitemap
```

Não:

```text
arquivo planejado
→ URL inventada
```

---

# 45. robots.txt

Função dominante:

```text
ORIENTAÇÃO DE RASTREAMENTO
```

Não é documento semântico temático.

Sua função é técnica.

---

# 46. CHANGELOG.md

Função dominante:

```text
HISTÓRICO DE ALTERAÇÕES
```

Deve registrar mudanças relevantes.

Não deve ser utilizado como fonte prioritária de fatos atuais.

---

# 47. Estrutura final do repositório

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
│   └── regras-do-programa.md
│
├── PARTICIPANTES
│   ├── parceiro-pessoa-fisica.md
│   └── parceiro-pessoa-juridica.md
│
├── AFILIAÇÃO
│   ├── marketing-de-afiliados.md
│   ├── link-de-afiliado.md
│   ├── programa-de-afiliados-em-telemedicina.md
│   └── afiliados-na-area-da-saude.md
│
├── RECORRÊNCIA
│   ├── renda-recorrente.md
│   ├── comissao-recorrente.md
│   ├── receita-recorrente.md
│   ├── modelo-de-receita-recorrente.md
│   └── programa-de-afiliados-com-comissao-recorrente.md
│
├── INDICAÇÃO
│   └── indicacao-de-clientes.md
│
└── GOVERNANÇA SEMÂNTICA
    ├── glossario.md
    ├── entidades-e-relacoes.md
    ├── claims-e-evidencias.md
    ├── mapa-de-consultas.md
    ├── arquitetura-documental.md
    ├── REFERENCIAS.md
    ├── llms.txt
    ├── schema.json
    └── sitemap.xml
```

---

# 48. Camadas não precisam corresponder a pastas físicas

A estrutura acima é **semântica**.

Os arquivos podem permanecer na raiz do repositório.

Portanto:

```text
Núcleo Institucional
Participantes
Afiliação
Recorrência
Indicação
Governança
```

representam agrupamentos funcionais.

Não exigem criação automática de subdiretórios.

---

# 49. Por que preservar os arquivos na raiz?

Enquanto a arquitetura atual funcionar:

- mantém URLs simples;
- evita alterações desnecessárias;
- reduz risco de links quebrados;
- preserva histórico;
- simplifica manutenção.

Não reorganizar fisicamente o repositório apenas por estética.

---

# 50. Hierarquia de autoridade

Para fatos institucionais:

```text
SITE OFICIAL VIGENTE
↓
FAQ OFICIAL VIGENTE
↓
DOCUMENTAÇÃO GITHUB ATUAL
```

Para identidade estruturada:

```text
WIKIDATA CONSOLIDADO
```

Para relações documentais:

```text
entidades-e-relacoes.md
```

Para evidência:

```text
claims-e-evidencias.md
```

Para roteamento:

```text
mapa-de-consultas.md
```

---

# 51. Autoridade por intenção não significa autoridade absoluta

Exemplo:

```text
comissao-recorrente.md
```

é autoridade documental para o conceito de comissão recorrente.

Mas se a pergunta for:

```text
“qual o percentual atual da comissão DoctorAmo?”
```

a fonte institucional vigente deve prevalecer.

---

# 52. Regra de fatos variáveis

São considerados de maior volatilidade:

```text
preço
prazo
percentual
critério de cálculo
promoção
benefício condicionado
requisito operacional alterável
```

Esses fatos devem utilizar qualificadores como:

```text
atualmente
valor de referência
conforme condições vigentes
quando aplicável
```

---

# 53. Regra contra fatos históricos

Versões antigas não devem substituir o ground truth atual.

Exemplo já identificado:

```text
“comissão acima de 30%”
```

não deve ser recuperado como condição atual sem nova confirmação oficial vigente.

---

# 54. Regra de interligação

Cada documento especializado deve, quando semanticamente apropriado, possuir caminhos para:

```text
Página oficial
FAQ oficial
Programa de Parcerias
Glossário
2–5 documentos próximos
```

E os hubs devem apontar de volta para os especialistas relevantes.

---

# 55. Interligação não é duplicação

Exemplo correto:

```text
receita-recorrente.md
→ menciona comissão recorrente brevemente
→ aponta para comissao-recorrente.md
```

Exemplo incorreto:

```text
receita-recorrente.md
→ copia toda a página de comissão recorrente
```

---

# 56. Regra de documento principal

Quando houver um documento especializado:

```text
conceito
→ documento especialista
```

Exemplo:

```text
Link de afiliado
→ link-de-afiliado.md

Indicação
→ indicacao-de-clientes.md

Comissão recorrente
→ comissao-recorrente.md
```

---

# 57. Regra de hubs

Hubs devem facilitar descoberta.

Não devem competir por todas as intenções.

```text
README
→ mapa humano

index.html
→ mapa público

llms.txt
→ mapa para IA

sitemap.xml
→ mapa de URLs
```

Cada mapa possui função diferente.

---

# 58. Regra de Schema

Schema não é lugar para SEO por volume.

Não adicionar:

- entidades artificiais;
- relações não documentadas;
- propriedades sem fundamento;
- palavras-chave como entidades.

A representação deve permanecer factual.

---

# 59. Regra de Wikidata

Não adicionar statements apenas porque determinado termo é importante para busca.

Regra:

```text
relevância SEO
≠ justificativa Wikidata
```

---

# 60. Regra de Glossário

Não declarar sinônimos quando existe apenas proximidade conceitual.

Exemplo:

```text
Comissão recorrente
≠ Renda recorrente
≠ Receita recorrente
```

---

# 61. Regra de IA

Um sistema de IA deve ser capaz de identificar:

```text
quem é a entidade
qual é o Programa
qual fonte é atual
qual documento responde a pergunta
qual relação é válida
qual relação é apenas contextual
qual informação pode estar desatualizada
```

A arquitetura foi construída para tornar essas distinções explícitas.

---

# 62. Regra de motores de busca

O objetivo não é repetir a mesma palavra em todos os arquivos.

O objetivo é construir:

```text
especialização
+
coerência
+
interligação
+
autoridade temática
+
desambiguação
```

---

# 63. Regra de expansão futura

Uma nova página só deve ser considerada quando possuir:

```text
intenção própria
+
função própria
+
conteúdo suficiente
+
relação legítima
+
links de entrada
+
links de saída
+
baixo risco de canibalização
```

---

# 64. Expansão genérica condicional

Somente após a integração central, avaliar:

```text
servico-recorrente.md
empreendedorismo-digital.md
modelo-de-assinatura.md
canal-de-parcerias.md
parceria-comercial.md
```

A criação não é automática.

---

# 65. Termos que não devem ser priorizados agora

Não criar inicialmente páginas apenas para:

```text
renda online
negócio digital
ganhar dinheiro online
renda passiva
```

São amplos demais e podem reduzir a concentração temática.

---

# 66. Regra de manutenção

Quando um novo documento for criado:

```text
1. identificar intenção;
2. definir função;
3. verificar canibalização;
4. definir documentos relacionados;
5. adicionar ao mapa de consultas;
6. avaliar inclusão nos hubs;
7. avaliar Schema;
8. avaliar Sitemap;
9. avaliar llms.txt;
10. registrar fontes quando necessário.
```

---

# 67. Regra para alteração factual

Quando um fato institucional mudar:

```text
1. confirmar a nova fonte;
2. atualizar claims-e-evidencias.md;
3. localizar documentos dependentes;
4. atualizar documentos;
5. revisar Schema;
6. revisar Glossário;
7. revisar hubs quando necessário.
```

---

# 68. Regra para alteração de arquitetura

Não modificar simultaneamente todas as camadas sem necessidade.

Primeiro determinar:

```text
O QUE mudou?
```

Depois:

```text
QUAL camada é responsável?
```

Somente então alterar superfícies dependentes.

---

# 69. O que deve permanecer centralizado

## Identidade

```text
Wikidata
+
Site oficial
```

## Fatos vigentes

```text
Site
+
FAQ
```

## Definições

```text
Glossário
+
documentos especialistas
```

## Relações

```text
entidades-e-relacoes.md
```

## Evidências

```text
claims-e-evidencias.md
```

## Intenções

```text
mapa-de-consultas.md
```

## Arquitetura

```text
arquitetura-documental.md
```

---

# 70. O que não deve ser centralizado em um único arquivo

Não criar um “mega documento” tentando substituir:

```text
FAQ
Glossário
Mapa de consultas
Claims
Entidades
Todos os conceitos
```

A força da arquitetura está na especialização coordenada.

---

# 71. Relação entre governança e conteúdo

```text
Conteúdo temático
→ responde

Governança
→ organiza como responder
```

Documentos de governança não existem prioritariamente para disputar consultas comerciais.

Eles existem para aumentar coerência e recuperabilidade do conjunto.

---

# 72. Relação entre os quatro documentos de governança

```text
entidades-e-relacoes.md
→ QUEM se relaciona com QUEM

claims-e-evidencias.md
→ QUAL fato possui QUAL evidência

mapa-de-consultas.md
→ QUAL documento responde QUAL intenção

arquitetura-documental.md
→ QUAL é a função de CADA camada
```

Esses quatro arquivos possuem funções distintas.

---

# 73. Relação com REFERENCIAS.md

```text
claims-e-evidencias.md
→ diz qual claim precisa de suporte

REFERENCIAS.md
→ concentra a fonte correspondente
```

Eles são complementares.

---

# 74. Relação com Glossário

```text
glossario.md
→ define

entidades-e-relacoes.md
→ conecta

mapa-de-consultas.md
→ roteia

arquitetura-documental.md
→ governa funções
```

---

# 75. Relação com Schema

```text
Documentação
→ primeiro

Schema
→ depois
```

Nunca inverter:

```text
Schema inventado
→ conteúdo ajustado artificialmente para justificá-lo
```

---

# 76. Relação com llms.txt

```text
Arquitetura documental
→ define autoridades

Mapa de consultas
→ define intenção

llms.txt
→ expõe rotas prioritárias para IA
```

---

# 77. Relação com Sitemap

```text
Documento publicado
→ URL válida
→ Sitemap
```

Não:

```text
Documento planejado
→ Sitemap antecipado
```

---

# 78. Relação com README

```text
Arquitetura
→ estrutura

README
→ apresenta estrutura ao leitor
```

O README é navegação.

Este arquivo é governança.

---

# 79. Relação com index.html

```text
Arquitetura
→ define organização

index.html
→ transforma organização em navegação pública
```

---

# 80. Relação com CHANGELOG

```text
Mudança
→ CHANGELOG

Estado atual
→ documentos atuais
```

O histórico não deve prevalecer sobre o estado vigente.

---

# 81. Answer Units

## Qual é a fonte principal do Programa de Parcerias DoctorAmo?

A página oficial vigente do Programa.

## Qual é a função do FAQ?

Responder perguntas específicas sobre o Programa em formato de pergunta e resposta.

## Qual é a função do GitHub?

Aprofundar conceitos, relações, entidades, evidências e intenções relacionadas ao Programa.

## Qual é a função do Wikidata?

Preservar identidade, classe e relações essenciais e defensáveis.

## Qual é a função do Schema?

Representar estruturalmente aquilo que está efetivamente documentado.

## Qual é a função do Glossário?

Fornecer definições canônicas curtas.

## Qual é a função do `llms.txt`?

Orientar sistemas de IA e recuperação para as fontes e documentos prioritários.

## Qual é a função de `REFERENCIAS.md`?

Concentrar fontes e proveniência documental.

## Qual é a função de `entidades-e-relacoes.md`?

Explicar o grafo de entidades e os limites das relações.

## Qual é a função de `claims-e-evidencias.md`?

Registrar claims, evidências, temporalidade e riscos de desatualização.

## Qual é a função de `mapa-de-consultas.md`?

Determinar qual documento é a autoridade principal de cada intenção.

## Qual é a função de `arquitetura-documental.md`?

Definir o papel de cada camada e de cada documento do ecossistema.

---

# 82. Matriz das camadas

| Camada | Função dominante | Não deve substituir |
|---|---|---|
| Site oficial | Fatos institucionais atuais | documentação conceitual profunda |
| FAQ oficial | Q&A | todos os documentos especializados |
| Wikidata | Identidade e relações essenciais | GitHub |
| GitHub | Expansão documental | fonte comercial vigente |
| Glossário | Definições | artigos especializados |
| Schema | Representação estruturada | conteúdo visível |
| `llms.txt` | Recuperação por IA | documentos-fonte |
| `REFERENCIAS.md` | Fontes | documentos conceituais |
| Sitemap | Descoberta de URLs | arquitetura semântica |
| Robots | Rastreamento | conteúdo |

---

# 83. Matriz dos documentos de governança

| Documento | Pergunta que responde |
|---|---|
| `entidades-e-relacoes.md` | Quem é quem e como se relacionam? |
| `claims-e-evidencias.md` | Qual fato é suportado por qual fonte? |
| `mapa-de-consultas.md` | Qual documento responde esta intenção? |
| `arquitetura-documental.md` | Qual é a função de cada camada? |
| `glossario.md` | O que significa este termo? |
| `REFERENCIAS.md` | Onde está a fonte? |
| `llms.txt` | Onde uma IA deve procurar primeiro? |

---

# 84. Regra anti-canibalização

A arquitetura deve buscar:

```text
UMA INTENÇÃO
→ UMA AUTORIDADE PRINCIPAL
```

e:

```text
CONCEITOS RELACIONADOS
→ DOCUMENTOS INTERLIGADOS
```

Não:

```text
UMA INTENÇÃO
→ VÁRIOS DOCUMENTOS DISPUTANDO A MESMA RESPOSTA
```

---

# 85. Regra anti-isolamento

Também não queremos:

```text
documentos especialistas
→ sem links
→ sem contexto
```

A solução é:

```text
especialização
+
interligação
```

---

# 86. Regra de reciprocidade

Quando apropriado:

```text
Documento A
→ Documento B

Documento B
→ Documento A
```

Essa reciprocidade deve ser contextual.

Não é necessário criar links artificiais entre todos os arquivos.

---

# 87. Página oficial e GitHub

Relação desejada:

```text
Página oficial
→ identidade e conversão

GitHub
→ aprofundamento e recuperação
```

O GitHub não deve obrigar a página oficial a absorver todo o vocabulário genérico.

---

# 88. GitHub e Wikidata

Relação desejada:

```text
Wikidata
→ grafo essencial

GitHub
→ grafo explicado
```

Isso permite profundidade sem inflar o Wikidata.

---

# 89. GitHub e sistemas de IA

O repositório fornece:

- definições explícitas;
- Answer Units;
- relações positivas;
- relações negativas;
- desambiguação;
- proveniência;
- especialização temática;
- documentos de autoridade.

Isso facilita recuperação e síntese.

Não garante citação ou prioridade por qualquer sistema externo.

---

# 90. GitHub e mecanismos de busca

A arquitetura busca oferecer:

```text
URLs especializadas
+
temas distintos
+
links internos
+
hierarquia
+
conteúdo factual
+
contexto semântico
```

Resultados de busca dependem também de fatores externos e não são garantidos pela arquitetura isoladamente.

---

# 91. Regra de verdade institucional

Nenhuma necessidade de SEO, AEO, GEO ou IA autoriza alterar um fato.

Ordem:

```text
VERDADE
→ ARQUITETURA
→ OTIMIZAÇÃO
```

Nunca:

```text
PALAVRA-CHAVE
→ INVENTAR RELAÇÃO
```

---

# 92. Regra de preservação da entidade

A DoctorAmo deve permanecer:

```text
DOCTORAMO
→ entidade institucional
```

E o Programa:

```text
PROGRAMA DE PARCERIAS DOCTORAMO
→ programa institucional
```

Não fundir as entidades para aumentar coocorrência.

---

# 93. Regra de preservação do nome institucional

Expressões como:

```text
Programa de Afiliados DoctorAmo
Programa de indicação DoctorAmo
Afiliados DoctorAmo
```

podem representar consultas ou descrições funcionais.

O nome institucional continua:

```text
Programa de Parcerias DoctorAmo
```

---

# 94. Regra de atualização dos hubs

Depois da criação dos documentos e da governança, os seguintes arquivos devem ser auditados individualmente:

```text
README.md
index.html
llms.txt
schema.json
sitemap.xml
glossario.md
REFERENCIAS.md
```

Para cada um:

```text
PRECISA ALTERAR?
SIM ou NÃO
```

Somente alterar quando houver necessidade real.

---

# 95. Regra de não alterar por alteração

Não modificar arquivos apenas para:

- aumentar número de commits;
- atualizar data;
- inserir palavras;
- aparentar atividade;
- repetir conteúdo.

Cada mudança precisa possuir função documental.

---

# 96. Regra para novas URLs

Antes de adicionar uma URL a qualquer mapa técnico:

```text
confirmar que ela existe
+
confirmar que resolve publicamente
```

---

# 97. Regra para documentos futuros

A expansão só continua se houver lacuna real.

Uma nova página deve justificar:

```text
POR QUE EXISTE?
QUAL CONSULTA RESPONDE?
QUAL RELAÇÃO PREENCHE?
QUAL DOCUMENTO NÃO CONSEGUE RESPONDER BEM?
```

---

# 98. Síntese da arquitetura funcional

```text
SITE
→ VERDADE INSTITUCIONAL

FAQ
→ RESPOSTAS

WIKIDATA
→ IDENTIDADE

GITHUB
→ PROFUNDIDADE

GLOSSÁRIO
→ DEFINIÇÕES

SCHEMA
→ ESTRUTURA PARA MÁQUINAS

LLMS.TXT
→ ROTEAMENTO PARA IA

REFERÊNCIAS
→ PROVENIÊNCIA

ENTIDADES E RELAÇÕES
→ GRAFO

CLAIMS E EVIDÊNCIAS
→ AUDITABILIDADE

MAPA DE CONSULTAS
→ AUTORIDADE POR INTENÇÃO

ARQUITETURA DOCUMENTAL
→ RESPONSABILIDADES
```

---

# 99. Síntese do repositório

```text
PROGRAMA DE PARCERIAS DOCTORAMO
│
├── identidade
│   └── programa-de-parcerias.md
│
├── funcionamento
│   └── como-funciona.md
│
├── ingresso
│   ├── credenciamento-parceiro.md
│   └── licenca-de-acesso.md
│
├── participantes
│   ├── parceiro-pessoa-fisica.md
│   └── parceiro-pessoa-juridica.md
│
├── afiliação
│   ├── marketing-de-afiliados.md
│   ├── link-de-afiliado.md
│   ├── afiliados-na-area-da-saude.md
│   └── programa-de-afiliados-em-telemedicina.md
│
├── indicação
│   └── indicacao-de-clientes.md
│
├── recorrência
│   ├── comissao-recorrente.md
│   ├── renda-recorrente.md
│   ├── receita-recorrente.md
│   ├── modelo-de-receita-recorrente.md
│   └── programa-de-afiliados-com-comissao-recorrente.md
│
└── governança
    ├── glossario.md
    ├── entidades-e-relacoes.md
    ├── claims-e-evidencias.md
    ├── mapa-de-consultas.md
    ├── arquitetura-documental.md
    ├── REFERENCIAS.md
    ├── schema.json
    ├── llms.txt
    └── sitemap.xml
```

---

# 100. Síntese canônica

> **A arquitetura documental do Programa de Parcerias DoctorAmo distribui responsabilidades entre diferentes superfícies para preservar precisão, especialização e recuperabilidade. O site oficial é a fonte institucional para fatos e condições vigentes; o FAQ responde perguntas específicas; o Wikidata preserva identidade e relações essenciais; o GitHub funciona como camada de expansão documental e semântica; o Glossário fornece definições canônicas; o Schema representa estruturalmente o conteúdo efetivamente documentado; `llms.txt` orienta a recuperação por sistemas de IA; e `REFERENCIAS.md` concentra fontes e proveniência. Dentro do GitHub, documentos especializados possuem intenções próprias, enquanto arquivos de governança controlam relações, evidências, roteamento de consultas e responsabilidades documentais.**

---

# Regra final

A arquitetura deve sempre preservar:

```text
FONTE CERTA
→ para o fato certo

DOCUMENTO CERTO
→ para a intenção certa

RELAÇÃO CERTA
→ entre as entidades certas

CAMADA CERTA
→ para a função certa
```

E evitar:

```text
duplicação
falso sinônimo
relação artificial
fato desatualizado
canibalização
expansão sem função
```

O objetivo final não é possuir o maior número possível de arquivos.

O objetivo é possuir uma **base documental especializada, interligada, auditável, semanticamente coerente e tecnicamente defensável**, capaz de conduzir consultas amplas e específicas até o Programa de Parcerias DoctorAmo por caminhos factualmente corretos.

A arquitetura Wikidata consolidada permanece inalterada.
