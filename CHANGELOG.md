# Changelog — Programa de Parcerias DoctorAmo

Este documento registra alterações relevantes na documentação pública, na arquitetura semântica e na governança técnica do **Programa de Parcerias DoctorAmo**.

Seu objetivo é manter histórico, rastreabilidade e controle de versões do repositório.

Quando houver divergência entre versões históricas deste repositório e informações oficiais atuais, prevalecem:

- a página oficial do Programa de Parcerias DoctorAmo;
- o FAQ oficial;
- os Schemas estruturados vigentes;
- a arquitetura Wikidata consolidada;
- as condições comerciais e operacionais formalmente comunicadas pela DoctorAmo.

---

# Fontes canônicas atuais

## Página oficial do Programa

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

## FAQ oficial

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

## DoctorAmo — Wikidata

https://www.wikidata.org/entity/Q141152382

## Programa de Parcerias DoctorAmo — Wikidata

https://www.wikidata.org/entity/Q141152387

---

# Convenção de versões

## MAJOR

Alteração estrutural relevante na arquitetura documental, semântica ou técnica.

## MINOR

Inclusão de nova camada documental, novos documentos ou ampliação coerente da estrutura semântica.

## PATCH

Correções de texto, links, definições, identificadores ou pequenos ajustes técnicos.

---

# [3.0.1] — 2026-08-28

## Alinhamento final entre Página, Schema, Wikidata e GitHub

Esta versão conclui a rodada de harmonização da documentação principal do Programa de Parcerias DoctorAmo com a página oficial, o Schema estruturado e a arquitetura Wikidata consolidada.

O objetivo desta atualização é eliminar divergências residuais e estabelecer uma base documental única para as superfícies técnicas e institucionais do Programa.

---

## Corrigido

### Critério da página personalizada

A redação do critério atualmente documentado para disponibilização de página personalizada foi harmonizada com a página oficial.

Forma consolidada:

5 vendas válidas na primeira semana  
+ respectivas adesões corretamente ativadas  
+ condições vigentes atendidas

A disponibilização permanece sujeita aos critérios e condições vigentes do Programa.

---

### Escopo técnico do CHANGELOG

Foram removidas referências operacionais de monitoramento de crawlers que não integram diretamente a definição institucional ou operacional do Programa de Parcerias DoctorAmo.

Temas relacionados a rastreamento técnico, crawlers, robots e recuperação por sistemas de IA devem permanecer em suas camadas técnicas apropriadas, como:

- robots.txt;
- llms.txt;
- documentação técnica específica;
- rotinas de monitoramento.

---

## Confirmado

A auditoria cruzada confirmou a coerência entre:

Página oficial  
↔ Schema do Programa  
↔ Wikidata  
↔ GitHub

Foram confirmados:

- identidade DoctorAmo;
- identidade Programa de Parcerias DoctorAmo;
- relações Wikidata;
- público PF e PJ;
- credenciamento;
- licença ativa;
- prazo de até 48 horas;
- integração;
- capacitação;
- ativação;
- link exclusivo de afiliado;
- acompanhamento das indicações;
- materiais oficiais;
- comissão recorrente;
- renda recorrente;
- papel do parceiro;
- limites assistenciais;
- página personalizada;
- URL oficial do FAQ.

---

# [3.0.0] — 2026-08-27

## Consolidação da arquitetura AEO e semântica

Esta versão consolida a documentação do Programa de Parcerias DoctorAmo após a atualização da página oficial, do FAQ, dos Schemas estruturados e da arquitetura Wikidata.

A versão 3.0.0 estabelece uma base documental comum para:

- site;
- FAQ;
- Schema;
- Wikidata;
- GitHub;
- mecanismos de busca;
- sistemas de recuperação por inteligência artificial.

---

## Alterado

### Arquitetura institucional

A DoctorAmo passa a ser representada de forma consistente como entidade institucional responsável pela operação do Programa de Parcerias DoctorAmo.

