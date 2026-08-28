# Changelog — Programa de Parcerias DoctorAmo

Este documento registra alterações relevantes na documentação pública, na arquitetura semântica e na governança técnica do **Programa de Parcerias DoctorAmo**.

Seu objetivo é manter histórico, rastreabilidade, proveniência e controle de versões do repositório sem competir com as fontes canônicas vigentes.

> **Regra de prevalência:** quando houver divergência entre versões históricas deste repositório e informações oficiais atuais, prevalecem a página oficial do Programa, o FAQ oficial, os Schemas vigentes e as condições formalmente comunicadas pela DoctorAmo.

---

# Fontes canônicas atuais

## Página oficial do Programa

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

## FAQ oficial

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

## Entidade DoctorAmo — Wikidata

https://www.wikidata.org/entity/Q141152382

## Programa de Parcerias DoctorAmo — Wikidata

https://www.wikidata.org/entity/Q141152387

---

# Convenção de versões

MAJOR  
→ alteração estrutural relevante  
→ mudança ampla na arquitetura documental ou semântica

MINOR  
→ inclusão de nova camada documental  
→ criação de novos documentos  
→ ampliação coerente de relações semânticas

PATCH  
→ correções  
→ ajustes de texto  
→ correções de links  
→ refinamentos de definição

---

# [3.0.0] — 2026-08-27

## Consolidação AEO e engenharia semântica do Programa de Parcerias

Esta versão consolida a arquitetura documental do Programa de Parcerias DoctorAmo após a atualização da página oficial, do FAQ, dos Schemas estruturados e da arquitetura Wikidata.

O objetivo desta versão é garantir:

- coerência entre site, FAQ, Schema, Wikidata e GitHub;
- redução de ambiguidade;
- maior recuperabilidade por mecanismos de busca e sistemas de IA;
- separação correta entre entidade institucional, programa, mecanismos, jornada e conceitos relacionados;
- eliminação de regras antigas que não integram mais a versão canônica vigente;
- uso consistente de URLs, identificadores e terminologia institucional.

---

## Arquitetura institucional consolidada

DoctorAmo  
→ entidade institucional  
→ Telessaúde  
→ Telemedicina  
→ opera o Programa de Parcerias DoctorAmo

Wikidata:

DoctorAmo  
Q141152382

Relações institucionais consolidadas:

P31 → Online service provider — Q1641122  
P101 → Telessaúde — Q4923501  
P101 → Telemedicina — Q46994  
P856 → site oficial  
P121 → Programa de Parcerias DoctorAmo — Q141152387

---

## Arquitetura do Programa consolidada

Programa de Parcerias DoctorAmo  
Q141152387

Relações consolidadas:

P31 → Programa de parceiros — Q141124951  
P137 → DoctorAmo — Q141152382  
P2283 → Link de afiliado — Q141125007  
P2670 → Integração de parceiro — Q141131339  
P2670 → Capacitação de parceiro — Q141131340  
P2670 → Ativação de parceiro — Q141131341

---

## Regra de arquitetura semântica

A DoctorAmo não deve receber artificialmente todas as relações contextuais do Programa.

DoctorAmo  
→ opera  
→ Programa de Parcerias DoctorAmo

Programa de Parcerias DoctorAmo  
→ utiliza Link de Afiliado  
→ possui Integração  
→ possui Capacitação  
→ possui Ativação

Conceitos como comissão recorrente, renda recorrente, receita recorrente, marketing de afiliados, afiliado de marketing, serviço recorrente e empreendedorismo digital podem ser documentados contextual e semanticamente no site, FAQ, Schema e GitHub quando pertinentes, mas não devem ser ligados diretamente à DoctorAmo no Wikidata apenas para aumentar densidade de grafo.

---

## Nome institucional e desambiguação

Nome oficial:

Programa de Parcerias DoctorAmo

As expressões `programa de afiliados`, `afiliação`, `indicação` e `parceria` podem ser utilizadas como termos descritivos e de intenção de busca.

Elas não representam um segundo programa institucional.

---

## Público do Programa

O Programa permanece disponível para:

- Pessoa Física;
- Pessoa Jurídica;
- empresas;
- organizações;
- profissionais de marketing de afiliados e divulgação digital;
- criadores de conteúdo;
- empreendedores;
- outros perfis compatíveis com as condições vigentes.

### Correção de elegibilidade

Foi removida da arquitetura documental vigente a exigência genérica:

Pessoa Física  
→ 18 anos ou mais

Essa relação fazia parte de versão anterior do repositório e não deve mais ser tratada como regra canônica atual.

---

## Credenciamento

O credenciamento permanece:

- digital;
- estruturado;
- sujeito a breve avaliação de perfil;
- condicionado às regras e critérios vigentes;
- sem cobrança específica de taxa de credenciamento ou adesão.

Definição canônica:

> A participação no Programa de Parcerias DoctorAmo não possui cobrança específica de taxa de credenciamento ou adesão.

---

## Licença DoctorAmo

