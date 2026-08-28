# KUGELMAN ACADEMY — HALLAZGOS DE DATOS + MODELO DE EMBUDO INVERSO

> **Complemento de la Auditoría (documento 00).** Aquí incorporo los datos reales de los 4 archivos que subiste + tus respuestas a las 7 preguntas. Todo cálculo estimado está marcado como **`SUPUESTO`**. Nada de esto reemplaza aún los datos críticos que siguen faltando (churn/bajas y capacidad).

---

# A. LO QUE CONFIRMAN LOS DATOS REALES

## A.1 El embudo, medido en 3 periodos (¡es consistente!)

| Periodo | Leads / Conversaciones | CM Agendadas | CM Efectivas | Inscritos | Lead→Inscrito |
|---|---|---|---|---|---|
| **Mayo** (8 may–7 jun, campaña Meta $4,998) | 210 | 29 (13.8%) | 21 (10.0%) | 16 | 7.6% |
| **Julio** (8 jul–6 ago) | 226 | 37 (16.4%) | 26 (11.5%) | 18 | 8.0% |
| **Blended (May+Jul)** | **436** | **66 (15.1%)** | **47 (10.8%)** | **34 (7.8%)** | **7.8%** |

**Tasas de paso confirmadas (blended):**
- Lead → Clase muestra **agendada**: **15%** ← 🔴 *el gran cuello de botella*
- CM agendada → CM **efectiva**: **71%** (buena)
- CM efectiva → **inscrito**: **72%** (excelente — confirma tu observación: "la mayoría que asiste se queda")
- Lead → inscrito global: **7.8%**

> **Conclusión dura:** el negocio cierra muy bien en persona (72% de quien va a la clase muestra se inscribe) pero **pierde el 85% de los leads antes de que agenden**. Cada punto que subamos en "lead→clase muestra" vale oro y **no cuesta pauta adicional**: es proceso de WhatsApp.

## A.2 Economía de la pauta (campaña Mayo, único mes con datos de gasto)

| Métrica | Valor |
|---|---|
| Inversión | $4,998.54 |
| Alcance | 66,459 personas |
| Impresiones | 189,343 |
| **Costo por Lead (CPL)** | **$23.80** |
| Costo por CM agendada | $172.36 |
| Costo por CM efectiva | $238.03 |
| **Costo por inscripción (solo pauta)** | **~$312–357** |
| ROI reportado | $1.24 por cada $1 (⚠️ metodología poco clara; ver nota) |

> ⚠️ **Inconsistencia detectada en el reporte de Mayo:** la tabla de indicadores dice **16 inscripciones**, pero el cálculo de costo usa **14**. Además el ROI de 1.24 no cuadra con 14–16 alumnos × $800 (que serían $11,200–12,800 de ingreso el primer mes vs. $4,998 invertido = ROI ~2.2–2.6x el primer mes, y mucho mayor a lo largo de la permanencia). **El ROI real es probablemente MUCHO mejor que 1.24** — conviene recalcularlo bien, porque subvalora la pauta ante Dirección.

## A.3 De dónde vienen realmente las inscripciones (archivo CLASES MUESTRA 2026)

Inscritos registrados por mes en 2026 (todas las fuentes):

| Ene | Feb | Mar | Abr | May | Jun | Jul | Ago* | **Total YTD** |
|---|---|---|---|---|---|---|---|---|
| 11 | 3 | 1 | 4 | 11 | 6 | 16 | 1* | **53** |

*Agosto incompleto (corte 27-ago).*

**Medio de contacto de los inscritos (todos los meses):** dominan **WhatsApp**, **Recomendación**, **Sitio/visita** y **Visita a escuela**. Facebook directo aporta pocos cierres *directos* — su rol es **generar la conversación**, que luego cierra por WhatsApp.

> **Implicación:** la pauta de Meta es la **boca del embudo** (genera volumen de conversaciones), pero el **cierre vive en WhatsApp y en el boca a boca**. Por eso invertir en el proceso de WhatsApp y en referidos tiene efecto multiplicador sobre TODO el gasto de pauta.

## A.4 Qué creatividad y segmento funcionan (archivo CAMPAÑAS, julio: 235 leads)

