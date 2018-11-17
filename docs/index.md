---
title: "index"
author: "John A. G. M"
date: "16 de noviembre de 2018"
output:
  html_document: default
  pdf_document: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Pruebas de ecuaciones

Se pretende minimizar un funcional de costo cuadrático para un problema de
horizonte finito con estados finales libres de la forma

$x_{i}$

\begin{equation}
 \left(\frac{1}{n} \right)^2 
\end{equation}

sujeto a la siguiente restricción dinámica 
\begin{equation}
\dot{x}(t)=f(x(t),u(t)),\text{  }x(0)=x_{0}, 
\end{equation}

\begin{equation}
	\sum_{i=1}^n X_i
\end{equation}
			$\sum_{i=1}^n X_i$
			

La estructura **if** consiste en la palabra clave **if** seguida de una expresión condicional entre paréntesis. A continuación viene un bloque de código entre llaves. Si la condición se cumple (es cierta) el bloque de código se ejecuta. Si la condición no se cumple (es falsa) el programa salta el bloque de código y continua.

	:::c
	if(condicion)
	{
		// Bloque si la condición se cumple
	}
	else
	{
		// Bloque si la condición no se cumple
	}


## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