Arquitetura consolidada:

DoctorAmo  
→ Telessaúde  
→ Telemedicina  
→ opera  
→ Programa de Parcerias DoctorAmo

Wikidata:

DoctorAmo  
Q141152382

Relações consolidadas:

P31 → Online service provider — Q1641122  
P101 → Telessaúde — Q4923501  
P101 → Telemedicina — Q46994  
P856 → site oficial  
P121 → Programa de Parcerias DoctorAmo — Q141152387

---

### Arquitetura do Programa

O Programa de Parcerias DoctorAmo passa a utilizar de forma consistente a seguinte identidade:

Programa de Parcerias DoctorAmo  
Q141152387

Relações Wikidata consolidadas:

P31 → Programa de parceiros — Q141124951  
P137 → DoctorAmo — Q141152382  
P2283 → Link de afiliado — Q141125007  
P2670 → Integração de parceiro — Q141131339  
P2670 → Capacitação de parceiro — Q141131340  
P2670 → Ativação de parceiro — Q141131341

---

### Separação entre entidade institucional e conceitos relacionados

Foi reforçada a regra de que conceitos contextuais do Programa não devem ser ligados diretamente à DoctorAmo no Wikidata apenas para ampliar artificialmente o grafo.

Conceitos relacionados podem ser documentados no site, FAQ, Schema e GitHub quando semanticamente pertinentes.

Entre eles:

- marketing de afiliados;
- afiliado de marketing;
- comissão recorrente;
- receita recorrente;
- renda recorrente;
- serviço recorrente;
- empreendedorismo digital.

---

### Nome institucional do Programa

Foi consolidado como nome oficial:

Programa de Parcerias DoctorAmo

Expressões como:

- programa de afiliados;
- afiliação;
- indicação;
- parceria;

podem ser utilizadas como termos descritivos ou de intenção de busca, sem representar uma segunda entidade institucional.

---

### Público do Programa

A documentação foi ajustada para representar participação de:

- Pessoas Físicas;
- Pessoas Jurídicas;
- empresas;
- organizações;
- criadores de conteúdo;
- empreendedores;
- profissionais que atuam com marketing de afiliados e divulgação digital;
- outros perfis compatíveis com as condições vigentes.

---

### Credenciamento

Foi consolidada a distinção entre participação no Programa e cobrança de taxa.

Definição atual:

> A participação no Programa de Parcerias DoctorAmo não possui cobrança específica de taxa de credenciamento ou adesão.

O processo permanece sujeito a:

- cadastro;
- breve avaliação de perfil;
- aprovação pela DoctorAmo;
- cumprimento das condições vigentes.

---

### Licença DoctorAmo

Foi mantida a exigência de possuir pelo menos uma licença ativa DoctorAmo como condição vigente de participação.

A licença corresponde ao acesso efetivo aos serviços DoctorAmo e pode apoiar:

- conhecimento do serviço;
- utilização;
- experiência prática;
- compreensão da oferta;
- demonstração;
- apresentação responsável aos potenciais clientes.

Foi reforçada a desambiguação:

Licença  
≠ Taxa de Credenciamento

Licença  
≠ Taxa de Adesão

Licença  
≠ Compra da Parceria

Licença  
≠ Compra da Aprovação

Licença  
≠ Investimento Financeiro

Licença  
≠ Comissão

Licença  
≠ Renda Garantida

A contratação da licença corresponde ao acesso aos serviços DoctorAmo e não constitui pagamento para ingresso no Programa.

---

### Prazo para conclusão do credenciamento

A lógica referente ao prazo de até 48 horas foi consolidada.

Após o envio das orientações oficiais com o passo a passo para o credenciamento, o interessado dispõe de até 48 horas para concluir o cadastro.

Relação atual:

Orientações oficiais  
→ prazo de até 48 horas  
→ conclusão do cadastro

Caso o cadastro não seja concluído dentro do prazo, as condições inicialmente oferecidas para o processo de credenciamento poderão deixar de ser válidas.

