# Evaluación interactiva de patrones en gráficos Q-Q

## Descripción

Este programa en HTML permite realizar una evaluación interactiva sobre la interpretación de **gráficos cuantil-cuantil**, también conocidos como **Q-Q plots**.

El objetivo es que el estudiante observe un gráfico Q-Q construido contra una **distribución normal** y seleccione, mediante opción múltiple, qué patrón estadístico parece sugerir la gráfica.

El programa genera casos aleatorios relacionados con distintos comportamientos de distribución, como:

* normalidad aproximada;
* cola derecha;
* cola izquierda;
* colas pesadas;
* colas ligeras;
* posible mezcla de distribuciones o bimodalidad.

Al finalizar, el programa muestra una evaluación con:

* nombre del estudiante;
* grupo;
* fecha y hora de inicio;
* fecha y hora de finalización;
* número de preguntas;
* aciertos;
* calificación;
* detalle de respuestas.

También permite imprimir el resultado o descargarlo como archivo de texto.

---

## Archivo principal

El programa está contenido en un solo archivo:

```text
evaluacion_patrones_qq.html
```

No requiere instalación ni conexión a internet.
Sólo se necesita abrir el archivo en un navegador web.

---

## Requisitos

Para usar el programa se necesita:

* computadora, tableta o celular;
* navegador web actualizado, por ejemplo:

  * Google Chrome;
  * Microsoft Edge;
  * Mozilla Firefox;
  * Safari.

No se requiere instalar Python, paquetes estadísticos ni programas adicionales.

---

## Cómo abrir el programa

1. Descargar el archivo `evaluacion_patrones_qq.html`.
2. Dar doble clic sobre el archivo.
3. El archivo se abrirá en el navegador web.
4. Llenar los datos solicitados.
5. Iniciar la evaluación.

---

## Datos que solicita el programa

Antes de iniciar, el estudiante debe indicar:

* nombre;
* grupo;
* número de datos a generar;
* número de preguntas de la evaluación.

El número de datos controla el tamaño de la muestra simulada para construir los gráficos.

Por ejemplo:

```text
20 datos  → gráficos más irregulares
50 datos  → patrones más visibles
100 datos → patrones más estables
500 datos → patrones más claros
```

Para una actividad inicial se recomienda usar entre **50 y 100 datos**.

---

## Qué muestra cada pregunta

En cada pregunta, el programa muestra un gráfico Q-Q construido contra una distribución normal.

El estudiante debe observar el patrón de los puntos y elegir la opción que mejor describa lo que sugiere la gráfica.

Las opciones pueden incluir patrones como:

* compatible con normalidad;
* posible cola derecha;
* posible cola izquierda;
* posibles colas pesadas;
* posibles colas ligeras;
* posible mezcla de grupos o bimodalidad.

---

## Interpretación básica de los patrones

| Patrón observado en el Q-Q plot                | Posible interpretación                      |
| ---------------------------------------------- | ------------------------------------------- |
| Los puntos siguen aproximadamente la recta     | Datos compatibles con normalidad            |
| Los puntos se curvan hacia arriba              | Posible sesgo o cola derecha                |
| Los puntos se curvan hacia abajo               | Posible sesgo o cola izquierda              |
| Los extremos se alejan mucho de la recta       | Posibles colas pesadas                      |
| Los extremos se acercan hacia el centro        | Posibles colas ligeras                      |
| Hay quiebres, forma irregular o dos tendencias | Posible mezcla de poblaciones o bimodalidad |

El gráfico Q-Q no demuestra de forma absoluta qué distribución tienen los datos. Sirve como herramienta visual para detectar si hay patrones que se alejan de la normalidad.

---

## Cómo realizar la evaluación

1. Abrir el archivo HTML.
2. Escribir nombre y grupo.
3. Elegir cuántos datos se generarán.
4. Elegir cuántas preguntas tendrá la evaluación.
5. Presionar el botón para iniciar.
6. Observar cada gráfico.
7. Seleccionar la respuesta que mejor describa el patrón.
8. Avanzar hasta terminar.
9. Revisar la calificación final.
10. Imprimir o descargar el resultado.

---

## Evidencia de entrega

El estudiante puede entregar cualquiera de las siguientes evidencias:

* captura de pantalla del resultado final;
* impresión en PDF del resultado;
* archivo `.txt` descargado desde el programa;
* documento con el resultado y una breve interpretación.

Se recomienda que el estudiante no sólo entregue la calificación, sino que también explique algunos de los patrones que observó.

---

## Sugerencia de evaluación para el docente

La actividad puede evaluarse sobre 100 puntos:

| Criterio                                       | Puntos |
| ---------------------------------------------- | -----: |
| Entrega del resultado generado por el programa |     10 |
| Identificación correcta de patrones            |     30 |
| Justificación de respuestas                    |     25 |
| Interpretación estadística de los patrones     |     20 |
| Reflexión final                                |     10 |
| Presentación ordenada                          |      5 |

La calificación automática del programa puede usarse para evaluar la identificación de patrones, pero se recomienda complementar con una explicación escrita.

---

## Preguntas de reflexión sugeridas

Después de realizar la evaluación, el estudiante puede responder:

1. ¿Qué patrón fue más fácil de reconocer?
2. ¿Qué patrón fue más difícil?
3. ¿Por qué no basta con observar solamente el histograma?
4. ¿Qué indica que los puntos se alejen en ambas colas?
5. ¿Qué indica una curvatura marcada en el Q-Q plot?
6. ¿Por qué el Q-Q plot no prueba por sí solo que los datos son normales?
7. ¿Qué otros elementos conviene revisar además del Q-Q plot?

---

## Uso didáctico recomendado

Este programa puede utilizarse para:

* introducir el concepto de normalidad;
* comparar distribuciones mediante gráficos;
* analizar visualmente supuestos estadísticos;
* preparar a los estudiantes para pruebas de normalidad;
* reforzar la interpretación de histogramas y Q-Q plots;
* discutir que la estadística no depende sólo de cálculos, sino también de interpretación visual.

Una dinámica sugerida es:

1. Primero mostrar los gráficos sin decir de qué distribución provienen.
2. Pedir a los estudiantes que identifiquen el patrón.
3. Discutir en grupo las respuestas.
4. Revelar la interpretación correcta.
5. Relacionar los patrones con normalidad, sesgo, colas y valores extremos.

---

## Advertencia conceptual

El programa no debe usarse para enseñar que el Q-Q plot “adivina” distribuciones de forma exacta.

La interpretación correcta es:

> El gráfico Q-Q permite observar si los datos son compatibles con una distribución normal o si presentan patrones visuales que sugieren desviaciones, como asimetría, colas pesadas, colas ligeras o mezcla de poblaciones.

Por lo tanto, las conclusiones deben expresarse con cuidado:

* “Los datos parecen compatibles con normalidad.”
* “El gráfico sugiere cola derecha.”
* “El gráfico muestra posibles colas pesadas.”
* “El patrón podría indicar mezcla de grupos.”

No se recomienda decir:

* “El gráfico demuestra que la distribución es normal.”
* “El gráfico prueba que los datos son exponenciales.”
* “El gráfico confirma exactamente la distribución.”

---

## Recomendación final

Para que la actividad sea más formativa, se recomienda que el estudiante entregue:

1. Resultado generado por el programa.
2. Tabla breve con algunas respuestas justificadas.
3. Reflexión final sobre la utilidad y limitaciones del gráfico Q-Q.

De esta manera, la actividad no se limita a seleccionar opciones, sino que ayuda a desarrollar interpretación estadística.
