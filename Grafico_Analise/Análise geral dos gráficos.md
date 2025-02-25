# Análise Geral

## Cards

### 1. **Quantidade Total de Pessoas Analisadas**
O primeiro card exibe a quantidade total de pessoas auditadas durante o período de tempo selecionado. Esse número é filtrado com base nas datas selecionadas e reflete o total de registros de auditoria no período.


### 2. **Porcentagem de Conformidade**
O segundo card apresenta a porcentagem de conformidade no período de tempo determinado. A conformidade é calculada com base no número de auditorias que resultaram em OK (conforme os requisitos) em relação ao total de auditorias realizadas.

#### Fórmula de Cálculo:

```DAX
Medida = 100 - DIVIDE(
    COUNTAX(FILTER('Auditoria', Auditoria[ID - RESULTADO.Índice] = 1), 0),
    COUNTA('Auditoria'[Resultados])
) * 100
```

![image](https://github.com/user-attachments/assets/2f91f08c-3f90-4b6e-8138-ebc7b7714951)

## Tabela

### Tabela (MATRIZ)
A tabela apresenta os motivos pelas **não conformidades** diferenciadas por **turno**, permitindo a visualização dos motivos de falhas durante as auditorias. Além disso, há a possibilidade de expandir a pesquisa para incluir o **setor** e o **nome do funcionário**, proporcionando uma análise mais detalhada e específica.

Essa matriz é útil para identificar padrões de falhas nos diferentes turnos, além de oferecer uma visão mais aprofundada das áreas ou funcionários com maior índice de não conformidade.

![image](https://github.com/user-attachments/assets/75cc8067-c84b-4ac5-b77d-c1edc4d0c211)
