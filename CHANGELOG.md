# Changelog — Programa de Parcerias DoctorAmo

> **Histórico canônico de alterações relevantes da documentação, arquitetura semântica, governança factual e superfícies técnicas do Programa de Parcerias DoctorAmo.**

Este arquivo registra **mudanças**.

Ele não é a fonte prioritária para determinar o estado atual de um fato.

Repositório:

https://github.com/DoctorAmo24/Seja-Um-Parceiro--DoctorAmo

---

# 1. Função deste documento

O `CHANGELOG.md` responde:

```text
O QUE MUDOU?
↓
QUANDO MUDOU?
↓
QUAL CAMADA FOI AFETADA?
↓
QUAL ERA O ESTADO ANTERIOR?
↓
QUAL PASSOU A SER O NOVO ESTADO?
```

Sua função dominante é:

```text
HISTÓRICO
+
RASTREABILIDADE
+
CONTROLE DE VERSÃO
+
AUDITABILIDADE DE MUDANÇAS
```

Não deve substituir:

```text
SITE OFICIAL
→ fatos institucionais atuais

FAQ OFICIAL
→ respostas institucionais atuais

CLAIMS-E-EVIDENCIAS.MD
→ status factual e temporalidade

REFERENCIAS.MD
→ fontes e proveniência

ARQUITETURA-DOCUMENTAL.MD
→ arquitetura vigente
```

---

# 2. Regra de prevalência

Quando uma entrada histórica divergir do estado documental atual:

```text
FONTE INSTITUCIONAL VIGENTE
>
CLAIM ATUAL VALIDADO
>
DOCUMENTAÇÃO ATUAL
>
REGISTRO HISTÓRICO DO CHANGELOG
```

Portanto:

```text
CHANGELOG
≠ GROUND TRUTH COMERCIAL
```

e:

```text
REGISTRO HISTÓRICO
≠ CONDIÇÃO VIGENTE
```

---

# 3. Fontes canônicas de referência

## Programa de Parcerias DoctorAmo

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

## FAQ oficial

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

## DoctorAmo

https://www.doctoramo.com.br/in%C3%ADcio

## DoctorAmo — Wikidata

https://www.wikidata.org/entity/Q141152382

## Programa de Parcerias DoctorAmo — Wikidata

https://www.wikidata.org/entity/Q141152387

## Referências e proveniência

[REFERENCIAS.md](REFERENCIAS.md)

## Claims e evidências

[claims-e-evidencias.md](claims-e-evidencias.md)

---

# 4. Convenção de versões

A numeração é inspirada em versionamento semântico aplicado à arquitetura documental.

## MAJOR

```text
X.0.0
```

Utilizar para:

- mudança estrutural incompatível;
- redefinição significativa da arquitetura;
- mudança de identidade central;
- reorganização ampla das responsabilidades documentais;
- alteração que exija migração conceitual relevante.

## MINOR

```text
3.X.0
```

Utilizar para:

- novos documentos especialistas;
- novos clusters;
- novas camadas de governança;
- expansão semântica compatível;
- integração estrutural relevante sem quebra da arquitetura principal.

## PATCH

```text
3.1.X
```

Utilizar para:

- correções;
- links;
- pequenas desambiguações;
- ajustes de fonte;
- correção de inconsistência;
- refinamento sem mudança estrutural.

---

# 5. Categorias de alteração

As versões podem utilizar:

```text
ADICIONADO
ALTERADO
CORRIGIDO
REMOVIDO
DEPRECADO
GOVERNANÇA
SEGURANÇA SEMÂNTICA
SEM ALTERAÇÃO
```

`SEM ALTERAÇÃO` deve ser utilizado somente quando uma auditoria importante concluiu explicitamente que determinado núcleo deveria permanecer inalterado.

---

# [3.1.0] — 2026-08-28

## Expansão Semântica Nacional e consolidação AEO Master Elite

A versão `3.1.0` registra a expansão documental especializada do Programa de Parcerias DoctorAmo e a consolidação de sua camada de governança semântica.

A release transforma a estrutura anterior em uma arquitetura baseada em:

```text
ENTIDADE
+
INTENÇÃO
+
AUTORIDADE DOCUMENTAL
+
PROVENIÊNCIA
+
TEMPORALIDADE
+
DESAMBIGUAÇÃO
+
INTERLIGAÇÃO
```

sem modificar a arquitetura Wikidata consolidada.

---

## ADICIONADO — documentos especialistas da expansão

Foram incorporadas autoridades documentais específicas para intenções que antes estavam concentradas em documentos mais amplos.

### Comissão recorrente

Arquivo:

```text
comissao-recorrente.md
```

Função:

```text
COMISSÃO RECORRENTE
→ remuneração
→ cliente ativo indicado
→ continuidade
```

Wikidata relacionado:

```text
Q141124952
```

---

### Programa de afiliados em Telemedicina

Arquivo:

```text
programa-de-afiliados-em-telemedicina.md
```

Função:

```text
PROGRAMA DE AFILIADOS
+
TELEMEDICINA
+
TELESSAÚDE
+
SAÚDE DIGITAL
```

---

### Programa de afiliados com comissão recorrente

Arquivo:

```text
programa-de-afiliados-com-comissao-recorrente.md
```

Função:

```text
AFILIAÇÃO
+
MODELO DE REMUNERAÇÃO RECORRENTE
```

---

### Marketing de Afiliados

Arquivo:

```text
marketing-de-afiliados.md
```

Função:

```text
MARKETING DE AFILIADOS
→ conceito amplo
```

Wikidata relacionado:

```text
Q382453
```

---

### Afiliados na Área da Saúde

Arquivo:

```text
afiliados-na-area-da-saude.md
```

Função:

```text
AFILIAÇÃO
+
SETOR DE SAÚDE
```

---

### Receita recorrente

Arquivo:

```text
receita-recorrente.md
```

Função:

```text
RECEITA RECORRENTE
→ entradas econômicas recorrentes
```

Wikidata relacionado:

```text
Q141124953
```

---

### Link de afiliado

Arquivo:

```text
link-de-afiliado.md
```

Função:

```text
IDENTIFICAÇÃO
+
ATRIBUIÇÃO
+
RASTREABILIDADE
```

Wikidata:

```text
Q141125007
```

---

### Indicação de clientes

Arquivo:

```text
indicacao-de-clientes.md
```

Função:

```text
INDICAÇÃO
→ VALIDAÇÃO
→ CLIENTE INDICADO
→ CLIENTE ATIVO
```

---

### Modelo de receita recorrente

Arquivo:

```text
modelo-de-receita-recorrente.md
```

Função:

```text
ESTRUTURA ECONÔMICA RECORRENTE
```

---

## ADICIONADO — expansão especializada complementar

Após auditoria de lacunas e risco de canibalização, duas intenções adicionais receberam autoridades próprias.

### Serviço recorrente

Arquivo:

```text
servico-recorrente.md
```

Função:

```text
CONTINUIDADE DA PRESTAÇÃO / ACESSO
```

Wikidata:

```text
Q141125008
```

Antes:

```text
Serviço recorrente
→ tratado contextualmente em documentos de recorrência
```

Agora:

```text
Serviço recorrente
→ servico-recorrente.md
```

---

### Modelo de assinatura

Arquivo:

```text
modelo-de-assinatura.md
```

Função:

```text
ESTRUTURA DE CONTRATAÇÃO / ACESSO
```

Estado Wikidata:

```text
SEM QID ESPECÍFICO CONSOLIDADO
```

Regra incorporada:

```text
SEM QID
→ NÃO INVENTAR QID
```

Antes:

```text
Modelo de assinatura
→ tratado como conceito de apoio
```

Agora:

```text
Modelo de assinatura
→ modelo-de-assinatura.md
```

---

## ADICIONADO — governança semântica

Foram consolidados quatro documentos especializados de governança.

### Entidades e relações

```text
entidades-e-relacoes.md
```

Função:

```text
QUEM É QUEM?
+
COMO SE RELACIONAM?
+
O QUE NÃO DEVE SER INFERIDO?
```

---

### Claims e evidências

```text
claims-e-evidencias.md
```

