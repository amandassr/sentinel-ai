
# Dicionário de Dados — Sentinel AI

## 1. Objetivo

Definir os principais campos utilizados pelo Sentinel AI para organizar informações cadastrais, operacionais, financeiras e evidências de uma análise KYC/KYB.

## 2. Identificação da empresa

| Campo | Descrição |
|---|---|
| case_id | Identificador único da análise |
| company_name | Nome empresarial |
| trade_name | Nome fantasia |
| tax_id | Identificador fiscal, mascarado nos exemplos públicos |
| legal_nature | Natureza jurídica |
| business_activity | Atividade econômica declarada |
| company_size | Porte empresarial |
| registration_status | Situação cadastral |

## 3. Informações operacionais

| Campo | Descrição |
|---|---|
| business_model | Modelo de negócio |
| sales_channels | Canais de venda |
| average_ticket | Ticket médio declarado |
| projected_volume | Volume transacional projetado |
| payment_methods | Meios de pagamento utilizados |
| requested_products | Produtos e serviços solicitados |

## 4. Informações financeiras

| Campo | Descrição |
|---|---|
| declared_revenue | Faturamento declarado |
| proven_revenue | Faturamento comprovado |
| projected_volume | Volume financeiro projetado |
| financial_evidence | Evidências financeiras apresentadas |
| financial_capacity | Avaliação da capacidade de suportar perdas potenciais |

Valores não comprovados devem ser identificados como declarados, nunca apresentados como fatos confirmados.

## 5. Evidências

| Campo | Descrição |
|---|---|
| evidence_id | Identificador da evidência |
| evidence_type | Tipo de evidência |
| source | Origem da informação |
| description | Descrição objetiva |
| collection_date | Data de obtenção |
| verification_status | Situação da validação |

## 6. Pesquisas e Background Check

| Campo | Descrição |
|---|---|
| search_type | Tipo de pesquisa |
| searched_entity | Pessoa ou empresa pesquisada |
| result_status | Resultado da pesquisa |
| match_confidence | Grau de correspondência |
| case_context | Contexto de eventual registro |
| case_outcome | Andamento ou desfecho identificado |

Resultados possíveis: correspondência confirmada, possível correspondência, inconclusivo, sem ocorrência identificada ou pesquisa não realizada.

## 7. Indicadores de risco

| Campo | Descrição |
|---|---|
| risk_id | Identificador do indicador |
| risk_category | Categoria do risco |
| finding | Apontamento identificado |
| supporting_evidence | Evidência relacionada |
| impact | Impacto potencial |
| severity | Relevância do apontamento |
| review_status | Situação da revisão |

## 8. Parecer e revisão

| Campo | Descrição |
|---|---|
| risk_classification | Classificação proposta |
| analytical_justification | Fundamentação da análise |
| pending_items | Pendências identificadas |
| analyst_review | Situação da revisão humana |
| final_decision | Decisão registrada pelo responsável |
| rules_version | Versão das regras utilizadas |

## 9. Padronização dos dados

O Sentinel AI deverá distinguir:

- Informação declarada.
- Informação comprovada.
- Informação não localizada.
- Informação inconclusiva.
- Informação divergente.
- Informação pendente de validação.

## 10. Privacidade

Os dados utilizados nos exemplos públicos devem ser exclusivamente fictícios ou adequadamente anonimizados. Informações pessoais e documentos reais não devem ser publicados.