- **Anuncio que más leads generó:** *Reel testimonial* (117 de 235 ≈ 50%), seguido de *Reel recorrido instalaciones* (41). → El **video testimonial es tu caballo de batalla**. Coincide con lo que el propio plan detectó (el video rinde más).
- **Segmento con más demanda (de los etiquetados):** **Junior** (20), luego Kids (8) y College (7). *Ojo: la mayoría de leads no traen segmento etiquetado — hueco de datos a corregir en el tracker.*
- **Inscritos de julio por segmento (campaña):** College 3, Junior 3, Kids 1. College convierte bien pese a menos volumen.
- **Etapa donde se estancan los leads:** "Información enviada" (119 de 235) → se manda info y **ahí muere la conversación**. Ese es el punto exacto de fuga operativa.

## A.5 La campaña nueva (agosto) aún no convierte

El tracker de agosto muestra 34 leads (20–27 ago), casi todos en "Información enviada"/"Contactado", **0 inscritos y 0 asistencias a clase muestra todavía**. Es normal por lo reciente, pero **refuerza que el seguimiento post-"info enviada" es donde hay que actuar ya**.

---

# B. MODELO DE EMBUDO INVERSO (de la meta a la pauta)

**Punto de partida:** ~65 alumnos activos (punto medio de tu 60–70) · **`SUPUESTO`**, falta el dato exacto.
**Horizonte:** Sep + Oct + Nov + Dic = **4 meses**.
**Meta:** 100 (mínimo) / 120 (ideal).

## B.1 La variable que no tengo y que cambia todo: BAJAS (churn)

No tengo datos de bajas mensuales. Sin churn no se puede calcular cuántos alumnos **nuevos** hacen falta, porque:

> **Alumnos nuevos necesarios = (Meta − Base actual) + Bajas del periodo**

Uso un **`SUPUESTO`** de churn mensual del **5%** sobre la base (rango típico en academias; hay que validarlo). Sobre ~65–100 alumnos ≈ **4 bajas/mes ≈ 16 bajas en 4 meses**.

## B.2 Escenarios (con supuestos explícitos)

| | 🟢 CONSERVADOR | 🎯 OBJETIVO | 🔴 AGRESIVO |
|---|---|---|---|
| Meta alumnos (dic) | 100 | 110 | 120 |
| Crecimiento neto | +35 | +45 | +55 |
| Bajas estimadas (churn 5% `SUPUESTO`) | ~16 | ~18 | ~20 |
| **Inscritos brutos necesarios (4 meses)** | **~51** | **~63** | **~75** |
| **Inscritos brutos / mes** | **~13** | **~16** | **~19** |
| Leads necesarios/mes (a 7.8% actual) | ~165 | ~205 | ~245 |
| Leads necesarios/mes (si subimos a 11%*) | ~118 | ~145 | ~173 |
| Pauta Meta/mes (a CPL $23.80, 100% pauta) | ~$3,900 | ~$4,900 | ~$5,800 |

*(*) 11% = lo que lograríamos si el tramo lead→clase muestra sube del 15% al ~22% manteniendo el cierre. Ver B.3.*

## B.3 El hallazgo central para Dirección

**El sistema ACTUAL ($5,000/mes en Meta) ya produce ~16–18 inscritos brutos/mes** (Mayo 16, Julio 18). Eso significa:

- El escenario **OBJETIVO (110)** es alcanzable **prácticamente con el gasto actual**, *si la conversión se mantiene y sumamos el orgánico/referidos que hoy no medimos*.
- El escenario **AGRESIVO (120)** NO requiere necesariamente duplicar la pauta. Requiere **subir la conversión lead→clase muestra del 15% a ~22%** (proceso de WhatsApp) **+** activar referidos y reactivación. Con eso, los **mismos ~210 leads/$5k producirían ~23 inscritos** en lugar de 16.

> **Mensaje a Dirección:** *"Con lo que ya gastamos podemos acercarnos a la meta. El crecimiento extra sale de arreglar el seguimiento y activar referidos —no de gastar más—. El presupuesto adicional (hasta $10k) lo reservamos para escalar SOLO lo que ya demostró que convierte (reel testimonial + remarketing) y para meses pico (Buen Fin)."*

