# WeeeMob — Guia SDD para IA (LP / Site)

## 1. Objetivo deste guia

Este documento existe para permitir que outra IA continue o ramo **LP / Site** da WeeeMob sem perder contexto, sem reabrir decisões já tomadas e sem desalinhar UX, copy, growth e estrutura do produto.

A IA que receber este guia deve tratar este ramo como **site público de conversão**, focado em:
- aquisição de usuários;
- aquisição de parceiros;
- páginas institucionais e legais;
- landing pages de campanha;
- encaminhamento para app, portal do parceiro e painel operador.

---

## 2. Premissas congeladas

### 2.1 Modelo do negócio
- WeeeMob é uma plataforma operadora de marketplace.
- Não é franquia.
- O parceiro/prestador oferta e executa o serviço.
- O usuário final contrata pela plataforma.

### 2.2 Categorias principais
- Estética
- Mecânica
- Estacionamento

### 2.3 Frentes do ecossistema
- LP / Site
- App do Usuário
- Portal do Parceiro
- Painel Operador

### 2.4 Função da LP / Site
A LP/Site:
- explica;
- converte;
- direciona.

Ela **não**:
- substitui o app;
- substitui o portal;
- substitui o backoffice.

### 2.5 Direção de UX
A LP deve priorizar:
- hero claro;
- CTA forte;
- blocos escaneáveis;
- pouco ruído;
- navegação rasa;
- mobile-first;
- foco em conversão.

---

## 3. O que esta IA deve preservar obrigatoriamente

A IA deve preservar estes pontos:

1. separar claramente o público usuário e o público parceiro;
2. manter as 3 categorias principais como núcleo do site;
3. manter a LP orientada à conversão, e não só “institucional”;
4. manter navegação rasa;
5. manter CTA forte;
6. tratar download do app e captação de parceiro como dois caminhos principais;
7. manter páginas legais mínimas;
8. manter o site preparado para growth, SEO e campanhas.

---

## 4. O que a IA NÃO deve fazer

A IA não deve:
- reabrir o modelo de negócio como franquia;
- tratar o parceiro como “franqueado”;
- transformar o site em blog genérico;
- criar navegação complexa cedo demais;
- escrever copy excessivamente técnica;
- esconder o CTA principal;
- criar páginas sem objetivo claro;
- fazer a LP parecer um painel administrativo;
- duplicar mensagens conflitantes entre usuário e parceiro.

---

## 5. Entregáveis esperados deste ramo

A IA deve trabalhar para produzir:

- sitemap do site
- arquitetura de páginas
- blocos por página
- copy por seção
- wireframes lógicos
- CTA por público
- páginas legais mínimas
- landing pages de campanha
- tracking plan
- backlog por página
- critérios de aceite por página

---

## 6. Ordem de trabalho recomendada

### Etapa 1 — Arquitetura
1. definir sitemap
2. definir objetivo de cada página
3. definir público principal de cada página
4. definir CTA principal de cada página

### Etapa 2 — Conteúdo
1. headline
2. subheadline
3. benefícios
4. objeções
5. FAQ
6. prova social
7. CTA final

### Etapa 3 — UX/UI
1. wireframe lógico
2. hierarquia visual
3. ordem dos blocos
4. regras mobile-first
5. consistência de componentes

### Etapa 4 — Growth
1. LPs de campanha
2. SEO base
3. UTMs
4. eventos de tracking
5. funis

### Etapa 5 — Operacionalização
1. backlog por página
2. critérios de aceite
3. dependências
4. handoff para frontend/marketing

---

## 7. Estrutura recomendada de specs

A IA deve organizar o trabalho usando este padrão:

### `specs/product/10-lp-site.md`
Documento executivo do ramo.

### `specs/ui/lp-site/`
- `sitemap.md`
- `home.md`
- `como-funciona.md`
- `categorias.md`
- `para-parceiros.md`
- `faq.md`
- `download-app.md`
- `paginas-legais.md`
- `campanhas.md`

### `specs/acceptance/lp-site/`
- `home.acceptance.md`
- `parceiros.acceptance.md`
- `campanhas.acceptance.md`

### `specs/growth/lp-site/`
- `tracking-plan.md`
- `seo-base.md`
- `utm-structure.md`

---

## 8. Template obrigatório por página

Toda página deve ser especificada com a seguinte estrutura:

```md
# Nome da página

## Objetivo
O que a página precisa converter ou esclarecer.

## Público principal
Quem é o público principal da página.

## CTA principal
Qual ação queremos que a pessoa execute.

## CTA secundário
Qual ação de fallback é aceitável.

## Blocos
1. Hero
2. Benefícios
3. Como funciona
4. Prova social
5. FAQ
6. CTA final

## Regras de UX
- hierarquia visual
- rolagem
- responsividade
- elementos obrigatórios

## Regras de conteúdo
- headline
- subtítulo
- bullets/cards
- FAQ
- prova

## Tracking
- eventos
- parâmetros
- origem/UTM

## Critérios de aceite
- checklist objetivo
```

---

## 9. Template obrigatório de CTA

Toda especificação de CTA deve responder:

- quem clica?
- em que contexto?
- para onde vai?
- qual resultado esperado?
- como medir sucesso?

Exemplo:

```md
## CTA principal
Baixar app

### Público
Usuário final

### Destino
Página da store ou deep link controlado

### Evento
click_download_app

### Métrica de sucesso
CTR do hero e taxa de clique por dispositivo
```

