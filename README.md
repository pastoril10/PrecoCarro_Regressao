# Preço do carro - Regressão

*Prever o preço dos carros a partir de algumas features*


Distribuição do preço do carro para cada marca. 

![image](https://user-images.githubusercontent.com/83425571/179366469-4a1d477a-3a92-4b90-8b3c-e667a846e906.png)

Após o tratamento dos dados e preparação das features, aplicamos os nosso modelos de machine learning para prever o preço dos carros, o modelo com melhor retorno foi o XGBoost, com 91%. Depois da escolha do modelo, ainda buscamos os melhores parametros afim de optimizar o uso do nosso modelo.

![image](https://user-images.githubusercontent.com/83425571/179366508-03535ff2-e0cc-40f3-995e-221f24e34c0a.png)

Depois fizemos a validação, mostramos os dados real e os dados previsto, veja que obtemos quase uma reta devido a alta precisão. 

![image](https://user-images.githubusercontent.com/83425571/179366577-faaa7b47-9859-447f-a737-0d3bfa51bbca.png)

Outra análise foi encontrar as features que mais contribue para o preço dos carros, como mostrado na figura abaixo.

![image](https://user-images.githubusercontent.com/83425571/179366592-6f9b34e9-6852-4e6b-8328-0fb39768a568.png)

O Nosso RMSE foi de 3.1 Lakh



