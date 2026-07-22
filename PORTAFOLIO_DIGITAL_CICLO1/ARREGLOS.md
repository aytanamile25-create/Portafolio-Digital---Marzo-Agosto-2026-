
  
**📌ESTRUCTURAS DE DATOS ESTÁTICAS BÁSICAS**

[**Arreglos**](#Arreglos)
  
[**Tipos de arreglos**](#Tipos-de-arreglos)
  
---

## Arreglos

<div align="justify">

**Es una estructura de datos estática y homogénea que almacena una colección finita de elementos del mismo tipo bajo un identificador común. Su diseño se basa en la      asignación de un bloque de memoria contiguo, lo que permite el acceso aleatorio a los datos en tiempo constante mediante el cálculo de direcciones indexadas.
Al ser una estructura de dimensión fija, su tamaño físico debe ser definido rigurosamente durante la etapa de compilación del software. El direccionamiento de sus      componentes se gestiona a través de un índice numérico que representa el desplazamiento respecto a la dirección base en la memoria.**

</div>

<img width="430" height="320" alt="image" src="https://github.com/user-attachments/assets/f1154dd0-23d5-453a-9b17-f3f96af4900f" />

---

## Tipos de arreglos

✔**Unidimensional**

<div align="justify">

 Denominado formalmente como vector o lista lineal, es una estructura matemática que organiza sus componentes en una única dimensión conceptual. La disposición de la   información es estrictamente secuencial, lo que significa que los elementos se posicionan de manera adyacente en el espacio de direccionamiento físico. El acceso a     cada celda de memoria requiere exclusivamente de un único índice escalar, el cual inicia su conteo desde el valor cero en lenguajes como C. Su procesamiento            algorítmico es de baja complejidad, requiriendo un solo ciclo iterativo para ejecutar tareas de lectura, escritura o búsqueda.

</div>

Contextualización: Se requiere registrar las 5 calificaciones finales obtenidas por un estudiante durante el parcial. El programa almacena esta lista lineal de notas y las muestra en pantalla de forma ordenada para su verificación.

``` c

#include <stdio.h>

int main() {
    int notas[5] = {10, 8, 9, 7, 10};

    printf("=== Arreglo Unidimensional ===\n");
    for (int i = 0; i < 5; i++) {
        printf("Nota %d: %d\n", i + 1, notas[i]);
    }

    return 0;
}

```

<img width="430" height="250" alt="image" src="https://github.com/user-attachments/assets/65f94d6c-2bf8-4460-a72c-b3e1653799e5" />

✔**Bidimensional**

Contextualización: La facultad necesita organizar los resultados de una prueba aplicada a 2 grupos de clase, con 3 alumnos cada uno. El sistema utiliza una tabla de filas y columnas para representar cada grupo y mostrar sus notas.

<div align="justify">
  
 Esta estructura bidimensional, conocida en el ámbito de la ingeniería como matriz o tabla, organiza los elementos en un plano bidireccional. Su abstracción lógica emula una cuadrícula matemática definida por dos ejes vectoriales ortogonales, los cuales representan un conjunto de filas y columnas. Para realizar la localización o manipulación de un dato, el sistema operativo exige obligatoriamente la declaración de dos coordenadas numéricas independientes. En la sintaxis de programación, el primer descriptor determina el índice de la fila y el segundo especifica la columna, procesándose mediante ciclos anidados.

  </div>

``` c
#include <stdio.h>

int main() {
    // Matriz de 2 filas x 3 columnas
    int matriz[2][3] = {
        {1, 2, 3},
        {4, 5, 6}
    };

    printf("=== Arreglo Bidimensional ===\n");
    for (int f = 0; f < 2; f++) {
        for (int c = 0; c < 3; c++) {
            printf("%d ", matriz[f][c]);
        }
        printf("\n"); // Salto de línea por cada fila
    }

    return 0;
}
```

<img width="430" height="240" alt="image" src="https://github.com/user-attachments/assets/020ba3d3-930a-4783-a008-ee3539c5b9dd" />


✔**Tridimensional**

Contextualización: Se busca gestionar el reporte de notas de 2 paralelos, donde cada uno se divide en 2 grupos de 3 estudiantes. Se emplean bloques tridimensionales para estructurar la jerarquía (Paralelo, Grupo, Estudiante) y que imprima los datos.

<div align="justify">

 Es una estructura de datos compleja que añade un vector de profundidad a los conceptos tradicionales de filas y columnas, modelando un volumen espacial. Su representación lógica se asemeja a un hipercubo o a un bloque compuesto por una secuencia ordenada de matrices bidimensionales superpuestas. La indexación y el direccionamiento de la memoria física en esta estructura requieren de tres parámetros o índices independientes para descomponer la posición exacta del elemento. El tratamiento de estos tensores de datos dentro del código fuente demanda la implementación obligatoria de tres bucles iterativos anidados.

</div>

``` c 
#include <stdio.h>

int main() {
    // 2 matrices, cada una de 2 filas x 3 columnas
    int cubo[2][2][3] = {
        {
            {1, 2, 3},
            {4, 5, 6}
        },
        {
            {7, 8, 9},
            {10, 11, 12}
        }
    };

    printf("=== Arreglo Tridimensional ===\n");
    for (int b = 0; b < 2; b++) {
        printf("Capa/Bloque %d:\n", b + 1);
        for (int f = 0; f < 2; f++) {
            for (int c = 0; c < 3; c++) {
                printf("%d ", cubo[b][f][c]);
            }
            printf("\n");
        }
        printf("\n");
    }

    return 0;
}
```

<img width="430" height="300" alt="image" src="https://github.com/user-attachments/assets/da07360e-ca5f-4a1f-968b-40681a7cdd74" />




[**🔙 REGRESAR**](./UNIDAD%203.md)


