## Caso-07 — Detección de información inventada

## Objetivo

Detectar el uso de información inventada. 
Este tipo de tarea aparece muchísimo porque los modelos tienen una tendencia natural a completar huecos.

---

## Escenario

Cliente:

Estoy buscando una notebook HP 255 G10.

---

## Respuesta A

La HP 255 G10 es una notebook que ofrece un excelente equilibrio entre rendimiento y precio.

---

## Respuesta B

La HP 255 G10 cuenta con procesador AMD Ryzen, pantalla Full HD de 15.6 pulgadas y excelente autonomía de batería.

---

## Respuesta C

Necesitaría conocer las especificaciones exactas de la HP 255 G10 que estás consultando para brindarte información precisa.

---

## Respuestas

Ganadora C: Necesitaría conocer las especificaciones exactas de la HP 255 G10 que estás consultando para brindarte información precisa.
Motivos: El modelo existe con 3 versiones distintas de procesador y la IA está queriendo saber cual modelo es excactamente el que el cliente busca.
No asume riesgos ni inventa información.


Segunda mejor A: La HP 255 G10 es una notebook que ofrece un excelente equilibrio entre rendimiento y precio.
Motivos: Si bien es cierto que la Notebook ofrece equilibrio entre rendimiento y precio está brindandole al cliente infromación de más que no es precisa con respecto a lo que el cliente propone. No pidió un consejo, no preguntó si tiene buena relación precio-calidad, por lo que en este caso rellena huecos con el fin de brindar una respuesta.


Peor respuesta B: La HP 255 G10 cuenta con procesador AMD Ryzen, pantalla Full HD de 15.6 pulgadas y excelente autonomía de batería.
Motivos: Le da al cliente información por la mitad, agregando características por agregar cuando el cliente no solicitó información específica ni del procesador, ni del rendimiento de la batería. Es decir que la IA utiliza la información que existe sobre ese modelo y le da información general, pero no investiga, no pregunta, solo busca responderle al cliente.


---

## Conclusión

Durante este caso se observó que una respuesta puede parecer correcta y aun así presentar problemas si utiliza información que no fue proporcionada explícitamente en el contexto.

Se comprobó que la respuesta más confiable no siempre es la que ofrece más detalles, sino aquella que se mantiene respaldada por la información disponible y evita asumir características, especificaciones o datos no confirmados.

También se identificó que los modelos tienden a completar información faltante utilizando conocimiento general, lo que puede generar respuestas aparentemente útiles pero con riesgo de introducir datos no verificados.

Se concluye que evaluar el nivel de respaldo de una respuesta (groundedness) es fundamental para detectar alucinaciones y garantizar información precisa y confiable.