## B.4 Dos frenos que pueden invalidar el modelo (riesgos duros)

1. **Capacidad (DATO NO DISPONIBLE):** llegar a 100–120 exige tener grupos/horarios/profesores para ~35–55 alumnos nuevos netos. Con grupos de máx. 12, son **~3 a 5 grupos nuevos o muchos lugares libres en los actuales**. *Si no hay capacidad, generar más demanda quema dinero.* **Este es el dato #1 que necesito.**
2. **Churn real (DATO NO DISPONIBLE):** si las bajas superan el 5%/mes, los brutos necesarios suben rápido. Ej.: a 8% de churn, el escenario Objetivo pasa de ~63 a ~78 inscritos brutos.

---

# C. ESTADO ACTUALIZADO DE LAS 7 PREGUNTAS

| # | Pregunta | Respuesta recibida | Estado |
|---|---|---|---|
| 1 | Alumnos activos y por producto | ~60–70; sin desglose por producto | 🟡 Parcial |
| 2 | Grupos / lugares libres | No disponible | 🔴 Falta (crítico) |
| 3 | Presupuesto | **$10,000/mes total; ~$5,000 a Meta** | ✅ |
| 4 | Campaña activa | Sí, nueva (arrancó ~20 ago), $5,000; datos en Excel | ✅ |
| 5 | Equipo / quién cierra | Hay responsable; falta mejorar proceso de cierre; orientar a clase muestra funciona | ✅ (confirmado por datos) |
| 6 | Meta | **100 mínimo, 120+ ideal**; meta de ingresos existe pero no compartida | 🟡 Parcial |
| 7 | Profesores / capacidad | No disponible | 🔴 Falta (crítico) |

## Datos que siguen bloqueando el dimensionamiento fino
- 🔴 **Bajas mensuales (churn)** y motivos.
- 🔴 **Capacidad:** nº de grupos, alumnos por grupo, lugares libres, nº de profesores, techo de la academia.
- 🟡 Desglose de los ~65 alumnos por producto.
- 🟡 Meta de ingresos.

---

# D. QUÉ CAMBIA EN LAS PRIORIDADES (ya con datos)

1. **P0 confirmado y cuantificado — Proceso de WhatsApp / seguimiento.** El 50% de los leads muere en "Información enviada". Subir lead→clase muestra del 15% al 22% equivale a ~40% más alumnos con el MISMO gasto. Es la palanca #1.
2. **P0 — Escalar el Reel Testimonial.** Ya está probado (50% de los leads de julio). Debe ser el formato núcleo de la pauta y del remarketing.
3. **P0 — Reactivación:** hay cientos de leads en "Información enviada"/"En espera" de julio-agosto ya pagados y sin cerrar. Flujo de reactivación por WhatsApp = alumnos casi gratis.
4. **P1 — Etiquetado del tracker:** la mayoría de leads no traen segmento/producto. Sin eso no podemos optimizar por producto. Arreglo de bajo costo, alto valor analítico.
5. **P1 — Recalcular y comunicar el ROI real de la pauta** (el 1.24 reportado subvalora el resultado y debilita el caso ante Dirección).
6. **P1 — Referidos** (con incentivo que no toque el precio de lista).

---

# E. PRÓXIMO PASO

Con esto puedo construir ya el **Plan de Septiembre semana por semana** (construir la maquinaria) y el esqueleto de Octubre. Pero antes de fijar metas por grupo/producto necesito cerrar **2 datos críticos**:

1. **Bajas mensuales típicas** (aunque sea un promedio aproximado de los últimos meses).
2. **Capacidad:** ¿cuántos grupos hay hoy, con cuántos alumnos y cuántos lugares libres? ¿Cuántos profesores?

Si no los tienes a la mano, propongo arrancar el **Plan de Septiembre igual** (varias tareas de "construir la maquinaria" no dependen de esos datos: WhatsApp, tracker, reactivación, banco de contenido, medición), y en paralelo dejamos como **primera tarea de septiembre** levantar esos dos datos. Así no frenamos la ejecución (principio de velocidad).
