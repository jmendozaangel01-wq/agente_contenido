# Nike — Design System
> Generado automáticamente · Content Studio AI · 2026-07-01
> Basado en análisis de AI Brand Architect — session_id: jxnnoyid

---

## 1. Visual Theme & Atmosphere

**Sector:** Sportswear, Athletic Footwear & Apparel
**Mercado:** Global — presencia en 190+ países; campañas en Norteamérica, Europa, Latinoamérica y Asia-Pacífico
**Audiencia:** Atletas y consumidores inspirados en el deporte, 14-45 años; performance seekers, entusiastas de la cultura sneaker y consumidores lifestyle de todo género
**Postura de marca:** Nike es el líder indiscutido del mercado mundial de ropa deportiva. Fusiona innovación de performance con storytelling cultural de primer nivel. Su posición es dual: marca #1 de performance Y marca #1 de cultura sneaker — dominio que ningún competidor ha igualado.

**Tagline:** Just Do It
**Elevator Pitch:** Nike empodera a cada atleta del planeta — si tienes un cuerpo, eres un atleta — con equipamiento orientado al rendimiento y storytelling cultural que convierte el deporte en un estilo de vida.

---

## 2. Color Palette & Roles

| Nombre | HEX | RGB | Rol |
|---|---|---|---|
| Nike Black | #111111 | rgb(17,17,17) | Primario — fondo, texto, navegación |
| Pure White | #FFFFFF | rgb(255,255,255) | Primario — fondo de cuerpo, texto de contraste, CTAs |
| Charcoal Gray | #707072 | rgb(112,112,114) | Secundario — subtexto, estados deshabilitados, captions |
| Light Silver | #CACACA | rgb(202,202,203) | Terciario — divisores, bordes, líneas UI |
| Soft Mist | #E5E5E5 | rgb(229,229,229) | Terciario — fondos de tarjeta, hover states |
| Deep Navy Overlay | #2B333F | rgb(43,51,63) | Acento — paneles de overlay oscuros, gradientes de hero |