---

## 10. Template obrigatório de copy

Toda página deve ter copy especificada em camadas:

```md
## Headline
Frase curta e direta.

## Subheadline
Explica a promessa em 1 ou 2 linhas.

## Blocos de benefício
3 a 6 pontos escaneáveis.

## Objeções
Perguntas ou medos que a página resolve.

## CTA
Texto do botão e motivação.
```

Regras:
- headlines curtas;
- subheadlines curtas;
- sem jargão desnecessário;
- linguagem comercial;
- valor antes de detalhe técnico.

---

## 11. Regras de UX que a IA deve obedecer

### 11.1 Estrutura
- uma intenção principal por página;
- hero sempre acima da dobra;
- CTA principal acima da dobra;
- poucos caminhos simultâneos.

### 11.2 Visual
- cards fortes;
- pouco texto corrido;
- tipografia hierárquica;
- espaçamento generoso;
- mobile-first.

### 11.3 Conversão
- CTA repetido em pontos estratégicos;
- FAQ perto do fechamento;
- prova social antes do CTA final;
- sem excesso de etapas.

---

## 12. Regras de growth que a IA deve obedecer

### 12.1 Tracking mínimo
- click_download_app
- click_become_partner
- click_login
- submit_partner_form
- click_faq
- scroll_depth
- click_contact

### 12.2 SEO mínimo
- title
- description
- heading hierarchy
- urls limpas
- páginas de categoria
- páginas de campanha
- conteúdo local/categórico

### 12.3 Campanhas
Toda LP de campanha precisa ter:
- público claro;
- um objetivo;
- um CTA principal;
- mensagem coerente com a origem;
- tags de tracking.

---

## 13. Regras de consistência com o produto

A IA deve manter coerência com o resto do projeto:

- categorias do site precisam bater com categorias do app;
- proposta ao parceiro precisa bater com o Portal do Parceiro;
- claims de operação precisam bater com o modelo real do marketplace;
- páginas legais precisam bater com o ramo jurídico;
- CTAs precisam encaminhar para as frentes corretas do produto.

---

## 14. Dependências que a IA deve considerar

Antes de especificar demais, a IA deve sempre considerar dependência com:

- modelo operacional
- legal/jurídico/contratual
- regras de negócio
- app do usuário
- portal do parceiro
- marketing e comercial

Se houver conflito entre LP e operação real, a operação real vence.

---

## 15. Definition of Done (DoD)

Este ramo só pode ser considerado pronto quando existir:

1. sitemap completo;
2. páginas principais definidas;
3. objetivo e CTA de cada página definidos;
4. copy framework básico definido;
5. wireframes lógicos definidos;
6. LPs de campanha prioritárias definidas;
7. páginas legais mínimas definidas;
8. tracking plan definido;
9. backlog por página definido;
10. critérios de aceite por página definidos.

---

## 16. Checklist de coerência para a IA

Antes de finalizar qualquer entrega, a IA deve validar:

- isso converte ou só informa?
- o público principal está claro?
- o CTA principal está claro?
- o site está separando bem usuário e parceiro?
- o texto está comercial e curto?
- a página está mobile-first?
- a estrutura está escaneável?
- a mensagem bate com o produto real?
- a página tem objetivo único?
- os critérios de aceite estão objetivos?

---

## 17. Prompt-base para continuar este ramo em outro chat

```text
Você está continuando o ramo LP / Site da WeeeMob.

Premissas congeladas:
- WeeeMob é uma plataforma operadora de marketplace.
- Não é franquia.
- As categorias principais são Estética, Mecânica e Estacionamento.
- A LP / Site existe para captar usuários e parceiros, explicar o produto, direcionar para download do app, login e cadastro de parceiro.
- A UX precisa ser limpa, direta, mobile-first, com hero forte, CTA forte, blocos escaneáveis e foco em conversão.

Seu trabalho agora é produzir artefatos de Spec-Driven Development para LP / Site, sem reabrir decisões congeladas.

Entregue sempre:
1. objetivo da página
2. público principal
3. CTA principal
4. blocos da página
5. regras de UX
6. regras de conteúdo
7. tracking
8. critérios de aceite

Comece por:
- sitemap completo
- home
- para parceiros
- categorias
- FAQ
- páginas legais
- LPs de campanha prioritárias
```

---

## 18. Backlog inicial recomendado

### Prioridade 1
- home
- como funciona
- categorias
- para parceiros
- download do app
- login/acessos

### Prioridade 2
- FAQ
- páginas legais
- contato/comercial

### Prioridade 3
- LP de estética
- LP de mecânica
- LP de estacionamento
- LP de parceiro por categoria/região

### Prioridade 4
- otimização SEO
- otimização de tracking
- testes A/B futuros
- variações de campanha

---

## 19. Dicionário de termos técnicos

**SDD**: desenvolvimento guiado por especificação antes da implementação.  
**LP**: landing page focada em conversão.  
**Hero**: bloco principal acima da dobra.  
**CTA**: chamada principal para ação.  
**Sitemap**: mapa de páginas e navegação.  
**Copy**: texto persuasivo/comercial da página.  
**Tracking**: medição de eventos e comportamento.  
**UTM**: parâmetro de rastreamento de campanha.  
**DoD (Definition of Done)**: definição objetiva de pronto.  
**Wireframe lógico**: estrutura funcional da página, sem depender de layout final.
