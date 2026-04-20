# WeeeMob — Guia SDD para IA
## Ramo: Marketing e Comercial

## Finalidade deste guia

Este documento orienta outra IA a continuar o ramo **Marketing e Comercial** com o mínimo de ambiguidade, usando **Spec-Driven Development (SDD)** como método.

A IA deve tratar este arquivo como fonte de verdade para:
- contexto congelado
- decisões já tomadas
- formato obrigatório de entrega
- ordem de trabalho
- critérios de qualidade
- definição de pronto

---

## 1. Contexto congelado

### 1.1 Modelo de negócio
- WeeeMob é uma **plataforma operadora de marketplace** para serviços automotivos.
- Não é franquia.
- Os atores principais são:
  - plataforma operadora
  - parceiro/prestador
  - usuário comprador

### 1.2 Categorias principais
- Estética
- Mecânica
- Estacionamento

### 1.3 Premissa do ramo
Marketing e Comercial devem operar como máquina de crescimento dos dois lados do marketplace.

Isso implica:
- aquisição de usuário
- aquisição de parceiro
- ativação de ambos
- retenção de ambos
- expansão regional
- leitura de densidade de oferta e demanda
- CRM
- campanhas
- attribution

### 1.4 Posicionamento congelado
A WeeeMob não vende só software.
A WeeeMob vende:
- demanda
- operação
- repasse
- reputação
- visibilidade
- automação
- crescimento

---

## 2. Objetivo deste ramo

A IA deve detalhar Marketing e Comercial de forma executável, transformando intenção estratégica em:
- specs
- funis
- playbooks
- KPIs
- backlog
- critérios de aceite
- artefatos reutilizáveis por produto, growth, comercial e dados

---

## 3. Regras obrigatórias de entrega

Toda resposta produzida para este ramo deve incluir, quando aplicável:
1. objetivo
2. escopo
3. premissas congeladas
4. regras obrigatórias
5. fluxos
6. responsabilidades
7. dependências
8. KPIs
9. riscos
10. backlog por fase
11. critérios de aceite
12. dicionário de termos técnicos

### 3.1 Formato preferido
Usar estrutura com:
- título claro
- seções numeradas
- linguagem executiva
- listas objetivas
- sem texto solto excessivo

### 3.2 Tom esperado
- profissional
- direto
- congelável
- orientado a operação real
- sem linguagem vaga

---

## 4. O que não pode ser quebrado

A IA **não pode**:
- voltar ao modelo de franquia como premissa principal
- tratar parceiro como franqueado no discurso oficial
- propor crescimento desancorado da oferta
- tratar marketing como apenas tráfego pago
- tratar comercial como apenas cadastro de lead
- separar growth de operação do marketplace
- ignorar atribuição e dashboards

---

## 5. Estrutura-alvo das specs

A IA deve produzir materiais compatíveis com a seguinte árvore:

```txt
specs/
  vision/
  product/
  domain/
  api/
  ui/
  infra/
  acceptance/
```

### 5.1 Local ideal para este ramo
- `specs/product/12-marketing-e-comercial.md`
- derivados por subtema em `specs/product/marketing/`
- critérios de aceite em `specs/acceptance/marketing/`

---

## 6. Ordem recomendada de aprofundamento

Quando continuar este ramo, seguir esta ordem:

1. posicionamento e narrativa
2. ICP do parceiro
3. funil de usuário
4. funil de parceiro
5. playbook comercial
6. ativação do parceiro
7. CRM e retenção
8. expansão geográfica
9. analytics e attribution
10. dashboards e metas operacionais

---

## 7. Template obrigatório por subtema

Usar este template para qualquer novo subtema:

```md
# [Nome do Subtema]

## 1. Objetivo
## 2. Escopo
## 3. Premissas congeladas
## 4. Regras obrigatórias
## 5. Fluxo ou funil
## 6. Responsabilidades
## 7. Dependências
## 8. KPIs
## 9. Riscos
## 10. Backlog por fase
## 11. Critérios de aceite
## 12. Dicionário de termos técnicos
```

---

## 8. Subtemas prioritários

### 8.1 Posicionamento e narrativa
A IA deve detalhar:
- proposta de valor por público
- mensagens-chave
- diferenciais
- objeções e respostas
- claims que podem ou não podem ser usados

### 8.2 ICP do parceiro
A IA deve detalhar:
- critérios de qualificação
- sinais positivos
- sinais de risco
- categorias prioritárias
- score de entrada

### 8.3 Funil de usuário
A IA deve detalhar:
- visita
- clique
- instalação
- cadastro
- onboarding
- primeiro pedido
- recompra
- retenção

