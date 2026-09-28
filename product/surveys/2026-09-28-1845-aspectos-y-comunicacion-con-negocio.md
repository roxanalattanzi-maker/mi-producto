---
source: survey-design
date: 2026-09-28
opportunity: mala-entrega-madurez-baja
status: draft (sin lanzar)
launched_by: líder de agilidad
---

# Survey: qué afecta la entrega de tu equipo y cómo es la relación con negocio

- **Learning goals:**
  1. Medir cuántos SM declaran alcance claro y buena comunicación con negocio. Decide: si la falta de comunicación con negocio se sostiene como dolor (hipótesis `comunicacion-con-negocio`, umbral: más del 20% la refuta).
  2. Medir qué aspectos pesan más en la entrega, relacionales o de negocio y claridad. Decide: si la constelación es el servicio adecuado o hay que ofrecer otro (creencia 3 del overview).
  3. Saber qué hicieron los equipos hasta ahora y si funcionó. Decide: cuánto espacio hay para un servicio complementario a retros y uno a uno.
  4. Reclutar entrevistados entre quienes viven conflictos que las retros no destrabaron.
- **Target respondents:** Scrum Masters o agilistas de equipos de 5 a 20 personas de la organización.
- **Estimated length:** 11 preguntas más screening y bloque de reclutamiento, unos 5 minutos. Q5 es la más pesada.
- **Lo que NO mide:** la aceptación de la constelación. Preguntar "¿aceptarías?" infla la respuesta; esa hipótesis (`aceptacion-constelacion`) se mide con una acción real, no con esta encuesta.

## Screening
S1. ¿Actualmente sos Scrum Master o agilista de un equipo de trabajo? [sí / no] → se descarta si no.
S2. ¿Cuántas personas tiene ese equipo? [menos de 5 / de 5 a 10 / de 11 a 20 / más de 20] → se descarta si menos de 5 o más de 20.

## Questions
Q1. Durante el último trimestre, ¿con qué frecuencia el alcance de lo que pedía negocio estuvo claro antes de empezar a trabajar? [likert-5 de frecuencia: nunca / casi nunca / a veces / casi siempre / siempre]
   > Goal 1. Cuenta como "alcance claro" si responde casi siempre o siempre.

Q2. La comunicación entre mi equipo y negocio durante el último trimestre fue buena. [likert-5 de acuerdo: totalmente en desacuerdo / en desacuerdo / ni de acuerdo ni en desacuerdo / de acuerdo / totalmente de acuerdo]
   > Goal 1. Cuenta como "buena comunicación" si responde de acuerdo o totalmente de acuerdo.

Q3. En el último trimestre, ¿cuántas veces cambió el alcance de un pedido que el equipo ya había empezado? [ninguna / 1 o 2 / de 3 a 5 / 6 o más / no lo sé]
   > Goals 1 y 2. Conducta observable que contrasta con las opiniones de Q1 y Q2.

Q4. De lo que el equipo se comprometió a entregar el último trimestre, ¿cuánto se entregó en el plazo acordado? [casi todo / la mayor parte / menos de la mitad / casi nada / no se mide]
   > Goals 1 y 2. Define quién tiene "mala entrega" para cruzar.

Q5. De esta lista, elegí hasta 3 aspectos que hoy más afectan el trabajo o la entrega de tu equipo. [múltiple, máximo 3, orden aleatorio por respondiente; escape: "ninguno de estos" y "otro: ____"]
   - Falta de reconocimiento
   - Conflictos de liderazgo
   - Tensiones entre áreas o departamentos
   - Desmotivación del equipo
   - Inseguridad en el rol
   - Resistencia al cambio
   - Falta de comunicación
   - Problemas de sucesión o traspaso de liderazgo
   - Estrés y sobrecarga de trabajo
   - Falta de cohesión en el equipo
   - Desacuerdos en la toma de decisiones
   - Falta de innovación
   - Miedo a equivocarse o fracasar
   - Dificultad para gestionar cambios en la estructura
   - Sentimiento de no pertenecer
   - Falta de confianza entre miembros
   - Desequilibrio entre trabajo y vida personal
   - Falta de claridad en los roles
   - Resistencia a la autoridad
   - Limitaciones por mala gestión de recursos
   - Alcance de los pedidos poco claro *(agregada)*
   - Prioridades que cambian sin aviso desde negocio *(agregada)*
   - Dependencias con otras áreas o ambientes técnicos inestables *(agregada)*
   > Goal 2. Las 20 primeras vienen del catálogo "Aspectos a sanar"; se agregaron las tres últimas porque el catálogo casi no cubre causas de negocio, técnicas o de dependencias. Sin la columna de "herida de infancia": el texto es neutro a propósito.