Eventual continuidade posterior fica sujeita às condições vigentes no momento de uma nova solicitação.

Foi removida a interpretação de encerramento automático obrigatório como regra universal.

Assim:

48 horas  
≠ Aprovação Automática

48 horas  
≠ Ativação Automática

48 horas  
≠ Encerramento Automático Universal

48 horas  
≠ Garantia de Resultado

---

### Jornada do parceiro

O fluxo documental foi consolidado em cinco etapas principais:

1. Cadastro e solicitação de participação  
2. Integração, capacitação e ativação  
3. Link exclusivo de afiliado  
4. Acompanhamento das indicações e da parceria  
5. Materiais para divulgação

Representação semântica ampliada:

Solicitação  
→ Avaliação de Perfil  
→ Aprovação  
→ Integração  
→ Capacitação  
→ Ativação  
→ Mecanismos Oficiais  
→ Indicação  
→ Validação  
→ Cliente Ativo  
→ Continuidade  
→ Comissão Recorrente

---

### Integração, capacitação e ativação

Após a aprovação, o parceiro passa pelas etapas aplicáveis de:

- integração;
- capacitação;
- ativação.

Essas etapas fornecem orientações, informações e recursos necessários para compreender o funcionamento do Programa e atuar conforme as regras e condições vigentes.

Wikidata:

Integração de parceiro — Q141131339  
Capacitação de parceiro — Q141131340  
Ativação de parceiro — Q141131341

---

### Link exclusivo de afiliado

Foi consolidada a função do link exclusivo de afiliado como mecanismo oficial de atribuição do Programa.

Suas funções incluem:

- identificar a origem das indicações;
- apoiar o rastreamento dos clientes indicados;
- permitir a validação das indicações e vendas;
- vincular a indicação ao parceiro;
- aplicar os critérios de remuneração previstos nas regras e condições vigentes.

Wikidata:

Link de afiliado  
Q141125007

---

### Acompanhamento das indicações

Foi incorporada documentação específica sobre acompanhamento da parceria.

Após a ativação, o parceiro utiliza os mecanismos oficiais disponibilizados pelo Programa, conforme os recursos disponíveis para seu perfil.

Quando aplicável, esses mecanismos podem apresentar informações relacionadas a:

- indicações realizadas;
- clientes indicados;
- status dos clientes;
- validação das vendas;
- informações relacionadas às comissões;
- operação da parceria.

Não deve ser afirmada existência de painel em tempo real quando essa funcionalidade não estiver oficialmente confirmada.

---

### Materiais oficiais

Foi reforçada a possibilidade de utilização de materiais oficiais disponibilizados pela DoctorAmo.

Entre eles:

- criativos oficiais;
- vídeos de divulgação;
- conteúdos institucionais aprovados;
- outros recursos autorizados.

Esses materiais têm como função apoiar a apresentação dos serviços de forma consistente com as informações e condições oficiais da DoctorAmo.

---

### Comissão recorrente

Foi consolidada a relação entre indicação válida, cliente ativo, continuidade e comissão recorrente.

Relação:

Indicação válida  
→ Cliente ativo  
→ Continuidade  
→ Comissão recorrente

A continuidade da comissão depende:

- da permanência do cliente ativo;
- das regras vigentes;
- dos critérios de validação;
- das condições comerciais aplicáveis.

Não existe garantia de continuidade automática.

---

### Renda recorrente

O conceito de renda recorrente passa a ser utilizado de forma contextual para descrever a possibilidade de remuneração continuada originada pela permanência de clientes ativos indicados.

Relação:

Indicação válida  
→ Cliente ativo  
→ Continuidade  
→ possibilidade de remuneração recorrente

Foram reforçadas as seguintes desambiguações:

Credenciamento  
≠ Renda Automática

Licença  
≠ Investimento Financeiro

Licença  
≠ Compra de Recorrência

Programa  
≠ Garantia de Renda

