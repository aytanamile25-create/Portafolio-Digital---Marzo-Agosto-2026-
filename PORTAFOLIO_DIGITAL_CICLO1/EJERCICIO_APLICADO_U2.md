
✔**PLANTEAMIENTO DEL PROBLEMA**

Una empresa de energía eléctrica desea automatizar el sistema de cobranza donde el usuario ingrese su nombre y de acuerdo a los kWh consumidos directamente el sistema le calcule si aplica un descuento o no de acuerdo a lo siguiente: 

Para cada cliente se ingresa el nombre y el consumo de energía en kWh (el cual debe ser un valor positivo). El costo por kWh es de $0.15. Sin embargo, se aplica la siguiente política de descuento condicional:

•	Si el consumo es mayor a 300 kWh, se aplica un descuento del 10% sobre el total de ese cliente.

•	Si el consumo es menor o igual a 300 kWh, se paga la tarifa normal (sin descuento).

El programa debe mostrar al 	cliente lo siguiente:

•	El valor bruto.

•	El descuento aplicado. 

•	El valor neto a pagar.

✔**ANÁLISIS DEL PROBLEMA

## 2. Análisis del Problema

| Datos de Entrada | Proceso | Datos de Salida |
| :--- | :--- | :--- |
| **Nombre** | |**Nombre** |
| **Consumo en kWh** | **Cálculo bruto:**<br>Valor bruto = consumo * 0.15 | **Valor bruto** |
| | **Condición de Descuento (Si consumo > 300):**<br>Descuento = valor bruto * 0.10 | **Descuento** |
| | **Cálculo neto:**<br>Valor neto = valor bruto - descuento | **Valor neto** |

