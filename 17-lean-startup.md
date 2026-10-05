# 17 · El método Lean Startup

> **Fuente en el material:** *Proyecto de Innovación Tecnológica – Lean Startup y KPI* (Ing. Mario Barrios), diapositivas 21–23.
> **Prerrequisitos:** [16 Proyectos y estrategia](16-proyectos-y-estrategia-de-innovacion.md), [13 Design Thinking](13-design-thinking.md).
> **Tiempo estimado:** 45 min.
> **Parcial 1:** ⏳ todavía no entra (es posterior al Día 3), **salvo el concepto de MVP**, que el Día 3 menciona: ver [22 · Guía del Parcial 1](22-foco-de-parcial.md).
> 🎯 **[Ruta al Parcial 1](README.md#-ruta-al-parcial-1-empezá-acá):** **Paso 11 · MVP:** leé solo [§I](#i-definición-y-objetivo) y [§IV](#iv-conceptos-clave) → seguí en [23 · V.10](23-parcial-anterior-nokia.md#v10-el-mvp-contra-la-competencia).

---

## 🎯 Objetivos de aprendizaje

1. Definir **Lean Startup** y su **objetivo**.
2. Conocer a su creador, **Eric Ries**.
3. Describir las **diez fases** del método en orden.
4. Explicar los conceptos de **Producto Mínimo Viable (MVP)**, **validación**, **iteración** y **pivotar**.
5. Relacionar Lean Startup con **proyectos de innovación**, **Design Thinking** y **KPI**.

---

## 🗺️ Esquema del tema

- **I. Definición y objetivo**
- **II. Eric Ries**
- **III. Las fases del método**
  - A. Entender el problema
    1. Necesidad del cliente
    2. Detección de oportunidad
  - B. Diseñar la solución
    3. Ideación de soluciones
    4. Priorización de la solución
    5. Construcción del MVP según hipótesis
  - C. Aprender del mercado
    6. Medición de resultados
    7. Aprendizaje de errores y detección de fortalezas
    8. Validación
  - D. Decidir
    9. Iteración
    10. Decisión de pivotar
- **IV. Conceptos clave**: MVP, hipótesis, pivotar, iterar
- **V. Lean Startup vs. Design Thinking**
- **VI. Lean Startup en proyectos de innovación**

---

## 🧠 Mapa visual

```mermaid
flowchart TB
    A["1. Necesidad del cliente"] --> B["2. Detección de oportunidad"] --> C["3. Ideación de soluciones"] --> D["4. Priorización"] --> E["5. Construir MVP<br/>según hipótesis"]
    E --> F["6. Medir resultados<br/>feedback de usuarios"]
    F --> G["7. Aprender:<br/>errores y fortalezas"]
    G --> H{"8. ¿Validado por<br/>el mercado?"}
    H -->|"sí, mejorar"| I["9. ITERAR"]
    I --> E
    H -->|"no cumple objetivos"| P["10. PIVOTAR<br/>cambiar aspectos clave"]
    P --> C
    H -->|"sí, cumple expectativas"| OK(["Producto final"])
```

---

## 📖 Desarrollo

## I. Definición y objetivo

> 📌 *"Lean Startup es una **metodología de gestión** creada por **Eric Ries** para **desarrollar negocios y productos de forma más eficiente**. Su objetivo es **reducir el riesgo y evitar el desperdicio de tiempo y dinero** mediante el **lanzamiento rápido de prototipos**, la **experimentación con usuarios reales** y el **aprendizaje continuo**."*

Tres mecanismos de la definición:
1. **Lanzamiento rápido de prototipos** (MVP).
2. **Experimentación con usuarios reales**.
3. **Aprendizaje continuo**.

> 💡 **Para entenderlo – "lean" = "esbelto, sin desperdicio":** el mayor desperdicio en innovación es **construir durante meses algo que nadie quiere**. Lean Startup invierte el orden: primero **probás** con lo mínimo, después **construís**.

> 🔗 **Por qué existe:** responde directamente a la característica **"incertidumbre y riesgo"** de la innovación tecnológica y al problema **"alto costo y riesgo"** de innovar (módulo [12](12-innovacion-tecnologica-e-ia.md)).

> 📝 **Citar y explayarse:** La cátedra define Lean Startup como *"una metodología de gestión creada por Eric Ries para desarrollar negocios y productos de forma más eficiente"*, cuyo objetivo es *"reducir el riesgo y evitar el desperdicio de tiempo y dinero"*. Lo logra invirtiendo el orden tradicional: en lugar de construir durante meses un producto completo y recién después ver si alguien lo quiere, se lanza rápido una versión mínima (el **MVP**), se experimenta con **usuarios reales** y se aprende de los datos. Así, el error se descubre temprano y sale barato. Por eso responde directamente a la **incertidumbre y el riesgo** propios de la innovación tecnológica. Antes de programar un sistema de turnos para gimnasios, por ejemplo, se puede publicar una página con un formulario de demo y medir cuántos dueños se interesan.

---

## II. Eric Ries

- **Emprendedor de Silicon Valley**, nacido en **1979**.
- **Autor reconocido del movimiento Lean Startup**, una estrategia empresarial para **reducir el riesgo al lanzar proyectos innovadores**.
- En **2001** se trasladó a Silicon Valley, donde trabajó como **ingeniero de software**.

> ➕ **Contexto adicional:** su libro ***The Lean Startup*** se publicó en **2011**. Ries se inspiró en el *lean manufacturing* de Toyota (eliminar desperdicio) y en el *customer development* de Steve Blank.

---

## III. Las fases del método

> 📌 *Nota del docente:* *"En la aplicación del método Lean Startup se distinguen varias etapas, **desde la detección de la necesidad del cliente** a la **creación del producto** e incluso **el cambio de estrategia cuando sea necesario**."*

### III.A Entender el problema

#### III.A.1 Necesidad del cliente
**Estudio y análisis del público** para detectar los **problemas** con el producto o servicio. Se **definen las necesidades del usuario** en función de la información obtenida.

#### III.A.2 Detección de oportunidad
Con las necesidades definidas, se detecta **la oportunidad de negocio** que solventará los problemas del usuario.

### III.B Diseñar la solución

#### III.B.3 Ideación de soluciones
Estudio de **ideas y posibilidades** sobre cómo abordar el problema existente en el mercado.

#### III.B.4 Priorización de la solución
Tras el análisis, se **elige una solución** y se **prioriza su desarrollo** con el objetivo de conseguir un **producto mínimo viable**.

#### III.B.5 Construcción del MVP según hipótesis
Desarrollo del producto y sus características **atendiendo al aprendizaje** extraído del análisis previo. El MVP se construye para **poner a prueba hipótesis**.

### III.C Aprender del mercado

#### III.C.6 Medición de resultados
Tras lanzar el producto mínimo **para testearlo**, se **recopila y analiza el feedback** de los usuarios. Luego **se adapta el producto**, mejorando sus características.

#### III.C.7 Aprendizaje de errores y detección de fortalezas
El análisis continuo de todas las fases aporta información sobre **fallos a evitar** y **aspectos positivos** a incluir en otros desarrollos.

#### III.C.8 Validación
Al llegar al producto final, se **decide si cumple con las expectativas del mercado**, en función de los análisis obtenidos.

### III.D Decidir

#### III.D.9 Iteración
**Repetir el proceso de mejora tantas veces como sea necesario** para afinar el producto final.

#### III.D.10 Decisión de pivotar
Si, cumplidas estas etapas, el producto **no cumple los objetivos que demanda el mercado**, lo más conveniente es **pivotar**: **cambiar aspectos clave del negocio** para que encaje en el mercado.

> ➕ **Contexto adicional – el ciclo Construir → Medir → Aprender:** en el libro de Ries, las fases 5–8 se resumen en un bucle continuo: **Construir** (MVP) → **Medir** (datos de uso) → **Aprender** (validar o refutar la hipótesis) → volver a construir. El objetivo es **recorrer el bucle lo más rápido posible**.

```mermaid
flowchart LR
    I(("Ideas")) --> B["CONSTRUIR"] --> P(("Producto / MVP")) --> M["MEDIR"] --> D(("Datos")) --> L["APRENDER"] --> I
```

---

## IV. Conceptos clave

| Concepto | Significado | 🧩 Ejemplo |
|---|---|---|
| **Hipótesis** | Suposición sobre el cliente o el negocio que **todavía no está probada**. | "Los dueños de gimnasios pagarían USD 30/mes por un sistema de turnos online." |
| **MVP (Producto Mínimo Viable)** | La versión **más simple** del producto que permite **probar la hipótesis con usuarios reales**. | Una landing page con un formulario de "reservá tu demo" antes de programar el sistema. |
| **Medir** | Recolectar datos del uso real (no opiniones). | 40 visitas, 12 dejaron su mail, 3 pidieron demo. |
| **Validación** | El mercado confirma (o no) la hipótesis. | 3 gimnasios aceptan pagar → hipótesis validada parcialmente. |
| **Iterar** | Mejorar **sin cambiar el rumbo**. | Agregar recordatorios por WhatsApp porque lo pidieron. |
| **Pivotar** | **Cambiar aspectos clave** del negocio. | Los gimnasios no pagan, pero los consultorios médicos sí → cambiar de segmento. |

> ⚠️ **Iterar vs. pivotar (clásico):** iterar = **ajustar** el producto manteniendo la estrategia. Pivotar = **cambiar algo fundamental** (segmento de cliente, problema, modelo de ingresos, canal). Pivotar **no es fracasar**: es usar lo aprendido para reorientarse.

> 🧩 **Ejemplos famosos de pivote (contexto adicional):** Slack nació como herramienta interna de un estudio de videojuegos; Instagram empezó como una app de check-in (Burbn) y pivotó a fotos.

> 📝 **Citar y explayarse:** Según la nota del docente, en Lean Startup se distinguen etapas que van *"desde la detección de la necesidad del cliente"* hasta *"la creación del producto e incluso el cambio de estrategia cuando sea necesario"*. Primero se entiende el problema, después se diseña la solución y se construye un MVP según hipótesis, luego se mide y se valida con el mercado y, por último, se decide: **iterar** —mejorar sin cambiar el rumbo— o **pivotar** —*"cambiar aspectos clave del negocio"* cuando el producto no cumple lo que demanda el mercado—. Pivotar no es fracasar, sino usar lo aprendido para reorientarse. Instagram es el ejemplo clásico: empezó como una app de check-in y pivotó hacia las fotos al ver que era lo que los usuarios realmente usaban.

---

## V. Lean Startup vs. Design Thinking

> ➕ **Contexto adicional (síntesis comparativa):** ambas metodologías aparecen en la materia y comparten prototipado e iteración, pero tienen focos distintos.

| | **Design Thinking** | **Lean Startup** |
|---|---|---|
| **Pregunta central** | ¿Cuál es el **problema real** del usuario? | ¿Este **producto/negocio** funciona en el mercado? |
| **Punto de partida** | Empatía con las personas | Hipótesis de negocio |
| **Herramienta clave** | Prototipo para **entender** | MVP para **medir** |
| **Evidencia** | Feedback cualitativo de usuarios | **Métricas** de uso real |
| **Decisión típica** | Volver a una etapa anterior | Iterar o **pivotar** |

```mermaid
flowchart LR
    DT["DESIGN THINKING<br/>¿qué problema resolver?"] --> LS["LEAN STARTUP<br/>¿la solución es un negocio viable?"] --> KPI["KPI / OKR<br/>¿estamos logrando los resultados?"]
```

> 💡 **Se complementan:** Design Thinking te ayuda a **encontrar el problema correcto**; Lean Startup a **validar que la solución es un negocio**; los KPI a **medir** el éxito una vez en marcha.

---

## VI. Lean Startup en proyectos de innovación

Relación con los **elementos clave** de un proyecto de innovación (módulo [16](16-proyectos-y-estrategia-de-innovacion.md)):

| Elemento del proyecto | Aporte de Lean Startup |
|---|---|
| Idea y propósito | Fases 1–2: necesidad del cliente y oportunidad. |
| Planificación | Fases 3–4: ideación y priorización. |
| **Experimentación y validación** | Fases 5–8: **MVP, medición, aprendizaje, validación** (el aporte central). |
| Recursos y gestión | Reduce el **desperdicio** de tiempo y dinero; gestiona el riesgo. |
| Generación de valor | Validación con el mercado; **pivotar** si no hay valor. |

Y con la **Gestión 2.0** (módulo [10](10-gestion-de-la-innovacion.md)): Lean Startup **institucionaliza** el pilar "**está bien fracasar, iterar y resiliencia**".

---

## ⚠️ Conceptos que se confunden

| Se confunde… | …con | Diferencia |
|---|---|---|
| MVP | Producto "malo" o incompleto | El MVP es lo **mínimo para aprender** sobre una hipótesis, no un producto mal hecho. |
| Iterar | Pivotar | Ajustar manteniendo el rumbo vs. **cambiar aspectos clave** del negocio. |
| Validación | Opinión favorable | Validar = el **mercado se comporta** como la hipótesis predijo (datos), no que a alguien "le guste". |
| Lean Startup | Design Thinking | Validar el **negocio con métricas** vs. entender el **problema del usuario**. |

---

## 🔗 Conexiones

- **← [16 Proyectos](16-proyectos-y-estrategia-de-innovacion.md):** pregunta "relacione Lean Startup con proyectos de innovación".
- **← [13 Design Thinking](13-design-thinking.md).**
- **→ [18 KPI](18-kpi.md):** la fase "medición de resultados" necesita indicadores.
- **← [15 VANI](15-entornos-vica-y-vani.md):** en un mundo no lineal, experimentar es mejor que planificar a 5 años.

---

## ✍️ Autoevaluación

**1. Defina Lean Startup y su objetivo. ¿Quién lo creó?**
<details><summary>Ver respuesta</summary>

Es una **metodología de gestión** creada por **Eric Ries** (emprendedor de Silicon Valley, n. 1979, ingeniero de software) para **desarrollar negocios y productos de forma más eficiente**. Su objetivo es **reducir el riesgo y evitar el desperdicio de tiempo y dinero** mediante el lanzamiento rápido de prototipos, la experimentación con usuarios reales y el aprendizaje continuo.
</details>

**2. Enumere las fases del método en orden.**
<details><summary>Ver respuesta</summary>

(1) Necesidad del cliente; (2) Detección de oportunidad; (3) Ideación de soluciones; (4) Priorización de la solución; (5) Construcción del MVP según hipótesis; (6) Medición de resultados; (7) Aprendizaje de errores y detección de fortalezas; (8) Validación; (9) Iteración; (10) Decisión de pivotar.
</details>

**3. ¿Qué es un MVP y para qué sirve?**
<details><summary>Ver respuesta</summary>

Es el **Producto Mínimo Viable**: la versión más simple del producto que permite **poner a prueba una hipótesis con usuarios reales**, recopilar feedback y medir resultados antes de invertir en el desarrollo completo, reduciendo riesgo y desperdicio.
</details>

**4. Diferencie iterar de pivotar con un ejemplo.**
<details><summary>Ver respuesta</summary>

**Iterar**: repetir el proceso de mejora para afinar el producto **sin cambiar el rumbo** (ej. mejorar la interfaz de una app de turnos según el feedback). **Pivotar**: si el producto **no cumple los objetivos del mercado**, **cambiar aspectos clave del negocio** para que encaje (ej. pasar de vender a gimnasios a vender a consultorios médicos).
</details>

**5. Aplique Lean Startup a una idea: una app que conecta estudiantes con tutores de la misma facultad.**
<details><summary>Ver respuesta</summary>

(1) Necesidad: estudiantes no encuentran apoyo para finales. (2) Oportunidad: estudiantes avanzados que quieren ingresos. (3–4) Ideas: app, grupo de WhatsApp, planilla; se prioriza lo más simple. (5) MVP: formulario de Google + grupo de WhatsApp. Hipótesis: "los estudiantes pagarían $X por una clase". (6) Medir: inscriptos, clases concretadas, pagos. (7) Aprender: qué materias se piden, qué falla. (8) Validar: ¿se concretan y pagan clases? (9) Iterar: agregar calendario. (10) Pivotar si no pagan: modelo gratuito financiado por la facultad o venta de apuntes.
</details>

---

🎯 [Volver a la Ruta al Parcial 1](README.md#-ruta-al-parcial-1-empezá-acá)

[← 16 Proyectos de innovación y estrategia de innovación](16-proyectos-y-estrategia-de-innovacion.md) · [🏠 Índice](README.md) · [Siguiente por clase → 18 KPI](18-kpi.md)