Estrutura canônica:

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

### Mapa de consultas

```text
mapa-de-consultas.md
```

Função:

```text
CONSULTA
↓
INTENÇÃO
↓
AUTORIDADE PRINCIPAL
↓
APOIO
```

Regra consolidada:

```text
UMA INTENÇÃO
→ UMA AUTORIDADE PRINCIPAL
```

---

### Arquitetura documental

```text
arquitetura-documental.md
```

Função:

```text
CAMADA
→ RESPONSABILIDADE
→ FRONTEIRA
→ DEPENDÊNCIA
```

---

## ALTERADO — arquitetura da recorrência

A recorrência deixou de ser tratada como um único território indistinto.

Arquitetura consolidada:

```text
RECORRÊNCIA
│
├── Serviço recorrente
│   └── prestação / acesso
│
├── Modelo de assinatura
│   └── contratação / acesso
│
├── Modelo de receita recorrente
│   └── estrutura econômica
│
├── Receita recorrente
│   └── entradas econômicas
│
├── Comissão recorrente
│   └── remuneração
│
└── Renda recorrente
    └── recebimentos do participante
```

Regra:

```text
PROXIMIDADE SEMÂNTICA
≠ SINONÍMIA
```

---

## ALTERADO — autoridade de Serviço recorrente

Roteamento anterior:

```text
Serviço recorrente
→ modelo-de-receita-recorrente.md
```

Roteamento atual:

```text
Serviço recorrente
→ servico-recorrente.md
```

---

## ALTERADO — autoridade de Modelo de assinatura

Roteamento anterior:

```text
Modelo de assinatura
→ modelo-de-receita-recorrente.md
```

Roteamento atual:

```text
Modelo de assinatura
→ modelo-de-assinatura.md
```

`modelo-de-receita-recorrente.md` permanece autoridade exclusiva de:

```text
Modelo de receita recorrente
```

---

## ALTERADO — Glossário Canônico

`glossario.md` foi reposicionado para sua função arquitetural correta.

Antes havia maior concentração de aprofundamento no próprio Glossário.

A função consolidada passa a ser:

```text
TERMO
→ DEFINIÇÃO
→ CATEGORIA
→ RELAÇÃO
→ NÃO CONFUNDIR
→ AUTORIDADE
```

Regra:

```text
GLOSSÁRIO
→ DEFINE E DESAMBIGUA

ESPECIALISTA
→ APROFUNDA
```

Resultado:

- menor redundância;
- maior atomicidade;
- melhor separação de autoridade;
- menor risco de canibalização;
- recuperação terminológica mais direta.

---

## ALTERADO — `REFERENCIAS.md`

A camada de referências foi consolidada como autoridade de:

```text
FONTE
+
ESCOPO
+
AUTORIDADE
+
PROVENIÊNCIA
```

Foram integradas as novas autoridades:

```text
servico-recorrente.md
modelo-de-assinatura.md
```

Também foi reforçada a separação entre:

```text
FONTE
≠ ENDOSSO

SCHEMA
≠ EVIDÊNCIA

WIKIDATA
≠ FONTE COMERCIAL

DOCUMENTO INTERNO
≠ PROVA INDEPENDENTE
```

A referência de Telemedicina passou a privilegiar o ato normativo correspondente do Conselho Federal de Medicina em vez de depender apenas de conteúdo explicativo secundário.

---

## ALTERADO — `mapa-de-consultas.md`

O Mapa de Consultas foi sincronizado com as novas autoridades.

Passou a reconhecer explicitamente:

```text
Serviço recorrente
→ servico-recorrente.md

Modelo de assinatura
→ modelo-de-assinatura.md

Modelo de receita recorrente
→ modelo-de-receita-recorrente.md
```

A regra:

```text
UMA INTENÇÃO
→ UMA AUTORIDADE PRINCIPAL
```

passa a governar formalmente todo o cluster.

Também foram consolidadas fronteiras entre:

- consultas institucionais;
- consultas conceituais;
- consultas factuais;
- consultas relacionais;
- consultas normativas;
- consultas comparativas.

---

## ALTERADO — `arquitetura-documental.md`

