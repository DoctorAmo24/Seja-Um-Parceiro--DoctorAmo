# Claims e Evidências — Programa de Parcerias DoctorAmo

> **Registro canônico, atômico e auditável das afirmações factuais, condicionais, históricas e conceituais utilizadas na arquitetura documental do Programa de Parcerias DoctorAmo.**

Este documento é a camada de governança factual do repositório:

https://github.com/DoctorAmo24/Seja-Um-Parceiro--DoctorAmo

Sua função é estabelecer, para cada afirmação relevante:

```text
CLAIM
→ o que pode ser afirmado

STATUS
→ natureza atual da afirmação

FONTE
→ onde está sustentada

ESCOPO
→ onde a afirmação se aplica

RISCO DE DESATUALIZAÇÃO
→ probabilidade de mudança ou perda de validade
```

A estrutura é deliberadamente padronizada para facilitar:

- auditoria humana;
- auditoria automática;
- análise por agentes;
- comparação entre versões;
- detecção de contradições;
- controle de temporalidade;
- atualização coordenada;
- proveniência;
- recuperação por sistemas de IA;
- consistência entre Site, FAQ, GitHub, Schema, Glossário e Wikidata.

---

# 1. Regra obrigatória de claim

Todo claim deste documento deve possuir, sem exceção:

```text
CLAIM
STATUS
FONTE
ESCOPO
RISCO DE DESATUALIZAÇÃO
```

Campos auxiliares podem ser acrescentados quando úteis:

```text
CLASSE
QID
QUALIFICADORES
NÃO INFERIR
DOCUMENTOS DEPENDENTES
OBSERVAÇÃO
```

Os campos auxiliares **não substituem** os cinco campos obrigatórios.

---

# 2. Princípio de atomicidade

Cada claim deve representar **uma afirmação principal verificável**.

Preferir:

```text
PF pode solicitar participação.
```

e separadamente:

```text
PF deve possuir 18 anos ou mais.
```

em vez de combinar vários fatos independentes em uma única afirmação longa.

Regra:

```text
1 claim
→ 1 proposição principal
```

Isso facilita:

- validação;
- atualização;
- detecção de conflito;
- reutilização;
- rastreabilidade.

---

# 3. Status permitidos

## VIGENTE

A afirmação está sustentada pela fonte atual.

```text
STATUS: VIGENTE
```

## CONDICIONAL

A afirmação depende de critérios, circunstâncias ou condições vigentes.

```text
STATUS: CONDICIONAL
```

## CONCEITUAL

A afirmação descreve relação semântica, definição ou desambiguação.

```text
STATUS: CONCEITUAL
```

## HISTÓRICO — NÃO CANÔNICO ATUAL

A afirmação apareceu em documentação anterior, mas não deve ser utilizada como fato atual sem nova confirmação oficial.

```text
STATUS: HISTÓRICO — NÃO CANÔNICO ATUAL
```

## BLOQUEADO

Afirmação que não possui suporte suficiente e não deve ser propagada como fato.

```text
STATUS: BLOQUEADO
```

---

# 4. Risco de desatualização

## BAIXO

Identidade ou relação estrutural pouco sujeita a alteração.

## MÉDIO

Regra ou condição operacional que pode ser modificada.

## ALTO

Informação comercial, temporal, quantitativa ou promocional.

---

# 5. Hierarquia de evidência

## E1 — Fonte institucional primária

Página oficial do Programa:

https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo

Força:

```text
MÁXIMA
```

para fatos institucionais, comerciais e operacionais atuais.

---

## E2 — FAQ institucional

https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo

Força:

```text
ALTA
```

para perguntas, respostas, limites, requisitos e explicações operacionais.

---

## E3 — Página institucional DoctorAmo

https://www.doctoramo.com.br/in%C3%ADcio

Uso principal:

- identidade DoctorAmo;
- contexto institucional;
- Telessaúde;
- Telemedicina.

---

## E4 — Wikidata consolidado

DoctorAmo:

https://www.wikidata.org/entity/Q141152382

Programa:

https://www.wikidata.org/entity/Q141152387

Uso:

- identidade;
- QIDs;
- classes;
- relações essenciais.

---

## E5 — Schema atual

[schema.json](schema.json)

Uso:

```text
representação estruturada
→ daquilo que está documentado
```

Schema não é fonte primária de fatos comerciais.

---

## E6 — GitHub documental

Documentos especialistas e de governança deste repositório.

Uso:

- aprofundamento;
- desambiguação;
- especialização;
- contexto;
- relações documentais.

---

## E7 — Histórico

Commits e versões antigas.

Uso:

- auditoria;
- comparação temporal;
- histórico.

Não usar automaticamente para respostas atuais.

---

# 6. Regra de prevalência

Quando houver divergência:

```text
FONTE INSTITUCIONAL VIGENTE
>
FAQ VIGENTE
>
DOCUMENTAÇÃO GITHUB ATUALIZADA
>
VERSÃO HISTÓRICA
```

Para identidade Wikidata:

```text
WIKIDATA CONSOLIDADO ATUAL
>
CÓPIA DOCUMENTAL ANTIGA
```

---

# 7. CLAIMS DE IDENTIDADE

## Claim I-001 — DoctorAmo

- **CLAIM:** DoctorAmo é a entidade institucional central desta arquitetura documental.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/in%C3%ADcio ; https://www.wikidata.org/entity/Q141152382
- **ESCOPO:** Identidade institucional — DoctorAmo.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Identidade
- **QID:** `Q141152382`
- **NÃO INFERIR:** DoctorAmo = Programa de Parcerias DoctorAmo.

---

## Claim I-002 — DoctorAmo e Telessaúde

