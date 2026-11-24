
# Workflows — Sentinel AI

## 1. Objetivo

Esta pasta documentará os fluxos de automação planejados para o Sentinel AI.

Na versão 0.1.0, ainda não existem workflows funcionais implementados.

## 2. Primeiro fluxo planejado: sentinel-report-intake

O primeiro workflow deverá organizar o recebimento de informações para uma análise KYC.

### Etapas previstas

1. Receber os dados do caso.
2. Validar a estrutura das informações.
3. Identificar campos ausentes ou inconsistentes.
4. Carregar o template de relatório.
5. Consultar as regras de negócio versionadas.
6. Organizar evidências e indicadores de risco.
7. Utilizar IA para auxiliar na elaboração da minuta.
8. Validar a estrutura da resposta.
9. Encaminhar o resultado para revisão humana.

## 3. Controles obrigatórios

- Não inventar informações.
- Não transformar ausência de dados em evidência de fraude.
- Preservar a origem das informações.
- Registrar limitações da análise.
- Validar a saída antes de gerar o relatório.
- Manter a decisão final sob responsabilidade humana.

## 4. Status da implementação

| Componente | Status |
|---|---|
| Documentação do fluxo | Planejado |
| Recebimento automatizado | Futuro |
| Validação de dados | Futuro |
| Integração com IA | Futuro |
| Geração automatizada de relatório | Futuro |
| Revisão humana | Obrigatória no desenho |

## 5. Tecnologias em avaliação

- n8n para orquestração.
- JSON para troca de informações.
- Modelos de linguagem para análise assistida.
- JSON Schema para validação.

## 6. Segurança

Nenhuma credencial, chave de API ou dado real de cliente deverá ser incluído nos arquivos públicos ou nos exemplos do projeto.