Foi removido o estado obsoleto em que:

```text
servico-recorrente.md
modelo-de-assinatura.md
```

ainda apareciam como candidatos futuros.

O estado atual é:

```text
servico-recorrente.md
→ CRIADO

modelo-de-assinatura.md
→ CRIADO
```

Também foi consolidado o cluster:

```text
RECORRÊNCIA E MODELOS
```

com seis objetos conceitualmente separados.

---

## ALTERADO — README

O hub documental foi sincronizado com a expansão temática.

Foram incorporados caminhos para:

```text
Serviço recorrente
Modelo de assinatura
```

e reforçada a navegação entre:

```text
conceito
→ categoria
→ especialização
→ implementação institucional
```

O README permanece hub.

Não passa a substituir os especialistas.

---

## ALTERADO — `llms.txt`

A camada de roteamento complementar para sistemas de IA foi sincronizada com:

```text
Serviço recorrente
Modelo de assinatura
Modelo de receita recorrente
Receita recorrente
Comissão recorrente
Renda recorrente
```

Foram reforçadas:

- autoridade por intenção;
- fontes prioritárias;
- relações negativas;
- distinção entre entidade e conceito;
- regra de não inventar QID;
- bloqueio de fatos históricos não canônicos.

---

## ALTERADO — `schema.json`

A representação estruturada foi sincronizada com a documentação efetivamente existente.

Foram incorporadas representações documentais para:

```text
servico-recorrente.md
modelo-de-assinatura.md
```

`Serviço recorrente` preserva:

```text
Q141125008
```

`Modelo de assinatura` permanece:

```text
SEM QID CONSOLIDADO
```

Não foram criados:

```text
sameAs artificial
QID fictício
relação institucional sem fonte
classificação DoctorAmo por proximidade temática
```

Regra mantida:

```text
DOCUMENTAÇÃO
→ PRIMEIRO

SCHEMA
→ DEPOIS
```

---

## ALTERADO — `sitemap.xml`

A descoberta foi sincronizada com os novos recursos públicos previstos na arquitetura:

```text
/servico-recorrente
/modelo-de-assinatura
```

Regra mantida:

```text
URL PÚBLICA REAL
→ SITEMAP
```

A inclusão não deve ser interpretada como garantia de:

```text
indexação
ranking
citação
```

---

## GOVERNANÇA — expansão avaliada e deliberadamente não criada

Foram avaliados:

```text
empreendedorismo-digital.md
canal-de-parcerias.md
parceria-comercial.md
```

Decisão:

```text
NÃO CRIAR NESTA FASE
```

### Empreendedorismo digital

Existe vocabulário Wikidata:

```text
Q141124954
```

Mas o conceito permanece amplo e contextual.

Regra aplicada:

```text
QID EXISTENTE
≠ NECESSIDADE DE PÁGINA
```

### Canal de parcerias

Apresentou sobreposição elevada com:

```text
programa-de-parcerias.md
```

### Parceria comercial

Apresentou escopo amplo e baixa diferenciação suficiente frente ao núcleo institucional.

Essas decisões reduzem:

```text
dispersão temática
+
duplicação
+
canibalização
```

---

## GOVERNANÇA — Wikidata preservado

A expansão `3.1.0` não altera a arquitetura Wikidata consolidada.

DoctorAmo:

```text
Q141152382
```

Relações:

```text
P31 → Online service provider Q1641122
P101 → Telessaúde Q4923501
P101 → Telemedicina Q46994
P856 → site oficial
P121 → Programa de Parcerias DoctorAmo Q141152387
```

Programa:

```text
Q141152387
```

Relações:

```text
P31 → Programa de parceiros Q141124951
P137 → DoctorAmo Q141152382
P2283 → Link de afiliado Q141125007
P2670 → Integração de parceiro Q141131339
P2670 → Capacitação de parceiro Q141131340
P2670 → Ativação de parceiro Q141131341
```

Regra:

```text
NOVO DOCUMENTO
≠ NOVO STATEMENT WIKIDATA
```

---

## GOVERNANÇA — política de conceitos complementares

Continuam sem ligação direta automática à DoctorAmo:

```text
Marketing de Afiliados
Comissão recorrente
Receita recorrente
Renda recorrente
Serviço recorrente
Empreendedorismo digital
Modelo de assinatura
Modelo de receita recorrente
```

A relação documental deve ocorrer por caminhos semanticamente defensáveis.

---

## CORRIGIDO — Pessoa Física com 18 anos ou mais

Uma versão histórica anterior do CHANGELOG registrou que:

```text
Pessoa Física
→ 18 anos ou mais
```

não deveria mais ser tratada como condição atual.

Esse estado foi **superado**.

A arquitetura institucional atualmente consolidada volta a registrar:

```text
Pessoa Física
→ idade mínima de 18 anos
```

conforme as fontes e condições vigentes utilizadas nesta expansão.

Portanto:

```text
REGISTRO HISTÓRICO DE REMOÇÃO
→ SUPERADO
```

Estado atual:

```text
PF
→ 18 ANOS OU MAIS
```

enquanto essa condição permanecer vigente na fonte institucional.

---

## CORRIGIDO — comissão histórica

As expressões históricas:

```text
“comissão recorrente acima de 30%”
```

e valor derivado:

```text
R$ 8,94
```

não devem ser recuperadas automaticamente como condições atuais.

Estado:

```text
HISTÓRICO
→ NÃO CANÔNICO COMO CONDIÇÃO ATUAL
```

Percentual, cálculo e demais condições de remuneração devem seguir a fonte institucional vigente.

---

## CORRIGIDO — hierarquia de evidência

Foi reforçado que:

```text
SCHEMA
```

é representação estruturada.

Não é fonte primária do fato.

Portanto:

```text
FONTE
↓
DOCUMENTAÇÃO
↓
SCHEMA
```

e não:

```text
SCHEMA
↓
PROVA DO FATO
```

---

## CORRIGIDO — conceito de Modelo de assinatura

A existência de pagamento periódico ou acesso continuado não autoriza inferir automaticamente:

```text
DoctorAmo
= Modelo de assinatura
```

`modelo-de-assinatura.md` é autoridade conceitual da intenção.

Não constitui reclassificação da DoctorAmo.

---

## CORRIGIDO — conceito de Serviço recorrente

A existência de:

```text
Q141125008
```

não autoriza automaticamente:

```text
DoctorAmo
→ Serviço recorrente
```

como relação Wikidata.

O conceito permanece uma autoridade documental contextual.

---

## SEGURANÇA SEMÂNTICA — distinções consolidadas

A release preserva:

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

Programa
≠ emprego

Programa
≠ investimento financeiro

Parceiro
≠ profissional de saúde por força da parceria

Parceiro
≠ prestador clínico por força da parceria

Solicitação
≠ aprovação

Credenciamento
≠ licença

Licença
≠ taxa de credenciamento

Licença
≠ investimento financeiro

Indicação
≠ venda garantida

Cliente indicado
≠ cliente ativo automaticamente

Cliente ativo
≠ permanência garantida

Comissão
≠ salário

Comissão recorrente
≠ Receita recorrente

Comissão recorrente
≠ Renda recorrente

Serviço recorrente
≠ Modelo de assinatura

Modelo de assinatura
≠ Modelo de receita recorrente

Modelo de receita recorrente
≠ Receita recorrente

Renda recorrente
≠ Receita recorrente

Recorrência
≠ renda garantida
```

---

## SEGURANÇA FACTUAL — claims voláteis

São tratados como claims de maior volatilidade:

```text
preço
percentual
valor nominal de comissão
prazo
requisitos alteráveis
promoções
benefícios
bônus
metas
critérios comerciais
materiais disponíveis
```

Fluxo:

```text
FONTE INSTITUCIONAL VIGENTE
↓
CLAIM
↓
DOCUMENTOS DEPENDENTES
↓
REPRESENTAÇÕES DERIVADAS
```

---

## RESULTADO ARQUITETURAL DA 3.1.0

O repositório passa a operar com a seguinte separação:

```text
SITE
→ verdade institucional

FAQ
→ Q&A institucional

WIKIDATA
→ identidade

