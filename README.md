# Taller de Ejercicios de Python

**Pontificia Universidad Javeriana**
**Curso:** Procesamiento de Datos
**Estudiante:** Javier Felipe Aldana Jaramillo

Este repositorio contiene los cuadernos (Jupyter Notebooks) desarrollados para el taller de ejercicios de Python, con base en el material del curso (`DatosGranEscala/Lab_01`). En vez de reproducir la teoria completa del material original, cada cuaderno va directo a lo que se pide entregar. La estructura es la misma en los 10 cuadernos:

- **Membrete de identificacion**: universidad, curso, fecha, autor del material original, estudiante, tema y objetivos.
- **Descripcion**: resumen breve y personal de que trata el cuaderno, sin copiar la teoria original.
- **Comandos nuevos**: cada comando o metodo nuevo del tema, con una descripcion muy breve y una celda de codigo propia que lo ejecuta como ejemplo (distinta a los ejercicios del examen). El cuaderno de bono no trae esta seccion porque es un ejercicio integrador que no introduce sintaxis nueva.
- **Solucion del examen/taller**: cada pregunta del cuestionario o actividad del cuaderno original, resuelta con codigo ejecutado (salidas reales, no simuladas) y una "Explicacion" personal y distinta para cada una.
- **Conclusiones**: cierre personal sobre lo aprendido en el cuaderno.

Los 10 cuadernos se ejecutaron de principio a fin sin errores. En el proceso se encontraron dos bugs del material original (una funcion `sum` que tapaba la funcion interna de Python en el cuaderno de Funciones, y una clase `Rectangle` nunca definida en el cuaderno de Clases); ambos quedan documentados con una nota personal en la Descripcion del cuaderno correspondiente.

## Estructura del repositorio

| # | Carpeta | Cuaderno | Tema |
|---|---------|----------|------|
| 01 | [01_cadenas](01_cadenas/) | [cadenas.ipynb](01_cadenas/cadenas.ipynb) | Cadenas (Strings) |
| 02 | [02_tuplas](02_tuplas/) | [tuplas.ipynb](02_tuplas/tuplas.ipynb) | Tuplas |
| 03 | [03_listas](03_listas/) | [listas.ipynb](03_listas/listas.ipynb) | Listas |
| 04 | [04_conjuntos](04_conjuntos/) | [conjuntos.ipynb](04_conjuntos/conjuntos.ipynb) | Conjuntos (Sets) |
| 05 | [05_diccionarios](05_diccionarios/) | [diccionarios.ipynb](05_diccionarios/diccionarios.ipynb) | Diccionarios |
| 06 | [06_condiciones](06_condiciones/) | [condiciones.ipynb](06_condiciones/condiciones.ipynb) | Condiciones |
| 07 | [07_bucles](07_bucles/) | [bucles.ipynb](07_bucles/bucles.ipynb) | Bucles |
| 08 | [08_funciones](08_funciones/) | [funciones.ipynb](08_funciones/funciones.ipynb) | Funciones |
| 09 | [09_clases](09_clases/) | [clases.ipynb](09_clases/clases.ipynb) | Clases (Programacion Orientada a Objetos) |
| 10 | [10_bono](10_bono/) | [bono.ipynb](10_bono/bono.ipynb) | Bono - Ejercicio Integrador |

## Bono

El ejercicio integrador de bono se encuentra en `10_bono/bono.ipynb` y combina varias de las estructuras y conceptos trabajados a lo largo del taller.

## Notas

- Fecha acordada en clase: 14 de agosto de 2026 (ver membrete de cada cuaderno).
- Cada cuaderno documenta las actividades de forma personal, breve y explicita.
- Los cuadernos ya se ejecutaron de principio a fin (incluidas las salidas y la grafica de la elipse en el cuaderno de Clases); al abrirlos en Jupyter/Colab se puede correr "Run All" para regenerar las salidas si hace falta.