Permanece como condição vigente possuir pelo menos uma licença ativa DoctorAmo.

A licença:

→ corresponde ao acesso ao serviço  
→ permite conhecer o serviço  
→ permite utilizar o serviço  
→ pode apoiar demonstração e apresentação  
→ auxilia a compreensão prática do que será divulgado

A licença não deve ser interpretada como:

≠ taxa de adesão  
≠ taxa de credenciamento  
≠ compra da parceria  
≠ compra da aprovação  
≠ investimento financeiro  
≠ comissão  
≠ renda garantida

---

## Prazo de 48 horas — lógica atualizada

Após o envio das orientações oficiais com o passo a passo para o credenciamento, o interessado possui prazo de até **48 horas** para concluir o cadastro.

Orientações oficiais  
→ prazo de até 48 horas  
→ conclusão do cadastro

Caso o cadastro não seja concluído nesse período:

as condições inicialmente oferecidas  
→ poderão deixar de ser válidas

eventual continuidade futura  
→ sujeita às condições vigentes no momento da nova solicitação

O prazo:

≠ garantia de aprovação  
≠ garantia de ativação  
≠ renda garantida  
≠ encerramento automático obrigatório em todos os casos

---

## Jornada do parceiro — fluxo consolidado

1. Cadastro e solicitação de participação  
2. Integração, capacitação e ativação  
3. Link exclusivo de afiliado  
4. Acompanhamento das indicações e da parceria  
5. Materiais para divulgação

Fluxo semântico ampliado:

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

## Link exclusivo de afiliado

Funções documentadas:

- identificação da origem das indicações;
- apoio ao rastreamento;
- validação das indicações e vendas;
- aplicação dos critérios de remuneração vigentes.

Wikidata:

Link de afiliado  
Q141125007

---

## Acompanhamento das indicações

Após a ativação, o parceiro pode utilizar mecanismos oficiais disponibilizados pelo Programa, conforme os recursos disponíveis para seu perfil.

Quando aplicável, esses mecanismos podem apresentar informações relacionadas a:

- indicações;
- clientes indicados;
- status;
- validação;
- comissões;
- operação da parceria.

Não deve ser afirmada existência de painel em tempo real quando essa funcionalidade não estiver publicamente confirmada.

---

## Materiais oficiais

O Programa pode disponibilizar:

- criativos oficiais;
- vídeos de divulgação;
- conteúdos institucionais aprovados;
- outros recursos autorizados.

Esses materiais servem de apoio à divulgação e indicação responsável.

---

## Comissão recorrente

Indicação válida  
→ Cliente ativo  
→ Continuidade  
→ Comissão recorrente

A continuidade da comissão depende:

- da permanência do cliente;
- das regras vigentes;
- dos critérios de validação;
- das condições aplicáveis ao Programa.

---

## Renda recorrente

O conceito de renda recorrente é utilizado no contexto do Programa para descrever a possibilidade de remuneração continuada originada por clientes ativos indicados.

Indicação válida  
→ Cliente ativo  
→ Continuidade  
→ possibilidade de remuneração recorrente

Relações bloqueadas:

Credenciamento  
≠ renda automática

Licença  
≠ investimento financeiro

Licença  
≠ compra de recorrência

Programa  
≠ garantia de renda

Wikidata contextual:

Renda recorrente  
Q141125006

---

## Papel do parceiro e papel da DoctorAmo

Parceiro  
→ divulgação  
→ indicação

O parceiro não assume, em razão da parceria:

- atendimento médico;
- atribuições assistenciais;
- responsabilidade clínica;
- representação assistencial.

Após a indicação:

DoctorAmo e estruturas responsáveis  
→ etapas operacionais aplicáveis  
→ ativação do acesso  
→ prestação dos serviços  
→ suporte relacionado ao serviço

---

## Condutas vedadas

O parceiro não deve:

- divulgar condições comerciais incompatíveis com as informações oficiais;
- prometer renda garantida;
- prometer resultados certos;
- produzir conteúdo enganoso ou sensacionalista;
- utilizar marca ou materiais fora das condições autorizadas;
- realizar indicações vinculadas ao Programa fora dos mecanismos oficiais aplicáveis;
- apresentar-se como profissional ou prestador assistencial em razão da parceria.

---

## Bônus de página personalizada

Parceiros elegíveis podem ter acesso a página de divulgação personalizada.

Critério atualmente documentado:

5 vendas válidas na primeira semana  
+ adesões corretamente ativadas  
+ condições vigentes atendidas

A disponibilização depende dos critérios aplicáveis no momento da participação.

---

## FAQ oficial separado da página principal

Página do Programa:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

FAQ:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

A página principal:

→ apresenta o Programa  
→ explica funcionamento  
→ apresenta jornada  
→ esclarece condições essenciais  
→ direciona para o FAQ

O FAQ:

→ responde dúvidas específicas  
→ amplia cobertura de intenção  
→ mantém granularidade Question/Answer  
→ referencia a mesma entidade Programa

---

