---
opportunity: mala-entrega-madurez-baja
status: testing-several
chosen: constelacion, alineacion-alcance
tests: product/tests/2026-10-24-1850-mala-entrega-madurez-baja.md
---

# Solutions for: mala entrega en equipos de madurez muy baja

## What the evidence says now
- Toda la evidencia de esta exploración es `synthetic` o `secondary`. No hay reacción real a ninguna solución. El CSV `notas/ensayo/2026-10-22-1743-respuestas-mala-entrega-madurez-baja.csv` es un set de ensayo generado por IA: sirve para ensayar el método, no como evidencia sobre los equipos reales.
- Comunicación con negocio (creencia de la oportunidad): en el set de ensayo, 9 de 27 (33%) declaran alcance claro y buena comunicación; supera el 20% de la regla y la refutaría. Según la guía de la encuesta, antes de darla por refutada se cruza con Q3 y Q4. No se registró anotación en el overview. `synthetic`
- Personas vs. otras causas (creencia 3): solo 4 de 25 respondientes eligen causas de personas; carga (9), negocio (7) y técnica (7) pesan más. `synthetic`
- La evidencia externa sobre constelaciones mide clima y conflicto percibido a 4 meses, no entrega. `secondary` (product/research/2026-09-28-constelaciones-y-causas-de-mala-entrega.md)
- Aceptación (creencia 6): debilitada por la entrevista a Tomás, que no la propondría solo y la aceptaría si la convoca Agilidad con condiciones. `synthetic` (product/insights/2026-10-22-1550-tomas-benitez.md)

## Baseline: what people do today
Retros (16 de 27), cambios de proceso (12), charlas uno a uno (7), talleres (6); solo 1 no hizo nada. 15 de 26 dicen que la entrega mejoró, casi siempre "un poco". Las personas Mariela y Tomás dicen que retros y uno a uno no destraban los conflictos. `synthetic` (set de ensayo y personas). Es lo primero que hay que confirmar con gente real.

## Alternatives
### A1. Constelación organizacional (`constelacion`)
Servicio actual del overview. Una dinámica facilitada que hace visible la relación entre personas y roles sin que nadie tenga que contar ni exponerse. Ataca conflictos y silencio frente al líder. Para Mariela Quiroga y Tomás Benítez (primary). Reemplaza la retro cuando esta no destraba.

### A2. Sesión de alineación de alcance equipo–negocio (`alineacion-alcance`)
Sesión conjunta al inicio del trimestre entre el equipo y quien define los pedidos, con un alcance acordado y un registro de cambios. Ataca alcance difuso y prioridades que cambian. Para SM y líderes con mala relación con negocio; Raúl Ferreyra la vive parcialmente. La persona principal de esta alternativa falta en la oportunidad (ver *Missing*). Reemplaza pedidos por mail, chat y pasillo.

## Comparison
| Alternative | Desirable | Feasible | Viable | Riskiest belief |
|---|---|---|---|---|
| A1 | mixed: pain evidenced, relief not tested (conflicto sin destrabar 7 de 27, `synthetic`; reacción condicional de Tomás, `synthetic`; solo 4 de 25 eligen causas de personas) | to check with tech (costo y capacidad de facilitadores `unknown`) | weak (`secondary`: resultados de clima a 4 meses, no de entrega; Tomás teme que un trimestre no alcance, `synthetic`) | Más del 20% de los convocados acepta con una acción concreta |
| A2 | mixed: pain evidenced, relief not tested (19 de 27 con 3 o más cambios de alcance, pero 9 de 27 declaran buena comunicación; `synthetic`) | to check with tech (depende de que negocio asista; Silvina negocia con las gerencias) | mixed (assumption) | Negocio acepta sentarse a alinear alcance y lo respeta durante el trimestre |

## Decision
Se prueban A1 y A2 en paralelo, por decisión de Roxana, que coincide con la recomendación: atacan las dos causas que compiten en la oportunidad (personas vs. negocio) y compararlas responde la pregunta de la agenda de research. Se descartó A4 por decisión de Roxana. A3 queda en `parked`.

