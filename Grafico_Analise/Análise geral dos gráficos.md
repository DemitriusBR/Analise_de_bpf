# Análise Geral

# Cards

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

# Tabela

### Tabela (MATRIZ)
A tabela apresenta os motivos pelas **não conformidades** diferenciadas por **turno**, permitindo a visualização dos motivos de falhas durante as auditorias. Além disso, há a possibilidade de expandir a pesquisa para incluir o **setor** e o **nome do funcionário**, proporcionando uma análise mais detalhada e específica.

Essa matriz é útil para identificar padrões de falhas nos diferentes turnos, além de oferecer uma visão mais aprofundada das áreas ou funcionários com maior índice de não conformidade.

![image](https://github.com/user-attachments/assets/75cc8067-c84b-4ac5-b77d-c1edc4d0c211)

# Gráfico de Barras

### Verificação de Quantidade de Análises por Turno e Quantidade de Inconformidade

O gráfico de barras apresenta a **quantidade de auditorias realizadas por turno** em um período pré-definido pelos filtros. Além disso, permitindo uma visualização clara de quais turnos possuem maior índice de falhas.

Em resumo esse gráfico facilita a identificação visual dos turnos com maior índice de não conformidades, ajudando a entender onde estão sendo realizadas mais auditorias e quais turnos precisam de mais atenção para melhorar a conformidade.

![image](https://github.com/user-attachments/assets/c1cbe83a-b483-4ccb-ae32-149fd26344d0)

# Gráfico de Rosca e Card

### Combinação de Gráfico de Rosca e Card

Essa combinação de visualizações é bastante útil para destacar os **setores com maior índice de inconformidade** durante o período selecionado. O **gráfico de rosca** apresenta os setores com maior número de não conformidades, facilitando a visualização de quais áreas precisam de mais atenção e foco nas auditorias.

O **card** complementa o gráfico ao apresentar a quantidade total de **inconsistências** registradas no período, oferecendo uma visão quantificável do número de falhas.

Essa combinação permite uma análise rápida tanto visual quanto quantitativa dos setores que necessitam de melhorias.

![image](https://github.com/user-attachments/assets/7a6dd527-d36f-446a-8bcc-7d522bfc38a1)

