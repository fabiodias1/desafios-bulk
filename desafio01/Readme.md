# Logs do centro espacial Kennedy da NASA

## Introdução

É comum muitos processos em organzações gerar arquivos de texto simples sobre a execução desses processos. Esses arquivos são conhecidos como arquivos de logs ou apenas logs.  
Os logs são usados para fins de monitoramento e manutenção e de sistemas. 
Um exemplo é os logs com os dados de requisições HTTP do centro espacial Kennedy da NASA.  
Com o passar do tempo um sistema podem gerar muitos arquivos de logs, tantos arquivos que ferramentas de Big Data podem ser usada para auxiliar na extração de inforamções importantes desses arquivos.  

## Dessafio 

### Etapa 1

Usar o Spark para desenvolver uma solução que processe os arquivos de logs nos links abaixo para responder as seguintes perguntas:

1) Número de hosts únicos?
2) O total de erros 404?
3) Os 5 URLs que mais causaram erro 404?
4) Quantidade de erros 404 por dia?
5) O total de bytes retornado?

Questões Bônus:

A) Média de requisições por dia?
B) Qual os 5 hosts que mais fizeram requisições?

### Etapa 2

Explicar/Apresentar a solução desenvolvida.  

### Urls com as bases de dados [Dataset]

- [https://github.com/fabiodias1/desafios-bulk/desafio1/data/blob/master/NASA_access_log_Aug95.gz](https://github.com/fabiodias1/desafios-bulk/desafio1/data/blob/master/NASA_access_log_Aug95.gz)
- [https://github.com/fabiodias1/desafios-bulk/desafio1/data/blob/master/NASA_access_log_Jul95.gz](https://github.com/fabiodias1/desafios-bulk/desafio1/data/blob/master/NASA_access_log_Jul95.gz)

##  Fonte original do dataset

[http://ita.ee.lbl.gov/html/contrib/NASA-HTTP.html](http://ita.ee.lbl.gov/html/contrib/NASA-HTTP.html)

## Dicas

Pesquisar expressão regular, conhecida como regexp.  
Pesquisar por **formatos de compactação** de arquivos no shell no linux.