### Color Law
- Nike Black (#111111) es la base dominante en layouts dark-mode y secciones hero — nunca reemplazar por #000000 puro
- White (#FFFFFF) y Nike Black (#111111) deben mantener ratio de contraste mínimo de 7:1 para todo el cuerpo de texto (WCAG AAA)
- Charcoal Gray (#707072) es exclusivo para copy de soporte, metadata y helper text — nunca para headlines
- Light Silver (#CACACA) y Soft Mist (#E5E5E5) solo como elementos estructurales, nunca como declaraciones de marca independientes
- Deep Navy Overlay (#2B333F) solo como panel translúcido o gradiente overlay sobre imágenes
- Prohibido introducir colores externos (rojo, naranja, amarillo) salvo que estén ligados a un equipo o atleta bajo licencia específica

---

## 3. Typography Rules

**Display:** Helvetica Now Text Medium, Helvetica, Arial, sans-serif
**Body:** Helvetica Now Text, Helvetica, Arial, sans-serif

**Reglas:**
- Headlines: 3-6 palabras, CAPS, sin signos de puntuación innecesarios, impacto inmediato
- Body: mínimo — las visuales cargan la narrativa
- Sin serifs, sin decorativas — Helvetica en todas sus formas
- Nunca usar itálicas para énfasis de marca — el énfasis viene de la brevedad y el CAPS

---

## 4. Voice & Tone

**Personalidad:** Empowering · Bold · Aspirational · Inclusive · Direct · Culturally Aware

**Style Guidelines:**
Nike habla con frases cortas y declarativas que llaman a la acción sin vacilación. El copy es enérgico y confiado — nunca pasivo. Los headlines son de 3-6 palabras, todo mayúsculas, directos y provocadores. El body copy es mínimo; los visuales cargan la narrativa. La marca defiende a atletas de todos los orígenes, integrando causas sociales de forma orgánica sin lenguaje performativo. El storytelling está anclado en jornadas atléticas reales, identidad cultural (ej. N7 Indigenous collection) y fuego competitivo.

**Frases que NUNCA se dicen:**
- We offer...
- Our products are...
- High-quality at affordable prices
- Best-in-class solutions
- Leading provider of...
- Please don't hesitate to...
- As an athlete, you might...
- Suitable for all fitness levels

**Frases que SÍ son Nike:**
- Imperativas directas: Run it. / Own the court. / Don't ask permission.
- Declaraciones de verdad atlética: You were built for this.
- Statements culturales sin explicación: N7. For the Earth. For the People.

---

## 5. Brand Audit

| Dimensión | Score |
|---|---|
| Brand Clarity | 96/100 |
| Digital Presence | 88/100 |
| Tone Consistency | 95/100 |
| Visual Consistency | 91/100 |

**Nota de contexto:** Scores excepcionalmente altos reflejan la madurez de la marca. La brecha en Digital Presence (88) está ligada a issues técnicos de performance web (LCP 20s, mobile-friendly fail) — no a debilidad de marca.

---

## 6. Anti-Patterns Visuales

| Patrón Prohibido | Por qué |
|---|---|
| Globe Ban | Metáfora corporativa genérica — Nike habla de atletas reales, no de alcance global abstracto |
| Handshake Ban | Connotación B2B/partnership que contradice el espíritu atlético directo de la marca |
| Three Cards Ban | Layout de features corporativo — Nike no lista beneficios, declara verdades |
| Generic Copy Ban | Frases de marca genérica (ver sección 4) — destruyen la voz construida en décadas |
| Floating UI Ban | Mockups de app sin contexto atlético real — solo si están integrados en narrativa de producto |
| Warm Color Ban | Rojo, naranja, amarillo sin licencia de equipo/atleta — rompen la paleta acromática de la marca |
| Stock Athlete Ban | Imágenes genéricas de persona corriendo sin identidad — Nike siempre tiene un atleta con historia |

---

## 7. Component Arsenal

### Fondos
- **Hero Oscuro:** Nike Black (#111111) sólido — dominante, sin textura, máxima legibilidad
- **Hero Claro:** Pure White (#FFFFFF) sólido — para campañas lifestyle o colecciones estacionales
- **Overlay Cinematográfico:** Fotografía atlética + Deep Navy Overlay (#2B333F) al 60-70% — profundidad sin perder imagen
- **Estructural Minimal:** Soft Mist (#E5E5E5) como base de card o panel secundario — nunca para hero principal

### Tratamiento Visual — Nike Stark
El sistema visual de Nike opera bajo el principio de reducción máxima: un solo sujeto, una sola idea, un solo color de acento si aplica. La composición tiene tensión entre el peso del tipo (CAPS, grande) y el espacio negativo. Nunca más de tres elementos visuales en un mismo frame.

### Elementos Gráficos
- Swoosh: siempre en blanco sobre negro o negro sobre blanco — sin variaciones de color salvo colección licenciada
- Líneas: finas, rectas, estructurales — solo en Light Silver o Charcoal Gray
- Sin gradientes de color, sin sombras decorativas, sin efectos que no sean luz y sombra natural sobre el sujeto

---

## 8. Agent Prompt Guide

**Paleta activa:** Nike Black #111111 / Pure White #FFFFFF / Charcoal Gray #707072 / Deep Navy Overlay #2B333F
**Tono:** Directo · Declarativo · Sin vacilación · Culturalmente enraizado
**Audiencia:** 14-45 · atleta o aspirante a atleta · sneaker culture · multicultural
**CTAs que funcionan:** Shop Now / Get It / Run It / Just Do It
**Qué nunca decir:** Ver Sección 4 — avoid_phrases completo
**Referencia visual primaria:** Campañas Dream Crazy / You Can't Stop Us / N7 Collection

---

## 9. Logo

**Logo URL:** https://upload.wikimedia.org/wikipedia/commons/a/a6/Logo_NIKE.svg
**Versiones aprobadas:**
- Swoosh blanco sobre fondo oscuro (uso primario en hero)
- Swoosh negro sobre fondo claro (uso en colecciones lifestyle/blancas)
- Wordmark NIKE en caps — puede usarse solo o con Swoosh

**Posición en posts:** Esquina inferior izquierda · ~180px de ancho · con margen de seguridad de 24px desde los bordes
**Nunca:** Swoosh en colores de la paleta secundaria · Swoosh rotado · Logo sobre área de textura compleja sin contraste mínimo garantizado

---

## 10. Prompt Engineering — Lecciones Aprobadas en Producción

*Marca nueva — Sección 10 iniciada con reglas universales de Recraft. Se enriquecerá con cada generación real aprobada.*

- **Modelo:** recraftv4.1-vector — nunca v3, nunca style: digital_illustration
- **Nombres de color:** Nunca usar nombres informales (mint, coral, sage, navy) — usar hex exacto o descripción neutra (dark near-black, off-white)
- **Porcentajes:** Nunca en el prompt — usar frases descriptivas (dominant, accent only, structural element)
- **Template fijo:** El agente nunca construye el prompt libremente — siempre usar el template de la skill generar-imagen-recraft
- **Controls RGB:** Pasar colores vía controls en RGB además de mencionarlos en el texto del prompt
- **Paleta acromática:** El sistema Nike es blanco/negro/gris — respetar la austeridad visual; cualquier color adicional debe tener justificación explícita de campaña
