Portfolio Selection, by Harry Markowitz
================
Marco de Pereira Binda

##### Markowitz, Harry. **Portfolio Selection**. The Journal of Finance, vol. 7, no. 1, 1952, pp. 77–91. JSTOR, [www.jstor.org/stable/2975974](www.jstor.org/stable/2975974).

### Introdução

Markowitz inicia seu trabalho rejeitando duas hipóteses (ou máximas) de
investimentos:

1.  que o investidor deve maximizar o valor descontado (ou capitalizado)
    de retornos futuros:
    
    1.  Ignoradas as imperfeições do mercado, essa regra implica que não
        poderia haver um portifólio diversificado que seria preferível a
        todo portifólio não diversificado (e, como será demonstrado,
        diversificação é fato observado e sensato);
    
    2.  Significa, ainda, que dois ou mais ativos com igual valor
        descontado seriam idênticos, não importando as taxas de desconto
        utilizadas ou a variabilidade de seus retornos.

2.  que o investidor deve tanto diversificar quanto maximizar o valor
    descontado (ou capitalizado) de retornos futuros:
    
    1.  A Lei dos Grandes números garante que existe um portifólio que
        apresente tanto o máximo retorno esperando quanto menor
        variância;
    
    2.  A afirmação anterior, contudo, não é válida para um portifólio
        de ativos, pois seus retornos são muito intercorrelacionados, de
        forma que a diversificação não é capaz de eliminar toda a
        variância;
    
    3.  O portifólio de maior retorno esperado não é, necessariamente, o
        de menor variância, podendo o investidor selecionar um
        portifólio de maior retorno esperado, assumindo mais variância,
        e reduzir a variância, abrindo mão de parte do retorno esperado.

### Retorno - Risco (E-V)

Makowitz apresenta então sua regra para formação de um portifólio, a do
retorno esperado - variância do retorno (E-V).

Seja \(R_{i}\) o retorno do ativo \(i\) e \(X_{i}\) a participação do
ativo \(i\) no portifólio \(R\), o retorno esperado deste é dado por:

\[E(R) = X_{1}E(R_{1}) + X_{2}E(R_{2}) + ... + X_{n}E(R_{n})\]

logo, o retorno esperado do portifólio é a soma dos retornos esperados
de cada ativo, ponderados por sua respectiva participação no portifólio.
De forma resumida:

\[E(R) = \sum_{i = 1}^{n} X_{i}E(R_{i})\]

### Tabela

``` 
  # A tibble: 8 x 3
    ativo   risk return
    <chr>  <dbl>  <dbl>
  1 BVSP   0.217  0.285
  2 BOVA11 0.222  0.288
  3 SMAL11 0.209  0.357
  4 VALE3  0.466  0.444
  5 ITUB4  0.291  0.243
  6 B3SA3  0.326  0.421
  7 PETR4  0.473  0.471
  8 BBDC4  0.345  0.357
```

### Gráfico

![](portfolio-selection_files/figure-gfm/grafico-risco-retorno-1.png)<!-- -->