### 8.4 Funil de parceiro
A IA deve detalhar:
- lead
- qualificação
- reunião
- proposta
- aceite
- documentação
- aprovação
- oferta ativa
- primeiro pedido
- retenção

### 8.5 Playbook comercial
A IA deve detalhar:
- pipeline
- SLA por etapa
- scripts de abordagem
- objeções e respostas
- checklist de handoff para onboarding

### 8.6 CRM e retenção
A IA deve detalhar:
- automações por estado
- gatilhos por evento
- campanhas de reativação
- controles anti-spam
- métricas de retenção

### 8.7 Expansão geográfica
A IA deve detalhar:
- critérios para abrir cidade/região
- densidade mínima de oferta
- ordem de categorias
- KPIs regionais

### 8.8 Analytics e attribution
A IA deve detalhar:
- eventos mínimos
- UTMs
- dashboards por canal
- dashboards por região
- dashboards por categoria

---

## 9. Definition of Done (DoD)

Um material deste ramo só está pronto quando:
- está alinhado ao modelo marketplace
- separa claramente usuário e parceiro
- tem regras operacionais e não só ideias
- tem KPIs concretos
- tem backlog aplicável
- tem critérios de aceite objetivos
- pode ser entregue para produto, growth, comercial e dados sem retrabalho conceitual

---

## 10. Checklist de coerência para a IA

Antes de concluir qualquer entrega, verificar:
- esta proposta cresce os dois lados do marketplace?
- existe risco de gerar demanda sem oferta?
- existe risco de captar parceiro sem ativar?
- existe leitura de CAC, conversão e retenção?
- existe dono da operação sugerida?
- existe dashboard ou KPI para acompanhar?
- existe handoff entre marketing, comercial e onboarding?

---

## 11. Anti-padrões

Evitar:
- "fazer campanhas" sem objetivo e sem KPI
- "captar parceiros" sem pipeline de ativação
- "fazer SEO" sem estrutura regional e de categoria
- "mandar e-mail/push" sem gatilho e contexto
- "expandir região" sem supply mínimo
- "provar ROI" sem dashboard visível

---

## 12. Prompt mestre para outra IA

```text
Você vai continuar o ramo Marketing e Comercial da WeeeMob.

Contexto congelado:
- WeeeMob é uma plataforma operadora de marketplace para serviços automotivos.
- Não é franquia.
- Existem dois lados do marketplace: usuário e parceiro/prestador.
- Marketing e Comercial existem para captar, ativar, reter e expandir os dois lados com previsibilidade.
- As categorias principais são Estética, Mecânica e Estacionamento.
- O parceiro entra com baixo atrito e a monetização principal é take rate, com receitas secundárias de destaque, mídia, CRM e produtos premium.

Formato obrigatório de resposta:
- objetivo
- escopo
- premissas congeladas
- regras obrigatórias
- fluxos/funis
- responsabilidades
- dependências
- KPIs
- riscos
- backlog por fase
- critérios de aceite
- dicionário técnico

Agora detalhe o subtema: [INSERIR SUBTEMA]
```

---

## 13. Exemplos de próximos prompts

### Prompt 1 — Posicionamento
```text
Detalhe o posicionamento e a narrativa oficial da WeeeMob para usuário e parceiro.
```

### Prompt 2 — Funil do parceiro
```text
Detalhe o funil completo do parceiro, do lead ao primeiro pedido.
```

### Prompt 3 — CRM
```text
Detalhe o CRM de usuário e parceiro com gatilhos, mensagens e métricas.
```

### Prompt 4 — Expansão regional
```text
Detalhe a estratégia de expansão geográfica com critérios e KPIs mínimos.
```

---

## 14. Definition of Constraints

A IA deve assumir:
- tudo precisa ser escalável
- tudo precisa ser mensurável
- tudo precisa ser auditável no nível de operação de growth/comercial
- as entregas precisam servir para implementação posterior no Painel Operador, no Portal do Parceiro, no Site e no App do Usuário

---

## Dicionário de termos técnicos

**SDD**: desenvolvimento guiado por especificações antes da implementação.
**ICP**: perfil ideal de cliente/parceiro.
**CAC**: custo de aquisição.
**CTR**: taxa de clique.
**CVR**: taxa de conversão.
**ROAS**: retorno sobre gasto em mídia.
**CRM**: gestão de relacionamento e automações.
**Lead score**: pontuação para priorização de leads.
**Attribution**: atribuição do resultado ao canal/origem.
**Activation**: momento em que o usuário/parceiro passa a gerar valor real.
**Churn**: perda ou desativação.
**Marketplace density**: densidade de oferta suficiente para o lado da demanda funcionar bem.