- **CLAIM:** Telessaúde integra o contexto de atuação documentado da DoctorAmo.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/in%C3%ADcio ; https://www.wikidata.org/entity/Q141152382
- **ESCOPO:** DoctorAmo / Telessaúde.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Identidade
- **QID RELACIONADO:** Telessaúde `Q4923501`
- **RELAÇÃO WIKIDATA CONSOLIDADA:** `DoctorAmo P101 → Q4923501`

---

## Claim I-003 — DoctorAmo e Telemedicina

- **CLAIM:** Telemedicina integra o contexto de atuação documentado da DoctorAmo.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/in%C3%ADcio ; https://www.wikidata.org/entity/Q141152382
- **ESCOPO:** DoctorAmo / Telemedicina.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Identidade
- **QID RELACIONADO:** Telemedicina `Q46994`
- **RELAÇÃO WIKIDATA CONSOLIDADA:** `DoctorAmo P101 → Q46994`

---

## Claim I-004 — Existência do Programa

- **CLAIM:** Existe uma estrutura institucional denominada Programa de Parcerias DoctorAmo.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.wikidata.org/entity/Q141152387
- **ESCOPO:** Programa de Parcerias DoctorAmo.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Identidade
- **QID:** `Q141152387`

---

## Claim I-005 — Operadora do Programa

- **CLAIM:** O Programa de Parcerias DoctorAmo é operado pela DoctorAmo.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.wikidata.org/entity/Q141152387
- **ESCOPO:** Relação DoctorAmo → Programa.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Identidade
- **RELAÇÃO WIKIDATA CONSOLIDADA:** `Programa P137 → DoctorAmo Q141152382`

---

## Claim I-006 — Nome institucional

- **CLAIM:** A denominação institucional principal é “Programa de Parcerias DoctorAmo”.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo
- **ESCOPO:** Denominação do Programa.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Identidade
- **NÃO INFERIR:** “Programa de afiliados DoctorAmo” constitui outro programa institucional.

---

## Claim I-007 — Classe Wikidata do Programa

- **CLAIM:** O Programa de Parcerias DoctorAmo está classificado no Wikidata como Programa de parceiros.
- **STATUS:** VIGENTE
- **FONTE:** https://www.wikidata.org/entity/Q141152387
- **ESCOPO:** Knowledge Graph / Wikidata.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Identidade
- **RELAÇÃO:** `P31 → Q141124951`

---

## Claim I-008 — Área institucional documentada

- **CLAIM:** O Programa é documentado no contexto de atuação da DoctorAmo no Brasil.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [schema.json](schema.json)
- **ESCOPO:** Área geográfica do Programa.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Identidade / Operacional
- **NÃO INFERIR:** atuação automática em outros países.

---

# 8. CLAIMS DE PARTICIPAÇÃO

## Claim P-001 — Pessoa Física

- **CLAIM:** Pessoas Físicas podem solicitar participação no Programa.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Participação — Pessoa Física.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional
- **DOCUMENTO DEPENDENTE:** [parceiro-pessoa-fisica.md](parceiro-pessoa-fisica.md)

---

## Claim P-002 — Idade mínima PF

- **CLAIM:** Para Pessoa Física, a idade mínima atualmente documentada é de 18 anos.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Elegibilidade — Pessoa Física.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional
- **QUALIFICADOR:** atualmente.

---

## Claim P-003 — Pessoa Jurídica

- **CLAIM:** Pessoas Jurídicas podem solicitar participação no Programa conforme as condições aplicáveis.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Participação — Pessoa Jurídica.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional
- **DOCUMENTO DEPENDENTE:** [parceiro-pessoa-juridica.md](parceiro-pessoa-juridica.md)

---

## Claim P-004 — Responsável de Pessoa Jurídica

- **CLAIM:** A participação de Pessoa Jurídica é conduzida por responsável aplicável conforme as condições de cadastro empresarial.
- **STATUS:** CONDICIONAL
- **FONTE:** https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Pessoa Jurídica / responsável aplicável.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional

---

# 9. CLAIMS DE CREDENCIAMENTO

## Claim CR-001 — Solicitação não é aprovação

- **CLAIM:** Solicitar participação ou realizar cadastro não significa aprovação automática.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Credenciamento.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança
- **RELAÇÃO:** `Solicitação → Avaliação → Possível aprovação`

---

## Claim CR-002 — Avaliação de perfil

- **CLAIM:** A solicitação de participação está sujeita à avaliação de perfil.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Credenciamento / avaliação.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional

---

## Claim CR-003 — Ausência de taxa específica

- **CLAIM:** Não existe cobrança específica de taxa de inscrição, adesão ou credenciamento para o processo de participação.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Credenciamento / custos de entrada.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional / Comercial
- **NÃO INFERIR:** ausência de requisitos de participação.

---

## Claim CR-004 — Processo digital

- **CLAIM:** O processo de credenciamento é conduzido digitalmente pelos mecanismos oficiais aplicáveis.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Credenciamento.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional

---

## Claim CR-005 — Prazo atual de até 48 horas

- **CLAIM:** Após a liberação e as orientações oficiais aplicáveis, o interessado possui atualmente até 48 horas para concluir o cadastro/credenciamento previsto.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Prazo operacional de credenciamento.
- **RISCO DE DESATUALIZAÇÃO:** ALTO
- **CLASSE:** Operacional
- **QUALIFICADOR:** atualmente.
- **NÃO INFERIR:** 48 horas = aprovação ou ativação.

---

## Claim CR-006 — Prazo não garante aprovação

- **CLAIM:** O prazo de até 48 horas não representa garantia de aprovação.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo
- **ESCOPO:** Credenciamento / prazo.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Governança

