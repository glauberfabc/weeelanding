# Marketing e Comercial — Dashboards e Attribution — Backlog de instrumentação

## 1. Definição

Este arquivo aprofunda o subtema **Dashboards e Attribution**, com foco específico em **backlog de instrumentação**.

Este ramo aprofunda eventos, naming, dashboards e qualidade de dados para growth.

## 2. Contexto congelado

- WeeeMob é um marketplace operado de serviços automotivos.
- Existem dois lados do marketplace: usuário e parceiro/prestador.
- Marketing e Comercial existem para equilibrar demanda e oferta, melhorar ativação, retenção e previsibilidade do crescimento.
- A plataforma não é franquia, não vende software genérico e opera com Painel Operador, Portal do Parceiro, App do Usuário e LP/Site.

## 3. Objetivo deste branch

Desdobrar backlog de tracking e modelagem analítica.

## 4. Escopo

- eventos
- UTMs
- dashboards

## 5. Regras e premissas

- manter consistência com o módulo Marketing e Comercial já congelado;
- não reintroduzir linguagem de franquia ou software genérico;
- separar claramente usuário, parceiro e camada institucional quando aplicável;
- toda definição precisa ser acionável por produto, growth, comercial ou dados;
- toda métrica sugerida precisa ter owner e interpretação de negócio;

## 6. Perguntas que este branch precisa responder

- como a WeeeMob deve estruturar backlog de instrumentação?
- quais são as decisões que precisam ser congeladas neste subtema?
- quais dependências existem com produto, comercial, growth, dados e operação?
- quais riscos surgem se esse subtema ficar mal definido?

## 7. Entregáveis esperados

- backlog
- dependências
- priorização

## 8. KPIs e leituras sugeridas

- eficiência do subtema dentro do funil correspondente;
- clareza de ownership e operação;
- capacidade de virar dashboard, playbook ou regra operacional;
- impacto esperado em aquisição, ativação, retenção ou receita;

## 9. Dependências

- posicionamento e narrativa da WeeeMob;
- LP/Site, App do Usuário, Portal do Parceiro e Painel Operador quando aplicável;
- observabilidade, dashboards e attribution;
- regras de negócio e modelo operacional do marketplace;

## 10. Riscos principais

- definição genérica demais e pouco aplicável;
- excesso de teoria sem impacto operacional;
- desalinhamento entre marketing, growth, comercial e produto;
- falta de source of truth e métricas úteis;

## 11. Critérios de aceite

- backlog de instrumentação está definido de forma clara e utilizável;
- existem entregáveis concretos para execução;
- há dependências, riscos e owners identificados;
- o ramo pode ser aprofundado por outra IA sem ambiguidade;

## 12. Prompt base para próximo chat

```text
Quero aprofundar o branch Dashboards e Attribution — Backlog de instrumentação da WeeeMob.

Contexto congelado:
- WeeeMob é um marketplace operado de serviços automotivos.
- Existem dois lados do marketplace: usuário e parceiro/prestador.
- Marketing e Comercial existem para equilibrar demanda e oferta, melhorar ativação, retenção e previsibilidade do crescimento.
- A plataforma não é franquia, não vende software genérico e opera com Painel Operador, Portal do Parceiro, App do Usuário e LP/Site.
- Este branch trata especificamente de {title.lower()}.

Quero que você detalhe agora:
1. decisões que precisam ser congeladas
2. estrutura completa do subtema
3. entregáveis finais
4. KPIs e dashboards
5. riscos e controles
6. backlog por frente
7. critérios de aceite
```

## 13. Dicionário de termos técnicos

**CAC**: custo de aquisição de cliente.  
**ICP**: perfil ideal de cliente/parceiro.  
**CTR**: taxa de clique.  
**CVR**: taxa de conversão.  
**Attribution**: atribuição do resultado ao canal/campanha de origem.  
**Activation**: momento em que o usuário ou parceiro realmente começa a gerar valor.  
**Retention**: capacidade de manter uso/recorrência ao longo do tempo.  
**Churn**: perda de usuário ou parceiro.  
**ROAS**: retorno sobre gasto em mídia.  
**UTM**: parâmetro de rastreamento de campanha.  
**Source of truth**: fonte oficial de verdade para leitura de dados.  
**Playbook**: roteiro padronizado de execução operacional/comercial.  
