
# Arquitetura do Sentinel AI

## 1. Visão geral

O Sentinel AI é um projeto experimental de apoio às atividades de KYC/KYB e inteligência antifraude.

Sua proposta é organizar informações de empresas, identificar inconsistências, estruturar evidências e gerar minutas de relatórios para revisão de um analista.

## 2. Fluxo de funcionamento proposto

1. **Recebimento:** entrada das informações cadastrais, operacionais e financeiras.
2. **Validação:** verificação da estrutura e identificação de informações ausentes.
3. **Organização:** agrupamento de documentos, pesquisas e evidências.
4. **Análise:** aplicação de regras de negócio e apoio de inteligência artificial.
5. **Validação da saída:** conferência da consistência das informações geradas.
6. **Relatório:** elaboração de uma minuta KYC estruturada.
7. **Revisão humana:** avaliação final por um analista.

## 3. Componentes planejados

- Entrada e organização de dados.
- Base de conhecimento com regras de negócio versionadas.
- Análise de indicadores de risco.
- Organização de evidências e pesquisas.
- Geração de relatórios.
- Registro de pendências e revisão humana.

## 4. Princípios de funcionamento

- Não inventar informações ausentes.
- Diferenciar fatos, inferências, riscos e pendências.
- Fundamentar apontamentos em evidências.
- Registrar limitações das pesquisas realizadas.
- Manter rastreabilidade das informações utilizadas.
- Submeter conclusões à revisão humana.

## 5. Segurança e privacidade

O projeto utilizará exclusivamente dados fictícios nos exemplos públicos.

Não devem ser incluídos dados pessoais reais, documentos de clientes, credenciais ou informações internas de empresas.

## 6. Tecnologias em avaliação

- JSON para estruturação de dados.
- Modelos de linguagem (LLMs) para análise assistida.
- n8n para automação de workflows.
- JSON Schema para validação de estruturas.

Essas tecnologias são possibilidades para versões futuras, não integrações já implementadas.

## 7. Status

Versão atual: 0.1.0.

Esta etapa contempla a documentação e o desenho conceitual da solução. A implementação funcional será desenvolvida gradualmente.
