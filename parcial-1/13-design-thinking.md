# 13 · Design Thinking

> **Fuente en el material:** *Día 3 – Innovación tecnológica, creatividad vs. innovación*, diapositivas 30–37.
> **Prerrequisitos:** [11 Creatividad](11-creatividad-y-proceso-creativo.md) y [12 Innovación tecnológica](12-innovacion-tecnologica-e-ia.md).
> **Tiempo estimado:** 50 min.
> **Primer Parcial · Tema 13 de 13** (Día 3). 🔥 Salió en el parcial anterior (pregunta [4](../evaluacion/parcial-anterior-resuelto.md#iii4-design-thinking-qué-es--al-menos-3-etapas)).

---

## 🎯 Objetivos de aprendizaje

1. Definir **Design Thinking** e identificar sus **tres dimensiones** (personas, tecnología, negocio).
2. Describir sus **cinco etapas** en orden, con técnicas de cada una.
3. Explicar sus **siete características**, su **importancia** y sus **beneficios**.
4. Analizar **casos de empresas** que lo usaron y **por qué**.
5. **Aplicar** Design Thinking a un problema concreto.

---

## 🗺️ Esquema del tema

- **I. Definición**
- **II. Etapas**
  1. Empatizar
  2. Definir
  3. Idear
  4. Prototipar
  5. Evaluar / testear
- **III. Características** (7)
- **IV. Importancia** (5)
- **V. Beneficios** (6)
- **VI. Empresas que lo utilizan**
- **VII. Por qué lo utilizaron** (4 razones)
- **VIII. Caso aplicado paso a paso**

---

## 🧠 Mapa visual

```mermaid
flowchart LR
    E["1. EMPATIZAR<br/>entender al usuario"] --> D["2. DEFINIR<br/>el problema real"]
    D --> I["3. IDEAR<br/>muchas soluciones"]
    I --> P["4. PROTOTIPAR<br/>rápido y barato"]
    P --> T["5. TESTEAR<br/>con usuarios reales"]
    T -.->|"iterar"| P
    T -.->|"volver a idear"| I
    T -.->|"redefinir"| D
    T -.->|"re-empatizar"| E
```

---

## 📖 Desarrollo

## I. Definición

> 📌 *"El Design Thinking es una **metodología centrada en el ser humano** para **resolver problemas complejos** y **fomentar la innovación**, integrando **necesidades de los usuarios, tecnología y requisitos de negocio**."*

Las tres dimensiones que integra:

```mermaid
flowchart TB
    U["👤 PERSONAS<br/>¿es deseable?<br/>necesidades del usuario"]
    T["⚙️ TECNOLOGÍA<br/>¿es factible?"]
    N["💼 NEGOCIO<br/>¿es viable?<br/>requisitos de negocio"]
    U --> INN(["Innovación"])
    T --> INN
    N --> INN
```

> ➕ **Contexto adicional:** IDEO (la consultora que popularizó el método) habla de **deseabilidad, factibilidad y viabilidad**: una buena innovación está en la intersección de las tres. El modelo de 5 etapas que usa la cátedra es el de la **d.school de Stanford**.

> 💡 **Para entenderlo:** la mayoría de los fracasos tecnológicos empiezan por la tecnología ("tenemos esta tecnología, ¿qué hacemos?"). Design Thinking **empieza por la persona** ("¿qué le pasa a esta persona?") y recién después busca la tecnología. Por eso es la respuesta directa al problema n.º 1 de innovar: **falta de comprensión del usuario** (módulo [12](12-innovacion-tecnologica-e-ia.md)).

> 📝 **Citar y explayarse:** La cátedra define el Design Thinking como *"una metodología centrada en el ser humano para resolver problemas complejos y fomentar la innovación"*, que integra *"necesidades de los usuarios, tecnología y requisitos de negocio"*. Que esté **centrada en el ser humano** significa que el punto de partida no es la tecnología disponible sino la persona y su problema: primero se empatiza y se define el reto, y recién después se idean, prototipan y testean soluciones. Integrar las tres dimensiones asegura que la solución sea **deseable** para el usuario, **factible** técnicamente y **viable** para el negocio. Además es iterativa: el testeo puede devolver al equipo a cualquier etapa anterior. Por ejemplo, una app de turnos médicos diseñada así empezaría observando a pacientes mayores pedir turno, y no por elegir la tecnología.

---

## II. Etapas

| # | Etapa | Qué se hace (cátedra) | Técnicas / productos |
|---|---|---|---|
| 1 | **Empatizar** (*Empathize*) | **Investigar y comprender** las necesidades, pensamientos, **emociones y motivaciones** del público objetivo. **Observar, escuchar y ponerse en la piel del usuario.** | **Entrevistas**, **inmersión**, **mapas de empatía**. |
| 2 | **Definir** (*Define*) | **Procesar y analizar** la información para **enfocar el problema real** y establecer un **punto de vista** claro. Se seleccionan los hallazgos más relevantes para un **enunciado del problema o "reto"**. | Enunciado del reto (*point of view*). |
| 3 | **Idear** (*Ideate*) | Generar **la mayor cantidad de soluciones posibles**, **sin restricciones ni juicios**. Pensamiento creativo y **lluvia de ideas**. | Brainstorming, SCAMPER, etc. (módulo [11](11-creatividad-y-proceso-creativo.md)). |
| 4 | **Prototipar** (*Prototype*) | Construir **versiones rápidas, económicas y tangibles** de las ideas para **evaluar su viabilidad**. | **Maquetas, dibujos, storyboards**, simulaciones. |
| 5 | **Evaluar / testear** (*Test*) | **Probar los prototipos con usuarios reales** para recibir **feedback** y validar si la solución funciona. **Es iterativa**: suele llevar a perfeccionar el prototipo **o volver a fases anteriores**. | Pruebas de usuario. |

> ⚠️ **No es lineal:** la cátedra subraya que el testeo **puede llevar a volver a cualquier etapa anterior**. Por eso en el diagrama hay flechas de retorno.

> 💡 **Divergir y converger otra vez:** Empatizar (divergir: juntar información) → Definir (converger: un reto) → Idear (divergir: muchas ideas) → Prototipar/Testear (converger: la que funciona). Es el mismo patrón de las reglas del proceso creativo.

```mermaid
flowchart LR
    A(("Inicio")) -->|"divergir"| E["Empatizar"]
    E -->|"converger"| D["Definir"]
    D -->|"divergir"| I["Idear"]
    I -->|"converger"| PT["Prototipar y testear"]
```

---

## III. Características

| # | Característica | Explicación |
|---|---|---|
| 1 | **Centrado en el usuario (empatía)** | Comprender profundamente necesidades, emociones y motivaciones del usuario final. |
| 2 | **Colaborativo y multidisciplinario** | Trabajo en equipo con **perfiles diversos**. |
| 3 | **Iterativo** | **No lineal**: se avanza, se retrocede, se prueba y se mejora continuamente. |
| 4 | **Orientado a la acción (prototipado)** | Pasa **rápido de la idea a la acción** con prototipos tangibles. |
| 5 | **Pensamiento abierto y creativo** | Gran **volumen de ideas** sin restricciones iniciales. |
| 6 | **Visual y tangible** | Bocetos, modelos y herramientas visuales para hacer las ideas **comprensibles**. |
| 7 | **Validación constante** | Prototipos testeados con **usuarios reales** → feedback temprano. |

## IV. Importancia

1. **Enfoque centrado en el usuario** – comprender no solo **lo que dicen** los usuarios, sino **lo que necesitan, piensan y sienten**.
2. **Innovación efectiva** – resolver problemas complejos y **diferenciarse** de la competencia aportando valor real.
3. **Aprendizaje y validación rápida** – la iteración (prototipar y testear) **minimiza el riesgo de fracasos costosos** al **fallar rápido y barato**.
4. **Resolución colaborativa** – equipos diversos enriquecen las ideas.
5. **Adaptabilidad** – fomenta creatividad y adaptación ante un mercado cambiante.

## V. Beneficios

| Beneficio | Explicación |
|---|---|
| **Enfoque en el usuario (*customer centric*)** | Soluciones a **problemas verdaderos**. |
| **Innovación disruptiva y creativa** | Lluvia de ideas y **pensamiento divergente** → soluciones más allá de lo convencional. |
| **Reducción de riesgos y costos** | Prototipos rápidos y económicos (**"fail fast"**): errores detectados **temprano**, evitando grandes inversiones en productos fallidos. |
| **Colaboración multidisciplinaria** | **Rompe silos**: diseño + ingeniería + negocio; mejora cultura y eficiencia. |
| **Proceso flexible e iterativo** | Permite **volver atrás** y aprender del feedback constante. |
| **ROI mejorado** | Mayor eficiencia y resultados económicos. |

> 💡 **"Fail fast" (fallar rápido):** si una idea va a fallar, es mucho mejor descubrirlo con un dibujo en papel que con un producto terminado. El costo del error **crece** cuanto más tarde se detecta.

```mermaid
flowchart LR
    A["Error detectado<br/>en un boceto"] -->|"$"| B["Error detectado<br/>en un prototipo"] -->|"$$"| C["Error detectado<br/>en desarrollo"] -->|"$$$"| D["Error detectado<br/>en el mercado<br/>$$$$"]
```

---

## VI. Empresas que utilizan esta metodología

| Empresa | Qué hizo con Design Thinking |
|---|---|
| **Apple** | **Pionera**: enfoca el desarrollo de productos en la **experiencia del usuario** y resuelve problemas de diseño creativamente. |
| **Netflix** | Reinventó su modelo **de alquiler de DVDs al streaming**, priorizando **contenido personalizado** y experiencias atractivas; ofrece contenido bajo demanda **anticipando los deseos** de sus usuarios. |
| **Airbnb** | Transformó la hotelería **empatizando con viajeros y anfitriones**; plataforma fácil de usar y experiencia personalizada. |
| **BBVA** | Rediseñó sus **cajeros automáticos** para hacerlos **más intuitivos, humanos y seguros**. |
| **IKEA** | Diseñó muebles pensando en el **transporte fácil por el consumidor** y la **reducción de costos**. |

## VII. Por qué utilizaron esta metodología

1. **Empatía con el usuario** – entienden necesidades reales **antes** de desarrollar.
2. **Innovación centrada en el humano** – soluciones originales que **la gente realmente desea**.
3. **Prototipado rápido** – probar ideas rápido y **fallar barato para aprender rápido**.
4. **Colaboración interdisciplinaria** – **romper silos** para resolver problemas complejos en conjunto.

---

## VIII. Caso aplicado paso a paso

> 🧩 **Reto:** los estudiantes de la facultad pierden mucho tiempo buscando aulas libres para estudiar en grupo.

| Etapa | Aplicación |
|---|---|
| **1. Empatizar** | Entrevistás a 10 estudiantes y observás los pasillos en hora pico. Hallazgos: recorren 3–4 pisos; los grupos se arman a último momento; se sienten frustrados y "echados" cuando llega un curso. Armás un **mapa de empatía** (qué piensa, siente, dice y hace). |
| **2. Definir** | Reto: *"¿Cómo podríamos ayudar a los grupos de estudio a encontrar un espacio libre y garantizado en menos de 5 minutos?"* |
| **3. Idear** | Lluvia de ideas sin juzgar: app con mapa en tiempo real, sensores de ocupación (IoT), reserva por QR en la puerta, bot de WhatsApp, cartel digital en cada piso, liberar aulas automáticamente… |
| **4. Prototipar** | Hacés un prototipo en Figma de "reserva por QR" + una planilla compartida simulando la disponibilidad (barato y rápido). |
| **5. Testear** | 15 estudiantes lo prueban una semana. Feedback: el QR funciona, pero no quieren instalar otra app → **volvés a idear**: bot de WhatsApp. Iterás. |

> 🔗 Fijate que el paso 5 de este caso se parece mucho a **Lean Startup** (MVP → medir → aprender → pivotar). Las diferencias se ven en el módulo [17](../resto-de-la-materia/17-lean-startup-y-mvp.md).

---

## ⚠️ Conceptos que se confunden

| Se confunde… | …con | Diferencia |
|---|---|---|
| Empatizar | Definir | Empatizar = **recolectar** comprensión del usuario. Definir = **sintetizar** en un enunciado del problema. |
| Prototipar | Producto final | El prototipo es **rápido, barato y tangible**, hecho para **aprender**, no para vender. |
| Design Thinking | Proceso lineal | Es **iterativo**: desde testear se vuelve a cualquier etapa. |
| Design Thinking | "Diseño gráfico" | Es una **metodología de resolución de problemas**, no de estética. |
| Design Thinking | Lean Startup | DT pone el foco en **entender el problema y al usuario**; Lean Startup en **validar un modelo de negocio con métricas** (ver tema 17). Se complementan. |

---

## 🔗 Conexiones

- **← [11 Creatividad](11-creatividad-y-proceso-creativo.md):** reglas (foco en usuario, iteración, interdisciplina).
- **← [12 Innovación tecnológica](12-innovacion-tecnologica-e-ia.md):** problema n.º 1 de innovar.
- **← [07 Gestión 2.0](07-gestion-de-la-innovacion.md):** fracaso aceptado, trabajo interdisciplinario.
- **→ [16 Proyectos](../resto-de-la-materia/16-proyectos-y-estrategia-de-innovacion.md):** DT es la metodología de "experimentación y validación".
- **→ [17 Lean Startup](../resto-de-la-materia/17-lean-startup-y-mvp.md)**.

---

## ✍️ Autoevaluación

**1. Defina Design Thinking.**
<details><summary>Ver respuesta</summary>

Es una **metodología centrada en el ser humano** para **resolver problemas complejos y fomentar la innovación**, integrando **necesidades de los usuarios, tecnología y requisitos de negocio**.
</details>

**2. Describa las cinco etapas en orden.**
<details><summary>Ver respuesta</summary>

(1) **Empatizar**: comprender necesidades, pensamientos, emociones y motivaciones del usuario (entrevistas, inmersión, mapas de empatía). (2) **Definir**: analizar la información y enfocar el problema real en un enunciado o reto. (3) **Idear**: generar la mayor cantidad de soluciones sin restricciones ni juicios. (4) **Prototipar**: versiones rápidas, económicas y tangibles (maquetas, dibujos, storyboards). (5) **Testear**: probar con usuarios reales, recibir feedback y validar; es iterativa y puede llevar a volver a fases anteriores.
</details>

**3. ¿Por qué se dice que Design Thinking reduce riesgos y costos?**
<details><summary>Ver respuesta</summary>

Porque con **prototipos rápidos y económicos** ("fail fast") los errores se **detectan y corrigen tempranamente**, cuando cuesta poco cambiar, evitando grandes inversiones en productos que el mercado no quiere.
</details>

**4. Explique qué hizo BBVA con Design Thinking y qué etapa considera clave en ese caso.**
<details><summary>Ver respuesta</summary>

Rediseñó sus **cajeros automáticos** para hacerlos **más intuitivos, humanos y seguros**, mejorando la relación con sus clientes. La etapa clave es **empatizar** (entender las dificultades y miedos de los usuarios al usar un cajero), complementada por **testear** los nuevos diseños con usuarios reales.
</details>

**5. Mencione cuatro características de Design Thinking.**
<details><summary>Ver respuesta</summary>

Centrado en el usuario (empatía); colaborativo y multidisciplinario; iterativo (no lineal); orientado a la acción (prototipado); pensamiento abierto y creativo; visual y tangible; validación constante.
</details>

---

[← 12 Innovación tecnológica e Inteligencia Artificial](12-innovacion-tecnologica-e-ia.md) · [🏠 Índice](../README.md) · [Terminaste los temas del Primer Parcial → Evaluación](../evaluacion/README.md) · [Resto de la materia → 14 Innovación abierta](../resto-de-la-materia/14-innovacion-abierta.md)
