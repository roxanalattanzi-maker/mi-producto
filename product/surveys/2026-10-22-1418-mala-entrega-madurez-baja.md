---
source: survey-design
date: 2026-10-22
opportunity: mala-entrega-madurez-baja
status: draft
launched_by: Roxana Lattanzi (investigación), no la Gerencia de Agilidad
replaces: 2026-09-28-1845-aspectos-y-comunicacion-con-negocio (descartada por sesgo del remitente)
---

# Survey: qué afecta la entrega de tu equipo y cómo es la relación con negocio

- **Learning goals:**
  - **A. Comunicación con negocio.** Qué % de SM y líderes declara alcance claro Y buena comunicación. *Decide:* si la falta de comunicación con negocio se sostiene como dolor (hipótesis `comunicacion-con-negocio`; 20% o menos la sostiene, más de 20% la refuta).
  - **B. Peso relativo de las causas.** Personas vs. negocio y claridad vs. dependencias técnicas vs. carga. *Decide:* si la constelación es el servicio adecuado o hay que ofrecer otro (creencia 3).
  - **C. Qué se probó y si funcionó.** *Decide:* cuánto espacio hay para un servicio complementario a retros y uno a uno.
  - **D. Reclutar entrevistados** de perfil tipo Mariela (conflictos no destrabados) y tipo Florencia (dependencias técnicas, sin conflictos).
- **Target respondents:** Scrum Masters y líderes de equipos de 5 a 20 personas de la organización.
- **Estimated length:** 8 preguntas, 2 de perfil y bloque de reclutamiento, ~5 minutos.
- **Lo que NO mide:** la aceptación de la constelación. Esa hipótesis (`aceptacion-constelacion`) se mide con una acción real, no con esta encuesta. Tampoco "madurez muy baja": no se autodeclara de forma neutra; se aproxima con tamaño del equipo (S2) y Q4, y al ser anónima no se cruza con el ranking.

## Screening
S1. ¿Qué rol tenés hoy en un equipo de trabajo? [Scrum Master / Líder de equipo / Otro] → se descarta si "Otro".
S2. ¿Cuántas personas tiene tu equipo? [menos de 5 / de 5 a 10 / de 11 a 20 / más de 20] → se descarta si menos de 5 o más de 20.

## Questions
Q1. Durante el último trimestre, ¿con qué frecuencia estuvo claro el alcance de lo que pedía negocio antes de empezar a trabajar? [likert-5 de frecuencia: nunca / casi nunca / a veces / casi siempre / siempre]
   > Goal A. Cuenta como "alcance claro" si responde casi siempre o siempre.

Q2. La comunicación entre mi equipo y negocio durante el último trimestre fue buena. [likert-5 de acuerdo: totalmente en desacuerdo / en desacuerdo / ni de acuerdo ni en desacuerdo / de acuerdo / totalmente de acuerdo]
   > Goal A. Cuenta como "buena comunicación" si responde de acuerdo o totalmente de acuerdo.

Q3. En el último trimestre, ¿cuántas veces cambió el alcance de un pedido que el equipo ya había empezado? [ninguna / 1 o 2 / de 3 a 5 / 6 o más / no lo sé]
   > Goals A y B. Conducta observable que contrasta con las opiniones de Q1 y Q2.

Q4. De lo que el equipo se comprometió a entregar el último trimestre, ¿cuánto se entregó en el plazo acordado? [casi todo / la mayor parte / menos de la mitad / casi nada / no se mide]
   > Goals A y B. Define quién tiene "mala entrega" para cruzar. "Casi todo" salta a Q6.

Q5. Pensá en lo que no se entregó a tiempo. Elegí hasta 2 causas que más pesaron. [múltiple, máximo 2, orden aleatorio por respondiente; escapes: "otro: ____" y "no lo sé"]
   - Conflictos entre personas del equipo
   - Miedo a decir lo que se piensa delante del líder
   - Salida o rotación de personas clave
   - Alcance de los pedidos poco claro
   - Prioridades que cambian desde negocio
   - Poco acceso a negocio para aclarar dudas
   - Dependencias con otras áreas
   - Ambientes o herramientas inestables
   - Calidad o deuda técnica heredada
   - Sobrecarga de trabajo
   - Falta de personas o de conocimientos
   - Estimaciones demasiado optimistas
   > Goal B. 3 opciones por familia, en orden aleatorio, para no empujar hacia ninguna causa (la encuesta descartada tenía 20 de 23 opciones relacionales). Las familias no se muestran al respondiente.

