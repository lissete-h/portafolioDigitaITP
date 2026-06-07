<a name="1-que-es-un-algoritmo"></a>
<div align="center">

## ⚙️ **1. ¿Qué es un Algoritmo?**

</div>

<p align="justify">
Un algoritmo es una secuencia ordenada, finita y definida de pasos o instrucciones estructuradas que sirven para resolver problemas complejos, realizar cálculos matemáticos precisos o ejecutar tareas específicas dentro de un sistema.
</p>

---

<a name="2-caracteristicas-de-los-algoritmos"></a>
<div align="center">

## 📋 **2. Características de los Algoritmos**

</div>

<p align="justify">
Para que un conjunto de instrucciones sea considerado un algoritmo válido, debe cumplir estrictamente con las siguientes propiedades fundamentales:
<br><br>
• <b>Precisos:</b> No debe existir ambigüedad; cada uno de los pasos establecidos tiene que ser claro, directo y fácil de comprender.
<br><br>
• <b>Ordenados:</b> Debe presentar una secuencia lógica y cronológica rigurosa para poder llegar a la solución del problema sin inconvenientes.
<br><br>
• <b>Finitos:</b> El algoritmo tiene que concluir en algún momento y poseer un número determinado de pasos, ya que no puede prolongarse infinitamente.
<br><br>
• <b>Definidos:</b> Rigurosidad ante todo; si se sigue el mismo algoritmo utilizando los mismos elementos de entrada (input), se debe obtener siempre el mismo resultado (output).
</p>

---

<a name="3-clasificacion-de-los-algoritmos"></a>
<div align="center">

## 📊 **3. Clasificación de los Algoritmos**

| Tipo de Algoritmo | Descripción | Ejemplo Práctico |
| :--- | :--- | :--- |
| **Cualitativos** | Son aquellos que estructuran la solución utilizando palabras, descripciones narrativas o instrucciones lógicas secuenciales. | **Preparar una taza de té:** <br> 1. Hervir agua limpia. <br> 2. Añadir 5 hojas de té. <br> 3. Reposar de 3 a 5 minutos. <br> 4. Colar y servir en la taza. |
| **Cuantitativos** | Son aquellos que se basan exclusivamente en la ejecución de cálculos numéricos, variables numéricas y fórmulas matemáticas. | **Restar dos números enteros:** <br> 1. **Inicio** <br> 2. Registrar número uno (5). <br> 3. Registrar número dos (3). <br> 4. Restar 5 menos 3. <br> 5. El resultado es 2. <br> 6. **Final** |

</div>

---

<a name="4-partes-de-un-algoritmo"></a>
<div align="center">

## 🧩 **4. Partes de un Algoritmo**

<p align="center">
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/c45d7a98ebf45a701aab7d4d0bd85cafebca56db/PARTES%20DE%20UN%20ALGORITMO.jpg" width="85%">
</p>

</div>

---

<a name="5-representacion-de-un-algoritmo"></a>
<div align="center">

## 📐 **5. Representación de un Algoritmo**

</div>

<p align="justify">
Existen diferentes metodologías y herramientas estandarizadas para modelar y representar gráficamente la estructura de un algoritmo antes de pasarlo a código real:
<br><br>
• <b>Pseudocódigo:</b> Es una descripción de alto nivel que mezcla el lenguaje natural (Español) con convenciones sintácticas propias de la programación, permitiendo un diseño rápido y comprensible de la lógica.
</p>

<p align="center">
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/9a2ba1c8d49fdd5837addd768fb1687ff3ff3fe3/pintura.png" width="500">
</p>

<p align="justify">
• <b>Diagrama de Flujo:</b> Es la representación gráfica y secuencial de un proceso o algoritmo. Utiliza símbolos geométricos estandarizados (óvalos, rectángulos, rombos) interconectados por flechas de flujo para ilustrar visualmente la secuencia de pasos, tomas de decisiones y acciones requeridas de principio a fin.
</p>

<p align="center">  
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/864ccc9c2aaa6f078a8a5c29340ad2dc8dd996b6/partes%20de%20un%20diagrama.png" width="500">
</p>

---

<a name="6-prueba-de-escritorio"></a>
<div align="center">

## 📝 **6. Prueba de Escritorio**

</div>

<p align="justify">
<b>¿En qué consiste una Prueba de Escritorio?</b>
<br>
Consiste en realizar una simulación manual y detallada del algoritmo paso a paso. Se van anotando de forma cronológica los valores cambiantes que toman las variables y los resultados de las operaciones en una tabla, un papel o un documento digital. El propósito central es detectar fallos lógicos ocultos, comprender a fondo la secuencia dinámica del programa y validar que la lógica entregue los datos correctos antes de realizar la compilación formal.
</p>

