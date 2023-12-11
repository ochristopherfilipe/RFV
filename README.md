# Projeto de segmentação de clientes RFV

## Objetivo

* O objetivo deste projeto é realizar a segmentação de clientes por meio da análise das métricas RFV (recência, frequência e valor). Essa segmentação permite identificar grupos de clientes com comportamentos semelhantes, o que pode ajudar a empresa a direcionar suas estratégias de marketing e CRM de forma mais eficiente.

## Método

### Para realizar a segmentação, foram calculadas as seguintes métricas para cada cliente:

* Recência: Quantidade de dias desde a última compra.
* Frequência: Quantidade total de compras no período.
* Valor: Total de dinheiro gasto nas compras do período.
Em seguida, as métricas RFV foram agrupadas em quartis, sendo que o melhor quartil foi classificado como "A", o segundo melhor quartil como "B", o terceiro melhor como "C" e o pior como "D".

## Resultados

### Após a segmentação, foram identificados os seguintes grupos de clientes:

* AAA: Clientes com menor recência, maior frequência e maior valor gasto.
* AAB: Clientes com menor recência e maior frequência.
* ABB: Clientes com menor recência e menor valor gasto.
* AAC: Clientes com maior frequência e maior valor gasto.
* ACC: Clientes com maior frequência e menor valor gasto.
* AAD: Clientes com maior valor gasto.
* DDD: Clientes com maior recência e menor valor gasto.
  
## Ações de marketing/CRM

### Com base nos resultados da segmentação, podem ser adotadas as seguintes ações de marketing/CRM para cada grupo de clientes:

* AAA: Enviar cupons de desconto, pedir para indicar o produto para algum amigo e, ao lançar um novo produto, enviar amostras grátis.
* AAB: Enviar cupons de desconto menor e pedir para indicar o produto para algum amigo.
* ABB: Enviar cupons de desconto bem menor e pedir para indicar o produto para algum amigo.
* AAC: Enviar cupons de desconto maior e pedir para indicar o produto para algum amigo.
* ACC: Enviar cupons de desconto bem maior e pedir para indicar o produto para algum amigo.
* AAD: Enviar cupons de desconto para tentar recuperar o cliente.
* DDD: Enviar: Churn! clientes que gastaram bastante e fizeram muitas compras, enviar cupons de desconto para tentar recuperar
  
## Conclusão

A segmentação de clientes por meio das métricas RFV é uma ferramenta importante para as empresas que desejam direcionar suas estratégias de marketing e CRM de forma mais eficiente. Com base nos resultados da segmentação, é possível identificar os clientes com maior potencial de compra e adotar ações específicas para atraí-los e retê-los.
