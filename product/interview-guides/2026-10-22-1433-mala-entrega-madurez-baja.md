---
source: design-interview
date: 2026-10-22
opportunity: mala-entrega-madurez-baja
mode: exploration
status: draft
---

# Interview guide: qué pasó con la última entrega que no se cumplió

- **Learning goals:**
  1. **Comunicación con negocio.** Cómo se vive el alcance y la comunicación con negocio en la última entrega mala. Es el "por qué" detrás de la hipótesis `comunicacion-con-negocio`. *Decide:* si negocio pasa a ser candidato a causa.
     - *Creencia en riesgo:* el alcance difuso y la mala comunicación son un dolor real.
     - *Falsificaría:* describen un alcance claro y un canal fluido, y la falla vino por otro lado.
  2. **Qué explicó la mala entrega** (creencia 3 del overview). *Decide:* si la constelación es el servicio adecuado o hay que ofrecer otro.
     - *Creencia en riesgo:* pesan más las personas y los roles que lo técnico o la carga.
     - *Falsificaría:* sus historias se explican por alcance, dependencias o carga, sin conflicto interpersonal.
  3. **Qué se probó y por qué no destrabó.** *(Cubierto con un sondeo en P1, de menor profundidad que la pregunta propia que se quitó.)* *Decide:* cuánto espacio queda para un servicio complementario a retros y uno a uno.
     - *Creencia en riesgo:* retros y uno a uno no destraban estos conflictos.
     - *Falsificaría:* las retros producen acuerdos que se cumplen.
- **Participant profile:** Scrum Master o líder de un equipo de 5 a 20 personas que tuvo al menos un compromiso incumplido en el último trimestre. Subperfiles: tipo Mariela (conflictos que las retros no destrabaron), tipo Florencia (dependencias técnicas, sin conflictos internos), tipo Tomás (rotación alta).
- **Mode:** exploration. No se nombra ni se muestra la constelación.
- **Duration:** 30 a 35 minutos.
- **Language:** español.

## Warm-up (5 min)
W0. *(Guion de confidencialidad, leerlo antes de empezar.)* Esto es una conversación para entender cómo trabajan los equipos. No se evalúa a nadie ni a tu equipo, y no se usa para bonos ni para el ranking. Lo que cuentes se presenta agregado y sin nombres, y lo ve solo quien investiga. Podés saltear cualquier pregunta y cortar cuando quieras.
W1. Contame de tu equipo: cuántos son, hace cuánto trabajan juntos y qué rol tenés vos. *(Confirma el perfil.)*

## Main body
Se arranca por la entrega y no por negocio: preguntar primero por negocio lo instalaría como causa. Que aparezca solo, o no, ya es un dato.

### Objetivo 2: la historia (8 min)
P1. Pensá en la última vez que el equipo no llegó a lo que había comprometido. Contame cómo fue, desde que se asumió el compromiso hasta que se vio que no llegaba.
   - Sondeos: ¿cuándo te diste cuenta? ¿Quién lo notó primero? ¿Qué se dijo en el equipo sobre lo que había pasado? Si responden con una categoría general (por ejemplo "faltó comunicación"): ¿entre quiénes? Contame una vez en que eso se notó. Para el objetivo 3: ¿qué hicieron después, en una retro o de otra forma? ¿Qué se acordó y qué pasó con eso dos semanas después?
P2. En esa entrega, contame un día en el que se complicó algo. ¿Qué pasó?
   - Sondeos: ¿quién estaba? ¿Cómo terminó? ¿Qué más intervino, de adentro o de afuera del equipo? ¿Había pasado algo parecido antes?

### Objetivo 1: negocio (8 min)
P3. Volvamos al principio de esa entrega. ¿Cómo te enteraste de lo que se esperaba?
   - Sondeos: ¿quién te lo contó y cuándo? ¿Quién hablaba con negocio, vos o el líder? ¿Qué sabés de lo que se habló con negocio? ¿Cambió en el camino, y cómo te enteraste? ¿Qué hacés cuando algo no está claro?
P4. ¿Cuándo fue la última vez que una duda del equipo llegó a negocio? ¿Cómo llegó?
   - Sondeos: ¿quién la llevó? ¿Qué respondieron y cuánto tardaron? Si nunca llegó: ¿qué pasó con la duda?

### Cierre del objetivo 2, ya con confianza
P5. Mirando todo lo que me contaste, ¿qué pensás que pasó en realidad con esa entrega?
   - Sondeo: ¿qué fue lo que más pesó? ¿Por qué ese y no otro?
   - Sondeo sobre salidas: en el último año, ¿se fue alguien del equipo? ¿Cuántas personas? Contame la última salida: ¿qué motivo dio la persona y qué pensás vos que pesó? ¿Qué cambió en el equipo después?

