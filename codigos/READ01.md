# READ01 — Primera exploración algorítmica

Las 24 trenzas son formas que emergen del Sitio Abismal, no una representación directa de él.

Cada una combina contención, ruido, acumulación y torsión.

El ruido produce pequeñas desviaciones y la acumulación hace que estas permanezcan en el recorrido. La torsión convierte una trayectoria en tres hebras entrelazadas.

Las 24 trenzas siguen las mismas reglas, pero cambian sus parámetros y colores.

El experimento explora cómo pequeñas variaciones durante un recorrido pueden convertirse en forma.

**Código asociado:** `01_trenzas_sitio_abismal.ipynb`

## 01 — Una trenza

El experimento comienza con una trayectoria generada mediante:

```text
CONTENCIÓN
    +
RUIDO
    +
ENTROPÍA


Aquí la entropía se entiende de manera sencilla como la acumulación de pequeñas variaciones durante el recorrido.

La trayectoria se construye paso a paso:

posición anterior
       +
     ruido
       +
   acumulación
       ↓
  nueva posición

La forma conserva parte de las marcas de su recorrido.

**02 — Tres hebras**

La primera prueba genera tres hebras a partir de una trayectoria central.

Inicialmente son paralelas. Al observar este resultado se introduce torsión para producir el entrelazamiento:

eje
 ↓
radio
 ↓
torsión
 ↓
3 hebras
 ↓
trenza

Las tres hebras se separan mediante fases de 120°.

La trenza aparece así como una forma que surge de un recorrido que se desvía, se acumula y finalmente se entrelaza.

**03 — De una a 24 trenzas**

La función generar_trenza() permite producir diferentes trenzas a partir de distintos parámetros:

límite
ruido
entropía
torsión
radio

Las mismas reglas generan 24 configuraciones diferentes.

MISMAS REGLAS
      ↓
DIFERENTES PARÁMETROS
      ↓
24 TRENZAS

No forman una secuencia: son 24 configuraciones coexistentes.

**04 — Color**

Se utiliza una paleta común de 8 colores, combinados en 24 tríadas de tres colores.

8 colores
   ↓
24 combinaciones
   ↓
3 colores por trenza

Los colores pueden repetirse y recombinarse entre las 24 trenzas.

**05 — Resultado**

El experimento permite observar:

una trayectoria con ruido y acumulación;
tres hebras entrelazadas;
24 trenzas con parámetros diferentes;
24 combinaciones cromáticas;
pequeñas diferencias entre las hebras.
REGLAS
  ↓
PARÁMETROS
  ↓
RECORRIDO
  ↓
FORMA

**06 — Próximo paso**

Los parámetros todavía se generan mediante variación controlada.

El siguiente desarrollo consiste en comenzar a vincularlos con el diccionario de operaciones de TTT2:

DICCIONARIO
     ↓
OPERACIONES
     ↓
COMBINACIONES
     ↓
PARÁMETROS
     ↓
FORMA


