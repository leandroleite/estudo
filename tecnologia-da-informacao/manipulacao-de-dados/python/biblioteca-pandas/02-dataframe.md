---
titulo: DataFrame
---
- [DataFrames do Pandas](https://pythonacademy.com.br/blog/dataframes-do-pandas): Agora que você é craque em Séries do Pandas, vamos ao complemento dessa dupla inseparável: Séries e Dataframes Pandas!
- [Python - Comparação e seleção de dados em Pandas](https://www.acervolima.com.br/2021/04/python-comparacao-e-selecao-de-dados-em.html): O mais importante na Análise de Dados é comparar valores e selecionar os dados de acordo. O operador “==” funciona para vários valores em um dataframe Pandas também. Os dois exemplos a seguir mostram como comparar e selecionar dados de um dataframe Pandas.

# DataFrame

- Dataframes são tabelas.
- É formado por um conjunto de séries, cada uma delas sendo uma coluna da ‘tabela’.

## Criação a partir de uma lista

~~~python
>>> df = pd.DataFrame([200, 350, 550])
>>> df
     0
0  200
1  350
2  550
~~~

## Criação a partir de um dicionário

~~~python
>>> df = pd.DataFrame({'calorias':[200, 350, 550], 'gordura (%)':[0, 6, 15]},
                      index=['banana', 'prato feito', 'big mac'])
>>> df
             calorias  gordura (%)
banana            200            0
prato feito       350            6
big mac           550           15
~~~

## df[coluna]

Acessar todos valores de uma coluna

~~~python
>>> df['gordura (%)']
banana          0
prato feito     6
big mac        15
Name: gordura (%), dtype: int64
~~~

## df[[coluna1,coluna2]]

Passar por parâmetro o array com os nomes de colunas

~~~python
>>> df[['gordura (%)','calorias']]
             gordura (%)  calorias
banana                 0       200
prato feito            6       350
big mac               15       550
~~~

## df[linha_inicio:linha_final]

- tabela começa com linha 0
- linha_final não está inclusa no resultado

~~~python
>>> df[1:2]
   calorias  gordura (%)
1       350            6
~~~

## Máscara Booleana

~~~python
>>> df['calorias'] <= 500
banana          True
prato feito     True
big mac        False
Name: calorias, dtype: bool
~~~

## Filtrando pela máscara booleana

~~~python
>>> df['calorias'] == 350
banana         False
prato feito     True
big mac        False
Name: calorias, dtype: bool

>>> df[df['calorias'] == 350]
             calorias  gordura (%)
prato feito       350            6
~~~