### Notas para quien entrevista
- Si el participante es el líder, adaptar las preguntas que mencionan "el líder".
- Si el participante nombra constelaciones u otras dinámicas, preguntar qué conoce y qué vivió, sin explicar el servicio.
- Las preguntas sobre el líder y los conflictos van después de que haya confianza, no en el calentamiento: por eso "qué pensás que pasó en realidad" está al final (P5).
- El SM suele no ver a negocio de cerca; P3 y P4 preguntan cómo se enteró, no qué habló.

## Wrap-up (5 min)
C1. ¿Qué debería haberte preguntado y no te pregunté?
C2. Si le contaras a alguien de otro equipo que hacemos estas charlas, ¿creés que le interesaría? *(No se piden nombres; si el participante los ofrece, se anotan.)*

## Recruitment plan
- **Fuente principal:** los opt-ins de la encuesta `product/surveys/2026-10-22-1418-mala-entrega-madurez-baja.md`. Los canales, el alcance (20 líderes y 50 SM) y los sesgos están en su sección Distribution. Se eligen por sus respuestas, empezando por quienes contradicen una creencia:
  - Creencia 3: Q5 con causas de negocio o dependencias y sin causas de personas (tipo Florencia), frente a R1 "sí" (tipo Mariela).
  - Negocio: Q1 y Q2 buenas pero Q3 con muchos cambios de alcance.
- **Lo que la encuesta no cubre:** líderes de mando vertical que no responden encuestas ni participan en comunidades. Canales propios: la pregunta C2 (referidos) y una invitación personal de Roxana a líderes de equipos con alta rotación.
- **Screener (referidos e invitados directos):**
  - E1. ¿Sos SM o líder de un equipo de 5 a 20 personas? → se descarta si no.
  - E2. En el último trimestre, ¿hubo algún compromiso del equipo que no se cumplió en el plazo? → se descarta si no.
  - E3. ¿Tu trabajo incluye dar bonos o evaluar equipos de agilidad? → se descarta si sí.
- **Target:** de 5 a 8 entrevistas, con al menos 3 por subperfil, o hasta que las respuestas empiecen a repetirse. El tamaño del pool de opt-ins se conoce en la revisión del 25/10.

## Pretest notes
- **2026-10-22.** Corrida contra Mariela Quiroga (primaria), solo estructura de la guía; no es evidencia.
- **Cambiado, con la evidencia que lo motivó:**
  - Agregado W0, guion de confidencialidad, y movida la pregunta "qué pensás que pasó en realidad" al final (P6). Evidencia: Mariela respondió "prefiero no meterme en eso por acá" en el minuto 7.
  - C2 sin pedir nombres. Evidencia: "no quisiera comprometer a nadie".
  - P3 y P4 reescritas desde "cómo te enteraste". Evidencia: la SM no ve a negocio ("eso lo sabe Jorge"), y los sondeos quedaban sin salida.
  - Cortada la antigua P3 (redundante con P1, y "falta de comunicación" no distinguía entre líder, equipo y negocio). P1 sondea ahora "¿entre quiénes?".
  - P2 pide un día concreto en que se complicó algo, con un sondeo neutro de causas de afuera del equipo. Evidencia: la versión anterior devolvió "bien, normal" y era la única que sondeaba lo relacional.
  - Eliminada W2 ("¿cómo es una semana normal?"): no servía a ningún objetivo. Se hizo junto con W0 sin que estuviera entre los tres cambios aprobados; se puede restaurar.
- **Propuesto y no aplicado, a decidir:** el sondeo de "otras actividades" en P5 hace pasar la guía de los 30 a 35 minutos declarados (estimado: unos 42 con la versión anterior).
- **2026-10-22 (después), quitada la antigua P5** (qué hizo el equipo después de la entrega: retros, uno a uno, otras actividades), por pedido de Roxana. El objetivo 3 pasó a cubrirse con un sondeo en P1 ("¿qué hicieron después? ¿qué se acordó y qué pasó dos semanas después?"), a pedido de Roxana. Pierde los sondeos de uno a uno y de otras actividades, así que el "por qué no destrabó" depende de lo que el participante cuente solo; verificarlo en la próxima corrida. La antigua P6 pasó a ser P5; las referencias a "P6" de estas notas son anteriores a esa renumeración.
- **2026-10-22 (después).** Por pedido de Roxana, agregado en la antigua P6 (hoy P5) un sondeo sobre salidas (cuántas personas y motivos, el declarado y el que cree el participante). Cubre el subperfil tipo Tomás y la parte de renuncias de la creencia 3. Va al final porque es sensible; suma unos 2 minutos, así que la duración de 30 a 35 minutos hay que verificarla en la próxima corrida.
