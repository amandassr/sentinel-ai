
# Análise Documental — Sentinel AI

## 1. Objetivo

Desenvolver um módulo capaz de receber documentos e extrair informações relevantes para apoiar processos de KYC/KYB.

A proposta é reduzir a conferência manual repetitiva e facilitar a identificação de divergências entre documentos e informações declaradas.

## 2. Formatos previstos

- PDF.
- DOCX.
- XLSX.
- JPG e JPEG.
- PNG.

## 3. Fluxo de processamento

1. Recebimento do documento por upload.
2. Identificação do formato e validação do arquivo.
3. Extração de texto e informações.
4. Aplicação de OCR para documentos digitalizados e imagens.
5. Organização dos dados extraídos.
6. Comparação com informações cadastrais e financeiras.
7. Identificação de divergências e campos ausentes.
8. Apresentação dos resultados para revisão humana.

## 4. Informações que poderão ser extraídas

- Razão social e nome fantasia.
- CNPJ e dados cadastrais.
- Endereço.
- Representantes legais.
- Datas de emissão e validade.
- Informações financeiras.
- Valores e movimentações.
- Dados relevantes para a atividade econômica.

## 5. Validação documental

O sistema deverá avaliar:

- Legibilidade do documento.
- Presença das informações esperadas.
- Coerência entre os campos extraídos.
- Divergências em relação aos dados informados.
- Ausência de informações necessárias.
- Indícios de documento incompleto ou inconsistente.

A extração de informações não significa autenticação do documento.

## 6. Comparação entre fontes

Sempre que possível, as informações extraídas deverão ser comparadas com:

- Dados cadastrais informados.
- Briefing comercial.
- Informações financeiras declaradas.
- Outros documentos apresentados.
- Resultados de pesquisas disponíveis.

## 7. Resultado do processamento

Cada documento deverá receber um status:

- Processado.
- Processado com ressalvas.
- Ilegível.
- Incompleto.
- Inconsistente.
- Não processado.

O sistema deverá apresentar os dados extraídos, a origem da informação e as limitações encontradas.

## 8. Segurança e privacidade

- Utilizar dados fictícios nos testes públicos.
- Evitar armazenamento desnecessário de documentos.
- Proteger informações pessoais e financeiras.
- Não publicar documentos reais no repositório.
- Não registrar credenciais ou informações confidenciais em logs.

## 9. Status de desenvolvimento

**Planejado — não implementado na versão 0.1.0.**

A leitura de documentos, o OCR, a comparação automatizada e a integração com inteligência artificial serão desenvolvidos em etapas futuras.
