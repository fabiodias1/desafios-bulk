# Desafio 3 - Pratica Shell Linux

## Introdução

O Linux é um sistema muito usado em TI. Muitas organizações possuem sistemas baseados em Linux.  
Na engenharia de dados ele é usado para automatizar processos, criar fluxos de dados, ...


## Desafio

Desenvolver um shell script:
1. Baixe base de dados do enem 2020;
2. Gere um arquivo de saída mostrando:
  A. O total de provas realizadas ou que deveriam ter sido realizadas em uma cidade ( O quadro I tem algumas sugestões);
  B. A Média da nota Línguaguem e suas tecnologias.

### Quadro I

|Cdiade|UF|
|------|---|
|Rio Branco|AC|
|Sorocaba|SP|
|Manaus|AM

### Observações

1. Em caso de overflow no cálculo, escolha uma cidade menor
2. Pode-se usar o Python e/ou Spark para obter uma "prova real", mas será considerado apenas como resposta para o desafio um shell script que:   
 A) Faça o downlaod da base;  
 B) Leia a base;  
 C) Coloque em arquivo de saída o total de provas e média de notas.  
3. Pode-se criar quaisquer arquivos intermediários, mas no fim do script, só deverá existir na pasta de trabalho:
 * o arquivo do shell script.
 * o arquivo de texto com a saída desejada.
 * o arquivo da base de origem.
4. Na pasta do desafio há um notebook que explica alguns comandos e conceitos básicos do Linux.
5. É recomendável usar cidades menos populosas para evitar problema de overflow.
6. É permitido separar em um arquivo de entrada uma determianda cidade, mas no shell script final, mesmo que comentado, deve estar o código que gerou a base com 1 cidade. 
7. Pode-se usar um repositório público do Github para compartilhar a solução.
8. Pelas diretrizes do MEC, não é permitido usar a base para criar "ranks".

## Links

* Base de dados
*![https://download.inep.gov.br/microdados/microdados_enem_2020.zip](https://download.inep.gov.br/microdados/microdados_enem_2020.zip)

## Dicas

* Pesquise por awk
