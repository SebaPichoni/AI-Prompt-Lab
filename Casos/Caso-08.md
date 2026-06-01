## Caso 08 - Conflicto entre instrucciones

## Objetivo

Detectar qué ocurre cuando el modelo recibe instrucciones que compiten entre sí.

Este tipo de ejercicios es MUY común en entrenamiento y evaluación de modelos.

---

## Escenario

Se le entrega a la IA el siguiente prompt:

Responde de forma breve y detallada.

Explica qué es una memoria RAM.

---

## Respuesta A

La memoria RAM es un componente que almacena temporalmente los datos que utiliza el sistema mientras está en funcionamiento.

## Respuesta B

La memoria RAM (Random Access Memory) es un componente fundamental de una computadora que almacena temporalmente los datos y programas en uso para permitir un acceso rápido por parte del procesador. Su capacidad influye directamente en la capacidad del sistema para ejecutar múltiples aplicaciones simultáneamente y mejorar la fluidez general del equipo.

---

## Análisis 

Ganadora: B

Motivos:

Intenta balancear brevedad y detalle.
Explica qué es la RAM.
Explica para qué sirve.
Explica impacto práctico.

No es perfecta.

Pero intenta satisfacer ambos requisitos.

Perdedora: A

Motivos:

Muy clara.
Muy breve.
Pero prácticamente ignora la parte de "detallada".

---

## Conclusión

Durante este caso se observó que los modelos pueden recibir instrucciones que compiten entre sí, generando conflictos de interpretación.

Se comprobó que no siempre existe una respuesta claramente correcta, ya que diferentes modelos pueden priorizar distintos objetivos dentro de una misma consigna.

La respuesta A priorizó la brevedad por encima del detalle, mientras que la respuesta B intentó equilibrar ambos requisitos, sacrificando parte de la concisión para aportar más información.

Este caso permitió comprender que la evaluación de respuestas no consiste únicamente en verificar si una instrucción fue cumplida, sino también en analizar cómo el modelo resuelve conflictos entre objetivos simultáneos.

Se concluye que, ante instrucciones potencialmente contradictorias, resulta fundamental identificar qué criterios fueron priorizados y evaluar si esa decisión fue coherente con la intención general del prompt.

### Concepto aprendido

Conflicting Instructions

Los modelos pueden recibir instrucciones que compiten entre sí. En estos casos, el evaluador debe analizar cómo el modelo resolvió el conflicto y qué objetivos decidió priorizar.