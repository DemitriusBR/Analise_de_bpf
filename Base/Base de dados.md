# Análise de BPF - Banco de Dados Fictício

Este repositório contém um banco de dados fictício relacionado à auditoria de BPF (Boas Práticas de Fabricação). Os dados aqui apresentados não são reais e foram criados apenas para fins de demonstração e análise. O banco de dados é composto por informações de auditorias realizadas em diversas áreas de uma empresa fictícia, com registros de resultados de auditoria em diferentes turnos de trabalho. O arquivo esta no formato .xlsx

## Estrutura do Banco de Dados

O banco de dados possui 341 linhas de dados, cada uma representando uma auditoria realizada. Cada linha contém informações sobre a auditoria, incluindo a data, o nome do auditor, a área auditada, o turno de trabalho, os resultados da auditoria, o motivo de falhas (caso existam) e o mês da auditoria.

### Colunas:

- **Data da Auditoria**: Data em que a auditoria foi realizada (formato: DD/MM/AAAA).
- **Nome**: Nome do auditor responsável pela auditoria.
- **Área**: Área auditada na organização (exemplo: Manutenção, Laboratório, etc.).
- **Turno**: Turno em que a auditoria foi realizada (exemplo: Noite, Dia, etc.).
- **Resultados**: Resultado da auditoria (OK ou NOK).
- **Motivo**: Motivo da falha, caso o resultado seja NOK (exemplo: Unha e barba grandes, etc.).
- **Mês**: Mês de realização da auditoria (abreviado, exemplo: jan, fev, mar).

### Exemplo de Dados

| Data da Auditoria | Nome          | Área         | Turno | Resultados | Motivo                | Mês |
|-------------------|---------------|--------------|-------|------------|-----------------------|-----|
| 23/01/2025        | Ana Silva     | Manutenção   | Noite | NOK        | Unha e barba grandes  | jan |
| 23/01/2025        | Carlos Souza  | Laboratório  | Noite | OK         | NA                    | jan |
| 23/01/2025        | José Oliveira | Laboratório  | Noite | OK         | NA                    | jan |

## Objetivo

O objetivo deste repositório é demonstrar a estrutura de um banco de dados fictício que pode ser utilizado para realizar análises relacionadas à BPF (Boas Práticas de Fabricação). As auditorias podem ser analisadas para detectar padrões de falhas, identificar áreas com maiores ocorrências de não conformidades e otimizar processos de auditoria.

## Como Usar

Para utilizar este banco de dados em suas análises, basta importar o arquivo de dados no formato CSV (ou outro formato, conforme necessário) para a ferramenta de sua escolha, como Python, R ou Excel, e começar a explorar as informações.