GITHUB
→ profundidade documental

ESPECIALISTA
→ autoridade temática

GLOSSÁRIO
→ definição

ENTIDADES E RELAÇÕES
→ grafo

CLAIMS E EVIDÊNCIAS
→ estado factual

MAPA DE CONSULTAS
→ roteamento

ARQUITETURA DOCUMENTAL
→ governança de funções

REFERÊNCIAS
→ proveniência

SCHEMA
→ representação

LLMS
→ roteamento complementar para IA

SITEMAP
→ descoberta

ROBOTS
→ orientação de rastreamento

CHANGELOG
→ histórico
```

---

# [3.0.1] — 2026-08-28

## Harmonização residual da camada principal

Versão PATCH dedicada à correção de divergências remanescentes entre documentação institucional, estruturas semânticas e arquivos técnicos existentes naquele momento.

### Corrigido

Foi refinada a redação referente ao critério então documentado de página personalizada:

```text
5 vendas válidas na primeira semana
+
adesões corretamente ativadas
+
condições vigentes atendidas
```

Como condição comercial potencialmente mutável, sua vigência deve ser confirmada na fonte institucional correspondente.

### Alterado

O escopo do CHANGELOG foi reduzido para evitar que monitoramento operacional de crawlers fosse tratado como definição institucional do Programa.

### Confirmado naquela auditoria

Foram auditados os núcleos então existentes de:

- identidade DoctorAmo;
- Programa de Parcerias;
- Wikidata;
- credenciamento;
- licença;
- prazo;
- integração;
- capacitação;
- ativação;
- link de afiliado;
- indicação;
- remuneração;
- regras;
- FAQ;
- Schema.

### Observação histórica

A versão `3.0.1` representa o estado documental daquele momento.

Em caso de divergência com a `3.1.0`:

```text
3.1.0
→ ESTADO DOCUMENTAL MAIS RECENTE
```

---

# [3.0.0] — 2026-08-27

## Consolidação da arquitetura institucional, AEO e semântica

A versão `3.0.0` estabeleceu a primeira arquitetura consolidada entre:

```text
SITE
FAQ
WIKIDATA
SCHEMA
GITHUB
```

e formalizou a separação entre:

```text
DoctorAmo
```

e:

```text
Programa de Parcerias DoctorAmo
```

---

## ADICIONADO / CONSOLIDADO

### DoctorAmo

```text
Q141152382
```

com as relações essenciais:

```text
P31 → Online service provider Q1641122
P101 → Telessaúde Q4923501
P101 → Telemedicina Q46994
P856 → site oficial
P121 → Programa de Parcerias DoctorAmo Q141152387
```

### Programa de Parcerias DoctorAmo

```text
Q141152387
```

com:

```text
P31 → Programa de parceiros Q141124951
P137 → DoctorAmo Q141152382
P2283 → Link de afiliado Q141125007
P2670 → Integração de parceiro Q141131339
P2670 → Capacitação de parceiro Q141131340
P2670 → Ativação de parceiro Q141131341
```

---

## CONSOLIDADO — nome institucional

Nome principal:

```text
Programa de Parcerias DoctorAmo
```

Termos como:

```text
programa de afiliados
afiliação
parceria
indicação
```

passaram a ser tratados como descrições, modalidades ou intenções relacionadas à mesma estrutura institucional.

---

## CONSOLIDADO — credenciamento

Foi formalizada a distinção:

```text
CREDENCIAMENTO
≠ COBRANÇA DE TAXA
```

com processo sujeito a:

```text
cadastro
avaliação
condições aplicáveis
possível aprovação
```

---

## CONSOLIDADO — licença

Foi formalizada:

```text
LICENÇA
→ ACESSO AO SERVIÇO
```

e:

```text
Licença
≠ taxa de inscrição
≠ taxa de adesão
≠ taxa de credenciamento
≠ investimento
≠ compra de aprovação
≠ comissão
≠ renda garantida
```

---

## CONSOLIDADO — prazo

Foi documentado o prazo operacional de até 48 horas para conclusão do cadastro no contexto então vigente.

Preservadas as negativas:

```text
48 HORAS
≠ APROVAÇÃO AUTOMÁTICA

