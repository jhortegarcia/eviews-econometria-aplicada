# Programas EViews — Econometría Aplicada

Transcripción de los programas en *Econometric Views* incluidos en:

> **Castro, J. F. & Rivas-Llosa, R.** (2005). *Econometría Aplicada*. Universidad del Pacífico, Lima.

Este repositorio contiene 21 programas escritos en el lenguaje de programación de **EViews**, organizados según el capítulo del libro en que aparecen. Los archivos fueron transcritos manualmente a partir del PDF de la obra.

---

## Contenido

| Archivo | Programa | Título | Páginas |
|---|---|---|---|
| `Programa_3_1.txt` | 3.1 | Técnica de estimación Jacknife | 217–218 |
| `Programa_3_2.txt` | 3.2 | Captura de resultados intermedios mediante un vector | 220 |
| `Programa_3_3.txt` | 3.3 | ¿Cómo registrar un máximo? Método A | 221–222 |
| `Programa_3_4.txt` | 3.4 | ¿Cómo registrar un máximo? Método B | 222–223 |
| `Programa_3_5.txt` | 3.5 | Rutinas para ordenar ascendentemente un vector (Quick-Sort) | 225–229 |
| `Programa_3_6.txt` | 3.6 | ¿Cómo crear un gráfico animado simple? | 231–232 |
| `Programa_3_7.txt` | 3.7 | Técnica de regresiones móviles — Momento óptimo de un quiebre | 234–236 |
| `Programa_4_1.txt` | 4.1 | Exploración de transformaciones univariadas | 247–255 |
| `Programa_4_2.txt` | 4.2 | Test de Farrar-Glauber (multicolinealidad) | 276–281 |
| `Programa_4_3.txt` | 4.3 | Análisis de Componentes Principales (ACP) | 301–303 |
| `Programa_5_1.txt` | 5.1 | Estimación recursiva del test de Chow | 348–349 |
| `Programa_6_1.txt` | 6.1 | Método iterativo de Cochrane-Orcutt | 389–392 |
| `Programa_6_2.txt` | 6.2 | Procedimiento de búsqueda de Hildreth-Lu | 392–394 |
| `Programa_6_3.txt` | 6.3 | Test de Goldfeld & Quandt (heterocedasticidad) | 411–413 |
| `Programa_6_4.txt` | 6.4 | Test de Spearman (heterocedasticidad) | 416–417 |
| `Programa_8_1.txt` | 8.1 | Test de Hausman (regresores estocásticos) | 496–498 |
| `Programa_8_2.txt` | 8.2 | Verificación de correlación contemporánea — Breusch-Pagan | 505–507 |
| `Programa_8_3.txt` | 8.3 | Consistencia del estimador de variables instrumentales (VI) | 532–534 |
| `Programa_8_4.txt` | 8.4 | Eficiencia del estimador MCG/SUR | 537–539 |
| `Programa_9_1.txt` | 9.1 | Aplicación secuencial del test ADF (Dickey-Fuller Aumentado) | 570–573 |
| `Programa_9_2.txt` | 9.2 | Aplicación recursiva del test de Zivot y Andrews | 580–585 |

---

## Uso

Cada archivo `.txt` puede copiarse directamente en el editor de programas de EViews (`File > New > Program`). Antes de ejecutar cualquier programa, revisar la sección **USO** en los comentarios del encabezado, donde se especifican los argumentos requeridos, los objetos que deben crearse previamente (grupos, series, etc.) y ejemplos de llamada.

### Nota sobre continuaciones de línea

El PDF original usa el símbolo `▶▶` como marcador tipográfico de continuación de línea. En esta transcripción, todas esas líneas fueron **unidas en una sola línea**, ya que EViews no tiene operador de continuación.

---

## Advertencias generales

- Los comentarios en español con tildes y eñes han sido conservados como literales de cadena dentro del código. Si su versión de EViews presenta problemas de codificación, reemplazar los caracteres especiales por sus equivalentes sin diacríticos.
- Algunos programas requieren que el usuario ajuste parámetros iniciales (nivel de convergencia, número de iteraciones, tamaño de muestra, etc.) antes de ejecutarlos.

---

## Atribución

Los programas son propiedad intelectual de sus autores originales:

**Juan Francisco Castro** y **Roddy Rivas-Llosa**  
*Econometría Aplicada*, Universidad del Pacífico, Lima, 2005.

Este repositorio tiene fines exclusivamente académicos y de referencia. No se reproduce texto narrativo del libro, únicamente el código fuente funcional de los programas.

---

## Licencia

Este repositorio se distribuye bajo la licencia **Creative Commons Atribución-NoComercial 4.0 Internacional (CC BY-NC 4.0)**.

Puede compartir y adaptar el material para fines no comerciales, siempre que cite la fuente original (Castro & Rivas-Llosa, 2005) y este repositorio.

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/deed.es)
