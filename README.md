# Haroldo Alcobaças

### Portifolio containing my Data Science Projects

## 📝 Project 2: Vendas Por Canal De Publicidade - Previsão Quantitativa 
!["Acesse Aqui - Project 2"](https://github.com/haroldoalcobacas/VendasPorCanalDePublicidade).

*Prática de Machine Learning com SKlearn - Análise de vendas por canal de publicidade.

 Para esse estudo foi utilizado o Dataset 'Advertising.csv' do livro ["An Introduction to Statistical Learning"](https://trevorhastie.github.io/ISLR/data.html).

###  Objetivo
* Realizar uma previsão quantitativa do número de vendas pelo valor investido em de canais de publicidade.
* O conjunto de dados conta com 200 observações e 4 varíaveis sendo TV, Rádio, Newspaper e Sales.
![Canais de Publicidade](RL_CanaisDePublicidade.PNG)
###  Métodos Utilizados

* Para análise das variáveis foi utilizado:
  -  Regressão Linear.
* Para análise da performance:
  - Mean absolute error(MAE);
  - Mean squared error (MSE) e;
  - Root Mean squared error (RMSE).
    
###  Resultados ( teste das variáveis e análise da performance do modelo )
* Para analise do resultado foi realizado o teste das 3 variáveis para identicação da suas contribuições para o modelo.
* Analisando os testes entre varíaveis, é possivel observar que a varíavel "newspaper" influencia de forma negativa a perfomance dos testes e tendo como melhor performance o teste com as váriáveis TV e Radio, gerando um erro de 1,5821 por unidade investida em publicidade.

