# Caso 04 — Clasificación y priorización

## Objetivo

Tengo varios mensajes entrando a Feber Informática. Quiero que la IA determine cuál atender primero.

---

## Prompt inicial

Analiza los siguientes mensajes de clientes y ordénalos por prioridad.

1. Hola, necesito presupuesto para una notebook.
2. Mi PC no enciende y la necesito para trabajar mañana.
3. ¿Tienen mouse gamer?
4. Dejé mi notebook hace una semana y quería consultar el estado.

---

## Respuesta ChatGPT

Ordenaría la prioridad así:

Prioridad	                      Mensaje	                             Motivo
1	2. “Mi PC no enciende y la necesito para trabajar mañana.”	         Es urgente, afecta directamente el trabajo del cliente y tiene una fecha límite clara. Requiere respuesta inmediata.
2	4. “Dejé mi notebook hace una semana y quería consultar el estado.”	 Ya es un cliente con equipo ingresado. Hay que cuidar la confianza y darle seguimiento rápido.
3	1. “Hola, necesito presupuesto para una notebook.”	                 Es una posible venta importante, pero todavía falta entender necesidad, uso y presupuesto.
4	3. “¿Tienen mouse gamer?”	                                         Es una consulta de producto puntual, probablemente de menor urgencia y menor impacto que las anteriores.

Orden final: 2 → 4 → 1 → 3.

---

## Respuesta Gemini

Aquí tenés el orden de prioridad recomendado para responderles, priorizando la urgencia técnica, el compromiso con el cliente actual y el potencial de venta:

1. Prioridad Máxima (Urgencia Operativa)
Mensaje 2: "Mi PC no enciende y la necesito para trabajar mañana."

Por qué: Es un cliente con el trabajo frenado ("no enciende") y un límite de tiempo crítico ("mañana"). Darle una respuesta rápida para que la traiga ya mismo al laboratorio demuestra el compromiso de un local de barrio que salva las papas en las urgencias.

2. Prioridad Alta (Compromiso y Fidelización)
Mensaje 4: "Dejé mi notebook hace una semana y quería consultar el estado."

Por qué: Ya es un cliente que confió en Feber y el equipo lleva una semana en el taller. Responderle rápido transmite transparencia, control del stock de reparaciones y evita la sensación de "olvido".

3. Prioridad Media (Alta Intención de Venta)
Mensaje 1: "Hola, necesito presupuesto para una notebook."

Por qué: Es un lead caliente con intenciones de hacer una inversión fuerte (una notebook). Requiere una respuesta armada (haciéndole las preguntas filtro) para empezar a asesorarlo antes de que consulte en otro lado.

4. Prioridad Baja (Consulta Simple / Accesorio)
Mensaje 3: "¿Tienen mouse gamer?"

Por qué: Es una consulta de mostrador/stock de resolución rápida (un "sí/no" con opciones de modelos). Al ser un accesorio menor, puede esperar unos minutos mientras se resuelven las urgencias técnicas y las ventas mayores.

---

## Aciertos y problemas encontrados

### ChatGPT
Lo bueno:
✅ Directo
✅ Fácil de leer
✅ Va al punto
✅ Excelente formato tabla

Lo malo:
Explica poco.
Por ejemplo:
"Es una posible venta importante"
Sí. Pero no profundiza.

### Gemini
Lo bueno:
✅ Justificación más rica
✅ Entiende relación cliente-negocio
✅ Considera fidelización
✅ Considera urgencia comercial

Lo malo:
Empieza a editorializar.
Por ejemplo:
"salva las papas"
"lead caliente"
Eso ya es interpretación.

---

## Prompt mejorado

Toma el rol de dueño en Feber Informática y realiza las siguientes tareas frente a mensajes y consultas que llegan al local.

Analiza los mensajes de los clientes, entiende sus necesidades y ordénalos priorizando la urgencia de cada uno.

Justifica de forma resumida cada decisión.

Utiliza criterios que estén familiarizados con el local de Feber:

- Urgencia detectable si utiliza frases como:
  "Mi PC o Notebook no enciende y la necesito para mañana."
  "Se me cayó y no tengo imagen y mañana rindo."

- Cliente que tiene un equipo en el taller y aún no ha recibido respuesta en un plazo superior a 3 días hábiles.

- Consulta por venta de productos específicos como:
  notebooks, combos de actualización, monitores o placas de video.

- Consultas simples como:
  horarios de atención, mouse, teclados, toners, mouse pads e insumos de línea de entrada.

Orden de prioridad:

1. Urgencias técnicas que impidan trabajar o estudiar.
2. Clientes con equipos ya ingresados en el taller.
3. Oportunidades comerciales de alto valor.
4. Consultas generales o de bajo impacto.

Clasifica cada consulta como:

- CRÍTICA
- ALTA
- MEDIA
- BAJA

Formato de salida:

| Orden | Prioridad | Mensaje | Motivo |

---

## Resultado final

| ORDEN  |  PRIORIDAD      |      MENSAJE                                                          |    MOTIVO               


| 1      | **CRÍTICA**     | **2. Mi PC no enciende y la necesito para trabajar mañana.**          | Es una urgencia técnica clara: el equipo no enciende y el cliente lo necesita para trabajar al día siguiente. Requiere respuesta inmediata.            
| 2      | **ALTA**        | **4. Dejé mi notebook hace una semana y quería consultar el estado.** | Es un cliente con equipo ya ingresado en taller y pasó más de 3 días hábiles sin respuesta. Hay que priorizar el seguimiento para cuidar la confianza. 
| 3      | **MEDIA**       | **1. Hola, necesito presupuesto para una notebook.**                  | Es una oportunidad comercial importante, ya que consulta por una notebook. Conviene responder rápido, pero no tiene urgencia técnica inmediata.        
| 4      | **BAJA**        | **3. ¿Tienen mouse gamer?**                                           | Es una consulta simple por un insumo o producto de menor impacto. Puede responderse después de las urgencias y seguimientos de taller.                 


---

## Conclusión

Durante este caso se observó que proporcionar contexto específico del negocio mejora significativamente la capacidad del modelo para clasificar y priorizar consultas.

Definir categorías claras, ejemplos reales y criterios de prioridad permite obtener resultados más consistentes y alineados con las necesidades operativas del local.

También se comprobó que los modelos responden mejor cuando las reglas de priorización son explícitas y no quedan sujetas a interpretación.