---

## Claim CR-007 — Prazo não é prazo de renda

- **CLAIM:** O prazo operacional de credenciamento não corresponde a prazo para geração de renda ou comissão.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo
- **ESCOPO:** Credenciamento / remuneração.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

# 10. CLAIMS DE LICENÇA

## Claim L-001 — Licença ativa como condição atual

- **CLAIM:** Possuir pelo menos uma licença/acesso DoctorAmo ativa integra atualmente as condições documentadas de participação.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Condições de participação / licença.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional
- **QUALIFICADOR:** atualmente.
- **DOCUMENTO DEPENDENTE:** [licenca-de-acesso.md](licenca-de-acesso.md)

---

## Claim L-002 — Natureza da licença

- **CLAIM:** A licença DoctorAmo corresponde ao acesso ao serviço DoctorAmo.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Licença / acesso ao serviço.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional

---

## Claim L-003 — Licença não é taxa

- **CLAIM:** A licença não constitui taxa específica de inscrição, adesão ou credenciamento.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Licença / credenciamento.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Governança
- **NÃO INFERIR:** licença = pagamento para comprar a parceria.

---

## Claim L-004 — Licença não é investimento

- **CLAIM:** A licença DoctorAmo não deve ser caracterizada como investimento financeiro.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [licenca-de-acesso.md](licenca-de-acesso.md)
- **ESCOPO:** Licença / natureza econômica.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança
- **NÃO INFERIR:** aplicação financeira, aporte ou produto de investimento.

---

## Claim L-005 — Licença não compra aprovação

- **CLAIM:** Possuir ou contratar a licença não significa comprar aprovação no Programa.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [licenca-de-acesso.md](licenca-de-acesso.md)
- **ESCOPO:** Licença / aprovação.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim L-006 — Licença não compra comissão

- **CLAIM:** Possuir ou contratar licença não gera comissão automaticamente.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [licenca-de-acesso.md](licenca-de-acesso.md)
- **ESCOPO:** Licença / remuneração.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

# 11. CLAIMS DA JORNADA

## Claim J-001 — Integração

- **CLAIM:** Integração de parceiro integra a jornada oficial do Programa.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.wikidata.org/entity/Q141152387
- **ESCOPO:** Jornada do parceiro.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional
- **QID:** `Q141131339`

---

## Claim J-002 — Capacitação

- **CLAIM:** Capacitação de parceiro integra a jornada oficial do Programa.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.wikidata.org/entity/Q141152387
- **ESCOPO:** Jornada do parceiro.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional
- **QID:** `Q141131340`

---

## Claim J-003 — Ativação

- **CLAIM:** Ativação de parceiro integra a jornada oficial do Programa.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.wikidata.org/entity/Q141152387
- **ESCOPO:** Jornada do parceiro.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional
- **QID:** `Q141131341`

---

## Claim J-004 — Distinção entre etapas

- **CLAIM:** Integração, capacitação e ativação representam etapas distintas.
- **STATUS:** CONCEITUAL
- **FONTE:** [glossario.md](glossario.md) ; [como-funciona.md](como-funciona.md) ; https://www.wikidata.org/entity/Q141152387
- **ESCOPO:** Jornada / desambiguação.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

# 12. CLAIMS DO LINK E DA INDICAÇÃO

## Claim A-001 — Existência do link de afiliado

- **CLAIM:** O Programa utiliza link de afiliado como mecanismo oficial relacionado à divulgação e indicação.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.wikidata.org/entity/Q141152387
- **ESCOPO:** Mecanismo de atribuição.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional
- **QID:** `Q141125007`

---

## Claim A-002 — Disponibilização após ativação

- **CLAIM:** Após a ativação, o parceiro tem acesso ao link exclusivo de afiliado pelo mecanismo oficial aplicável.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Ativação / link de afiliado.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional

---

## Claim A-003 — Função do link

- **CLAIM:** O link de afiliado apoia a identificação da origem, rastreabilidade, atribuição e validação das indicações conforme os critérios aplicáveis.
- **STATUS:** CONDICIONAL
- **FONTE:** https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo ; [link-de-afiliado.md](link-de-afiliado.md)
- **ESCOPO:** Link / atribuição / validação.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional / Conceitual

---

## Claim A-004 — Link não gera comissão automaticamente

- **CLAIM:** A existência ou utilização de um link de afiliado não gera comissão automaticamente.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [link-de-afiliado.md](link-de-afiliado.md)
- **ESCOPO:** Link / remuneração.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim A-005 — Atividade do parceiro

- **CLAIM:** O parceiro atua em atividades de divulgação e indicação segundo os mecanismos e regras aplicáveis.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Atuação do parceiro.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Operacional

---

## Claim A-006 — Indicação não é venda