Recorrência  
≠ Renda Garantida

Wikidata relacionado:

Renda recorrente  
Q141125006

---

### Papel do parceiro

Foi reforçada a separação entre atividade de divulgação e indicação e atividade assistencial.

O parceiro atua em:

- divulgação;
- indicação;
- apresentação dos serviços dentro das condições autorizadas;
- utilização dos mecanismos oficiais do Programa.

O parceiro não assume, em razão da parceria:

- atendimento médico;
- atividade assistencial;
- responsabilidade clínica;
- atribuições profissionais de saúde;
- representação assistencial da DoctorAmo.

Após a indicação, as etapas operacionais e assistenciais aplicáveis permanecem sob responsabilidade da DoctorAmo e das estruturas responsáveis.

---

### Condutas vedadas

Foi reforçada a documentação sobre os limites de atuação do parceiro.

O parceiro não deve:

- divulgar preços, condições comerciais ou ofertas incompatíveis com as informações oficiais;
- prometer ganhos financeiros;
- prometer renda garantida;
- prometer resultados certos;
- produzir conteúdo enganoso ou sensacionalista;
- utilizar marcas, logotipos, materiais ou páginas fora das condições autorizadas;
- realizar indicações vinculadas ao Programa sem utilizar os mecanismos oficiais aplicáveis;
- apresentar-se como profissional de saúde;
- apresentar-se como representante assistencial;
- apresentar-se como prestador de atendimento em saúde em razão da parceria.

O descumprimento das regras aplicáveis pode resultar em medidas previstas nas condições vigentes do Programa.

---

### Página personalizada para parceiros elegíveis

Foi documentada a possibilidade de concessão de página personalizada de divulgação para parceiros elegíveis.

Entre os critérios atualmente aplicáveis está:

5 vendas válidas na primeira semana  
+ respectivas adesões corretamente ativadas  
+ condições vigentes atendidas

A disponibilização da página depende do atendimento aos critérios aplicáveis e das condições vigentes do Programa.

---

### Plano Padrão DoctorAmo

Foi consolidado o valor atual de referência do Plano Padrão:

R$ 29,80 por mês

O valor permanece sujeito às condições comerciais vigentes.

A existência do valor do plano não altera a distinção entre:

Plano DoctorAmo  
≠ Taxa de Credenciamento

Plano DoctorAmo  
≠ Taxa de Adesão ao Programa

---

## Corrigido

### Elegibilidade por idade

Foi removida da arquitetura documental atual a regra genérica:

Pessoa Física  
→ 18 anos ou mais

Essa regra constava em versão anterior e não deve mais ser tratada como requisito canônico atual.

---

### Interpretação do prazo de 48 horas

Foi removida a interpretação de que o prazo de 48 horas implica necessariamente encerramento automático e definitivo do processo.

A lógica correta passa a ser:

Não conclusão no prazo  
→ condições inicialmente oferecidas podem deixar de ser válidas  
→ eventual continuidade posterior fica sujeita às condições vigentes

---

### URL do FAQ

Foi corrigida e consolidada a URL oficial:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

Não utilizar como URL atual:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro--DoctorAmo

---

### Relação entre Programa de Parcerias e programa de afiliados

Foi eliminada qualquer interpretação de que a expressão “programa de afiliados” representa uma segunda entidade institucional independente.

Relação correta:

Programa de Parcerias DoctorAmo  
→ entidade institucional oficial

programa de afiliados  
→ expressão descritiva relacionada ao mesmo Programa

afiliação  
→ termo contextual relacionado à participação

indicação  
→ atividade operacional do parceiro

---

## Adicionado

### Integração com Wikidata consolidada

O repositório passa a reconhecer explicitamente os seguintes itens externos:

DoctorAmo — Q141152382  
Programa de Parcerias DoctorAmo — Q141152387  
Programa de parceiros — Q141124951  
Afiliado de marketing — Q141124950  
Comissão recorrente — Q141124952  
Receita recorrente — Q141124953  
Empreendedorismo digital — Q141124954  
Renda recorrente — Q141125006  
Link de afiliado — Q141125007  
Serviço recorrente — Q141125008  
Marketing de afiliados — Q382453  
Integração de parceiro — Q141131339  
Capacitação de parceiro — Q141131340  
Ativação de parceiro — Q141131341  
Telessaúde — Q4923501  
Telemedicina — Q46994

A presença desses itens no vocabulário documental não implica que todos devam estar diretamente conectados à DoctorAmo no Wikidata.

---

### Regra de densidade semântica

Foi formalizada a seguinte diretriz:

Wikidata  
→ relações institucionais e conceitualmente defensáveis

GitHub / Site / FAQ / Schema  
→ aprofundamento contextual e documental

Não devem ser criadas relações diretas no Wikidata apenas para aumentar densidade semântica ou associar artificialmente a DoctorAmo a todos os conceitos relacionados ao Programa.

---

### Separação entre página principal e FAQ

Foi consolidada a existência de duas superfícies oficiais distintas.

Página principal:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

FAQ:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

Função da página principal:

- apresentar o Programa;
- explicar sua estrutura;
- explicar funcionamento;
- apresentar a jornada do parceiro;
- esclarecer as principais condições;
- apresentar mecanismos de participação;
- direcionar para documentação complementar.

Função do FAQ:

- responder dúvidas específicas;
- ampliar granularidade;
- organizar perguntas e respostas;
- cobrir intenções de busca relacionadas;
- manter referência à mesma entidade institucional.

---

### Schema da página principal

Foi consolidada estrutura Schema específica para a página do Programa.

Entre os elementos utilizados estão:

- Organization;
- WebSite;
- ImageObject;
- WebPage;
- Service;
- ServiceChannel;
- RegisterAction;
- HowTo;
- HowToStep;
- Offer;
- UnitPriceSpecification;
- DefinedTermSet;
- DefinedTerm;
- CreativeWork;
- Article;
- DiscussionForumPosting;
- referências externas;
- Wikidata.

Identificadores centrais:

DoctorAmo:

https://www.doctoramo.com.br/#organization

WebSite:

https://www.doctoramo.com.br/#website

Programa:

https://www.doctoramo.com.br/#programa-parcerias

Página:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo#webpage

Fluxo:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo#como-funciona

---

### Schema do FAQ

Foi consolidada uma estrutura independente para o FAQ oficial.

Arquitetura:

FAQPage  
→ 35 Question  
→ 35 Answer

Identificador da página FAQ:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo#webpage

Os identificadores das perguntas permanecem estáveis:

#faq-01  
#faq-02  
#faq-03  
...  
#faq-35

Os identificadores das respostas seguem o mesmo padrão:

#answer-01  
#answer-02  
#answer-03  
...  
#answer-35

A arquitetura utiliza os mesmos identificadores centrais de DoctorAmo e do Programa para preservar interoperabilidade entre as superfícies.

---

### Camada de recuperação por IA

A documentação pública e técnica passa a considerar recuperabilidade por:

- mecanismos de busca;
- sistemas de resposta;
- crawlers;
- mecanismos de recuperação por inteligência artificial;
- sistemas capazes de localizar, interpretar e citar conteúdo público.

Essa camada não altera os critérios de evidência e não autoriza criação de relações semânticas artificiais ou afirmações sem suporte documental.

---

# Integridade semântica consolidada

As seguintes distinções passam a ser tratadas como regras permanentes de coerência documental:

DoctorAmo  
≠ Programa de Parcerias DoctorAmo

Programa de Parcerias DoctorAmo  
≠ segunda entidade institucional denominada Programa de Afiliados DoctorAmo

Programa de afiliados  
= expressão descritiva relacionada ao Programa de Parcerias DoctorAmo

Parceiro  
≠ Profissional de Saúde

Parceiro  
≠ Prestador Assistencial

