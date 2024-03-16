# Projeto Estatística I - Vem Ser Tech Ada & Ifood

## Trabalho Realizado por
- [Mariana Franz](https://github.com/framzz)

## Objetivo
Este projeto tem como objetivo colocar em prática os conhecimentos adquiridos durante o módulo de Estatística I da formação Vem Ser Tech | Dados.

A partir de um conjunto de dados (escolhido por você ou por sugestão do professor), o objetivo será desenvolver uma análise exploratória dos dados.

### Pontos a serem entregues:

- __Definição do Conjunto de Dados:__ Determinar qual conjunto de dados deve ser analisado e se o conjunto de dados atende as espectativas para o projeto;

- __Análise de Consistência dos Dados__: Verificar se o conjunto de dados tem algum eventual problema (podendo ser dados faltantes, dados erroneos entre outros casos);


- __Análise Exploratória dos Dados__: Consiste em estudar o conjunto de dados! Então seria entender quais tipos de informações que pode-se obter, quais conclusões e/ou interpretações pode-se tirar dos dados (neste caso, gráfico para auxiliar nas análises são bem vindos).

## Diretório do Projeto

```bash
├── data
│   └── imdb_data.csv
├── processed_data
│   └── imdb_processed_data.csv
├── analysis.py
├── etl.py
├── README.md
```

## Sobre o Projeto - Dados IMDB

O dataset utilizado é uma parte reduzida de uma junção de datasets de filmes e ratings dos mesmos. Ele contém várias colunas que trazem dados importantes sobre cada filme, e, a partir delas analisaremos o que podemos extrair de informação a partir desses registros. O dataset contém duas mil linhas com vários registros sobre diferentes títulos. 

Para acompanhar o projeto melhor, começe pela parte de extração, limpeza e transformação dos dados (ETL), que se encontra no script etl.ipynb. Depois, siga para a parte de análise, que está dentro do script analysis.ipynb.

Esse projeto ainda será aprimorado no futuro, onde tudo ocorrerá seguindo melhores táticas de engenharia de dados e POO.