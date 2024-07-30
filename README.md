# Desafio Setor Aéreo
Projeto Final do Bootcamp Data Analytics 2024 desenvolvido pelas Squads Rita Levi-Montalcini e Margaret Hamilton

## Ficha técnica dos dados
- Fonte: Banco de dados WoMakers
- Recorte temporal: 2018-2022
- Recorte geográfico: EUA
- 62 colunas e 292.111 linhas
  - nome das companhias aéreas
  - datas, atrasos e cancelamentos de voos
  - origem e destino dos voos
  - informações sobre as aeronaves
  - tempo de voo, desvio de rotas e outras.


## Análise dos dados

### Análise de Companhias Aéreas

1 - Quais são as principais companhias aéreas que mais voaram durante cada ano? 

2 - A pandemia afetou a operação de alguma delas? De que forma?

3 - Quais as companhias que alteraram mais voos durante a pandemia?

4 - Quais as principais rotas aéreas das principais companhias?

5 - Qual é a companhia que tem maior % de cancelamento de voos e atraso? 

### Análise da eficiência das rotas.
1- Quais as principais rotas de voos? 

2- Quais as rotas em que temos maior tempo de atraso? 

3- Quais as rotas em que temos maior índice de cancelamento de voos?

4- Quais são as rotas mais eficientes e as menos eficientes?

### Análise do atraso das rotas
1- Qual o tempo médio de atraso dos voos? Considere as colunas ArrDelayMinutes e DepDelayMinutes.

2- Quais os fatores mais correlacionados com o atraso de um voo?

### Modelagem:
1)	Construa um modelo de regressão linear em que queremos estimar o tempo de atraso de um voo, considere o atraso da partida variável (DepDelayMinutes). Lembre-se de construir variáveis dummy a partir de categorias como: mês do ano e rotas específicas.   
