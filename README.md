# Tema Primolius

Un tema claro, sencillo y distintivo para visualizar el código sin cansarse demasiado. Este es el tema oficial del grupo RLatinoamérica en 2020-2021.

![](figs/Primolius.png)

## Installation

Necesitarás la versión de RStudio version 1.2. o más reciente. Descarga [la versión más reciente aquí](https://www.rstudio.com/products/rstudio/download/preview/).

Run the following code in RStudio to download and apply the theme.

```r
tema_Primolius <- fs::path_temp("tema_Primolius", ext = "rstheme")
download.file("https://raw.githubusercontent.com/irwingss/Primolius-Theme/main/Primolius_Color.rstheme",tema_Primolius)
rstudioapi::addTheme(tema_Primolius, apply = TRUE)

```
