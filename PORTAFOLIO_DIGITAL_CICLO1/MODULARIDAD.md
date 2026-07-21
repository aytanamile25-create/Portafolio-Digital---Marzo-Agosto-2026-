<div align="center">
  
**📌MODULARIDAD**

[**Funciones**](#funciones)
  
[**Tipos de funciones**](#Tipos-de-funciones)

<div align="justify">
  
**Cuando tenemos algoritmos largos y complejos, una técnica para reducir la complejidad es dividir el programa grande en subprogramas pequeños (divide y vencerás). En programación, a esta técnica se la conoce como modularización (paradigma de programación). Estos módulos reciben el nombre de: procesos, funciones, rutinas, sub-rutinas, etcétera.**

</div>

---

## Funciones

<div align="justify">
  
- Una función es un conjunto de sentencias que realiza una tarea determinada, responde a un propósito único e identificable. En el lenguaje se puede determinar dos tipos de funciones las que están predeterminadas por el lenguaje, por ejemplo, librerías #include <stdio.h>, y las que están definidas por el desarrollador.
  
- Consta básicamente de dos partes: una línea llamada cabecera, donde se especifica el tipo del resultado que devuelve, el nombre de la función y los parámetros que recibe, y un conjunto de sentencias encerradas entre llaves que forman el cuerpo de la función y el valor de retorno.

- No pueden ejecutarse por sí solas, estas deben estar ancladas a un programa principal. Las funciones solicitadas por el main a su vez pueden llamar a otras funciones.

</div>

<img width="430" height="400" alt="image" src="https://github.com/user-attachments/assets/fa576ce5-0ddd-4428-a3c1-069a529050f0" />

---

✔**Funciones con retorno de valor.**

<div align="justify">
  
Es un bloque de código diseñado para procesar datos y devolver un resultado al programa principal mediante la palabra clave return. El valor devuelto debe coincidir con el tipo de dato especificado en la declaración de la función (como int, float, string, etc.). Este dato devuelto puede ser almacenado en una variable o reutilizado directamente en otras operaciones o expresiones.

</div>

<img width="430" height="400" alt="image" src="https://github.com/user-attachments/assets/44f56ea0-495e-4229-911e-3f5148e73392" />

✔**Funciones sin valor de retorno ni paso de parámetros.**

<div align="justify">
  
Es una función declarada con el tipo void que ejecuta una serie de instrucciones o tareas específicas sin recibir ninguna información del exterior. Al no tener parámetros entre sus paréntesis (), trabaja de forma completamente autónoma con datos propios o globales. Además, al finalizar su ejecución no devuelve ningún resultado al programa invocador, finalizando sin usar la sentencia return.

</div>

<img width="430" height="169" alt="image" src="https://github.com/user-attachments/assets/9609ee92-fab2-4295-9e50-dc351af28dea" />

---

## Tipos de funciones

✔**Funciones con envío de parámetros**

<div align="justify">
  
**Enviado por valor:** Es un mecanismo donde la función recibe únicamente una copia del dato contenido en la variable original. Debido a que el módulo trabaja sobre este duplicado en una ubicación de memoria independiente, cualquier modificación realizada internamente no altera la variable original. Resulta ideal para procesar datos garantizando la protección de la información de entrada.

</div>

<img width="314" height="259" alt="image" src="https://github.com/user-attachments/assets/560b79a8-ef32-497e-b6b3-c0d911c65699" />

<div align="justify">
  
**Envío por referencia:** Es un mecanismo mediante el cual la función recibe la dirección de memoria directa donde se aloja la variable original. Al operar directamente sobre esa ubicación, cualquier cambio o cálculo realizado dentro del módulo modificará de forma inmediata el valor real del programa. Es fundamental para manipular estructuras complejas o devolver múltiples resultados.

</div>

<img width="345" height="265" alt="image" src="https://github.com/user-attachments/assets/de6f8405-f93f-46e3-9288-8a7bde3dbaa5" />

[**🔙 REGRESAR**](./UNIDAD%203.md)

