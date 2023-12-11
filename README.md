# automa-o-de-e-mail-com-google-Sheets
Esse projeto tem como propósito consultar dados em uma planilha validar e enviar e-mails de acordo com a condição desejada.

## Cenário
Contextualizando esse projeto tem como objetivo criar uma automação de e-mails baseado na analise de estoque abaixo segue um exemplo de planilha que está sendo consultada. 
O processo é o seguinte o script deve ler a quantidade de estoque de cada produto, 
se a quantidade estiver menor de 5 ou negativa deve-se enviar um e-mail ao resposável avisando qual produto está com estoque baixo e a qual loja ele pertence,
 no caso de produtos com estoque negativo deve enviar uma menssagem falando sobre o erro encontrado no produto 

### exemplo da plainha que está sendo consultada

Código do produto | Estoque | descrição | Total do produto em estoque| Nome do produto | Marca | Modelo Preço
--------------------------------------------------------------------------------------------------------------
40051              |12      |Camiseta_Azul| Camiseta|Loja modelo|Marca B| 100,00
40052              |-1      | Camiseta Vermelha    | Camiseta  | Loja 2| Marca Z| 50,00
40053             |2        |Boné verde |Boné|Loja 1| Marca C| 35,00
40054               |5  |Meia longa | Boné| Loja 3| Marca S | 45,00


