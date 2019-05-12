+++
title = "Análise de Dados - Aula 02"
subtitle = "Curso de Extensão - Feagri 2019"
date = 2019-05-01T09:32:50-03:00
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
## Homework

1. Baixe os dados em https://transfer.sh/ElXkS/adult_data.csv

2. Importe os dados no Rstudio

3. Envie as respostas pelo [formulário](https://forms.gle/UQxbW6csWnfFWMw69)

## Arquivos da aula

O notebook da aula pode ser baixado [neste link](https://kyso.io/mferrac/analise-de-dados-02-manipulacao-de-dados)

Os arquivos da aula podem ser baixados [neste link](http://bit.ly/feagri_analise_dados_aula02).

## Instalação do Jupyter com R

Para instalar o Jupyter notebook no windows, primeiro é preciso instalar o anaconda no link:

https://www.anaconda.com/distribution/

Selecione "windows" e clique em `Download` abaixo de `Python 3.7 Version`.

Em seguida, execute o arquivo `Anaconda3-2019.03-Windows-x86_64.exe` e siga as instruções de instalação.

Após instalar, procure `Anaconda Prompt` na pesquisa do Windows e execute o programa.

No terminal aberto, digite o comando:

```
conda install -c r r-irkernel
```

## Básicos de R com `swirl`

Para instalar o pacote `swirl`, basta executar o comando abaixo. Este comando instala o pacote na sua máquina. As aspas são obrigatórias. Uma vez instalado, não precisa executar de novo.

```{r}
install.packages('swirl')
```

Para carregar o pacote, use `library(swirl)` ou `library('swirl')`. Este comando ativa o pacote na sessão aberta do R e deve ser executado sempre que se reinicia o programa. As aspas são opcionais.

Para começar o tutorial, após executar o comando acima, digite:

```{r}
swirl()
```

Em seguida, siga o tutorial que vai começar na tela. Coloque um nome para continuar de onde parou e manter o progresso de cada sessão. Recomendamos fazer as sessões de **1 a 4**, no mínimo para a aula 02. Idealmente, façam quantas puderem, até a 8.

É melhor fazer uma ou duas sessões por dia, do que todas de uma vez no final de semana.


**Lembrem-se que para o `swirl` o correto é usar `<-` no lugar de `=`.**
