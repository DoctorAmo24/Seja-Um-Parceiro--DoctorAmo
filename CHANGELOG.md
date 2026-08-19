# Changelog — Programa de Parcerias DoctorAmo

Este documento registra alterações relevantes na documentação pública e na arquitetura semântica do **Programa de Parcerias DoctorAmo**.

Seu objetivo é manter histórico, rastreabilidade e governança das mudanças realizadas no repositório.

O changelog não substitui:

- a página oficial do Programa de Parcerias;
- as regras vigentes;
- a documentação institucional;
- o schema estruturado;
- as referências normativas;
- as condições comerciais e operacionais oficialmente publicadas pela DoctorAmo.

Quando houver divergência entre versões históricas deste repositório e informações oficiais atuais, deve prevalecer a condição vigente publicada ou formalmente comunicada pela DoctorAmo.

---

# Convenção de versões

As versões deste repositório podem seguir a seguinte lógica:

```text
MAJOR
→ alteração estrutural relevante
→ mudança ampla na arquitetura documental ou semântica

MINOR
→ inclusão de nova camada documental
→ criação de novos documentos
→ ampliação de relações semânticas

PATCH
→ correções
→ ajustes de texto
→ correções de links
→ refinamentos de definição
```

Exemplo:

```text
2.1.0
│ │ │
│ │ └── correção
│ └──── nova camada
└────── alteração estrutural
```

---

# [2.1.0] — 2026-08-19

## Nova camada de credenciamento e condições de adesão

Foi incorporada ao repositório uma nova camada semântica e documental referente ao processo de entrada no **Programa de Parcerias DoctorAmo**.

### Adicionado

- credenciamento de parceiro;
- solicitação de participação;
- processo 100% digital;
- credenciamento simples e rápido;
- ausência de taxa de inscrição;
- ausência de taxa de adesão;
- ausência de taxa de credenciamento;
- breve avaliação de perfil;
- prazo operacional de credenciamento;
- condições de adesão;
- licença de acesso ao serviço;
- conhecimento do serviço;
- utilização do serviço;
- demonstração do serviço;
- parceiro credenciado;
- manutenção de cadastro;
- atividade de indicação.

---

## Elegibilidade de Pessoa Física

Foi documentada a idade mínima de:

**18 anos**

para solicitação de participação como Pessoa Física, conforme as condições vigentes do Programa de Parcerias.

Relação:

```text
Pessoa Física
→ 18 anos ou mais
→ pode solicitar participação
```

---

## Participação de Pessoa Jurídica

Foi reforçada a possibilidade de solicitação de participação por:

- Pessoa Jurídica;
- empresa;
- organização;

conforme as condições aplicáveis ao Programa de Parcerias.

---

## Credenciamento sem taxa

Foi estabelecida a definição documental:

> **O processo de credenciamento no Programa de Parcerias DoctorAmo não possui taxa específica de inscrição, adesão ou credenciamento.**

Foi também adicionada a seguinte desambiguação:

```text
Credenciamento sem taxa
≠ ausência de condições de adesão
```

---

## Avaliação de perfil

Foi adicionada a definição de **breve avaliação de perfil** como etapa do processo de credenciamento.

Relação:

```text
Solicitação
→ Avaliação de Perfil
→ Verificação das Condições
→ Possível Aprovação
```

Foi explicitado:

```text
Solicitação
≠ Aprovação Automática

Avaliação
≠ Garantia de Aprovação
```

---

## Prazo operacional

Foi documentado o prazo operacional atualmente estabelecido para conclusão das etapas aplicáveis:

**até 48 horas**

após o primeiro contato e a liberação do processo, salvo condição diferente expressamente comunicada pela DoctorAmo.

Relação:

```text
Primeiro Contato / Liberação
→ Prazo Operacional
→ Até 48 Horas
→ Conclusão das Etapas
```

---

## Licença de acesso

Foi adicionada uma nova camada documental para diferenciar a **Licença de Acesso DoctorAmo** do processo de credenciamento.

Definição adotada:

> **Licença de Acesso DoctorAmo corresponde ao acesso efetivo ao serviço DoctorAmo e pode integrar as condições de adesão do parceiro conforme as condições vigentes.**

Foi estabelecido:

```text
Licença
→ Acesso ao Serviço
```

E explicitamente bloqueado:

```text
Licença
≠ Taxa de Credenciamento

Licença
≠ Taxa de Inscrição

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
```

---

## Boa prática de conhecimento do serviço

Foi documentada a função da licença como recurso de:

- conhecimento do serviço;
- utilização;
- experiência prática;
- apoio à demonstração;
- apoio à divulgação responsável.

Relação:

```text
Licença de Acesso
→ Conhecimento
→ Utilização
→ Demonstração
→ Apoio à Divulgação
→ Indicação Responsável
```

---

## Separação entre credenciamento e remuneração

Foi reforçada a distinção entre o processo de entrada e a geração de comissão.

Relação correta:

```text
Credenciamento
→ Parceiro Credenciado
→ Indicação Responsável
→ Cliente Ativo
→ Continuidade
→ Comissão Recorrente
```

Relação incorreta:

```text
Credenciamento
→ Renda Automática
```

Também:

```text
Licença
≠ Evento Gerador de Comissão
```

---

## Novos documentos criados

Foram criados os seguintes documentos especializados:

```text
credenciamento-parceiro.md
licenca-de-acesso.md
glossario.md
CHANGELOG.md
```

### Função de cada documento

```text
credenciamento-parceiro.md
→ processo de entrada
→ avaliação
→ condições de adesão
→ prazo
→ aprovação

licenca-de-acesso.md
→ natureza da licença
→ acesso ao serviço
→ conhecimento
→ utilização
→ demonstração
→ desambiguação

glossario.md
→ vocabulário canônico
→ definições
→ relações semânticas
→ desambiguação

CHANGELOG.md
→ histórico
→ rastreabilidade
→ governança documental
```

---

## Documentos atualizados nesta versão

A nova camada foi incorporada ou refletida nos seguintes documentos:

```text
README.md
REFERENCIAS.md
como-funciona.md
faq-parcerias.md
index.html
llms.txt
parceiro-pessoa-fisica.md
parceiro-pessoa-juridica.md
programa-de-parcerias.md
regras-do-programa.md
renda-recorrente.md
schema.json
sitemap.xml
```

O arquivo `robots.txt` não exigiu alteração.

---

## Atualização do README

O `README.md` passou a incorporar:

- credenciamento;
- condições de adesão;
- licença de acesso;
- avaliação de perfil;
- nova camada no grafo semântico;
- novo vocabulário controlado.

---

## Atualização das referências

O `REFERENCIAS.md` passou a documentar a proveniência institucional das informações relacionadas a:

- credenciamento;
- ausência de taxa;
- avaliação de perfil;
- prazo operacional;
- licença;
- condições de adesão.

---

## Atualização do funcionamento

O arquivo `como-funciona.md` passou a representar o fluxo ampliado:

```text
Solicitação
→ Credenciamento
→ Avaliação
→ Condições de Adesão
→ Licença
→ Parceiro Credenciado
→ Indicação
→ Validação
→ Cliente Ativo
→ Continuidade
→ Comissão Recorrente
```

---

## Atualização do FAQ

O `faq-parcerias.md` passou a responder diretamente dúvidas sobre:

- custo do credenciamento;
- processo 100% digital;
- avaliação de perfil;
- idade mínima;
- prazo;
- licença;
- diferença entre licença e taxa;
- condições de adesão.

---

## Atualização da Pessoa Física

O documento `parceiro-pessoa-fisica.md` passou a incluir:

- idade mínima de 18 anos;
- credenciamento;
- avaliação;
- prazo;
- condições de adesão;
- licença de acesso;
- manutenção do cadastro.

---

## Atualização da Pessoa Jurídica

O documento `parceiro-pessoa-juridica.md` passou a incluir:

- credenciamento empresarial;
- breve avaliação de perfil;
- condições de adesão;
- licença de acesso;
- manutenção da participação.

---

## Atualização das regras

O arquivo `regras-do-programa.md` passou a separar explicitamente:

```text
Regra de Credenciamento
≠ Condição de Adesão
≠ Boa Prática
≠ Proibição
```

Também passou a documentar:

- ausência de taxa de credenciamento;
- avaliação de perfil;
- licença como acesso ao serviço;
- manutenção de cadastro;
- atividade de indicação.

---

## Atualização de renda recorrente

O documento `renda-recorrente.md` passou a desambiguar:

```text
Licença
≠ Investimento Financeiro

Licença
≠ Compra de Recorrência

Credenciamento
≠ Renda Automática
```

A intenção principal do documento continuou sendo:

```text
Indicação
→ Cliente Ativo
→ Continuidade
→ Recorrência
```

---

## Atualização do llms.txt

O `llms.txt` passou a representar explicitamente:

- credenciamento;
- avaliação;
- condições de adesão;
- licença de acesso;
- conhecimento do serviço;
- novo fluxo operacional;
- novas desambiguações.

---

## Atualização do index.html

O `index.html` passou a apresentar de forma pública e resumida:

- credenciamento simples;
- processo 100% digital;
- ausência de taxa de credenciamento;
- avaliação de perfil;
- condições de adesão;
- licença como acesso ao serviço.

