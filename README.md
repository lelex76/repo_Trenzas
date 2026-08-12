# READ01 — Primera exploración algorítmica

## 01 — Una trenza como sistema

Este primer experimento desarrolla una primera aproximación  a las **24 trenzas del Sitio Abismal**. ( https://vestibles.cl/proyectos/ttt-textiles-tecnicas-tecnologias-2023/): especulaciones que se desprenden del proyecto TTT2 https://www.academia.edu/144409160/TTT2_La_Piel_Tejida_Codificar_y_Significar_mediante_una_proto_Escritura_Desde_una_constelaci%C3%B3n_de_lenguaje_s_ 

Antes de construir las 24 trenzas, el sistema se prueba con una sola estructura para observar cómo diferentes condiciones pueden producir una trayectoria irregular.

La primera trenza se construye a partir de tres componentes:

```text
CONTENCIÓN
    +
RUIDO
    +
ENTROPÍA
```

La intención no es dibujar una trenza previamente definida, sino observar qué ocurre cuando una trayectoria se modifica progresivamente mediante estas tres condiciones.

---

## 02 — Contención

La contención establece un límite espacial para el desplazamiento de la trayectoria.

El sistema puede desviarse, pero permanece dentro de un territorio determinado.

```text
trayectoria
     ↓
desviación
     ↓
límite
     ↓
contención
```

La contención funciona como una condición que evita que la trayectoria se disperse indefinidamente.

No elimina el ruido: **lo mantiene dentro de un campo de acción**.

---

## 03 — Ruido

El ruido introduce pequeñas desviaciones en cada paso de la trayectoria.

Estas desviaciones no están completamente predeterminadas.

En términos computacionales, se utiliza una variación aleatoria controlada.

```text
posición anterior
       +
     ruido
       ↓
nueva posición
```

El ruido permite introducir irregularidad sin abandonar las reglas generales del sistema.

---

## 04 — Entropía y memoria

La entropía se incorpora como una acumulación parcial de las desviaciones anteriores.

La trayectoria no depende únicamente del ruido producido en el punto actual.

También conserva parte de su historia.

```text
desviación
     ↓
acumulación
     ↓
memoria
     ↓
nueva desviación
     ↓
nueva estructura
```

Esto permite explorar computacionalmente una idea central del proyecto:

> **El error no necesariamente se corrige; puede acumularse y convertirse en estructura.**

---

## 05 — Tres hebras

Una vez generada la trayectoria central, se construyen tres hebras alrededor de ella.

Las tres hebras comparten el comportamiento general de la trayectoria, pero se separan mediante una función de torsión.

```text
              trayectoria
                   │
             ┌─────┴─────┐
             ↓     ↓     ↓
           hebra hebra hebra
             1     2     3
```

La torsión produce el entrelazamiento y permite que la trayectoria inicial se convierta en una estructura de tres hebras.

La trenza aparece así como una relación entre:

```text
trayectoria
+
desviación
+
memoria
+
torsión
```

---

## 06 — De una trenza a 24

Después de observar el comportamiento de una única trenza, el experimento se amplía a **24 trenzas**.

Las 24 utilizan las mismas reglas generales, pero reciben diferentes combinaciones de parámetros.

Entre ellos:

* contención;
* ruido;
* entropía;
* torsión;
* radio de entrelazamiento;
* microdesviaciones.

La intención es producir **variaciones de un mismo sistema**, no 24 formas completamente independientes.

```text
MISMAS REGLAS
      ↓
DIFERENTES PARÁMETROS
      ↓
24 COMPORTAMIENTOS
      ↓
24 TRENZAS
```

Las 24 trenzas no representan una progresión.

No existe una primera y una última trenza en términos de evolución.

Son **24 configuraciones coexistentes**.

---

## 07 — Color

En una primera prueba se exploró la posibilidad de asignar tres colores a cada trenza.

Sin embargo, una asignación de 72 colores independientes producía demasiada diferenciación cromática y debilitaba la relación entre las 24 formas.

Por esta razón se modifica el sistema.

Se establece una paleta común de **8 colores**, que se recombinan en **24 tríadas**.

```text
8 colores base
      ↓
24 combinaciones
      ↓
3 colores por trenza
      ↓
24 trenzas
```

El color deja así de funcionar como una identificación individual de cada trenza.

Su repetición y recombinación introducen una estructura relacional compartida.

---

## 08 — Del azar hacia una gramática

En este primer Colab, algunos parámetros todavía se generan mediante variación controlada.

Esto es deliberado.

En esta etapa se busca explorar el comportamiento del sistema antes de introducir las reglas específicas del diccionario del proyecto.

Por lo tanto:

```text
PRIMERA ETAPA

variación controlada
        ↓
exploración
        ↓
observación
        ↓
ajuste del sistema
```

El objetivo posterior es reemplazar progresivamente esta variación por reglas derivadas del **diccionario de operaciones**.

Entonces el sistema podrá pasar de:

```text
parámetros
     ↓
forma
```

a:

```text
diccionario
     ↓
operaciones
     ↓
combinaciones
     ↓
parámetros
     ↓
comportamiento
     ↓
forma
```

---

## 09 — Qué se ha conseguido en este experimento

Este primer Colab permite comprobar que es posible construir un sistema donde:

* una trayectoria puede incorporar ruido;
* las desviaciones pueden acumularse;
* la trayectoria puede permanecer contenida;
* una trayectoria puede transformarse en tres hebras;
* la torsión puede producir entrelazamiento;
* un mismo conjunto de reglas puede producir 24 variaciones;
* una paleta común puede generar 24 combinaciones cromáticas.

El experimento todavía **no utiliza el diccionario de operaciones ni el QR Abismal como semilla computacional**.

Estas corresponden a etapas posteriores.

---

## 10 — Próximo paso

El siguiente desarrollo será construir el **diccionario de operaciones** como un conjunto de funciones capaces de modificar las trayectorias.

La intención es pasar de un sistema basado parcialmente en variaciones aleatorias a un sistema basado en una **gramática de operaciones**.

```text
01 — Una trenza              ✓
02 — Tres hebras             ✓
03 — 24 trenzas              ✓
04 — 8 colores / 24 tríadas  ✓

05 — Diccionario de operaciones
06 — Combinaciones específicas
07 — QR Abismal como semilla
08 — Sistema generativo final
```

Este primer experimento constituye, por tanto, una **prueba de comportamiento del sistema**, no todavía su versión definitiva.
