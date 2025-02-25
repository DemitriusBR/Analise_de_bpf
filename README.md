# Projeto de Análise de BPF - Boas Práticas de Fabricação

## O que é BPF?

BPF (Boas Práticas de Fabricação) refere-se a um conjunto de diretrizes e práticas adotadas pelas indústrias, especialmente nas áreas de farmacêutica, alimentícia e cosméticos, para garantir que os produtos sejam fabricados de maneira consistente, segura e com qualidade. A implementação de BPF é fundamental para prevenir erros e contaminações nos processos produtivos, garantindo que os produtos atendam aos padrões estabelecidos pelas autoridades regulatórias.

## A Importância da Análise de BPF

A análise de BPF tem como objetivo identificar possíveis falhas iregulariadas na vestimenta dos colobaradores, melhorar a eficiência operacional e garantir que todos os procedimentos sigam as normas estabelecidas. Através da auditoria e avaliação contínua das práticas adotadas, é possível detectar não conformidades, posiveis causas de contaminação do produto e promover a segurança tanto dos produtos quanto dos trabalhadores.

## Estrutura do Repositório

Este repositório foi desenvolvido para apresentar uma análise de BPF com base em um banco de dados fictício de auditorias realizadas em uma organização. A estrutura do repositório é organizada da seguinte forma:


- **Base**: Contém os dados brutos da análise, incluindo o banco de dados fictício e as especificações do banco. Este banco de dados serve como base para realizar a auditoria e análise de BPF.
    - **banco_de_dados**: Arquivo no formato EXCEL contendo os dados das auditorias de BPF, como Data da Auditoria, Nome do Auditor, Área Auditada, Turno, Resultados, Motivos e Mês.
    - **especificações**: Documento explicando as características e estrutura do banco de dados, como a descrição de cada coluna e o significado dos dados.

- **Grafico_Analise**: Contém a parte visual do projeto, com gráficos e o arquivo Power BI.
    - **Graficos/**: Imagens ou relatórios gerados a partir da análise dos dados. Contém visualizações como gráficos de barras, pizza, cards e outros.
    - **Projeto_PowerBI.pbix**: Arquivo do projeto Power BI com a análise dos dados. Esse arquivo pode ser aberto no Power BI Desktop para explorar a visualização de dados.

## Como Usar

1. **Banco de Dados**: O arquivo EXCEL no diretório `Base/` pode ser utilizado para realizar análises de auditoria usando a ferramenta de sua escolha (por exemplo, Python, Excel, Power bi etc.).
2. **Análises Visuais**: O arquivo `.pbix` contido em `Grafico_Analise/` pode ser aberto e visualizado com o Power BI. Ele contém as visualizações e gráficos baseados nas auditorias de BPF.
3. **Exploração de Dados**: Ao abrir o Power BI ou qualquer outra ferramenta de análise, você pode personalizar os gráficos ou realizar novas análises sobre os dados de auditoria.

## Contribuições

Este repositório é aberto para contribuições. Se você deseja colaborar ou melhorar a análise de BPF, fique à vontade para criar uma **issue** ou um **pull request**.

## Licença

Este repositório é destinado a fins educacionais e demonstrativos. Os dados apresentados são fictícios e não têm qualquer vínculo com entidades ou empresas reais.