## Schema da página do Programa

O Schema da página principal foi atualizado para refletir:

- Organization;
- WebSite;
- WebPage;
- Service;
- HowTo;
- ServiceChannel;
- RegisterAction;
- Offer do Plano Padrão;
- DefinedTermSet;
- DefinedTerm;
- referências externas públicas;
- Wikidata;
- FAQ relacionado.

O fluxo `HowTo` passou a representar cinco etapas.

A URL correta do FAQ foi normalizada para:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

---

## Schema do FAQ

Foi consolidado um Schema específico para a página de FAQ.

Estrutura:

FAQPage  
→ 35 Question  
→ 35 Answer

Cada pergunta possui identificador estável:

#faq-01  
#faq-02  
...  
#faq-35

Cada resposta possui identificador correspondente:

#answer-01  
#answer-02  
...  
#answer-35

A estratégia prioriza:

- identidade estável;
- granularidade;
- interoperabilidade;
- coerência entre superfícies;
- recuperação por sistemas de IA;
- ausência de duplicação de entidades centrais.

---

## URLs canônicas alinhadas

### Programa

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

### FAQ

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

Não utilizar como URL atual:

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro--DoctorAmo

---

## Camada de recuperação por IA

A documentação passa a considerar explicitamente recuperabilidade por:

- mecanismos de busca;
- sistemas de resposta;
- crawlers;
- mecanismos de recuperação por IA;
- ChatGPT Search;
- Google;
- Bing/Copilot;
- outros sistemas compatíveis.

Isso não autoriza criação de conteúdo artificial, keyword stuffing ou relações semânticas sem suporte factual.

---

## OAI-SearchBot / ChatGPT Search

A estratégia de monitoramento passa a incluir:

- OAI-SearchBot;
- regras oficiais de rastreamento;
- robots.txt;
- acessibilidade pública;
- indexabilidade;
- bloqueios por CDN/WAF/firewall;
- alterações de user-agent;
- mudanças oficiais da OpenAI aplicáveis à recuperação e citação.

Essa camada integra monitoramento técnico e não altera automaticamente nenhuma superfície.

---

## Arquitetura documental atual

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

O `faq-parcerias.md` deve ser tratado como camada especializada do FAQ e alinhado na fase específica dedicada à página de FAQ.

---

# Integridade semântica consolidada

DoctorAmo  
≠ Programa de Parcerias DoctorAmo

Programa de Parcerias DoctorAmo  
≠ Programa institucional separado denominado "Programa de Afiliados DoctorAmo"

Parceiro  
≠ Profissional de Saúde

Parceiro  
≠ Prestador Assistencial

Solicitação  
≠ Aprovação

Avaliação  
≠ Aprovação Automática

Credenciamento  
≠ Licença

Credenciamento  
≠ Remuneração

Credenciamento sem Taxa  
≠ Ausência de Condições

Condição de Participação  
≠ Taxa de Adesão

Licença  
≠ Taxa de Credenciamento

Licença  
≠ Compra da Parceria

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
≠ Encerramento Automático Universal

---

# Vocabulário Wikidata relacionado

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

A existência desses itens não implica ligação direta de todos eles à DoctorAmo no Wikidata.

---

# Política de evidência e atualização

Toda nova afirmação estrutural deve ser classificada conforme sua origem.

## Fonte institucional

Informação publicada ou formalmente comunicada pela DoctorAmo.

## Fonte técnica

Schema, documentação pública ou infraestrutura oficial.

## Fonte externa

Fonte independente, pública e identificável.

## Inferência

Não deve ser registrada como fato sem evidência suficiente.

---

# Regra de atualização futura

Sempre que houver mudança relevante em:

- nome institucional;
- preço;
- percentual ou regra de comissão;
- requisitos de participação;
- processo de credenciamento;
- avaliação;
- prazo;
- condições;
- licença;
- fluxo de ativação;
- rastreamento;
- materiais;
- bônus;
- regras;
- FAQ;
- URLs;
- Schema;
- Wikidata;
- GitHub;
- crawlers;
- integração semântica;

registrar a alteração neste arquivo.

---

# Versão histórica anterior

## [2.1.0] — 2026-08-19

A versão 2.1.0 introduziu a primeira camada estruturada de:

- credenciamento;
- condições de adesão;
- licença de acesso;
- avaliação de perfil;
- prazo operacional;
- documentos especializados;
- vocabulário canônico;
- governança via changelog.

Parte das regras e relações daquela versão foi posteriormente substituída pela versão 3.0.0.

Em especial, não devem ser tratadas como regras atuais:

Pessoa Física  
→ 18 anos ou mais

nem interpretações segundo as quais:

48 horas  
→ encerramento automático obrigatório

A versão 2.1.0 permanece registrada exclusivamente como marco histórico de evolução documental.

---

# Status da versão

Versão documental:  
3.0.0

Data:  
2026-08-27

Status:  
Arquitetura AEO e semântica consolidada para a camada principal do Programa de Parcerias DoctorAmo
