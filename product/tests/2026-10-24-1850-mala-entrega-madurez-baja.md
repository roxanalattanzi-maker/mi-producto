---
opportunity: mala-entrega-madurez-baja
solutions: product/solutions/2026-10-22-1844-mala-entrega-madurez-baja.md
status: ready
---

# Solution tests for: mala entrega en equipos de madurez muy baja

## Why test
Se testea A1 (`constelacion`). A2 queda sin diseñar y se agregará a este archivo en otra pasada.
La evidencia del dolor es toda `synthetic` (personas, entrevista a Tomás, set de ensayo). Ningún agilista real reaccionó a la propuesta.
El dolor está evidenciado; que la constelación lo alivie no lo está. Este primer paso no prueba alivio: prueba si los agilistas aceptan, con una acción concreta, que Agilidad les ofrezca la constelación.

## T1. constelacion: convocatoria con confirmación de fecha
- **Test status:** ready
- **Belief under test:** "[product] [value] En los equipos antiguos con mando vertical, líderes y miembros que por miedo no hablan en las retros aceptarían participar en una constelación, porque el formato no les pide contar ni exponer lo que les pasa delante de su jerarquía." (creencia 1 del overview). Este test mide a SM y líderes; la participación de los miembros del equipo sigue abierta.
- **Risk:** [value]
- **Test type:** fake-door
- **What we do:**
  1. Antes del envío, Agilidad confirma cuántas sesiones puede atender (cupo) y con qué conductor externo.
  2. Agilidad envía a 40 agilistas un mensaje que explica primero qué es y qué no es: nadie tiene que contar ni exponerse, no es una retro, la conduce alguien externo a Agilidad, dura una hora, al SM solo se le devuelven conclusiones agregadas sin atribuciones, hay seguimiento a las dos semanas y se mide con métricas de entrega que ya existen.
  3. El mensaje pide una acción: confirmar fecha para una constelación con su equipo o inscribirse a una sesión de prueba. También pide responder una pregunta cerrada: si su equipo tiene cada uno de los dolores descritos (sí/no).
  4. Se manda un único recordatorio al día 10, igual para todos. Las confirmaciones se cuentan a los 21 días.
  5. Quien confirma recibe una respuesta honesta: las sesiones tienen cupo y se asignan por orden de confirmación.
- **With whom:** 40 agilistas (SM o líder de equipo) sorteados al azar de los 100 equipos, sin filtrar por dolores. Un agilista por equipo; si un equipo tiene SM y líder, se sortea uno. El sorteo sale de la lista de equipos del área de Agilidad y queda documentado.
- **Material needed:** un mensaje de Agilidad y un formulario de una pantalla con fecha, equipo y la pregunta cerrada de dolores. El diferencial ("nadie cuenta ni se expone") va primero. Incluye las condiciones de Tomás (una hora, seguimiento a las dos semanas, conductor externo, regla de devolución, qué se mide). Incluye un caso de otro equipo solo si existe uno real; si no existe, el mensaje dice que es la primera ronda y no se inventa ninguno. Se deja afuera: descripción del método, precio, promesas de métricas y el ranking de bonos como encuadre (riesgo de que se lea como evaluación).
- **Material:** product/tests/materials/t1-constelacion/ (01-mensaje-convocatoria.md, 02-formulario.md, 03-hoja-de-captura.md)
- **Duration:** 21 días desde el envío, con un recordatorio al día 10.
- **Signal and threshold:** aceptación = el agilista confirma fecha o se inscribe a una sesión de prueba; "me interesa" no cuenta. Tasa = aceptaciones / 40 convocados (denominador fijo: los convocados, no los que respondieron). Umbral: más del 20%, o sea 9 o más de 40. Lectura secundaria descriptiva: aceptación entre quienes declaran los dolores (marcan `sí` en 2 o más de los 4, definición fijada antes del envío); no cambia el denominador ni el umbral.
- **Decision rule:** continue si 9 o más de 40 aceptan · change si 8 o menos aceptan, pero entre quienes declaran los dolores (al menos 8 que los declaren) acepta más del 20%: se revisa el segmento o cómo se presenta · discard (esta versión de la oferta) si 8 o menos aceptan y el segmento con dolores también está en 20% o menos, o si menos de 8 declaran dolores.
- **Expected provenance:** real
- **Next step if it passes:** convocar al resto de los agilistas con el mismo mensaje y el mismo umbral. En paralelo, diseñar un test de concierge con un equipo real para la participación de los miembros y la creencia de factibilidad (facilitadores disponibles a un costo compatible), que es de tech y de Agilidad.

## Results
{Added by /analyze-solution-tests.}

## Decision
{Added by /analyze-solution-tests.}
