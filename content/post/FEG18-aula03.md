+++
title = "Análise de Dados - Aula 03"
subtitle = "Árvores de Decisão - Feagri 2019"
date = 2019-05-12T16:13:50-03:00
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

1. Baixe os dados na [pasta Homework da Aula 03](https://drive.google.com/drive/folders/1yn_5FuPA_wRddyM7WR8_fo94-6DDut3W?usp=sharing)

2. Importe os dados no Rstudio

3. Envie as respostas pelo [formulário](https://forms.gle/3EmTaTxzfYEx43oG9)

# Dados para a aula

Baixar em https://transfer.sh/I109G/aula03.zip

# Instalações

Para esta aula, serão necessários os pacotes:

* `mlr`: Esta bibloteca serve com interface para os algoritmos de machine learning usados no curso.
Mais informações no [site](https://mlr.mlr-org.com/).
* `rpart`: A implementação do algoritmo de árvores de decisão. Mais informações no [manual](https://cran.r-project.org/web/packages/rpart/rpart.pdf).
* `rpart.plot`: Contém funções para visualização da árvore de decisão.
* `tidyverse`: Instalado na aula 02.

Para instalar cada um destes pacotes, basta usar o comandos `install.packages("nome_do_pacote")`. Por exemplo:

```r
install.packages("mlr")
install.packages("rpart")
install.packages("rpart.plot")
```

Para instalar todos os pacotes de uma vez, use:

```r
install.packages(c("mlr","rpart","rpart.plot"))
```