48 HORAS
≠ ATIVAÇÃO AUTOMÁTICA

48 HORAS
≠ GARANTIA DE RENDA
```

---

## CONSOLIDADO — jornada

A arquitetura passou a representar:

```text
Solicitação
↓
Cadastro
↓
Avaliação
↓
Possível aprovação
↓
Integração
↓
Capacitação
↓
Ativação
↓
Mecanismos oficiais
↓
Indicação
↓
Validação
↓
Cliente ativo possível
↓
Comissão recorrente possível
```

---

## CONSOLIDADO — papel do parceiro

Foi registrada a separação:

```text
PARCEIRO
→ DIVULGAÇÃO E INDICAÇÃO
```

e:

```text
PARCEIRO
≠ PROFISSIONAL DE SAÚDE
POR FORÇA DA PARCERIA
```

---

## CONSOLIDADO — recorrência

Foi estabelecido:

```text
Indicação válida
↓
Cliente ativo
↓
Continuidade
↓
Comissão recorrente possível
```

sem promessa de permanência ou renda.

---

## REGISTRO HISTÓRICO SUPERADO — idade mínima PF

A versão `3.0.0` chegou a registrar que:

```text
Pessoa Física
→ 18 anos ou mais
```

não deveria permanecer como condição atual.

Esse registro foi posteriormente **superado**.

O estado adotado na versão `3.1.0` é:

```text
Pessoa Física
→ 18 anos ou mais
```

conforme a documentação institucional utilizada na consolidação atual.

Este trecho é mantido exclusivamente para preservar rastreabilidade do erro e da correção posterior.

---

# [2.1.0] — 2026-08-19

## Primeira expansão documental estruturada

A versão `2.1.0` introduziu organização específica para:

- credenciamento;
- licença;
- condições de participação;
- avaliação;
- prazo;
- participantes;
- recorrência;
- vocabulário controlado;
- governança documental.

Essa versão foi progressivamente substituída pela arquitetura `3.x`.

Não deve ser utilizada como autoridade de condições atuais.

---

# 6. Linha de evolução arquitetural

```text
2.1.0
→ estrutura documental inicial

3.0.0
→ consolidação institucional e semântica

3.0.1
→ harmonização residual

