# Estudo de Markdown

## Títulos em Markdown

o Simbolo de # adciona uma Título a ao documento. Podendo ser referido de h1 a h6 como no html.

## Negrito e Itálico em Markdown

__Teste Negrito__
**Teste Negrito**

_Teste Itálico_
*Teste Itálico*


## Listas no Markdown

### Lista ordenada

1. Html
2. Css
3. Javascript
4. PHP 
5. Mysql

### Lista não ordenada.

* Barra de menu
* Menu de contexto
* Body da página
* Rodapé

## Inserindo imagem

**Inserindo imagem local**

![imagem PHP](./img/php.png)

**Inserindo imagem por url**

![imagem python](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgseY7mdhgtrJDNY8abXq9uCj1qJUQ37N9yQ&usqp=CAU)


## Inserindo Link

[Site da Google](https://www.google.com/)


## Inserindo Código Fonte

```
x <- rnorm(n = 10, mean = 100, sd = 5)
hist(x, main = "")
```
´´´
def calcular_pagamento(qtd_horas, valor_hora):
    horas = float(qtd_horas)
    taxa = float(valor_hora)
    if horas <= 40:
        salario = horas*taxa
    else:
        h_excd = horas - 40
        salario = 40*taxa+(h_excd*(1.5*taxa))
    return salario
´´´

