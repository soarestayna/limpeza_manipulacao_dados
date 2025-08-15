### **Informações de estudo**



##### Lab 4 - Limpeza e Manipulação de dados



Nesse dashboard foram feitas as limpezas e manipulações nos seguintes dados:



1. Limpeza de dados duplicados onde foi utilizado o Power Query para reduzir linhas (removendo) duplicadas, pois em uma planilha de dados podem conter clientes com o mesmo nome, idade ou peso, mas não podem haver clientes com o mesmo ID, CPF, identificação única.
   
2. Manipulação dos dados com valor nulo, quando um arquivo estiver com informações ausentes a duas formas de resolver, uma é removendo aquele dados, o que pode ocasionar em perdas de informações sobro determinados clientes, outra forma de resolver seria colocar valores aproximados nos dados nulos, esses valores podem ser média, mediana ou moda dos dados que serão manipulados. Também é possível colocar valores através do teste estatístico (mas não há um botão no power bi para realizar esse teste, ele deverá ser feito em Python, R ou por Machine Learning).
   
3. Visualizando e tratando Outliers: Quando a valores extremos existem algumas formas de resolver, uma delas é a remoção desses valores ( quando fizer a remoção de um dado, se necessário coloque uma observação), outra alternativa seria substituir os valores outliers pelo valor da mediana. Uma forma de visualizar o outliers é através do boxplot (esse gráfico não consta no power bi) outras alternativa é utilizar o gráfico de dispersão conjunto com algumas medidas criadas em dax.