<p align="justify">
<b>¿Por qué es importante realizar una Prueba de Escritorio?</b>
<br>
Esta técnica de verificación manual es crucial en la ingeniería de software porque permite:
<br><br>
• Visualizar de manera exacta el orden de ejecución de las instrucciones y la forma en que los bloques se repiten o saltan de acuerdo a las condiciones lógicas evaluadas.
<br><br>
• Capturar fallos semánticos y problemas de asignación de forma temprana, lo que ahorra tiempo de cómputo y recursos de depuración.
<br><br>
• Analizar detalladamente las estructuras cíclicas y condicionales, observando el comportamiento interno de las variables de control en cada iteración.
<br><br>
• Garantizar con certeza matemática que las salidas obtenidas coincidan de punta a punta con el resultado teórico planteado.
</p>

<p align="justify">
<b>Procedimiento Metodológico</b>
<br>
Para efectuar de forma correcta este control de calidad analítico, se ejecutan de manera ordenada las siguientes fases:
<br><br>
1. <b>Definición del problema:</b> Comprender rigurosamente las necesidades y los requerimientos del sistema.
<br>
2. <b>Análisis del problema:</b> Identificar con precisión matemática las variables de entrada, las operaciones de proceso, las constantes y las salidas esperadas.
<br>
3. <b>Diseño del algoritmo:</b> Plantear y estructurar la solución en pseudocódigo o diagramas de flujo formalizados.
<br>
4. <b>Ejecución manual:</b> Utilizando datos de prueba representativos, recorrer paso a paso el algoritmo, registrando los cambios en las variables en una matriz de seguimiento.
<br>
5. <b>Evaluación:</b> Si los resultados corresponden a lo esperado, el algoritmo es validado como correcto; caso contrario, se reajusta el diseño y se itera la prueba.
</p>

---

<a name="7-lenguajes-de-programacion"></a>
<div align="center">

## 💻 **7. Lenguajes de Programación**

</div>

<p align="justify">
Un lenguaje de programación representa un sistema formal estructurado de símbolos, operadores y reglas sintácticas y semánticas que faculta a los ingenieros de software para codificar conjuntos de instrucciones precisas capaces de gobernar el comportamiento físico, lógico y el procesamiento de datos de una computadora.
</p>

<div align="center">

| Lenguaje | Descripción Técnica y Campos de Aplicación |
| :--- | :--- |
| **Python** | Herramientas de alto nivel, sumamente versátil y legible. Dominante en análisis de datos, Machine Learning, inteligencia artificial, desarrollo backend y automatización de scripts. | 
| **JavaScript** | Lenguaje multiparadigma esencial y estándar para el desarrollo web interactivo del lado del cliente (frontend) y del servidor (Node.js). | 
| **Java** | Lenguaje orientado a objetos robusto y multiplataforma. Es pilar en sistemas empresariales de gran escala, arquitecturas de software distribuidas y desarrollo nativo Android. | 
| **C#** | Diseñado por Microsoft, orientado a objetos, robusto y ampliamente utilizado en entornos corporativos de Windows y en el desarrollo de videojuegos profesionales mediante Unity. | 
| **C++** | Evolución del lenguaje C que añade orientación a objetos. Ofrece control de hardware de bajo nivel y un rendimiento óptimo, siendo vital en sistemas operativos, motores gráficos y software crítico. | 

</div>

<p align="justify">
<b>Clasificación de los Lenguajes según su Proceso de Ejecución:</b>
<br><br>
• <b>Compilados:</b> Son aquellos lenguajes donde un software especializado (compilador) traduce la totalidad del código fuente de una sola vez, generando un binario ejecutable independiente (como un archivo `.exe` o un ejecutable nativo) antes de proceder con el arranque del programa.
<br><br>
• <b>Interpretados:</b> Aquellos sistemas donde el código fuente no pasa por una fase de pre-compilación binaria, sino que un programa intérprete procesa y ejecuta las sentencias línea por línea en tiempo de ejecución real.
<br><br>
• <b>Híbridos:</b> Modelos donde el código fuente es inicialmente compilado hacia un lenguaje de nivel intermedio neutro (como el <i>Bytecode</i> en Java). Posteriormente, una Máquina Virtual dedicada (JVM o CLR) interpreta o compila ese archivo intermedio de forma dinámica justo a tiempo (JIT - Just-In-Time) en el procesador del usuario.
</p>

---

<a name="8-programacion-por-bloques"></a>
<div align="center">

## 🧱 **8. Programación por Bloques**

</div>

<p align="justify">
La programación por bloques es un paradigma y modelo de aprendizaje visual diseñado para abstraer la complejidad del código escrito. Permite a los usuarios ensamblar bloques gráficos que contienen instrucciones encapsuladas para estructurar algoritmos lógicos complejos sin necesidad de lidiar directamente con errores de sintaxis textual.
</p>

