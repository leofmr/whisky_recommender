# whisky_recommender
Recomendações de whisky single malt

## Sobre

Esse projeto é baseado nos dados trabalhados no artigo: Lapointe, F.-J. & P. Legendre. 1994. A classification of pure malt Scotch whiskies. Applied Statistics 43: 237-257.

Os dados foram obtidos no site:
http://adn.biol.umontreal.ca/~numericalecology/data/scotch.html


## Objetivo

O objetivo desse projeto é o desenvolvimento de um sistema de recomendação de whiskeys baseados na semelhança entre os atributos das bebidas.
A recomendação poderá ser realizada de duas formas:
 - através da informação de um whiskey (destilaria) de referência.
 - através da informação de atributos de referência.

Com base nessas informações o sistema de recomendação deverá retornar uma lista de whiskey com os atributos mais próximos dos informados.

Dependendo do resultado do sistema de recomendação, uma interface gráfica pode vir a ser desenvolvida para operacionalizar o sitema de recomendação.

## Dependências

O projeto foi desenvolvido em Python 3.9 com as seguintes bibliotecas sendo utilizadas:
  - pandas
  - scikit-learn

O ambiente de desenvolvimento através da utilização da biblioteca de gestão de bibliotecas e ambientes virutais `pipenv`. Para montar o ambiente virtual basta executar o comando `pipenv install` na pasta onde o arquivo `Pipfile` está localizado (raiz do projeto).