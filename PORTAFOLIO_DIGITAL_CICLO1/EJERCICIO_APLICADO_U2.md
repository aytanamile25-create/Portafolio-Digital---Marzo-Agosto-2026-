
✔**PLANTEAMIENTO DEL PROBLEMA**

Diseñar e implementar un programa en lenguaje C que evalúe un número entero positivo ingresado por el usuario para determinar si es primo o no. El sistema deberá contabilizar cuántas veces el número es divisible de manera exacta de forma secuencial y, con base en este resultado, emitir el mensaje si es primo o no.

✔**ANÁLISIS DEL PROBLEMA**

| ENTRADA | PROCESO | SALIDA | 
| :---: | :---: | :---: | 
| **Inicio** | **Se uso estructuras coondicionales como proceso con estructuras repetitivas lo cual son útiles para el proceso de la división del número para el contador, en este caso el contador va aunmentando hasta que se igual al numero ingresado**| **En la salida se uso if -  else porque dicha estructura ayuda a evaluar que si es divisible para 2 es primo de lo contrario no es primo**|  
| **a** | for | - | 
| **i** | if | - | 
| **división = 0** | if - else| El número es primo o El número no es primo| 

✔**DISEÑO DEL ALGORITMO**

<img width="789" height="489" alt="image" src="https://github.com/user-attachments/assets/a8e659ef-3ab9-44eb-bd0f-9f4175f3389f" />

✔**CODIFICACIÓN**

<img width="789" height="489" alt="image" src="https://github.com/user-attachments/assets/f046bd03-713e-442d-b1ef-cdd344ee0c1e" />

✔**VALIDACIÓN**

**Prueba de escritorio**

**Se ingresa el número 3**

| i | a | División / Proceso | Salida |
| :---: | :---: | :---: | :---: |
| **3** | **1**| **3/1 = 3 == 0**| **división == 2    El número es primo**|
| | **2** | **3/2 = 1.5 != 0**| |
|  | **3**| **3/3 = 1 == 0** | 

**Se ingresa el número 10**

| i | a | División / Proceso | Salida |
| :---: | :---: | :---: | :---: |
| **10** | **1**| **10/1 = 10 == 0**| **división == 2**|
| | **2** | **10/2 = 5 == 0**| Supera las dos divisiones |
|  | **3**| **10/3 = 3.33 ! = 0** | El número no es primo |
| | **4** | **10/4 = 2.5 ! = 0** ||
| |**5** | **10/5 = 2 == 0**| |
| | **6** | **10/6 = 1.66 ! = 0**| |
|  | **7**| **10/7 = 1.43 ! = 0** | |
|  | **8** | **10/8 = 1.25 ! = 0**||
|  | **9** | **10/9 = 1.11 ! = 0**| |
|  | **10** | **10/10 = 1 == 0**||
<img width="789" height="216" alt="image" src="https://github.com/user-attachments/assets/fb73722d-87a1-48e4-a62a-d482ff50ff82" />

[**🔙 REGRESAR**](./UNIDAD%202.md)
