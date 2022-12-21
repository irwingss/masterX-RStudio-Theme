# Temas de RStudio

Este repo es para publicar los temas de RStudio creados para las clases del [Instituto de Ciencias Antonio Brack](https://www.brackinstitute.com/). Son temas sencillos y distintivo para visualizar el código sin cansarse demasiado, con colores diferenciales para las diferentes partes del código.

## Instalación

Necesitarás la versión de RStudio version 1.2. o más reciente. Descarga [la versión más reciente aquí](https://www.rstudio.com/products/rstudio/download/preview/).

Ejecuta el siguiente código en un script de RStudio para descargar, instalar y aplicar el tema. 

### Tema masterX (2023)

![](figs/masterXtema.png)

```r
install.packages("rstudioapi")
install.packages("xml2")
install.packages("fs")
rstudioapi::addTheme("https://raw.githubusercontent.com/irwingss/Primolius-Theme/main/tema_masterx.rstheme", 
                     apply = TRUE)
```