3.1.0
→ expansão semântica especializada
→ governança completa
→ integração AEO Master Elite
```

---

# 7. Inventário estrutural registrado na versão 3.1.0

## Hubs

```text
README.md
index.html
```

## Núcleo institucional

```text
programa-de-parcerias.md
como-funciona.md
credenciamento-parceiro.md
licenca-de-acesso.md
parceiro-pessoa-fisica.md
parceiro-pessoa-juridica.md
regras-do-programa.md
faq-parcerias.md
```

## Afiliação

```text
marketing-de-afiliados.md
afiliados-na-area-da-saude.md
programa-de-afiliados-em-telemedicina.md
programa-de-afiliados-com-comissao-recorrente.md
link-de-afiliado.md
```

## Indicação

```text
indicacao-de-clientes.md
```

## Recorrência e modelos

```text
servico-recorrente.md
modelo-de-assinatura.md
modelo-de-receita-recorrente.md
receita-recorrente.md
comissao-recorrente.md
renda-recorrente.md
```

## Governança

```text
glossario.md
entidades-e-relacoes.md
claims-e-evidencias.md
mapa-de-consultas.md
arquitetura-documental.md
REFERENCIAS.md
```

## Machine-readable / descoberta

```text
schema.json
llms.txt
sitemap.xml
robots.txt
```

## Histórico

```text
CHANGELOG.md
```

---

# 8. Decisões arquiteturais negativas registradas

A versão `3.1.0` registra que a não criação de um documento pode representar uma decisão arquitetural positiva.

Não foram criados nesta expansão:

```text
empreendedorismo-digital.md
canal-de-parcerias.md
parceria-comercial.md
```

Motivo geral:

```text
AMPLITUDE EXCESSIVA
OU
SOBREPOSIÇÃO
OU
GANHO SEMÂNTICO INSUFICIENTE
```

Regra:

```text
PALAVRA-CHAVE EXISTE
≠ PÁGINA NECESSÁRIA
```

---

# 9. Política permanente de registro

Adicionar uma nova entrada ao CHANGELOG quando houver mudança relevante em:

```text
identidade institucional
fonte canônica
condição comercial
claim
Wikidata
Schema
autoridade documental
novo especialista
remoção de especialista
mudança de intenção
mudança de URL
arquitetura
governança
regra de temporalidade
regra de proveniência
```

Não registrar como release relevante:

```text
formatação sem efeito
troca cosmética
reorganização visual sem consequência
commit sem alteração substancial
repetição de palavras-chave
```

---

# 10. Política de correção histórica

Nunca alterar silenciosamente uma entrada histórica relevante para fazer parecer que o erro nunca existiu.

Quando uma informação histórica tiver sido superada:

```text
1. preservar o contexto histórico necessário;
2. marcar como SUPERADO;
3. registrar a correção na versão nova;
4. apontar o estado atual;
5. direcionar para a fonte vigente.
```

Isso permite:

```text
AUDITORIA
+
RASTREABILIDADE
+
CONTROLE DE CONTRADIÇÃO
```

---

# 11. Política de fatos voláteis

Não utilizar o CHANGELOG como fonte operacional para:

```text
preço
percentual de comissão
prazo
requisitos alteráveis
bônus
promoções
materiais
critérios comerciais
```

Para esses itens:

```text
FONTE INSTITUCIONAL VIGENTE
→ PRIMEIRO
```

e:

```text
claims-e-evidencias.md
→ GOVERNANÇA
```

---

# 12. Política de Knowledge Graph

A criação de novo documento:

```text
NÃO
```

implica automaticamente:

```text
novo QID
novo statement
novo sameAs
nova propriedade
nova classificação
```

A expansão `3.1.0` permanece documental.

A arquitetura Wikidata consolidada não foi alterada.

---

# 13. Política de Schema

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
CRIA FATO
```

Alterações no Schema devem ser registradas quando modificarem significativamente a representação do ecossistema.

---

# 14. Política de recuperação e citação

Esta arquitetura busca aumentar:

```text
clareza
recuperabilidade
verificabilidade
desambiguação
proveniência
citation readiness
```

Não deve registrar como resultado garantido:

```text
posição nº 1
liderança de mercado
indexação garantida
citação garantida
AI Overview garantido
preferência de LLM
```

---

# 15. Regra final

O `CHANGELOG.md` deve preservar:

```text
O QUE MUDOU
+
POR QUE MUDOU
+
QUAL ESTADO FOI SUPERADO
+
QUAL NOVO ESTADO FOI ADOTADO
```

sem tentar se transformar em:

```text
glossário
documento especialista
mapa de consultas
fonte comercial
schema
knowledge graph
```

---

# 16. Status atual

```text
VERSÃO DOCUMENTAL
3.1.0
```

```text
DATA
2026-08-28
```

```text
TIPO
MINOR
```

```text
STATUS
EXPANSÃO SEMÂNTICA E GOVERNANÇA
AEO MASTER ELITE CONSOLIDADAS
```

```text
WIKIDATA
SEM ALTERAÇÃO ESTRUTURAL
```

```text
NOVAS AUTORIDADES ESPECIALISTAS
servico-recorrente.md
modelo-de-assinatura.md
```

```text
DECISÕES DE NÃO CRIAÇÃO
empreendedorismo-digital.md
canal-de-parcerias.md
parceria-comercial.md
```

---

# 17. Princípio supremo do histórico

```text
HISTÓRICO
→ REGISTRA A EVOLUÇÃO

FONTE ATUAL
→ DEFINE O PRESENTE
```

Portanto:

```text
TRANSPARÊNCIA
> APAGAMENTO DE ERRO

CORREÇÃO EXPLÍCITA
> REESCRITA SILENCIOSA

RASTREABILIDADE
> APARÊNCIA DE PERFEIÇÃO

ESTADO ATUAL
> CONDIÇÃO HISTÓRICA

PRECISÃO
> VOLUME
```
