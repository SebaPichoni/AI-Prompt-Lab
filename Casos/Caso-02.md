# Caso 02 — Clasificación / Evaluación

## Objetivo

Evaluar si una respuesta de IA ayuda realmente a un cliente.

---

## Escenario ##

Hola, mi notebook está lenta y hace ruido. ¿Conviene formatearla?

---

## Prompt inicial

Respondé la consulta del cliente.

---

## Respuesta ChatGPT

¡Hola! Sí, puede ser que un formateo ayude si la notebook está lenta por problemas de sistema, programas acumulados o virus. Pero si además hace ruido, primero conviene revisarla, porque puede necesitar limpieza interna, mantenimiento del cooler o cambio de pasta térmica. En ese caso, formatearla sola no solucionaría el ruido. Lo ideal sería que la traigas al local para hacer un diagnóstico y decirte qué conviene hacer antes de gastar de más.

---

## Respuesta Gemini

¡Hola! Qué buena pregunta. Te cuento: formatearla puede ayudar un montón si el problema es de software (por ejemplo, si tiene virus, programas pesados o archivos basura acumulados). Sin embargo, el ruido suele ser una señal de alerta de hardware. Por lo general, se debe a que el ventilador está sucio o forzado porque la pasta térmica se secó, lo que hace que la notebook levante temperatura y se ponga lenta para protegerse. ¿Qué te recomendamos? Antes de borrar todo, lo ideal es hacerle un diagnóstico. Traela a Feber Informática acá en Villa Elisa; le hacemos una limpieza interna profunda, cambio de pasta térmica y revisamos el sistema. ¡Así atacamos el problema de raíz y te queda como nueva! Si querés, pasanos el modelo exacto por acá y te vamos asesorando. ¡Te esperamos!

---

## Problemas encontrados

(A completar más adelante)

---

## Prompt mejorado

Tengo esta consulta de un cliente y necesito que generes una respuesta: 
Escenario: Hola, mi notebook está lenta y hace ruido. ¿Conviene formatearla? 

Tarea:
Brindarle al cliente la mejor respuesta posible a su consulta, sin asumir riesgos innecesarios.

Rol: 
Toma el rol de Técnico Informático especializado.

Como deberás proceder:
Analiza la consulta del cliente y efectúa una respuesta humana sin extenderte demasiado, como si el dueño de Feber estuviera contestando.

Prioridades:
-Si falta información para responder correctamente, realiza entre 1 y 3 preguntas relevantes antes de sugerir una solución.
-Prioriza entender el problema antes de emitir una conclusión.
-La precisión del diagnóstico tiene prioridad sobre la rapidez de respuesta.

Restricciones:
Evita dar diagnósticos apresurados o información que sea innecesaria como podría ser: El ruido SE DEBE a tal problema, o LA LENTITUD se debe a tal otro. 

---

## Resultado final

¡Hola! Antes de recomendarte formatearla, conviene revisar un poco el equipo para no hacer un trabajo innecesario.

Te consulto:
¿Hace cuánto empezó a ponerse lenta? ¿El ruido aparece todo el tiempo o cuando abrís programas? ¿Alguna vez se le hizo limpieza interna o mantenimiento?

El formateo puede ayudar en algunos casos, pero si también hay ruido, lo ideal es hacer primero un diagnóstico general para ver si el problema viene del sistema, del uso del disco, temperatura, suciedad interna o algún otro factor. Así te podemos decir con más seguridad qué conviene hacer y evitar que gastes de más.

### Topics ###

✅ hace preguntas primero
✅ evita diagnóstico fuerte
✅ tono humano
✅ evita vender de más
✅ protege al cliente

---

## Conclusión

Durante las pruebas de este caso orientado a clasificación y evaluación sobre una consulta de soporte técnico, se observó que una mejor estructura del prompt permitió modificar el flujo de respuesta del modelo.

En lugar de emitir diagnósticos apresurados o asumir causas específicas, el modelo priorizó realizar preguntas relevantes antes de sugerir soluciones.

Esto permitió reducir incertidumbre, disminuir riesgos y generar una respuesta más segura, precisa y confiable para el cliente.

Se concluye que definir prioridades, restricciones y pasos de razonamiento ayuda a controlar mejor el comportamiento del modelo frente a escenarios con información incompleta.