# Changelog

Historial de cambios del material. Cada versión tiene un **tag de git con la fecha** (`vAAAA.MM.DD`; si hay más de una en el mismo día: `vAAAA.MM.DD.2`, `.3`…).

## v2026.10.05.6 — 2026-10-05

**Motivo:** los enlaces "Siguiente" seguían el orden numérico de los archivos y no la ruta al parcial.

### Cambiado
- **Navegación de la ruta encadenada:** recuadro 🎯 al inicio de cada módulo con el paso de la ruta, las secciones a leer y el enlace directo al siguiente destino (otra sección o la pregunta del 23); al final de cada pregunta del 23, enlace al paso siguiente. Se puede hacer toda la ruta sin volver al índice.
- **Pies de página:** "Siguiente por clase" en el orden de la cursada (00 → 01 → 02 → 03 → 07 → 08 → 09 → 10 → 04 → 05 → 06 → 11 … → 23), más un enlace para volver a la ruta.
- **Ruta:** Big Data (paso 2) pasa antes que BI y Data Mining (paso 3), para seguir el orden del examen y del módulo 23; la tabla Big Data vs. Data Mining se lee en el paso 3.

## v2026.10.05.5 — 2026-10-05

**Motivo:** el índice seguía el orden de las clases y no llevaba directo al parcial. Se pidió un índice para **ir avanzando paso a paso hasta el parcial**.

### Cambiado
- **README:** el índice principal pasa a ser la **🎯 Ruta al Parcial 1**: 16 pasos en orden (Día 1: objetivo → teoría → caso → simulacro; Día 2: esqueletos → variantes → resto del temario → trampas). Cada paso indica qué secciones leer del módulo, qué pregunta resolver del 23, el tiempo y un checkpoint. Se agrega qué **no** estudiar antes del parcial. El índice por clase queda abajo, como consulta.
- **00, 22 y 23:** remiten a la ruta; el plan de 6 sesiones de la 22 queda para estudiar el temario completo, y la sección VIII de la 23 resume la ruta.

## v2026.10.05.4 — 2026-10-05

**Motivo:** apareció el **parcial de la cursada anterior** (caso Nokia vs. Apple), con alta probabilidad (7–8/10) de repetirse, y se agregaron archivos nuevos en la carpeta `TP/` (caso Nokia de la cátedra y versiones del TP NEXA).

### Agregado
- **23 · Parcial anterior resuelto:** las 10 preguntas (5 teóricas + 5 sobre el caso Nokia) con cita de la cátedra, respuesta modelo **citar y explayarse**, esqueleto para memorizar y trampas; resumen del caso, 8 variantes probables con el mismo caso, tabla Nokia / Kodak / NEXA, plan de 4 h + repaso y simulacro.
- **casos/**: enunciado del parcial anterior, caso Nokia de la cátedra (versión larga, convertido con `markitdown` y limpiado: flechas y tablas reconstruidas), enunciado del TP NEXA y respuestas del grupo (preguntas 1–6, sin datos personales).
- **Glosario:** ambidestreza, cultura del miedo, ecosistema, explotar/explorar, miopía temporal, resiliencia organizacional.

### Cambiado
- **22:** el parcial anterior pasa a ser la primera señal de prioridad (aviso en la cabecera, fila en la sección III y nueva sección IX); el **MVP entra** en el alcance.
- **README** y **00:** acceso directo al módulo 23 y a `casos/`.

### Fuera del repo
- `TP-md/`: conversión a markdown de todos los archivos de `TP/` (incluidos borradores).

## v2026.10.05.3 — 2026-10-05

**Motivo:** el índice no seguía el orden de la cursada y no estaba claro qué estudiar. Alcance del **Parcial 1: todo hasta el Día 3** (puede ampliarse).

### Cambiado
- **README**: índice reordenado **por clase** (Clase 1 → Clase 2 → Clase 3 → Día 3), separando lo que entra en el Parcial 1 de lo posterior; mapa de la materia nuevo.
- **00**: el orden sugerido pasa a ser el de las clases.
- **Cabecera de cada módulo (01–19)**: indica si entra en el Parcial 1 y en qué clase se dio.
- **22** pasa a ser la **Guía del Parcial 1**: alcance actualizable, plan de estudio en 6 sesiones, prioridades de los módulos 01–15, posibles preguntas resueltas (**MVP** y **etapas del proceso creativo**), mapa del TP NEXA por módulo, 5 preguntas de práctica nuevas para la Clase 3 y el Día 3, y checklist por clase.

## v2026.10.05.2 — 2026-10-05

**Motivo:** el profesor pidió **no citar a secas, sino citar y explayarse**, y advirtió que la diapositiva de *Objetivos* de Big Data mezcla contenido de Data Mining (los apuntes hay que leerlos con criterio).

### Agregado
- Convención **📝 Citar y explayarse** (README y módulo 00): párrafo modelo que cita a la cátedra y la desarrolla con palabras propias, ejemplo y consecuencia.
- **51 bloques 📝** en los módulos 01–19, uno por cada definición o idea central de la cátedra.
- **06 · III.+ Lectura crítica**: tabla que separa, objetivo por objetivo, qué es Big Data y qué es en rigor Data Mining; advertencia en *Importancia* y nueva fila en *Conceptos que se confunden*.
- **05**: aviso del cruce con los objetivos de Big Data.
- **22**: la sección III pasa a "citar y desarrollar"; nueva prioridad y checklist sobre el cruce Big Data / Data Mining.

### Cambiado
- Se reemplazó el consejo de saber definiciones "casi textuales" por "citar y explayarse" (00, 04, 22, README).
- **09**: la lectura del gráfico País 1–4 queda como interpretación del apunte (coherente con Schumpeter), no como dato de la diapositiva.

## v2026.10.05 — 2026-10-05

**Fuentes integradas:** apunte de cursada (PDF *Tecnología e Innovación*, Clases 1–2) y notas de clase (*Tendencias Tecnológicas*: Clase 1, Clase 2, Clase 3, repaso).

### Agregado
- **22 · Foco de parcial**: señales de prioridad, mapa por módulo, definiciones textuales, preguntas probables y checklist.
- Nueva convención **🔥 Prioridad de parcial** (README y módulo 00).
- **01**: frase de clase *"una tecnología desarrollada que no se utiliza no es innovación"*; marcas de prioridad en la pregunta de apertura y en la relación tripartita.
- **03**: síntesis de clase (cambio de paradigma · deja obsoleta a la anterior · cambio brusco); lista rápida de la Clase 1; ejemplo Nokia–Apple; metodologías ágiles y pivotar en el paso 7; nueva sección **V.+ I+D+i** para no quedar desplazado.
- **04**: marca "PONER EN PARCIAL" en los aspectos clave; síntesis de clase de BI.
- **05**: marcas 🔥 en objetivos, usos y características resaltados en el apunte; síntesis de clase.
- **06**: marca de prioridad y síntesis de clase Big Data / Data Mining.
- **10**: marca de prioridad; piramidal vs. innovación según la clase.
- **21**: pregunta 11 (*"La tecnología mejoró la vida de las personas. ¿Por qué?"*) con respuesta modelo.
- README: sección **Versiones**, fila del módulo 22 y estructura actualizada.

### Corregido
- **09**: la nota sobre el gráfico de barras (País 1–4) queda resuelta con el apunte: *los países que más innovan son los que más crecen*.

## v2026.10.02 — 2026-10-02

- Versión inicial: módulos 00–21 armados a partir de las presentaciones de clase (Escandell y Barrios), glosario, preguntas integradoras y diagramas SVG.