Q6. En el último año, ¿qué hizo tu equipo para atender esos aspectos? [múltiple: retros / charlas uno a uno / capacitación o taller / coach o facilitador externo / cambios de proceso / nada en particular / otro]
   > Goal 3.

Q7. ¿Los aspectos principales se resolvieron? [sí, del todo / en parte / no / no hicimos nada]
   > Goal 3. Opinión con fundamento en conducta previa (Q6).

Q8. ¿Qué es lo más difícil hoy para que tu equipo entregue bien? [respuesta abierta, opcional]
   > Goals 1 y 2. Se codifica por temas.

## Perfil (al final, no obligatorio)
D1. Antigüedad del equipo: [menos de 1 año / de 1 a 3 / de 3 a 10 / más de 10]
D2. Personas que dejaron el equipo en los últimos 12 meses: [ninguna / 1 o 2 / de 3 a 4 / 5 o más]
D3. Tu antigüedad como SM o agilista en este equipo: [menos de 1 año / de 1 a 3 / más de 3]

## Screening + opt-in (reclutamiento de entrevistas)
R1. En el último año, ¿hubo en tu equipo conflictos entre personas que las retros y las charlas uno a uno no lograron destrabar? [sí / no] → no es candidato si "no".
R2. ¿Aceptarías una conversación de 30 minutos sobre esto? [sí / no]
R3. Si dijiste que sí, ¿cómo te contactamos? [abierta, opcional, solo si R2 = sí]

## Reglas de análisis (fijadas antes de lanzar)
- **Denominador:** los SM que respondieron y pasaron el screening. Informar n y cuántos se convocaron. Con n menor a 30 por segmento, se reportan patrones direccionales, no porcentajes.
- **Hipótesis `comunicacion-con-negocio`:** el porcentaje que responde casi siempre o siempre en Q1 Y de acuerdo o totalmente de acuerdo en Q2. Si es más del 20%, se refuta; si es 20% o menos, se sostiene. Falta fijar el mínimo de respuestas para concluir.
- **Q5, agrupación fijada de antemano:**
  - Negocio y claridad: falta de comunicación, falta de claridad en los roles, tensiones entre áreas, alcance poco claro, prioridades que cambian, y desacuerdos en decisiones.
  - Relacional: conflictos de liderazgo, falta de confianza, falta de cohesión, resistencia a la autoridad, sentimiento de no pertenecer, falta de reconocimiento, miedo a equivocarse.
  - Carga y contexto: estrés y sobrecarga, desequilibrio trabajo y vida, gestión de recursos, dependencias técnicas.
  - El resto se reporta por separado.
- **Cortes que importan:** tamaño del equipo, antigüedad del equipo, rotación (D2) y Q4 (quién entrega mal). El hallazgo suele estar en la diferencia entre segmentos.
- **Contradicciones:** si Q1 y Q2 son buenas pero Q3 muestra muchos cambios de alcance, se marca como candidato a entrevista.
- **Entrevistas:** primero los que contradicen creencias, luego el resto de los que dijeron sí en R2.

## Lanzamiento (lo envía el líder de agilidad)
Que la lance quien administra los bonos tiene un riesgo: los SM pueden responder pensando que se evalúa a su equipo. El efecto probable es inflar Q1 y Q2 ("alcance claro", "buena comunicación"), lo que empujaría el resultado por encima del 20% y refutaría la hipótesis por una razón equivocada. Por eso:
- **Anónima.** No se pide nombre ni equipo. R3 (contacto) es opcional y se guarda separado de las respuestas.
- **Mensaje de invitación** que diga: para qué es ("entender qué afecta la entrega de los equipos"), que no se usa para bonos ni para el ranking, que los resultados se muestran agregados, y quién ve las respuestas. No menciona constelaciones, para no condicionar las respuestas ni generar expectativas.
- **Sin cortes con menos de 5 respondientes.** Los rangos de D1, D2 y D3 ya evitan identificar equipos.
- **Registrar los convocados.** El líder informa cuántos SM recibieron la encuesta y cuántos respondieron. Sin ese número no hay denominador ni tasa de respuesta.
- **Cómo leer el resultado.** Si el porcentaje supera el 20%, se contrasta con Q3 y Q4 antes de dar por refutada la hipótesis: si dicen "alcance claro" pero reportan muchos cambios de alcance y entregas incumplidas, la respuesta declarada es sospechosa. Un resultado de 20% o menos es más confiable, porque el sesgo de deseabilidad empuja en la dirección contraria.
