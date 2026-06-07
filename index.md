<p align="center">
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/3f3110ff62fd0bef406a20bd62e3230cac1a4339/AS.png" width="100%">
</p>

---

<p align="center">
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/143045457dd73863c9893f3b62f2837017c09198/UNIVERSIDAD%20NACIONAL%20DE%20LOJA.png" width="100%">
</p>

---
<div align="center">
  
# [**UNIDAD 1**](UNIDAD1.md)

### **6. Prueba de Escritorio**
* **¿En qué consiste una Prueba de Escritorio?**

Una prueba de escritorio consiste en seguir paso a paso las instrucciones de un algoritmo, anotando los valores que toman las variables y los resultados de las operaciones, ya sea en papel, en una tabla o en un documento digital. Con el objetivo principal de detectar errores lógicos, comprender el flujo del programa y validar que los resultados sean correctos antes de ejecutar el código en un compilador.

* **¿Por qué es importante realizar una Prueba de Escritorio?**

Porque permite:

* Comprender el orden de ejecución de las instrucciones y cómo se repiten o se saltan según las condiciones.
* Identificar errores lógicos y problemas en el código antes de la ejecución real, ahorrando tiempo y recursos.
* Analizar bucles y condicionales, observando cómo cambian las variables dentro de estas estructuras.
* Validar resultados, asegurando que las salidas del programa coincidan con lo esperado.

* **Procedimiento**

Para realizar una prueba de escritorio, se siguen los siguientes pasos:

* Definición del problema: comprender qué se desea lograr con el algoritmo.
* Análisis del problema: identificar los datos de entrada, salida, fórmulas y ciclos necesarios.
* Diseño del algoritmo: estructurar el pseudocódigo o diagrama de flujo.
* Ejecución manual: con datos de prueba, recorrer cada paso del algoritmo, anotando los valores de las variables y los resultados intermedios.
* Evaluación: si los resultados son correctos, el algoritmo es lógico; de lo contrario, se corrigen errores y se repite la prueba.

### **7. Lenguajes de Programación**

Un lenguaje de programación es un sistema estructurado de símbolos y reglas sintácticas que permite a los desarrolladores escribir instrucciones (Código) para controlar el comportamiento físico y lógico de una computadora.

<div align="center">

| Lenguaje | Descripción |
| :--- | :--- |
| **Python** | Es una herramienta versátil, popular en la ciencia de datos, inteligencia artificial y automatización. | 
| **JavaScript** | Es el lenguaje estándar para el desarrollo web interactivo. | 
| **Java** | Es utilizado en aplicaciones empresariales a gran escala y desarrollo Android. | 
| **C#** | Se utiliza en el desarrollo de videojuegos y aplicaciones Windows. | 
| **C++** | Es utilizado para software de alto rendimiento, sistemas operativos y videojuegos. | 

</div>

### **Clasificación según su ejecución:**

* **Compilados:** Es aquel que traduce todo el código fuente de una vez y genera un archivo ejecutable independiente (Como un .exe) antes de que el programa corra.
* **Interpretados:** Es aquel que lee y ejecuta el código línea por línea en tiempo real (No genera un archivo ejecutable previo).
* **Híbridos:** Es aquel en el cual el código fuente se compila primero a un lenguaje intermedio (Como el Bytecode en Java) y luego una máquina virtual lo interpreta o lo compila "al vuelo" (JIT - JUST-IN-TIME) en el dispositivo del usuario.
---
<div align="center">
  
# **Programación por Bloques**
</div>

La programación por bloques es un método de programación visual que permite a los usuarios ensamblar bloques gráficos para crear algoritmos sin necesidad de escribir código.

### **1. Ventajas de la Programación por Bloques**

* **Fácil de usar:** No requiere memorizar comandos complicados ni reglas de sintaxis estrictas.
* **Prevención de errores:** Los bloques están diseñados para encajar solo si la lógica es correcta, lo que evita errores de escritura.
* **Aprendizaje visual:** Permite ver la estructura del programa de forma clara y colorida.
* **Fomenta la creatividad:** Al reducir la frustración técnica, el usuario puede enfocarse en resolver el problema.

### **2. ¿Cómo funciona la programación por bloques?**

El funcionamiento de este sistema se basa en un entorno gráfica que traduce las acciones del usuario en código real. Es decir, en lugar de escribir, el usuario "ensambla" la lógica del programa siguiendo estos principios:

* **Interfaz de Arrastrar y Soltar (Drag and Drop):** Los usuarios seleccionan bloques desde una paleta categorizada y los arrastran al área de trabajo.
* **Lógica de Rompecabezas:** Los bloques tienen muescas y salientes que indican visualmente qué piezas pueden conectarse. Si una conexión no es lógica, las piezas simplemente no encajan.
* **Categorización por Colores:** Para facilitar la identificación, los bloques se dividen por funciones (por ejemplo: azul para movimiento, amarillo para eventos, naranja para variables).
* **Traducción en Tiempo Real:** Mientras el usuario une los bloques, el entorno de programación interpreta esas uniones y las convierte en instrucciones que la computadora puede ejecutar inmediatamente.

<p align="center">  
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/62facff4b4e05a4fa69313e87fe8a2d0552a6086/Captura%20de%20pantalla%202026-05-03%20000128.png" width="500">
</p>

---

<div align="center">

## **EJERCICIO CON ESTRUCTURAS SECUENCIALES**

</div>

### **1. Planteamiento del Problema**

