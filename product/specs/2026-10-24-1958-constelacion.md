# Constelación organizacional para equipos con mando vertical

> Estado de la evidencia: todo lo que respalda el problema y las reacciones es `synthetic` (personas, entrevista a Tomás, set de ensayo) o `secondary`. Ningún agilista real reaccionó todavía a la propuesta. El riesgo más grande (T1) no corrió.

## Problema
Los equipos de madurez muy baja con mando vertical entregan mal y pierden gente, y las retros y las charlas uno a uno no destraban los conflictos: en la retro nadie habla delante del líder, y en privado la gente cuenta todo pero pide que no se repita. El SM sabe lo que pasa y no puede usarlo sin romper la confianza. Se enmarca ahora porque la Gerencia de Agilidad necesita ver mejoras de calidad, valor y velocidad de entrega en un trimestre para seguir financiando el servicio.
> Evidence: "Eso suena a lo que ya hacemos en la retro: contar cómo es el día y qué le pedimos al otro. Y eso es justo lo que no sale, porque nadie habla si el líder está presente." — Tomás Benítez, product/insights/2026-10-22-1550-tomas-benitez.md (`synthetic`)
> Evidence: "Ya probé todas las dinámicas de retro que existen. El problema no es el formato: es que nadie se anima a decir lo que piensa delante de Jorge." — Mariela Quiroga, product/personas/mariela-quiroga.md (`synthetic`)

## Para quién
- **Tomás Benítez** (primary): SM junior de un equipo donde rotaron 5 de 8 personas en 12 meses; la única entrevista de validación es la suya.
- **Mariela Quiroga** (primary): SM de un equipo antiguo con líder de mando vertical; sufre el mismo problema, sin entrevista todavía.
- Límite: **Florencia Aguirre** (negative). Su mala entrega viene de dependencias técnicas, sin conflictos internos; la constelación no es para ella.

## Recorrido del usuario
Persona principal del recorrido: Tomás, porque es la única con entrevista.
1. **Disparador** — otra retro con silencio (40 segundos cada vez que pregunta qué mejorar) u otra renuncia.
2. Recibe una convocatoria de Agilidad, no la pide él: dice que no la propondría solo por miedo a quedar como "el de la moda". El mensaje empieza por lo que la distingue de una retro: nadie tiene que contar ni exponerse.
3. Mira las condiciones: una hora, conductor externo a Agilidad, qué se le devuelve, seguimiento a las dos semanas, qué se mide y, si existe, un caso de un equipo parecido.
4. Confirma fecha para una constelación con su equipo, o se inscribe a una sesión de prueba.
5. Hace la sesión de una hora con el equipo, conducida por una persona externa. Nadie cuenta nada de su situación.
6. **Valor** — recibe conclusiones agregadas y propuestas, sin atribuciones a personas, y por primera vez tiene un diagnóstico de la dinámica del equipo que puede usar como coach.
7. A las dos semanas hay un seguimiento sobre lo que surgió.
8. **Resultado** — entiende mejor por qué se va la gente y tiene acuerdos con seguimiento, sin haber roto la confianza de nadie. Que haya acuerdos concretos nuevos es una creencia sin verificar.

## Historias críticas

### Una propuesta que no se confunde con una retro
Como Tomás, quiero recibir una propuesta que deje claro desde la primera línea que nadie tiene que contar ni exponerse, para no descartarla como otra retro.

Criterios de aceptación:
- [ ] El primer párrafo del mensaje dice que nadie tiene que contar ni exponerse y que no es una retro.
- [ ] El mensaje indica quién conduce (una persona externa a Agilidad), la duración (una hora), qué se devuelve al SM, el seguimiento a las dos semanas y qué se mide.
- [ ] El mensaje pide una acción concreta: confirmar fecha o inscribirse a una sesión de prueba.
- [ ] El mensaje dice cuántos cupos hay y cómo se asignan.
- [ ] Caso límite: si no existe un caso real de otro equipo, el mensaje lo dice (primera ronda) y no incluye ningún caso inventado.

Traces to: product/insights/2026-10-22-1550-tomas-benitez.md (propuesta que suena a "contar"; condiciones para decir que sí)

### Una devolución que no rompe la confianza
Como Tomás, quiero que lo que se me devuelve esté definido por escrito antes de la sesión y no permita identificar a nadie, para que si algo se filtra no sea yo el responsable.
> Evidence: "'Se les pide' no me alcanza como garantía. Es un acuerdo entre personas y alguien puede contarlo igual, y si se filtra, el que lo organizó soy yo." — Tomás Benítez (`synthetic`)

Criterios de aceptación:
- [ ] Antes de la sesión, el equipo y el SM reciben por escrito qué se devuelve (conclusiones agregadas y propuestas) y qué no (atribuciones individuales).
- [ ] La devolución no menciona ni permite identificar a una persona por nombre, rol o frase.
- [ ] Por escrito se aclara si el SM está presente durante la sesión.
- [ ] La conduce una persona que no es de Agilidad.
- [ ] Caso límite: si el equipo es tan chico que una conclusión permitiría identificar a alguien, esa conclusión se generaliza o se omite.

