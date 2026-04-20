# Dashboards e Attribution — Marketing e Comercial
## 1. Contexto congelado
- WeeeMob é um marketplace operado para serviços automotivos
- os públicos principais são usuário final e parceiro/prestador
- marketing, comercial e growth precisam trabalhar juntos
- a plataforma vende conveniência para usuário e crescimento operacional para parceiro
- este arquivo serve como base para um novo branch especializado

## 2. Definição executiva
Define a leitura analítica de canais, campanhas, regiões, categorias, usuários e parceiros para tomada de decisão.

## 3. Objetivo
Garantir que marketing, comercial, growth e liderança vejam a mesma verdade do funil.

## 4. Camadas de leitura
- canal
- campanha
- LP
- categoria
- região
- usuário
- parceiro
- coorte
- receita/GMV

## 5. Eventos mínimos
- site_visit
- cta_click
- app_install / store_view
- signup_started
- signup_completed
- vehicle_added
- category_selected
- partner_selected
- order_paid
- first_order_completed
- partner_lead_created
- partner_meeting_completed
- partner_activated
- first_partner_order

## 6. Dashboards oficiais
- aquisição de usuários
- aquisição de parceiros
- ativação
- retenção
- regional
- campanhas patrocinadas
- executivo de crescimento

## 7. Regras
- toda campanha com UTM
- toda fonte com naming padrão
- toda tela crítica com evento
- same source of truth para marketing/comercial/produto
- números financeiros precisam bater com o módulo financeiro

## 8. Entregáveis
- taxonomia de eventos
- naming convention de campanhas
- painéis por área
- documentação de attribution
- metas por dashboard

## 9. KPIs
- CAC
- CPA
- CPL parceiro
- CVR
- first order rate
- activation rate parceiro
- repeat order rate
- payback
- LTV/CAC

## 10. Riscos
- eventos faltando
- campanhas sem rastreio
- dashboards divergentes
- leitura por canal sem corte regional
- lead/partner/user sem identificação clara no funil

## 11. Prompt base para branch
Quero aprofundar o subtema Dashboards e Attribution da WeeeMob.

Contexto congelado:
- Precisamos medir aquisição e ativação de usuário e parceiro.
- Toda campanha precisa de UTM e naming padrão.
- Os dashboards devem servir marketing, comercial, growth e liderança.

Quero que você detalhe:
1. taxonomia de eventos
2. UTMs e naming padrão
3. dashboards oficiais
4. KPIs por dashboard
5. regras de source of truth
6. backlog de instrumentação
7. regras de qualidade de dados
8. critérios de aceite

## Dicionário de termos técnicos
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