<p align="justify">
<b>Ventajas de la Programación por Bloques:</b>
<br><br>
• <b>Fácil de usar:</b> Elimina la necesidad de memorizar un vocabulario técnico rígido y comandos de sintaxis demandantes en las primeras etapas de formación.
<br><br>
• <b>Prevención nativa de errores:</b> Las piezas visuales están diseñadas bajo un esquema de restricciones geométricas, encajando exclusivamente si la estructura lógica subyacente posee sentido de programación.
<br><br>
• <b>Aprendizaje y abstracción visual:</b> Facilita al programador novato mapear el flujo del programa, las condiciones y los ciclos repetitivos mediante colores y jerarquías físicas.
<br><br>
• <b>Fomento de la creatividad analítica:</b> Al mitigar la frustración sintáctica inicial, el usuario puede canalizar todos sus recursos cognitivos directamente hacia el diseño de la solución del algoritmo.
</p>

<p align="justify">
<b>Mecánica de Funcionamiento Interno:</b>
<br>
El entorno de desarrollo traduce los eventos y uniones gráficas realizadas en el espacio de trabajo en secuencias lógicas directas mediante las siguientes interacciones:
<br><br>
• <b>Interfaz de Arrastrar y Soltar (Drag and Drop):</b> Los bloques se seleccionan desde cajones categorizados por funciones y se posicionan libremente en el canvas o zona de edición.
<br><br>
• <b>Lógica de Rompecabezas:</b> Las uniones cuentan con muescas y guías físicas virtuales que impiden combinaciones erróneas entre variables incompatibles o estructuras desordenadas.
<br><br>
• <b>Categorización por Colores:</b> Segmentación semántica que permite identificar rápidamente bloques de control, operadores matemáticos, eventos lógicos y variables según su color institucional.
<br><br>
• <b>Traducción en Tiempo Real:</b> El motor del software genera una conversión instantánea de los bloques apilados hacia lenguajes estructurados nativos para su ejecución en el ordenador.
</p>

<p align="center">  
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/62facff4b4e05a4fa69313e87fe8a2d0552a6086/Captura%20de%20pantalla%202026-05-03%20000128.png" width="500">
</p>

---

<a name="9-ejercicio-con-estructuras-secuenciales"></a>
<div align="center">

## 🚀 **9. Ejercicio con Estructuras Secuenciales**

</div>

<p align="justify">
<b>1. Planteamiento del Problema</b>
<br>
Un productor de leche lleva el registro de lo que produce en litros, pero cuando entrega le pagan en galones. Realice un algoritmo que ayude al productor a saber cuánto recibirá por la entrega de su producción de un día (1 galón = 3.785 litros).
</p>

<p align="justify">
<b>2. Análisis del Problema</b>
<br>
Para diseñar el programa secuencial de forma matemática y estructurada, aislamos los siguientes elementos de control:
<br><br>
• <b>Entradas requeridas (Inputs):</b> Cantidad total de litros recolectados en el día ($L$), Precio establecido por cada galón entregado ($PG$).
<br><br>
• <b>Procesamiento de datos:</b> 
<br>
&nbsp;&nbsp;&nbsp;&nbsp;1. Conversión de volumen métrico de litros a galones ingleses: $GA = L / 3.785$
<br>
&nbsp;&nbsp;&nbsp;&nbsp;2. Cálculo monetario del rendimiento del productor: $PAGO = GA \times PG$
<br><br>
• <b>Salidas calculadas (Outputs):</b> El monto financiero neto total en dólares que el productor recibirá al finalizar su jornada de entrega ($PAGO$).
</p>

<p align="justify">
<b>3. Diseño del Algoritmo</b>
<br><br>
• <b>Diagrama de Flujo del Proceso:</b>
</p>
<p align="center">
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/a69d095e7bb4f5a5d214067d3b0475fdf71dbdc5/litro%20diagrama.png" width="550">
</p>
  
<p align="justify">
• <b>Modelado del Pseudocódigo (PSeInt):</b>
</p>
<p align="center">
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/7b2f3f9ea02c9434ba5f784c7a01c9650b82b778/litro%20pseudoc%C3%B3digo.png" width="550">
</p>
  
<p align="justify">
<b>4. Codificación en Lenguaje Fuente (C)</b>
</p>
<p align="center">  
  <img src="https://github.com/lissete-h/portafolioDigitaITP/blob/738d0a9de20a957f91123305059cc6bf38c6e6c6/codigo%20fuente.png" width="550">
</p>

<p align="justify">
<b>5. Validación Mediante Datos de Prueba</b>
</p>

<div align="center">

| Cantidad de Litros ($L$) | Precio por Galón ($PG$) | Proceso (Cálculo Algorítmico) | Salida Real (Pago Total) |
| :---: | :---: | :--- | :---: |
| 5 litros | $1.50 | $(5 / 3.785) \times 1.50$ | **$1.98** |
| 10 litros | $1.50 | $(10 / 3.785) \times 1.50$ | **$3.96** |

</div>

<div align="right">[ 🔼 Volver al Índice ](#seccion-unidad-1)</div>
