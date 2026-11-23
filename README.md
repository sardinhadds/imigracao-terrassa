Análise da Imigração em Terrassa – Espanha 🇪🇸

📌 Sobre o projeto

Este projeto consiste numa análise exploratória de dados públicos sobre a imigração no município de Terrassa, Espanha.

O objetivo é analisar a evolução temporal dos registos de imigração e identificar os principais países e províncias de procedência, procurando compreender como esses padrões se alteraram ao longo dos anos.

🎯 Objetivos da análise

Comparar os registos de procedência espanhola com os de outros países.

Analisar a evolução temporal da imigração.

Identificar os 10 países estrangeiros com maior número de registos.

Identificar as 10 províncias espanholas com maior número de registos.

Comparar a evolução temporal das principais origens de imigração.

📂 Fonte dos dados

Os dados foram obtidos através do portal europeu de dados abertos:

Dataset: Immigracions per mes, lloc de procedència i sexe

Localização: Terrassa, Espanha

Fonte: European Data Portal

Data de acesso: Novembro de 2026

🛠️ Tecnologias utilizadas

Python 3.13.9

Pandas: exploração, tratamento e manipulação dos dados.

Matplotlib: criação de visualizações.

Seaborn: construção de gráficos estatísticos.

Jupyter Notebook: desenvolvimento e documentação da análise.

⚙️ Etapas do projeto

1. Exploração e preparação dos dados

Importação do ficheiro CSV.

Verificação da estrutura e dos tipos de dados.

Padronização dos nomes das colunas.

Criação de uma variável temporal (data), combinando ano e mês.

Separação dos registos entre procedência espanhola e procedência estrangeira.

2. Análise da origem dos registos

Criação de um gráfico circular (Pie Chart) para comparar a proporção dos registos de procedência espanhola com os de outros países.

3. Evolução temporal

Utilização de um gráfico de linhas para comparar a evolução dos registos de procedência espanhola e estrangeira ao longo do período analisado.

4. Principais países e províncias

Identificação e visualização dos dez principais países estrangeiros e das dez principais províncias espanholas de procedência, através de gráficos de barras.

5. Comparação temporal por origem

Criação de gráficos de barras agrupadas para acompanhar a evolução temporal dos dez principais países estrangeiros e das dez principais províncias espanholas.

📊 Principais conclusões

A análise permitiu identificar alguns padrões interessantes:

A procedência espanhola e a estrangeira apresentam volumes de registos relativamente próximos em parte do período analisado.

A partir de 2016, observa-se um crescimento da participação dos registos de procedência estrangeira.

Durante o período das restrições associadas à pandemia de COVID-19, os volumes voltaram a aproximar-se.

A partir de 2022, os registos de procedência estrangeira voltaram a apresentar crescimento.

Marrocos destaca-se como o país estrangeiro com maior número de registos.

Entre os dez principais países estrangeiros, sete são países latino-americanos.

Entre as províncias espanholas, Girona ocupa a primeira posição, seguida de Barcelona e Tarragona.

⚠️ Considerações metodológicas

As contagens apresentadas nos gráficos foram calculadas através dos métodos count() e groupby().size() do Pandas.

Consequentemente, os resultados representam a quantidade de registos por categoria, e não necessariamente o número de indivíduos.

A variável POBLACIO está presente na fonte original, mas não foi utilizada nesta análise.


👨‍💻 Autor

Projeto desenvolvido como parte do meu percurso de aprendizagem em Análise de Dados, com foco na exploração, tratamento e visualização de dados públicos.