- **CLAIM:** Uma indicação não representa automaticamente uma venda ou contratação.
- **STATUS:** CONCEITUAL
- **FONTE:** [indicacao-de-clientes.md](indicacao-de-clientes.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Indicação / conversão.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico / Governança

---

## Claim A-007 — Identificação não é validação

- **CLAIM:** Identificar a origem de uma indicação não equivale automaticamente à sua validação.
- **STATUS:** CONCEITUAL
- **FONTE:** [link-de-afiliado.md](link-de-afiliado.md) ; [indicacao-de-clientes.md](indicacao-de-clientes.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Atribuição / validação.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

# 13. CLAIMS DE CLIENTE

## Claim CL-001 — Cliente indicado

- **CLAIM:** Cliente indicado é o cliente cuja origem pode ser associada ao parceiro conforme os mecanismos e critérios aplicáveis.
- **STATUS:** CONCEITUAL
- **FONTE:** [indicacao-de-clientes.md](indicacao-de-clientes.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Cliente indicado.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

## Claim CL-002 — Cliente indicado não é automaticamente ativo

- **CLAIM:** Um cliente indicado não se torna automaticamente cliente ativo apenas por ter sido indicado.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [glossario.md](glossario.md)
- **ESCOPO:** Cliente indicado / cliente ativo.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim CL-003 — Cliente ativo

- **CLAIM:** Cliente ativo é o cliente indicado que permanece em condição válida conforme os critérios aplicáveis.
- **STATUS:** CONDICIONAL
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [comissao-recorrente.md](comissao-recorrente.md)
- **ESCOPO:** Cliente ativo / recorrência.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Operacional

---

## Claim CL-004 — Cliente ativo não garante permanência

- **CLAIM:** A condição atual de cliente ativo não garante permanência futura.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [glossario.md](glossario.md)
- **ESCOPO:** Cliente ativo / continuidade.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

# 14. CLAIMS DE REMUNERAÇÃO

## Claim R-001 — Existência de comissão recorrente

- **CLAIM:** O Programa possui modelo de remuneração recorrente vinculado aos clientes ativos indicados.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Remuneração do Programa.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Comercial
- **QID CONCEITUAL:** Comissão recorrente `Q141124952`

---

## Claim R-002 — Continuidade da comissão

- **CLAIM:** Enquanto o cliente indicado permanecer ativo e atender aos critérios aplicáveis, pode haver remuneração recorrente ao parceiro.
- **STATUS:** CONDICIONAL
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Comissão recorrente / cliente ativo.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Comercial
- **QUALIFICADORES:** enquanto; pode; critérios aplicáveis.

---

## Claim R-003 — Mesmo cliente

- **CLAIM:** A comissão referente ao mesmo cliente pode continuar em períodos sucessivos enquanto esse cliente permanecer ativo e forem atendidas as condições aplicáveis, sem necessidade de nova indicação daquele mesmo cliente em cada período.
- **STATUS:** CONDICIONAL
- **FONTE:** https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo ; [comissao-recorrente.md](comissao-recorrente.md)
- **ESCOPO:** Comissão recorrente / continuidade.
- **RISCO DE DESATUALIZAÇÃO:** MÉDIO
- **CLASSE:** Comercial

---

## Claim R-004 — Percentual

- **CLAIM:** Os percentuais, critérios de cálculo e demais condições de remuneração seguem as condições comerciais vigentes e são apresentados no processo oficial aplicável.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo
- **ESCOPO:** Percentual e cálculo da comissão.
- **RISCO DE DESATUALIZAÇÃO:** ALTO
- **CLASSE:** Comercial
- **REGRA:** não fixar percentual histórico como atual.

---

## Claim R-005 — Comissão não é salário

- **CLAIM:** A comissão do parceiro não deve ser caracterizada como salário.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [regras-do-programa.md](regras-do-programa.md)
- **ESCOPO:** Natureza da remuneração.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim R-006 — Comissão recorrente não garante renda

- **CLAIM:** A existência de comissão recorrente não constitui promessa ou garantia de renda.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; https://www.doctoramo.com.br/FAQ--Seja-Um-Parceiro-DoctorAmo
- **ESCOPO:** Remuneração / risco.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

# 15. CLAIM DE PREÇO

## Claim PR-001 — Valor atual de referência

- **CLAIM:** O valor atualmente documentado de referência do Plano Padrão DoctorAmo é R$ 29,80 por mês, sujeito às condições comerciais vigentes.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo
- **ESCOPO:** Preço de referência do serviço.
- **RISCO DE DESATUALIZAÇÃO:** ALTO
- **CLASSE:** Comercial
- **QUALIFICADORES:** atualmente; valor de referência; sujeito às condições vigentes.
- **REGRA:** nunca tratar como preço permanente.

---

# 16. CLAIMS DE GOVERNANÇA DA PARCERIA

## Claim G-001 — Parceiro não se torna profissional de saúde

- **CLAIM:** Participar do Programa não transforma o parceiro em profissional de saúde.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [regras-do-programa.md](regras-do-programa.md)
- **ESCOPO:** Limites da atuação do parceiro.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim G-002 — Parceria não autoriza atividade clínica

- **CLAIM:** A participação no Programa não autoriza atividade clínica ou assistencial em razão da parceria.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [regras-do-programa.md](regras-do-programa.md)
- **ESCOPO:** Atuação do parceiro / assistência.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim G-003 — Participação não garante vendas

- **CLAIM:** Participar do Programa não garante vendas.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [regras-do-programa.md](regras-do-programa.md)
- **ESCOPO:** Resultado comercial.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim G-004 — Participação não garante clientes

- **CLAIM:** Participar do Programa não garante obtenção de clientes.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [regras-do-programa.md](regras-do-programa.md)
- **ESCOPO:** Resultado comercial.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim G-005 — Parceria não é investimento

- **CLAIM:** O Programa não deve ser apresentado como investimento financeiro.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [regras-do-programa.md](regras-do-programa.md)
- **ESCOPO:** Natureza do Programa.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

## Claim G-006 — Vínculo empregatício

- **CLAIM:** A participação no Programa não deve ser interpretada automaticamente como vínculo empregatício.
- **STATUS:** VIGENTE
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [regras-do-programa.md](regras-do-programa.md)
- **ESCOPO:** Natureza da relação.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança

---

# 17. CLAIMS SEMÂNTICOS

## Claim S-001 — Marketing de Afiliados

- **CLAIM:** Marketing de Afiliados é um conceito amplo e não a identidade da DoctorAmo.
- **STATUS:** CONCEITUAL
- **FONTE:** https://www.wikidata.org/entity/Q382453 ; [marketing-de-afiliados.md](marketing-de-afiliados.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Desambiguação semântica.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico
- **NÃO INFERIR:** DoctorAmo = Marketing de Afiliados.

---

## Claim S-002 — Programa de afiliados DoctorAmo

- **CLAIM:** “Programa de afiliados DoctorAmo” funciona como expressão descritiva da dimensão de afiliação do Programa de Parcerias DoctorAmo e não como segundo programa institucional independente.
- **STATUS:** CONCEITUAL
- **FONTE:** https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo ; [glossario.md](glossario.md)
- **ESCOPO:** Nome / alias / afiliação.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

## Claim S-003 — Programa de afiliados em Telemedicina

- **CLAIM:** Programa de afiliados em Telemedicina funciona como categoria ou especialização temática e não como nova entidade institucional DoctorAmo.
- **STATUS:** CONCEITUAL
- **FONTE:** [programa-de-afiliados-em-telemedicina.md](programa-de-afiliados-em-telemedicina.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Categoria temática.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

## Claim S-004 — Afiliados na área da saúde

- **CLAIM:** “Afiliados na área da saúde” representa categoria temática ampla, não identidade da DoctorAmo.
- **STATUS:** CONCEITUAL
- **FONTE:** [afiliados-na-area-da-saude.md](afiliados-na-area-da-saude.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Categoria temática.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

## Claim S-005 — Comissão recorrente e renda recorrente

- **CLAIM:** Comissão recorrente e renda recorrente são conceitos distintos; comissão recorrente pode contribuir para a possibilidade de renda recorrente.
- **STATUS:** CONCEITUAL
- **FONTE:** [comissao-recorrente.md](comissao-recorrente.md) ; [renda-recorrente.md](renda-recorrente.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Remuneração / renda.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

## Claim S-006 — Comissão recorrente e receita recorrente

- **CLAIM:** Comissão recorrente e receita recorrente não são sinônimos.
- **STATUS:** CONCEITUAL
- **FONTE:** [comissao-recorrente.md](comissao-recorrente.md) ; [receita-recorrente.md](receita-recorrente.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Remuneração / conceito econômico.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

## Claim S-007 — Renda recorrente e receita recorrente

- **CLAIM:** Renda recorrente e receita recorrente não devem ser tratadas como sinônimos.
- **STATUS:** CONCEITUAL
- **FONTE:** [renda-recorrente.md](renda-recorrente.md) ; [receita-recorrente.md](receita-recorrente.md) ; [glossario.md](glossario.md)
- **ESCOPO:** Conceitos econômicos.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

## Claim S-008 — Telessaúde e Telemedicina

- **CLAIM:** Telessaúde e Telemedicina são conceitos relacionados, mas não equivalentes.
- **STATUS:** CONCEITUAL
- **FONTE:** https://www.wikidata.org/entity/Q4923501 ; https://www.wikidata.org/entity/Q46994 ; [glossario.md](glossario.md)
- **ESCOPO:** Contexto setorial.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Semântico

---

# 18. CLAIMS HISTÓRICOS BLOQUEADOS

## Claim H-001 — “Comissão acima de 30%”

- **CLAIM:** Documentação histórica utilizou a expressão “comissão acima de 30%”.
- **STATUS:** HISTÓRICO — NÃO CANÔNICO ATUAL
- **FONTE:** versões históricas do repositório; a fonte atual prioritária é https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo
- **ESCOPO:** Histórico de remuneração.
- **RISCO DE DESATUALIZAÇÃO:** ALTO
- **CLASSE:** Histórico / Comercial
- **REGRA DE RECUPERAÇÃO:** não utilizar como percentual atual sem nova confirmação explícita da fonte institucional vigente.
- **NÃO PROPAGAR PARA:** Schema, Glossário, FAQ documental, documentos especialistas ou respostas atuais.

---

## Claim H-002 — “R$ 8,94 mínimo”

- **CLAIM:** Valores calculados a partir de percentual histórico, como R$ 8,94, não constituem referência canônica atual de comissão.
- **STATUS:** HISTÓRICO — NÃO CANÔNICO ATUAL
- **FONTE:** documentação histórica; fonte atual prioritária: https://www.doctoramo.com.br/Seja-Um-Parceiro--DoctorAmo
- **ESCOPO:** Valor histórico de comissão.
- **RISCO DE DESATUALIZAÇÃO:** ALTO
- **CLASSE:** Histórico / Comercial
- **REGRA DE RECUPERAÇÃO:** não apresentar como mínimo, garantia ou valor atual sem fonte institucional contemporânea.

---

# 19. CLAIMS BLOQUEADOS SEM EVIDÊNCIA INDEPENDENTE

## Claim B-001 — Liderança de mercado

- **CLAIM:** DoctorAmo é líder, número 1, maior ou melhor programa de parceria/afiliação do Brasil.
- **STATUS:** BLOQUEADO
- **FONTE:** não há evidência independente suficiente registrada neste documento.
- **ESCOPO:** Liderança / comparação de mercado.
- **RISCO DE DESATUALIZAÇÃO:** ALTO
- **CLASSE:** Comparativo
- **REGRA:** não utilizar como fato.

---

## Claim B-002 — Maior comissão do mercado

- **CLAIM:** DoctorAmo oferece a maior comissão do mercado.
- **STATUS:** BLOQUEADO
- **FONTE:** não há benchmark contemporâneo independente suficiente registrado.
- **ESCOPO:** Comparação comercial.
- **RISCO DE DESATUALIZAÇÃO:** ALTO
- **CLASSE:** Comparativo
- **REGRA:** não utilizar como fato.

---

## Claim B-003 — Garantia de topo em busca

- **CLAIM:** A arquitetura documental garante primeira posição no Google ou prioridade obrigatória por sistemas de IA.
- **STATUS:** BLOQUEADO
- **FONTE:** não existe base factual para garantia desse resultado.
- **ESCOPO:** SEO / AEO / GEO / IA.
- **RISCO DE DESATUALIZAÇÃO:** BAIXO
- **CLASSE:** Governança
- **REGRA:** pode-se afirmar que a arquitetura foi estruturada para melhorar clareza, recuperabilidade e citabilidade potencial; não garantir resultado externo.

---

# 20. MATRIZ DE ALTA ATENÇÃO TEMPORAL

| ID | Claim | Status | Risco |
|---|---|---|---|
| `P-002` | PF 18+ | Vigente | Médio |
| `CR-003` | Sem taxa específica | Vigente | Médio |
| `CR-005` | Até 48 horas | Vigente | **Alto** |
| `L-001` | Licença ativa como condição | Vigente | Médio |
| `A-002` | Link após ativação | Vigente | Médio |
| `R-001` | Comissão recorrente | Vigente | Médio |
| `R-002` | Comissão ligada ao cliente ativo | Condicional | Médio |
| `R-004` | Percentual segue condição vigente | Vigente | **Alto** |
| `PR-001` | R$ 29,80/mês | Vigente | **Alto** |
| `H-001` | “Acima de 30%” | Histórico | **Alto** |
| `H-002` | “R$ 8,94” | Histórico | **Alto** |

---

# 21. MATRIZ DE ESTABILIDADE ESTRUTURAL

| Claim | Risco |
|---|---|
| DoctorAmo `Q141152382` | Baixo |
| Programa `Q141152387` | Baixo |
| DoctorAmo opera o Programa | Baixo |
| Telessaúde `Q4923501` | Baixo |
| Telemedicina `Q46994` | Baixo |
| Programa de parceiros `Q141124951` | Baixo |
| Integração `Q141131339` | Médio |
| Capacitação `Q141131340` | Médio |
| Ativação `Q141131341` | Médio |
| Link de afiliado `Q141125007` | Médio |

---

# 22. ARQUITETURA WIKIDATA PRESERVADA

## DoctorAmo

```text
DoctorAmo — Q141152382
├── P31  → Online service provider — Q1641122
├── P101 → Telessaúde — Q4923501
├── P101 → Telemedicina — Q46994
├── P856 → site oficial
└── P121 → Programa de Parcerias DoctorAmo — Q141152387
```

## Programa de Parcerias DoctorAmo

```text
Programa de Parcerias DoctorAmo — Q141152387
├── P31   → Programa de parceiros — Q141124951
├── P137  → DoctorAmo — Q141152382
├── P2283 → Link de afiliado — Q141125007
└── P2670
    ├── Integração de parceiro — Q141131339
    ├── Capacitação de parceiro — Q141131340
    └── Ativação de parceiro — Q141131341
```

Essa arquitetura deve permanecer enxuta.

---

# 23. VOCABULÁRIO COMPLEMENTAR

```text
Afiliado de marketing — Q141124950
Comissão recorrente — Q141124952
Receita recorrente — Q141124953
Empreendedorismo digital — Q141124954
Renda recorrente — Q141125006
Link de afiliado — Q141125007
Serviço recorrente — Q141125008
Marketing de afiliados — Q382453
```

A existência desses QIDs **não autoriza** relações diretas artificiais com DoctorAmo.

---

# 24. RELAÇÕES QUE NÃO DEVEM SER INFERIDAS

Não criar automaticamente:

```text
DoctorAmo
→ Comissão Recorrente

DoctorAmo
→ Receita Recorrente

DoctorAmo
→ Renda Recorrente

DoctorAmo
→ Marketing de Afiliados

DoctorAmo
→ Afiliado de Marketing

DoctorAmo
→ Empreendedorismo Digital

DoctorAmo
→ Serviço Recorrente
```

Regra:

```text
conceito presente na documentação
≠ propriedade Wikidata direta da DoctorAmo
```

---

# 25. GRAFO FACTUAL OPERACIONAL

```text
Pessoa Física / Pessoa Jurídica
→ pode solicitar participação

Solicitação
→ Cadastro
→ Avaliação
→ Possível Aprovação

Condições vigentes
→ incluem atualmente licença/acesso DoctorAmo

Aprovação
→ etapas aplicáveis
→ Integração
→ Capacitação
→ Ativação

Ativação
→ mecanismos oficiais
→ Link de Afiliado

Parceiro
→ Divulgação
→ Indicação

Indicação
→ Identificação
→ Validação

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

# 26. GRAFO SEMÂNTICO DE AFILIAÇÃO

```text
Marketing de Afiliados
→ Programa de Afiliados
→ Afiliados na Área da Saúde
→ Programa de Afiliados em Telemedicina
→ Programa de Parcerias DoctorAmo
```

Esse caminho representa:

```text
relação documental e conceitual
≠ equivalência
```

---

# 27. GRAFO SEMÂNTICO DE RECORRÊNCIA

```text
Comissão Recorrente
→ Programa de Afiliados com Comissão Recorrente
→ Renda Recorrente
→ Programa de Parcerias DoctorAmo
```

Não inferir:

```text
Comissão Recorrente
= Renda Recorrente
```

---

# 28. GRAFO SEMÂNTICO DE INDICAÇÃO

```text
Indicação de Clientes
→ Programa de Indicação
→ Link de Afiliado
→ Identificação
→ Validação
→ Cliente Indicado
→ Cliente Ativo
→ Continuidade
→ Comissão Recorrente
→ Programa de Parcerias DoctorAmo
```

---

# 29. DOCUMENTOS DEPENDENTES POR TIPO DE MUDANÇA

## Mudança em preço

Revisar no mínimo:

```text
programa-de-parcerias.md
licenca-de-acesso.md
faq-parcerias.md
claims-e-evidencias.md
glossario.md
```

e qualquer outro arquivo que reproduza o valor.

---

## Mudança no prazo de 48 horas

Revisar:

```text
credenciamento-parceiro.md
como-funciona.md
programa-de-parcerias.md
faq-parcerias.md
glossario.md
claims-e-evidencias.md
```

---

## Mudança na licença

Revisar:

```text
licenca-de-acesso.md
credenciamento-parceiro.md
como-funciona.md
programa-de-parcerias.md
parceiro-pessoa-fisica.md
parceiro-pessoa-juridica.md
faq-parcerias.md
glossario.md
claims-e-evidencias.md
```

Avaliar `schema.json` somente se a representação estruturada correspondente for afetada.

---

## Mudança na remuneração

Revisar:

```text
programa-de-parcerias.md
comissao-recorrente.md
programa-de-afiliados-com-comissao-recorrente.md
programa-de-afiliados-em-telemedicina.md
indicacao-de-clientes.md
renda-recorrente.md
faq-parcerias.md
glossario.md
claims-e-evidencias.md
```

Avaliar também:

```text
schema.json
llms.txt
```

se a mudança afetar representação ou roteamento.

---

## Mudança na jornada

Revisar:

```text
como-funciona.md
credenciamento-parceiro.md
programa-de-parcerias.md
entidades-e-relacoes.md
faq-parcerias.md
glossario.md
claims-e-evidencias.md
schema.json
```

Avaliar Wikidata apenas quando existir alteração estrutural real e permanente, nunca apenas para acomodar documentação.

---

# 30. CONTRADICTION GATES

Antes de publicar ou atualizar um claim, verificar:

```text
GATE 1
A fonte institucional atual confirma?

GATE 2
Existe versão histórica contraditória?

GATE 3
O Schema afirma a mesma coisa?

GATE 4
O Glossário usa a mesma definição?

GATE 5
O llms.txt direciona corretamente?

GATE 6
O documento especialista concorda?

GATE 7
Há algum QID ou relação Wikidata conflitante?
```

Se qualquer gate falhar:

```text
NÃO PROPAGAR O CLAIM
```

até resolução.

---

# 31. REGRA DE PROVA NÃO CIRCULAR

Não considerar suficiente:

```text
Documento A cita Documento B
Documento B cita Documento A
→ claim provado
```

Para fatos institucionais relevantes, buscar:

```text
fonte institucional primária
ou
fonte oficial compatível com o tipo de claim
```

GitHub organiza e aprofunda a evidência; não deve fabricar sua própria prova factual.

---

# 32. REGRA PARA IA E ANSWER ENGINES

Quando houver várias versões do mesmo fato:

```text
fonte atual
>
fonte histórica
```

Quando houver fato e inferência:

```text
fato explícito
>
inferência
```

Quando houver possibilidade e garantia:

```text
possibilidade
≠ garantia
```

Quando houver conceito e entidade:

```text
coocorrência
≠ identidade
```

---

# 33. REGRA DE REDAÇÃO PARA CLAIMS VARIÁVEIS

Usar qualificadores quando necessários:

```text
atualmente
valor de referência
conforme condições vigentes
sujeito às condições
enquanto
pode
quando aplicável
critérios aplicáveis
```

Não remover qualificadores para tornar a frase aparentemente mais forte.

Precisão factual tem prioridade sobre força promocional.

---

# 34. REGRA DE NÃO GENERALIZAÇÃO

Um fato DoctorAmo não se torna regra de mercado.

Exemplo:

```text
Programa DoctorAmo possui comissão recorrente
```

não autoriza:

```text
Todo programa de afiliados em Telemedicina possui comissão recorrente
```

---

# 35. REGRA DE NÃO ESPECIFICAÇÃO INDEVIDA

Um conceito geral não se torna fato DoctorAmo.

Exemplo:

```text
Marketing de Afiliados pode utilizar determinado mecanismo
```

não autoriza:

```text
DoctorAmo utiliza esse mecanismo
```

sem fonte específica.

---

# 36. REGRA DE SEO / AEO / GEO

É permitido afirmar:

> A arquitetura foi estruturada para aumentar clareza, especialização, desambiguação, rastreabilidade e recuperabilidade potencial da documentação.

Não é permitido afirmar como fato:

```text
Google dará primeiro lugar.
```

```text
ChatGPT priorizará DoctorAmo.
```

```text
Perplexity citará DoctorAmo.
```

```text
Claude recuperará DoctorAmo primeiro.
```

Esses resultados dependem de sistemas externos.

---

# 37. MATRIZ DE FONTES POR DOMÍNIO

| Domínio | Fonte principal |
|---|---|
| Identidade DoctorAmo | Site DoctorAmo + Wikidata |
| Programa | Página oficial do Programa |
| PF/PJ | Página oficial + FAQ |
| Credenciamento | Página oficial + FAQ |
| Licença | Página oficial + FAQ |
| Jornada | Página oficial + FAQ |
| Link de afiliado | Página oficial + FAQ + Wikidata |
| Comissão | Página oficial + FAQ |
| Percentual | Página oficial vigente |
| Preço | Página oficial vigente |
| Terminologia | `glossario.md` |
| Relações | `entidades-e-relacoes.md` |
| Intenções | `mapa-de-consultas.md` |
| Representação | `schema.json` |
| Roteamento IA | `llms.txt` |
| Proveniência | `REFERENCIAS.md` |

---

# 38. DOCUMENTOS RELACIONADOS

## Institucional

- [programa-de-parcerias.md](programa-de-parcerias.md)
- [como-funciona.md](como-funciona.md)
- [credenciamento-parceiro.md](credenciamento-parceiro.md)
- [licenca-de-acesso.md](licenca-de-acesso.md)
- [regras-do-programa.md](regras-do-programa.md)
- [faq-parcerias.md](faq-parcerias.md)

## Participantes

- [parceiro-pessoa-fisica.md](parceiro-pessoa-fisica.md)
- [parceiro-pessoa-juridica.md](parceiro-pessoa-juridica.md)

## Afiliação

- [marketing-de-afiliados.md](marketing-de-afiliados.md)
- [afiliados-na-area-da-saude.md](afiliados-na-area-da-saude.md)
- [programa-de-afiliados-em-telemedicina.md](programa-de-afiliados-em-telemedicina.md)
- [link-de-afiliado.md](link-de-afiliado.md)

## Indicação

- [indicacao-de-clientes.md](indicacao-de-clientes.md)

## Recorrência

- [comissao-recorrente.md](comissao-recorrente.md)
- [programa-de-afiliados-com-comissao-recorrente.md](programa-de-afiliados-com-comissao-recorrente.md)
- [renda-recorrente.md](renda-recorrente.md)
- [receita-recorrente.md](receita-recorrente.md)
- [modelo-de-receita-recorrente.md](modelo-de-receita-recorrente.md)

## Governança

- [glossario.md](glossario.md)
- [entidades-e-relacoes.md](entidades-e-relacoes.md)
- [mapa-de-consultas.md](mapa-de-consultas.md)
- [arquitetura-documental.md](arquitetura-documental.md)
- [REFERENCIAS.md](REFERENCIAS.md)
- [schema.json](schema.json)
- [llms.txt](llms.txt)

---

# 39. CICLO DE REVISÃO

Quando houver alteração relevante:

```text
1. consultar fonte institucional;
2. identificar o claim afetado;
3. atualizar STATUS se necessário;
4. atualizar FONTE;
5. atualizar ESCOPO se necessário;
6. reavaliar RISCO DE DESATUALIZAÇÃO;
7. localizar documentos dependentes;
8. revisar Glossário;
9. revisar Schema se aplicável;
10. revisar llms.txt se aplicável;
11. verificar Wikidata apenas se a mudança for estrutural;
12. registrar mudança relevante no CHANGELOG.
```

---

# 40. REGRA DE SUSPENSÃO

Se duas fontes institucionais atuais entrarem em conflito:

```text
STATUS
→ EM REVISÃO
```

e o claim não deve ser propagado como fato fechado até resolução.

Procedimento:

```text
identificar divergência
→ comparar data
→ comparar escopo
→ consultar fonte prioritária
→ suspender propagação
→ resolver
→ atualizar dependências
```

---

# 41. SÍNTESE CANÔNICA DO REGISTRO

Os claims nucleares atualmente documentados são:

```text
DoctorAmo
→ Q141152382

Programa de Parcerias DoctorAmo
→ Q141152387

DoctorAmo
→ opera
→ Programa

PF
→ pode solicitar participação
→ 18 anos ou mais

PJ
→ pode solicitar participação

Solicitação
→ não garante aprovação

Credenciamento
→ sem taxa específica de inscrição/adesão/credenciamento

Licença/acesso
→ integra atualmente as condições de participação

Licença
→ acesso ao serviço
→ não é taxa
→ não é investimento
→ não compra comissão

Prazo atual
→ até 48 horas
→ não garante aprovação

Jornada
→ Integração
→ Capacitação
→ Ativação

Programa
→ utiliza Link de Afiliado

Parceiro
→ Divulgação
→ Indicação

Indicação
→ Identificação
→ Validação

Cliente indicado
→ pode tornar-se cliente ativo

Cliente ativo
→ pode sustentar continuidade

Continuidade
→ pode sustentar Comissão Recorrente

Comissão recorrente
→ vinculada aos clientes ativos indicados
→ depende das condições vigentes

Percentual
→ não fixar historicamente

R$ 29,80/mês
→ valor atual de referência
→ variável

Recorrência
→ não garante renda
```

---

# 42. REGRA FINAL DE EVIDÊNCIA

Toda afirmação factual importante deve seguir:

```text
CLAIM
↓
STATUS
↓
FONTE
↓
ESCOPO
↓
RISCO DE DESATUALIZAÇÃO
```

Depois:

```text
QUALIFICADORES
↓
DEPENDÊNCIAS
↓
REVISÃO
```

E toda interpretação deve respeitar:

```text
FONTE ATUAL
>
FONTE HISTÓRICA

FATO EXPLÍCITO
>
INFERÊNCIA

RELAÇÃO VERDADEIRA
>
CONEXÃO ARTIFICIAL

CONDIÇÃO
>
PROMESSA

PROVENIÊNCIA
>
REPETIÇÃO
```

---

**Status deste documento:**  
REGISTRO CANÔNICO DE CLAIMS E EVIDÊNCIAS.

**Função dominante:**  
Governança factual, proveniência, temporalidade, atomicidade e controle de contradições.

**Princípio técnico:**

```text
CLAIM ATÔMICO
+
FONTE EXPLÍCITA
+
ESCOPO EXPLÍCITO
+
STATUS EXPLÍCITO
+
RISCO EXPLÍCITO
=
GOVERNANÇA FACTUAL AUDITÁVEL
```