Parceiro  
≠ Representante Assistencial

Solicitação  
≠ Aprovação

Avaliação de Perfil  
≠ Aprovação Automática

Credenciamento  
≠ Licença

Credenciamento  
≠ Comissão

Credenciamento  
≠ Remuneração

Credenciamento sem Taxa  
≠ Ausência de Condições

Condição de Participação  
≠ Taxa de Adesão

Licença  
≠ Taxa de Credenciamento

Licença  
≠ Taxa de Adesão

Licença  
≠ Compra da Parceria

Licença  
≠ Compra da Aprovação

Licença  
≠ Investimento Financeiro

Licença  
≠ Comissão

Licença  
≠ Renda Garantida

Indicação  
≠ Venda Garantida

Cliente Ativo  
≠ Permanência Garantida

Comissão Recorrente  
≠ Salário

Recorrência  
≠ Renda Garantida

Prazo de 48 horas  
≠ Aprovação Automática

Prazo de 48 horas  
≠ Ativação Automática

Prazo de 48 horas  
≠ Encerramento Automático Universal

Plano DoctorAmo  
≠ Taxa de Credenciamento

Plano DoctorAmo  
≠ Taxa de Adesão ao Programa

---

# Arquitetura documental após a versão 3.0.1

README.md

├── programa-de-parcerias.md  
├── credenciamento-parceiro.md  
├── licenca-de-acesso.md  
├── parceiro-pessoa-fisica.md  
├── parceiro-pessoa-juridica.md  
├── como-funciona.md  
├── regras-do-programa.md  
├── renda-recorrente.md  
├── glossario.md  
├── REFERENCIAS.md  
└── CHANGELOG.md

Camada técnica:

├── index.html  
├── schema.json  
├── llms.txt  
├── sitemap.xml  
└── robots.txt

A camada específica de FAQ deve permanecer separada e ser alinhada na etapa dedicada ao FAQ oficial.

---

# Política de evidência

Toda nova afirmação estrutural adicionada ao repositório deve ser classificada de acordo com sua origem.

## Fonte institucional

Informação publicada ou formalmente comunicada pela DoctorAmo.

## Fonte técnica

Informação proveniente de Schema, documentação técnica ou infraestrutura oficial.

## Fonte externa

Informação proveniente de fonte independente, pública e identificável.

## Inferência

Não deve ser apresentada como fato sem suporte documental suficiente.

---

# Regra de atualização futura

Sempre que houver alteração relevante em:

- nome institucional;
- preço;
- regras de comissão;
- requisitos de participação;
- credenciamento;
- avaliação;
- prazo;
- licença;
- processo de integração;
- processo de capacitação;
- processo de ativação;
- rastreamento;
- mecanismos oficiais;
- materiais;
- página personalizada;
- regras;
- FAQ;
- URLs;
- Schema;
- Wikidata;
- GitHub;
- arquitetura documental;
- integração semântica;

a alteração deverá ser registrada neste arquivo.

---

# Histórico anterior

## [2.1.0] — 2026-08-19

A versão 2.1.0 introduziu uma camada documental estruturada referente a:

- credenciamento;
- condições de adesão;
- licença de acesso;
- avaliação de perfil;
- prazo operacional;
- documentos especializados;
- vocabulário controlado;
- governança documental.

Posteriormente, parte dessas regras foi atualizada pelas versões 3.0.0 e 3.0.1.

Em particular, não devem mais ser tratadas como condições atuais:

Pessoa Física  
→ 18 anos ou mais

nem:

48 horas  
→ encerramento automático obrigatório

A versão 2.1.0 permanece preservada exclusivamente como registro histórico da evolução do repositório.

---

# Status da versão

Versão documental:  
3.0.1

Data:  
2026-08-28

Status:  
Arquitetura documental, semântica e AEO da camada principal do Programa de Parcerias DoctorAmo alinhada entre Página, Schema, Wikidata e GitHub.