---

## Atualização do schema.json

O `schema.json` passou a modelar:

- credenciamento de parceiro;
- credenciamento sem taxa;
- avaliação de perfil;
- condições de adesão;
- licença de acesso;
- conhecimento do serviço;
- audiência de Pessoa Física;
- audiência de Pessoa Jurídica;
- fluxo ampliado do programa.

Também foi reforçada a separação entre:

```text
Programa de Parcerias
```

e:

```text
Plano DoctorAmo
```

para evitar interpretação incorreta de que o programa possui uma taxa de adesão vinculada ao preço do plano.

---

## Atualização do sitemap.xml

O `sitemap.xml` permaneceu restrito às páginas públicas relevantes do projeto.

Não foram criadas entradas artificiais para conceitos que não possuíam páginas próprias.

---

# Integridade semântica consolidada

A partir desta versão, as seguintes distinções passam a integrar formalmente a arquitetura documental do projeto:

```text
Solicitação
≠ Aprovação

Credenciamento
≠ Licença

Credenciamento
≠ Remuneração

Credenciamento sem Taxa
≠ Ausência de Requisitos

Avaliação de Perfil
≠ Aprovação Automática

Condição de Adesão
≠ Taxa de Adesão

Licença
≠ Taxa de Credenciamento

Licença
≠ Investimento Financeiro

Licença
≠ Comissão

Licença
≠ Renda Garantida

Parceiro
≠ Profissional de Saúde

Indicação
≠ Venda Garantida

Cliente Ativo
≠ Permanência Garantida

Comissão
≠ Salário

Recorrência
≠ Renda Garantida
```

---

# Arquitetura documental após a versão 2.1.0

```text
README.md
│
├── programa-de-parcerias.md
├── credenciamento-parceiro.md
├── licenca-de-acesso.md
├── parceiro-pessoa-fisica.md
├── parceiro-pessoa-juridica.md
├── como-funciona.md
├── regras-do-programa.md
├── renda-recorrente.md
├── faq-parcerias.md
├── glossario.md
├── REFERENCIAS.md
└── CHANGELOG.md

Camada técnica:
│
├── index.html
├── schema.json
├── llms.txt
├── sitemap.xml
└── robots.txt
```

---

# Próxima etapa prevista

Após a criação dos novos documentos especializados, a etapa seguinte consiste em uma **rodada final de integração**.

Essa integração deverá revisar:

```text
README.md
programa-de-parcerias.md
parceiro-pessoa-fisica.md
parceiro-pessoa-juridica.md
como-funciona.md
regras-do-programa.md
renda-recorrente.md
faq-parcerias.md
llms.txt
index.html
schema.json
sitemap.xml
```

O objetivo da rodada final será:

- interligar os novos documentos;
- evitar documentos órfãos;
- atualizar mapas documentais;
- atualizar referências internas;
- atualizar descoberta por sistemas de IA;
- atualizar o grafo estruturado;
- atualizar o sitemap com URLs públicas pertinentes.

---

# Integração futura com Wikidata

Uma etapa futura poderá incorporar alinhamentos externos quando existirem itens Wikidata adequados e semanticamente correspondentes.

Possíveis relações futuras incluem:

```text
Entidade Local
↔ Wikidata QID
```

A integração deverá ser feita apenas quando houver identidade ou correspondência conceitual real.

Não utilizar:

```text
sameAs
```

para entidades apenas relacionadas.

---

# Regra de atualização futura

Sempre que houver mudança relevante em:

- preço;
- percentual de comissão;
- requisitos de participação;
- processo de credenciamento;
- avaliação;
- prazo;
- condições de adesão;
- licença;
- regras;
- estrutura documental;
- schema;
- integração semântica;

registrar a alteração neste arquivo.

---

# Modelo para futuras versões

```markdown
# [X.Y.Z] — AAAA-MM-DD

## Adicionado

- novo recurso
- novo documento
- nova entidade

## Alterado

- documento atualizado
- definição alterada
- fluxo alterado

## Corrigido

- erro corrigido
- link corrigido
- definição corrigida

## Removido

- conteúdo removido
- relação removida

## Impacto semântico

```text
Relação anterior
→ Relação nova
```
```

---

# Fonte oficial

Programa de Parcerias DoctorAmo:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

---

# DoctorAmo

Página principal:

https://www.doctoramo.com.br/in%C3%ADcio

Documentação institucional:

https://doctoramo24.github.io/doctoramo-proposito-missao-visao-valores/

---

# Status da versão

```text
Versão documental:
2.1.0

Data:
2026-08-19

Status:
Nova camada de credenciamento e adesão documentada
```
