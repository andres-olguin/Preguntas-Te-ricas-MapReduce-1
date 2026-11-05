# mapreduce-theory-notes — Ingeniería, pruebas y escalabilidad realista

**Estado:** plan técnico documentado el 04-11-2026. No constituye resultado experimental ejecutado.

## Evidencia de partida

PDF académico de preguntas teóricas y README breve, sin motor de MapReduce.

## Incrementos de ingeniería

Índice de conceptos, glosario, ejemplo trazado a mano (map, shuffle, reduce), bibliografía y enlace al proyecto mapreduce-csv-pipeline.

## Estrategia de escalabilidad

Mostrar dónde aparecen costos de red, memoria, particionamiento, cardinalidad y skew. Distinguir explicación teórica de benchmark medido.

## Riesgos y condición de aprobación

Proteger derechos de contenidos y citar fuentes; la calidad aquí es pedagogía verificable, no microservicios.

## Protocolo de experimentación y calidad

Cada comparativa debe incluir referencia de código/commit, entorno, versiones, semilla cuando corresponda, entrada reproducible, comando de ejecución, datos brutos, repetición y límites. Separar datos de ejemplo de resultados realmente ejecutados. Mantener código histórico y coautoría intactos; publicar evidencias de tests de CI y pruebas manuales en su contexto, sin inventar métricas.

## Referencias consultadas (2026-11-04)

- [AWS Well-Architected — rendimiento y costo](https://docs.aws.amazon.com/wellarchitected/).
- [NIST SSDF — prácticas seguras de software](https://csrc.nist.gov/pubs/sp/800/218/final).
- [Google SRE — medición y objetivos](https://sre.google/workbook/implementing-slos/).

Las referencias son metodológicas; no corroboran los benchmarks particulares de este repositorio.