Q6. En el último año, ¿qué hizo tu equipo para mejorar la entrega? [múltiple: retros / charlas uno a uno / capacitación o taller / coach o facilitador externo / cambios de proceso / otras dinámicas grupales / nada en particular / otro: ____]
   > Goal C. "Nada en particular" salta a Q8.

Q7. Desde entonces, la entrega del equipo... [empeoró / quedó igual / mejoró un poco / mejoró mucho]
   > Goal C. Es autoinforme: no prueba causalidad.

Q8. ¿Qué es lo más difícil hoy para que tu equipo entregue bien? [abierta, opcional]
   > Goals A, B y C. Se codifica por temas.

## Perfil (al final, opcional)
D1. Antigüedad del equipo: [menos de 1 año / de 1 a 3 / de 3 a 10 / más de 10]
D2. Personas que dejaron el equipo en los últimos 12 meses: [ninguna / 1 o 2 / de 3 a 4 / 5 o más]

## Screening + opt-in (reclutamiento de entrevistas)
R1. En el último año, ¿hubo en tu equipo conflictos entre personas que las retros y las charlas uno a uno no lograron destrabar? [sí / no / no sé]
R2. ¿Aceptarías una conversación de 30 minutos sobre cómo trabaja tu equipo con negocio y entre personas? [sí / no]
R3. Si dijiste que sí, ¿cómo te contactamos? [abierta, opcional, solo si R2 = sí; se guarda separada de las respuestas]

- **Candidatos:** perfil tipo Mariela = R1 "sí". Perfil tipo Florencia = Q5 con dependencias o ambientes y sin causas de personas. Se entrevista primero a quienes contradicen una creencia.

## Distribution
| Channel | Who it reaches | Approx. reach | Link |
|---|---|---|---|
| Canal de líderes de equipo (lo envía Roxana) | Líderes. Sobrerrepresenta a los más activos y a quienes responden encuestas internas; subrepresenta a los de mando vertical que no participan en canales. | unknown | `?canal=lideres` |
| Comunidad de práctica de SM (lo envía Roxana) | Scrum Masters. Sobrerrepresenta a los más participativos; no llega a quienes están fuera de la comunidad. | unknown | `?canal=sm` |

- **Target n:** al menos 30 por canal (SM y líderes). El subgrupo de mala entrega (Q4) es direccional si queda por debajo de 30.
- **Chequeo de alcance:** la organización tiene 100 equipos (`product/overview.md`). Con un SM por equipo, 30 respuestas de SM serían cerca del 30% del total, exigente para una encuesta interna sin incentivo. Confirmar el alcance real de cada canal antes de lanzar.
- **First review:** 25/10/2026 (domingo; si no hay respuestas, revisar el lunes 26/10).
- **Closes:** 12/11/2026, o antes si se alcanza la meta de n.

## Lanzamiento (lo envía Roxana)
- **Anónima.** No se pide nombre ni equipo. R3 es opcional y se guarda separada.
- **Mensaje de invitación:** para qué es ("entender qué afecta la entrega de los equipos"), que no se usa para bonos ni para el ranking, que los resultados se muestran agregados y quién ve las respuestas. No menciona constelaciones.
- **Un enlace por canal** (`?canal=lideres`, `?canal=sm`) para cortar por canal en el análisis.
- **Registrar cuántas personas recibieron la encuesta por canal.** Sin ese número no hay tasa de respuesta.
- **Sin cortes con menos de 5 respondientes.**

## Reglas de análisis (fijadas antes de lanzar)
- **Denominador:** quienes respondieron y pasaron el screening. Informar n, convocados y tasa por canal.
- **Hipótesis `comunicacion-con-negocio`:** % con Q1 casi siempre o siempre Y Q2 de acuerdo o totalmente de acuerdo. Si es más de 20%, se contrasta con Q3 y Q4 antes de darla por refutada.
- **Q5, agrupación fijada de antemano:** personas (conflictos, miedo, rotación); negocio y claridad (alcance, prioridades, acceso); dependencias y técnica (otras áreas, ambientes, deuda); carga (sobrecarga, falta de gente, estimaciones).
- **Cortes:** canal, tamaño del equipo, antigüedad (D1), rotación (D2) y Q4.
- **Contradicciones:** Q1 y Q2 buenas pero Q3 con muchos cambios de alcance → candidato a entrevista.
