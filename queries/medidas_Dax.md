medidas\_Dax



Medidas utilizadas para análise estatística para identificar valores atípicos (outliers) e entender a distribuição dos dados. Limite inferior do meio dos dados.



Essa medida calcula o primeiro quartil (Q1): 

o valor abaixo do qual estão 25% das alturas da amostra.

Limite inferior do meio dos dados.



**Q1Altura = PERCENTILE.INC(Clientes\[Altura], 0.25)**



Essa medida calcula o terceiro quartil (Q3): 

o valor abaixo do qual estão 75% das alturas.

Limite superior do meio dos dados.



**Q3Altura = PERCENTILE.INC(Clientes\[Altura], 0.75)**



Essa medida calcula o Intervalo Interquartil (IQR): Q3 - Q1.

E mede a dispersão dos valores centrais e ajuda a detectar outliers.



**IQRAltura = \[Q3Altura] - \[Q1Altura]**



Essa medida calcula o limite inferior para identificar outliers.

Qualquer altura abaixo desse valor é considerada potencial outlier para baixo.



**LimiteInferiorAltura = \[Q1Altura] - 1.5 \* \[IQRAltura]**



Essa calcula o limite superior para identificar outliers.

Qualquer altura acima desse valor é considerada potencial outlier para cima.



**LimiteSuperiorAltura = \[Q3Altura] + 1.5 \* \[IQRAltura]**



Essa medida calcula a mediana: que é o valor central da distribuição 

(metade dos dados está abaixo e metade acima).



**MedianaAltura = MEDIAN(Clientes\[Altura])**





