# Desafio 2

## Introdução

Em sistemas *real time* é comuns APIs REST fornecer dados para serem lidos e monitorados por outros sistemas.  
Por meio do *Spark Streaming Reader* o spark permite a captura ou leitura de informações desses sistemas de streaming.  

## Objetivo

O obejtivo deste desafio é construir um programa / notebook que obtenha dados da API do Twitter que contenham as hashtags dos candidatos a presidente do Brasil usando o *Spark Streaming Reader*.  

### Notas

1. Salve os dados no formato `parquet`.
2. Realize uma consulta presquisando qual a 'hashtags' mais usadas em um determinado período de tempo.
