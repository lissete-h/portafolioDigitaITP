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
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/d8ccaebcfcbddc64824c6220bed44e09d4b9c370/img/Captura%20de%20pantalla%202026-07-18%20111636.png" width="55%">
          </p>
• Procedimiento (o subrutina): Es un bloque que realiza una acción pero no devuelve un valor directamente (ej. una función que simplemente imprime un reporte en pantalla o limpia la consola). En C, estos se definen como void.  
 <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/e0f7db1330cb65fe45c61097cf65fa0124b52a25/img/Captura%20de%20pantalla%202026-07-18%20111803.png" width="55%">
          </p>

 [REGRESAR](UNIDAD3.md)
 
   * ### Funciones con envio de parámetros 
     * **Por valor**: Cuando llamas a una función y pasas un parámetro por valor, la función recibe una copia de x.
        * **¿Qué hace la función?**: Trabaja con la copia. Si la función modifica ese número, la copia cambia, pero tu x original de el main sigue valiendo lo mismo.
        * **¿Cuando se usa?**: Cuando solo quieres usar el dato para calcular algo pero no quieres arriesgarte a dañar el dato original.
        * **Ejemplo**: Calcular cuánto sería el saldo después de aplicar un interés del 5%, pero no quieres cambiar el saldo real todavía.
       
         <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/d0516a94e67d663ee68b96d0953fe259221502e9/img/Captura%20de%20pantalla%202026-07-18%20115247.png" width="75%">
          </p>
          
     * **Por referencia**: Cuando se trabaja por referencia, no le damos una copia a la función; le damos la dirección de memoria donde esta la variable x.
        * **¿Qué hace la función?**: Como tiene la dirección, va directo a donde está el original y cambia el valor allí mismo.
        * **Ejemplo**: El usuario hace un retiro de dinero. Necesitamos que, al terminar la función, el valor de miDinero en el main sea realmente menor.
   
        <p align="center"> 
         <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/dc77af98f9a857e46272af1b23b7d4aadd7912c3/img/Captura%20de%20pantalla%202026-06-08%20091732.png" width="55%">
          </p>

 [REGRESAR](UNIDAD3.md)

   * ### Estructura en Pseudocódigo
      * **Condicional Simple**
        <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/0d39a11c7115d9b938b8055cfdc4f03be1adfac1/img/Captura%20de%20pantalla%202026-06-08%200908370.png" width="55%">
          </p>
      * **Condicional Doble**
        <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/c7ba9714455ca4508b119d3e484b87d8cdf14d5d/img/Captura%20de%20pantalla%202026-06-08%200917320.png" width="55%">
          </p>
      * **Condicional Múltiple**
        <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/51ef566c25e59b59ebf45f6865bf900742e70185/img/Captura%20de%20pantalla%202026-06-08%200937560.png" width="55%">
          </p>
      * **Condicional Anidado**
        <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/357f20800bde4818f7d20f3a633afc6a3f2f6a48/img/Captura%20de%20pantalla%202026-06-08%200954340.png" width="55%">
          </p>

<a id="repetitivas"></a>

 [REGRESAR](UNIDAD3.md)

### *⚡ 2.Esctructuras Repetitivas*

<a id="tipos-repetitivas"></a>
   * ###  Tipos de Bucles Repetitivos
     * **While**: Es aquel que evalua una condición, dependiendo si el resultado es verdadero (T) o si es falso (F), simplemente ignorando el bloque y continuando con el flujo del programa.
     * **Do-While**: Es aquel que permite elegir entre dos caminos o alternativas posibles. Si la condición es verdadera, ejecuta un bloque de código; si es falsa, ejecuta un bloque de código diferente.
     * **For**: Es aquel que permite evaluar una variable y elegir entre múltiples rutas posibles según el valor que esta contenga, este condicional es util cuando hay muchas opciones.

<a id="diagrama-repetitivas"></a>

 [REGRESAR](UNIDAD3.md)

   * ### Estructuras en Diagrama de Flujo
     * **While**
         <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/d92d2d5b4a29aebb789e164b632c5867b088ea19/img/Captura%20de%20pantalla%202026-06-08%20143414.png" width="55%">
         </p>
     * **Do-While**
        <p align="center"> 
         <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/5ec14746f64ce2d642ae4aa67ffcd4d4fec444ec/img/Captura%20de%20pantalla%202026-06-08%20144633.png" width="55%">
          </p>
     * **For**
        <p align="center"> 
         <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/4e8bf6e11a7b1b9f95dc755b5281e1afc610814c/img/Captura%20de%20pantalla%202026-06-08%20144926.png" width="55%">
          </p>

