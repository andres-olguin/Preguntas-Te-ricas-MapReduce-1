# MapReduce Theory Notes — Fundamentos de procesamiento distribuido

Repositorio de **material académico teórico sobre MapReduce**. Conserva el documento original de preguntas y respuestas y complementa el laboratorio práctico [`mapreduce-csv-pipeline`](https://github.com/andres-olguin/mapreduce-csv-pipeline).

> **Estado:** colección de apuntes. No contiene una implementación ejecutable de MapReduce, un cluster de procesamiento ni resultados de benchmarking.

## Contenido

- [Preguntas Teóricas MapReduce 1.pdf](Preguntas%20Te%C3%B3ricas%20MapReduce%201.pdf): entregable académico original.
- [`docs/`](docs/): estudio de evolución, prioridades y lectura complementaria.

## Conceptos esenciales

| Etapa | Qué hace | Ejemplo didáctico |
|---|---|---|
| **Map** | Convierte registros de entrada en pares clave-valor | `("Drama", 15)` |
| **Shuffle / Sort** | Agrupa valores por clave | `"Drama" -> [15, 20]` |
| **Reduce** | Agrega o resume valores agrupados | `"Drama" -> 35` |

Este ejemplo es ilustrativo; **no representa una ejecución del PDF ni una medición en un entorno distribuido**.

## Cómo aprovechar el repositorio

1. Leer el documento histórico y elaborar un glosario de map, shuffle, reduce, particionado y fallos.
2. Reproducir en papel un conjunto pequeño de pares clave-valor.
3. Comparar los pasos con los scripts de [`mapreduce-csv-pipeline`](https://github.com/andres-olguin/mapreduce-csv-pipeline).
4. Registrar qué partes están paralelizadas y cuáles siguen siendo operaciones locales.
5. Citar las fuentes técnicas utilizadas y separar explicaciones de benchmarks.

## Evolución propuesta

Añadir un glosario estructurado, ejercicios resueltos, diagramas del flujo, escenarios de skew y notas sobre costos de red, memoria y particionado. No convertir este material de lectura en una plataforma artificialmente compleja.

[Plan de ingeniería](docs/ENGINEERING_ROADMAP_2026-11-04.md) · [Estudio de escalabilidad](docs/ARCHITECTURE_SCALABILITY_2026-11-04.md).

**Autoría y derechos:** conservar el PDF original y comprobar permisos de distribución antes de reutilizar su contenido en material comercial.
