# Projeto Final do Bootcamp Data Analytics 2024


## Descrição do Projeto
Este projeto foi desenvolvido pelas **Rita Levi-Montalcini** e **Margaret Hamilton** como parte do **Bootcamp Data Analytics 2024**. O objetivo do projeto foi realizar uma apresentação em forma de pitch, abordando o desafio de melhorar a performance das companhias aéreas através de análises de dados.


## Desafio Proposto
1. Estudo do banco de dados e dicionário.
2. Análise de dados para melhorar a performance das companhias aéreas.
3. Análise exploratória das principais companhias aéreas, rotas eficientes e atrasos.
4. Geração de insights para otimização de rotas de voo.


## Tecnologias Utilizadas
- Python (código disponível [aqui](./final_project_Margaret_Hamilton_Rita_Levi.ipynb))

 

## Objetivos Alcançados
- **Estudo do banco de dados**: Compreensão e estruturação do banco de dados para a análise.
- **Análise de dados**: Utilização de técnicas de análise de dados para identificar áreas de melhoria.
- **Análise exploratória**: Investigação das principais companhias aéreas, rotas e atrasos para identificar padrões e tendências.
- **Geração de insights**: Propostas para otimização de rotas de voo baseadas nos insights obtidos.

Este projeto demonstra a aplicação prática das habilidades adquiridas durante o bootcamp, utilizando Python e suas bibliotecas para realizar análises de dados complexas e gerar insights valiosos para a indústria aérea.


## Apresentação do projeto
<div align="center">
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=V3s3uWntt5Y?si=vRzcn20jIuu4c4Az" target="_blank">
    <img src="https://github.com/user-attachments/assets/98f48d04-9de0-4dbc-94e4-1d6605966017" alt="Assista a apresentação" width="480" />
  </a>
</div>


## Slides do Projeto
Você pode também acessar os slides da apresentação [aqui](https://docs.google.com/presentation/d/1tmkdWD0qL2g4Ny_MUfW4YwXqNMOCCIgy/present).


## Ficha Técnica dos Dados

- Fonte: Banco de dados WoMakers
- Recorte temporal: 2018-2022
- Recorte geográfico: EUA
- 62 colunas e 292.111 linhas
- Nome das companhias aéreas
- Datas, atrasos e cancelamentos de voos
- Origem e destino dos voos
- Informações sobre as aeronaves
- Tempo de voo, desvio de rotas e outras.

## Análise dos Dados Proposto no Desafio

### Análise de Companhias Aéreas

1. Quais são as principais companhias aéreas que mais voaram durante cada ano?
2. A pandemia afetou a operação de alguma delas? De que forma?
3. Quais as companhias que alteraram mais voos durante a pandemia?
4. Quais as principais rotas aéreas das principais companhias?
5. Qual é a companhia que tem maior % de cancelamento de voos e atraso?

### Análise da Eficiência das Rotas

1. Quais as principais rotas de voos?
2. Quais as rotas em que temos maior tempo de atraso?
3. Quais as rotas em que temos maior índice de cancelamento de voos?
4. Quais são as rotas mais eficientes e as menos eficientes?

### Análise do Atraso das Rotas

1. Qual o tempo médio de atraso dos voos? Considere as colunas ArrDelayMinutes e DepDelayMinutes.
2. Quais os fatores mais correlacionados com o atraso de um voo?

### Modelagem

1. Construa um modelo de regressão linear em que queremos estimar o tempo de atraso de um voo, considere o atraso da partida variável (DepDelayMinutes). Lembre-se de construir variáveis dummy a partir de categorias como: mês do ano e rotas específicas.


