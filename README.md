# CYP-01
Generar un programa en C que dado un conjunto de parámetros, sea capaz de calcular la posición de un elemento en una pantalla de tamaño variable.

Se desea un programa que dada la resolución de un dispositivo, (pixeles de ancho x pixeles de alto), una
coordenada inicial, y el tamaño del elemento a lo ancho y alto expresado en un porcentaje

![Captura](https://user-images.githubusercontent.com/90359568/146662407-22e679bd-8a98-4243-a08c-f6661c7ee159.PNG)

En el ejemplo mostrado el cuadro de estatus de Waze debe aparecer al 50% del ancho total de la pantalla, y al
10% de lo alto. Siempre considerando que la coordenada x se incrementa de izquierda a derecha y la
coordenada y se incrementa de arriba hacia abajo.
El programa deberá entonces calcular la coordenada (x, y) de la esquina superior izquerda y la coordenada (x,
y) de la esquina inferior derecha.

![image](https://user-images.githubusercontent.com/90359568/146662430-9d42682d-3d22-4350-a2ae-c1af2442db41.png)

El resultado se mostrará indicando la coordenada de la esquina superior izquierda y la coordenada de la
esquina inferior derecha, para el ejemplo (147,384) y (467,432) respectivamente.
La respuesta debera venir en una sola linea
El programa debe retornar el valor de 0 al sistema operativo.