Traces to: product/insights/2026-10-22-1550-tomas-benitez.md (la confidencialidad tiene que estar garantizada por diseño)

### Un seguimiento que evita que los acuerdos se abandonen
Como Tomás, quiero un seguimiento a las dos semanas de la sesión, para que los acuerdos no queden abandonados como los de las retros.
> Evidence: "Para que valga la pena, necesitaría que haya un seguimiento a las dos semanas, porque si no los acuerdos se abandonan como los de las retros. Con eso, yo estaría dispuesto a probarla con el equipo." — Tomás Benítez (`synthetic`)

Criterios de aceptación:
- [ ] El seguimiento queda agendado al confirmar la fecha de la sesión.
- [ ] En el seguimiento se revisa cada acuerdo y se marca como hecho o no hecho.
- [ ] El seguimiento ocurre a las dos semanas de la sesión, no antes ni después.
- [ ] Caso límite: si la sesión no produjo acuerdos, el seguimiento lo registra y no se inventa ninguno.

Traces to: product/insights/2026-10-22-1550-tomas-benitez.md (condiciones concretas para decir que sí); product/personas/mariela-quiroga.md (planes de mejora abandonados a las dos semanas)

### Una medición que no evalúa lo que cada uno dijo
Como Tomás, quiero que el resultado se mire con las métricas de entrega que el equipo ya tiene, para que nadie sienta que se evalúa lo que dijo en la sesión.

Criterios de aceptación:
- [ ] Antes de la sesión se declara qué métricas se miran y quién las ve.
- [ ] Las métricas son las que ya existen por equipo; no se crea ninguna nueva.
- [ ] No se registra ni se guarda lo dicho durante la sesión.
- [ ] La rotación del equipo se registra aparte de las métricas de entrega.
- [ ] Caso límite: si en un trimestre las métricas no cambian, el informe lo dice sin atribuirlo a personas.

Traces to: product/insights/2026-10-22-1550-tomas-benitez.md (condiciones concretas; el SM necesita entender por qué se va la gente)

## Hipótesis
Creemos que los agilistas (Scrum Masters y líderes de equipo) convocados por Agilidad aceptarán pasar por una constelación con su equipo, confirmando fecha o inscribiéndose a una sesión de prueba, porque las retros y las charlas uno a uno no les destrabaron los dolores y la constelación no les pide exponerse.
Nos equivocamos si el 20% o menos de los convocados acepta dentro de los 21 días (en T1: 8 o menos de 40).

## Alternativas consideradas
Explorado en: product/solutions/2026-10-22-1844-mala-entrega-madurez-baja.md
- A2 Alineación de alcance equipo–negocio — en prueba en paralelo, no descartada.
- A3 Pulso anónimo de causas (`pulso-causas`) — parked: no mueve por sí sola las métricas que financia la Gerencia de Agilidad.
- A4 Escalamiento de dependencias (`escalamiento-dependencias`) — discarded: decisión de Roxana; es para Florencia, fuera del segmento de esta propuesta.

## Probado antes del spec
Probado en: product/tests/2026-10-24-1850-mala-entrega-madurez-baja.md
- T1 Convocatoria con confirmación de fecha — no corrió (envío previsto 25/10/2026, cierre del conteo 16/11/2026) · creencia 1
- riskiest belief not tested (declared): este spec se escribe antes del resultado de T1. Cuando T1 se analice, el resultado se agrega acá.

## Supuestos
Registrados en product/overview.md:
- [product] [value] creencia 1 — aceptarían participar en una constelación. T1 pendiente.
- [product] [value] creencia 3 — la mala entrega se explica sobre todo por conflictos entre personas. Contradicha parcialmente por research (`secondary`).
- [product] [value] creencia 4 — la constelación lleva a acuerdos concretos que no habían surgido en las retros.
- [product] [viability] creencia 5 — mejoran las métricas de entrega en un trimestre. Tomás teme que un trimestre no alcance.
- [product] [value] creencia 6 — la pedirían por iniciativa propia. Debilitada por la entrevista a Tomás (`synthetic`).

Propuestos para registrar (pendientes de aprobación):
- [feature: constelacion] [value] Un conductor externo a Agilidad y una regla explícita de qué se devuelve al SM (solo conclusiones agregadas, sin atribuciones) alcanzan para que los miembros de un equipo con mando vertical participen.
- [feature: constelacion] [feasibility] Hay facilitadores disponibles a un costo por sesión compatible con el presupuesto de Agilidad.
- [feature: constelacion] [value] Que el SM esté presente o no durante la sesión no rompe la confianza del equipo (decisión abierta).
