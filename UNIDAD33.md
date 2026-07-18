[REGRESAR](UNIDAD3.md)
 
<a id="unidad3-inicio"></a>

<div align="center">

## UNIDAD 3: *✍🏻 Programación Modular y Estructuras de Datos Estáticas ✍🏻*

</div>

<p align="justify">
En esta unidad se analizó la programación modular, desde los conceptos básicos hasta el uso de módulos y funciones en la resolución de problemas. Asimismo, se abordaron las estructuras de datos estáticas básicas, abarcando desde los arreglos hasta las cadenas.
</p>

<a id="condicionales"></a>

[REGRESAR](UNIDAD3.md)
 
### *⚡ 1. Programación Modular*

<a id="tipos-condicionales"></a>

### Conceptos básicos de programación modular

<p align="justify">
• <b>¿Qué es la Programación Modular?</b>: Es un paradigma de diseño de software que consiste en dividir un problema complejo en subproblemas más pequeños y manejables, llamados módulos. Cada módulo debe estar diseñado para realizar una tarea específica, de modo que el sistema completo sea la suma de estas piezas trabajando en armonía.
</p>

<p align="justify">
• <b>Pilares Fundamentales</b>: Para que una estructura sea realmente modular, debemos buscar dos propiedades técnicas clave:
</p>

<div align="center">

| Propiedad | Descripción |
| :--- | :--- |
| **Alta Cohesión** | Un módulo debe tener una única responsabilidad bien definida (principio de responsabilidad única). Si un módulo intenta hacer demasiadas cosas distintas, es momento de dividirlo. |
| **Bajo Acoplamiento** | Los módulos deben ser lo más independientes posible. Un cambio en la lógica interna de un módulo no debería romper el funcionamiento de los otros. La comunicación debe ser mínima y definida mediante interfaces. |

</div>

<br>

[REGRESAR](UNIDAD3.md)

<p align="justify">
• <b>¿Qué es una función?</b>: Una función es un bloque de código con nombre que encapsula una tarea específica, que contiene lo siguiente:
</p>

<div align="center">

| Componente | Descripción |
| :--- | :--- |
| **Entrada (Parámetros)** | Se le entrega la información necesaria para trabajar. |
| **Procesamiento** | La función ejecuta una lógica interna (cálculos, transformaciones, validaciones). |
| **Salida (Retorno)** | Devuelve un resultado al lugar donde fue llamada. |

</div>

<p align="justify">
• <b>¿Diferencia entre "Procedimiento y Función"?</b>: 
</p>
• Función: Es un bloque que devuelve un valor (ej. una función que calcula un promedio y entrega el número resultante).
 <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/d8ccaebcfcbddc64824c6220bed44e09d4b9c370/img/Captura%20de%20pantalla%202026-07-18%20111636.png" width="75%">
          </p>
• Procedimiento (o subrutina): Es un bloque que realiza una acción pero no devuelve un valor directamente (ej. una función que simplemente imprime un reporte en pantalla o limpia la consola). En C, estos se definen como void.  
 <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/e0f7db1330cb65fe45c61097cf65fa0124b52a25/img/Captura%20de%20pantalla%202026-07-18%20111803.png" width="75%">
          </p>

 [REGRESAR](UNIDAD3.md)
 
   * ### Funciones con envio de parámetros 
     * **Por valor**: Cuando llamas a una función y pasas un parámetro por valor, la función recibe una copia de x.
        * **¿Qué hace la función?**: Trabaja con la copia. Si la función modifica ese número, la copia cambia, pero tu x original de el main sigue valiendo lo mismo.
        * **¿Cuando se usa?**: Cuando solo quieres usar el dato para calcular algo pero no quieres arriesgarte a dañar el dato original.
        * **Ejemplo**: Calcular cuánto sería el saldo después de aplicar un interés del 5%, pero no quieres cambiar el saldo real todavía.
       
         <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/d0516a94e67d663ee68b96d0953fe259221502e9/img/Captura%20de%20pantalla%202026-07-18%20115247.png" width="80%">
          </p>
          
     * **Por referencia**: Cuando se trabaja por referencia, no le damos una copia a la función; le damos la dirección de memoria donde esta la variable x.
        * **¿Qué hace la función?**: Como tiene la dirección, va directo a donde está el original y cambia el valor allí mismo.
        * **Ejemplo**: El usuario hace un retiro de dinero. Necesitamos que, al terminar se muestre cuanto le queda.
   
        <p align="center"> 
         <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/147abb7ed33b50c57d5baa2edf2f5df7f90fa140/img/Captura%20de%20pantalla%202026-07-18%20120349.png" width="80%">
          </p>

 [REGRESAR](UNIDAD3.md)

 ### 📊 Arreglos

<p align="justify">
• <b>¿Qué es un Arreglo?</b>: Un arreglo (o array) es una estructura de datos que permite almacenar una colección de elementos del mismo tipo bajo un mismo nombre.
</p>

<p align="justify">
• <b>¿Cómo se declara y se usa?</b>: Para declarar un arreglo, se debe especificar el tipo de dato y el tamaño (cantidad de espacios) que se requiere.
</p>

• <b>Tipos de arreglos:</b>

*   <b>Unidimensional:</b> Es una lista lineal de datos. Se asemeja a una sola fila de casilleros donde accedes a cada uno mediante un solo índice y se declara como `int vector[i]`.

Ejemplo: Desarrolle un programa en lenguaje C que inicialice un arreglo unidimensional de tipo float con tres valores correspondientes a los precios de diversos productos. El sistema deberá recorrer dicho arreglo mediante una estructura de control iterativa y mostrar en pantalla cada precio, utilizando un formato de salida que indique claramente el número de producto y su costo asociado.
 <p align="center">
    <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/27f6d2e97345e46a8d6120294947b931ece22d9e/img/Captura%20de%20pantalla%202026-07-18%20124548.png" width="80%">
    </p>
  <p align="center">
    <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/71a6992052719cd0b66108c8dde2a1c40edc5faf/img/Captura%20de%20pantalla%202026-07-18%20124557.png" width="80%">
    </p>

*   <b>Bidimensionales:</b> Son aquellos que tienen filas y columnas; para acceder a un elemento se necesitan dos índices: uno para la fila y otro para la columna. Se declara como `int matriz[fila][columna]`.
  
Ejemplo: Desarrolle un programa en lenguaje C que utilice una matriz de tipo float de 3 filas por 4 columnas. Cada fila representa un vendedor (3 vendedores en total) y cada columna representa las ventas realizadas durante los 4 días de la semana laboral. El programa debe permitir ingresar las ventas de cada vendedor y, posteriormente, mostrar la matriz completa en pantalla organizada como una tabla.
    <p align="center">
    <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/0d39a11c7115d9b938b8055cfdc4f03be1adfac1/img/Captura%20de%20pantalla%202026-06-08%200908370.png" width="55%">
    </p>

*   <b>Tridimensional:</b> Son arreglos de tres dimensiones, útiles para representar estructuras más complejas, y se declaran como `int cubo[profundidad][fila][columna]`.
    <p align="center">
    <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/0d39a11c7115d9b938b8055cfdc4f03be1adfac1/img/Captura%20de%20pantalla%202026-06-08%200908370.png" width="55%">
    </p>