Un productor de leche lleva el registro de lo que produce en litros, pero cuando entrega le pagan en galones. Realice un algoritmo que ayude al productor a saber cuánto recibirá por la entrega de su producción de un día ( 1 galón = 3.785 litros)

### **2. Análisis del Problema**
Identificamos los siguientes datos:
* **Entrada:**
  * Cantidad de litros producidos en el día.
  * Precio por Galón
* **Proceso:**
  * Primero, convertimos los litros a galones:
    
    GA = L/3.785
    
  * Segundo, calculamos el pago total:
    
    PAGO = GA*PG
    
* **Salida:** El monto total de dinero que el productor recibirá por su entrega del día

### **3. Diseño del Algoritmo**

* **Diagrama de Flujo**
  
<p align="center">
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/a69d095e7bb4f5a5d214067d3b0475fdf71dbdc5/litro%20diagrama.png" width="550">
</p>
  
* **Pseudocódigo**

<p align="center">
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/7b2f3f9ea02c9434ba5f784c7a01c9650b82b778/litro%20pseudoc%C3%B3digo.png" width="550">
</p>
  

### **4. Codificación**

<p align="center">  
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/738d0a9de20a957f91123305059cc6bf38c6e6c6/codigo%20fuente.png" width="550">
</p>

### **5. Validación**

<div align="center">

| Cantidad de Litros | Precio por Galón | Proceso (Cálculo) | Salida (Pago Total) |
| :--- | :--- | :--- | :--- |
| 5 litros | $1.50 | (5 / 3.785) * 1.50 | $1.98 |
| 10 litros | $1.50 | (10 / 3.785) * 1.50 | $3.96 |

</div>

---

### **Principales Dificultades en el Aprendizaje**

Durante la revisión de los temas las principales dificultades que se presentaron fueron:

* Realizar las pruebas de escritorio de manera correcta porque al mezclar las variables o no respetar el orden del algoritmo los resultados de la prueba de escritorio son diferentes a los obtenidos en el pseudocódigo, por lo tanto al obtener esto daba por hecho que su ejecución era incorrecta.
* Identificar de manera correcta cuales son los datos de entrada, proceso y salida de mi codigo fuente. 
* Aprenderme la sintaxis del codigo fuente (signos, palabras claves y la estructura) y entender el por qué muchas veces mi código no copilaba.

### **Reflexión Crítica en la Aplicación de Contenidos**

El aprendizaje del estudio de algoritmos, pseudocódigos, diagramas de flujo y la prueba de escritorio, son una parte fundamental para lograr desarrollar una solución antes de implementar cualquier lenguaje de programación, ya que la aplicación de estos contenidos nos permite estructurar ideas de manera clara, reducir errores y mejorar la comprensión del funcionamiento de un programa. Por ejemplo, una prueba de escritorio nos ayuda a verificar paso a paso los resultados que obtenemos durante la ejecución. Asimismo, al trabajar con el lenguaje de programación C, logramos evidenciar cómo la lógica previamente desarrollada se traduce en instrucciones precisas. Además, logramos comprender que el estudio de estos temas no solo se basa en memorizar conceptos o pasos ya que para lograr comprender de mejor manera estos contenidos nuestro trabajo es practicar de manera constante para desarrollar o mejorar nuestras habilidades.

---

### **Bibliografías y Referencias**

[1] A. J. Edwards-Crespo et al., "El pensamiento computacional: un reto para la educación de cara al siglo XXI," *Revista Universidad y Sociedad*, vol. 11, no. 1, 2019. [En línea]. Disponible: http://scielo.sld.cu/scielo.php?script=sci_arttext&pid=S2077-29552019000100147

[2] F. Monroy Tenorio, "¿Qué es PSeInt?," *Fernando Monroy Tenorio - Blog de Tecnología*. [En línea]. Disponible: https://fernandomonroytenorio.com/tema/que-es-pseint/

[3] Miro, "¿Qué es un diagrama de flujo y cómo se hace?," *Miro Software*. [En línea]. Disponible: https://miro.com/es/diagrama-de-flujo/que-es-diagrama-de-flujo/

[4] Lucidchart, "Tutorial de diagrama de flujo: Qué es y cómo se hace," *Lucid Software Inc.* [En línea]. Disponible: https://www.lucidchart.com/pages/es/tutorial/diagrama-de-flujo

[5] ID Tech, "What is block-based coding?," *ID Tech Blog*. [En línea]. Disponible: https://www.idtech.com/blog/what-is-block-based-coding

[6] Educa JCyL, "Programación por bloques y pensamiento computacional," *Portal de Educación de la Junta de Castilla y León*. [En línea]. Disponible: https://www.educa.jcyl.es/educacyl/cm/gallery/CCD/Area_6/B1.6_Creacion_de_contenido/5_programacin_por_bloques_y_pensamiento_computacional.html

[7] Millennials Consulting, "Programación en C: Todo lo que necesitas saber," *Millennials Consulting Blog*. [En línea]. Disponible: https://millennialsconsulting.es/programacion-c/

### **Declaración de Uso de Inteligencia Artificial**

Se utilizo la Inteligencia Artificial (Gemini) para estructurar de manera correcta y jerarquica los titulos y subtitulos, es decir cuales son los caracteres para que el titulo salga en negrita y centrado. Asimismo, como agregar las rutas de las imagenes que necesitaba colocar, como resaltar un texto y como agregar un tipo separador de hojas. Además, me ayudo a redactar algunas partes de mi portafolio.

---