<a id="pseudocodigo-repetitivas"></a>

 [REGRESAR](UNIDAD3.md)

   * ### Estructura en Pseudocódigo
      * **While**
        <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/0d39a11c7115d9b938b8055cfdc4f03be1adfac1/img/Captura%20de%20pantalla%202026-06-08%200908370.png" width="55%">
          </p>
      * **Do-While**
        <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/5ec14746f64ce2d642ae4aa67ffcd4d4fec444ec/img/Captura%20de%20pantalla%202026-06-08%20144646.png" width="55%">
          </p>
      * **For**
        <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/4e8bf6e11a7b1b9f95dc755b5281e1afc610814c/img/Captura%20de%20pantalla%202026-06-08%20144937.png" width="55%">
          </p>

<a id="ejercicio-integrador"></a>

 [REGRESAR](UNIDAD3.md)

### ⚡3.EJERCICIO PRACTICO INTEGRADOR

<a id="planteamiento-problema"></a>
* #### Planteamiento del problema
  * Una tienda de abarrotes vende cajas de aceite multiusos y tiene un inventario inicial de 20 cajas. El cajero debe registrar las ventas una por una intoduciendo la cantidad de cajas que compra cada cliente.
    
    REGLAS:
     * El programa debe repetirse mientras queden cajas en el inventario.
     * Si un cliente pide mas cajas de las que hay disponibles, el programa debe mostrar un mensaje de error y rechazar esa venta en especifico.
     * El programa debe terminar automaticamente cuando el inventario llege exactamente a 0.
<a id="analisis-problema"></a>

 [REGRESAR](UNIDAD3.md)

* #### Análisis del problema
| Componente | Elementos / Descripción |
| :--- | :--- |
| **📥 Entrada** | <ul><li>**cantidad_venta**: Variable que almacena el dato que se lee del usuario.</li></ul> |
| **⚙️ Proceso** | <ul><li>**Variables**: int inventario=20 / int clientes_atendidos=0 </li><li>**Estructuras Repetitivas**: while (inventario>0) </li><li>**Estructura condicional**: if(cantidad_venta<=inventario)</li><li>**Operaciones**: inventario-=cantidad_venta / clientes_atendidos++ </li></ul> |
| **📤 Salida** | **Si se cumple todo (Caso Éxito):**<br>• Inventario disponible:  <br>•  Venta realizada con exito.<br>• Inventario Agotado *(Al llegar a 0)*<br>• El total de clientes atendidos fue de: <br><br>**Por lo contrario (Caso Error):**<br>• Error: Cantidad Insuficiente, Intente con una cantidad menor. |
* #### Diseño del Algoritmo
  
   [REGRESAR](UNIDAD3.md)
  
 <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/c7627aa233cbbd4dc0a239eadb8f70d29742055b/img/Diagrama%20sin%20t%C3%ADtulo.drawio.png" width="55%">
          </p>
          
<a id="codificacion-fuente"></a>

 [REGRESAR](UNIDAD3.md)

* #### Codificación (Código Fuente)
 <p align="center"> 
          <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/527af58b93e3717831db0c943d89e9732b9f798c/img/Captura%20de%20pantalla%202026-06-09%20094744.png" width="55%">
          </p>

<a id="validacion-escritorio"></a>

 [REGRESAR](UNIDAD3.md)

* #### Validación (Prueba de Escritorio)
| Cajas (Inventario) | Proceso | Pantalla | Mensaje |
| :---: | :--- | :--- | :--- |
| **20** | Inicialización de variables. | | |
| **20** | Evalúa:<br>20 > 0 | "Inventario disponible"<br>20 cajas | |
| | | "Ingrese la cantidad de cajas..." | |
| **20** | Cliente pide 15.<br>15 <= 20 | 15 | |
| **5** | 20 - 15 = 5 | | "Venta realizada con exito."<br>Clientes atendidos = 1 |
| | | | |
| **5** | Evalúa:<br>5 > 0 | "Inventario disponible"<br>5 cajas | |
| | | "Ingrese la cantidad de cajas..." | |
| **5** | Cliente pide 5.<br>5 <= 5 | 5 | |
| **0** | 5 - 5 = 0 | | "Venta realizada con exito."<br>Clientes atendidos = 2 |
| | | | |
| **0** | Evalúa:<br>0 > 0 (No) -> Fin bucle | | "Inventario Agotado"<br><br>"El total de clientes atendidos fue de: 2" |