## To test
- A1 — "más del 20% de los agilistas convocados acepta la constelación con una acción concreta" (hipótesis `aceptacion-constelacion`): si los convocados no la aceptan, el resto de la propuesta no importa. Diseñado como T1 en product/tests/2026-10-24-1850-mala-entrega-madurez-baja.md.
- A2 — "negocio acepta sentarse a alinear alcance y lo respeta durante el trimestre": si negocio no asiste o no respeta el acuerdo, la sesión es otra reunión del equipo sin efecto. Se diseña en /design-solution-tests.

## Value proposition: A1. Constelación organizacional
- Pain relieved: las retros terminan en silencio (40 segundos de silencio cada vez que Tomás pregunta qué mejorar) y las charlas uno a uno no se pueden usar sin romper la confianza (personas/tomas-benitez.md, personas/mariela-quiroga.md, `synthetic`).
- Gain created: la dinámica del equipo se hace visible sin exponer a nadie, y el SM recibe conclusiones agregadas con las que puede trabajar, además de entender por qué se va la gente (insight de Tomás, `synthetic`).
- Replaces: la retro, para los equipos donde la gente calla delante del líder. Se cambia si el formato se distingue de una retro desde la primera explicación.
- Deliberately does not: evaluar personas, devolver atribuciones individuales, aplicarse a equipos cuyo problema es técnico o de dependencias (Florencia), ni prometer métricas de entrega dentro de un trimestre.

## Value proposition: A2. Alineación de alcance equipo–negocio
- Pain relieved: pedidos que cambian después de empezar (19 de 27 con 3 o más cambios) y dudas que no se pueden aclarar con negocio (set de ensayo, `synthetic`). Falta una persona que lo sufra: no hay entrevista que lo respalde.
- Gain created: un alcance acordado por trimestre y un registro de cada cambio, visible para ambas partes.
- Replaces: los pedidos por mail, chat y pasillo.
- Deliberately does not: resolver conflictos entre personas, definir las prioridades de negocio, ni sumar un tablero o herramienta nueva.

## Beliefs
- [product] [value] creencia 1 del overview (mando vertical aceptaría participar) — referenciada como registrada
- [product] [value] creencia 3 del overview (personas explican la mala entrega) — referenciada como registrada
- [product] [value] creencia 4 del overview (la constelación lleva a acuerdos concretos) — referenciada como registrada
- [product] [viability] creencia 5 del overview (mejora trimestral) — referenciada como registrada
- [product] [value] creencia 6 del overview (piden la constelación por iniciativa propia) — referenciada como registrada, con su anotación vigente
- [opportunity: mala-entrega-madurez-baja] [value] la falta de comunicación con negocio es un dolor real (20% o menos declara alcance claro y buena comunicación) — referenciada como registrada
- [feature: constelacion] [value] Un conductor externo a Agilidad y una regla explícita de qué se devuelve al SM (solo conclusiones agregadas, sin atribuciones) alcanzan para que los miembros de un equipo con mando vertical participen, pending registration
- [feature: constelacion] [feasibility] Hay facilitadores disponibles a un costo por sesión compatible con el presupuesto de Agilidad, pending registration
- [feature: alineacion-alcance] [value] Con un alcance acordado y un registro de cambios, el equipo reporta menos cambios de alcance sobre pedidos ya iniciados que en el trimestre anterior (umbral a fijar en /design-solution-tests), pending registration
- [feature: alineacion-alcance] [viability] Negocio dedica tiempo a la sesión y firma el alcance, sin que Agilidad tenga que obligarlo, pending registration

## Discarded or parked
- A3. Pulso anónimo de causas con devolución al SM (`pulso-causas`) — parked: no mueve por sí sola las métricas que financia la Gerencia de Agilidad. Volvería si los tests muestran que las causas varían mucho de un equipo a otro, o como instrumento para derivar equipos al servicio correcto.
- A4. Escalamiento de dependencias y ambientes desde Agilidad (`escalamiento-dependencias`) — discarded: decisión de Roxana en esta exploración. Para Florencia (negative) en el segmento de dependencias técnicas.

## Outcome
{Se completa con /analyze-solution-tests.}
