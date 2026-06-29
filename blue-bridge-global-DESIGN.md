# Blue Bridge Global — Design System
> Actualizado manualmente · Jairo / 180 Grados · 2026-06-22
> Paleta corregida con colores reales de marca

---

## 1. Visual Theme & Atmosphere

- **Sector:** Business Process Outsourcing (BPO) / AI & Digital Marketing
- **Mercado:** Europa (Bélgica, España) → América Latina (Costa Rica, México, Colombia)
- **Postura:** BPO boutique de élite especializado en expansión Europa→LatAm, posicionado entre los grandes proveedores globales (Teleperformance, Foundever) y los proveedores locales genéricos, con propuesta de valor integrada de expansión estratégica con tecnología AI.
- **Concepto:** Elite BPO y proveedor de agentes AI/humanos especializados en ventas, marketing y soporte técnico. Empodera a empresas europeas para escalar hacia América Latina mediante operaciones localizadas 24/7, marketing digital, gestión de redes sociales y desarrollo de marca.

---

## 2. Color Palette & Roles

| Rol         | Nombre       | Hex       | Uso principal                                      |
|-------------|--------------|-----------|---------------------------------------------------|
| primary     | Electric Blue | `#091FF9` | Fondos dominantes, headers, elementos de autoridad |
| text        | White         | `#FFFFFF` | Todo el texto sobre fondo primary                  |
| accent      | Mint          | `#00FFD5` | Highlights, iconografía tech, CTAs, líneas de acento |
| background_alt | Deep Navy | `#050D6B` | Variante más oscura del primary para profundidad   |

**Color Law:**
- **Regla 1:** El azul eléctrico `#091FF9` es el color de fuerza — fondos de posts, headers, elementos que declaran autoridad. Es intenso y específico. Nunca mezclarlo con otros azules.
- **Regla 2:** El mint `#00FFD5` es el único acento permitido. Úsalo con economía: una línea horizontal, un label, un dato numérico, un CTA. Máximo 2 elementos por composición. Nunca como fondo dominante.
- **Regla 3:** El blanco `#FFFFFF` domina el texto. Es el contrapeso al azul eléctrico. En composiciones sobre fondo azul, todo el copy va en blanco.
- **Regla 4:** `#050D6B` se usa como variante de profundidad — para gradientes tonal muy sutiles, fondos de sección secundaria, o capas de overlay. Nunca como color independiente sin el primary.

**Lo que NUNCA entra en la paleta:**
- Ningún otro azul (no navy oscuro, no celeste, no cobalt)
- Neon, purple, coral, amber, warm colors
- Grises neutros como fondo (la marca es azul eléctrico — no teme al color)

---

## 3. Typography Rules

- **Headlines / Títulos:** Space Grotesk — weights 500, 600, 700 · uso: headlines, statements, títulos de posts
- **Body / Copy / Labels:** Inter — weights 400, 500, 600, 700 · uso: cuerpo de texto, labels, subtext, CTAs, métricas

**Reglas tipográficas:**
- Headlines siempre en Space Grotesk 700, blanco `#FFFFFF` sobre azul eléctrico
- Labels de categoría en Inter 600, mint `#00FFD5`, uppercase, letter-spacing amplio
- Body copy en Inter 400 o 500, blanco `#FFFFFF`
- CTAs en Inter 600, mint `#00FFD5`
- Métricas y datos numéricos en Space Grotesk 700
- Nunca mezclar más de estas 2 familias en una misma composición

---

## 4. Voice & Tone

**Tono general:** Comunicación B2B de alto nivel en inglés, directa y ejecutiva. Uso de vocabulario de expansión y escalabilidad ('scale', 'bridge', 'elite', 'empower'). Frases cortas y contundentes con orientación a métricas y resultados. Énfasis en expertise local en LatAm combinado con estándares globales.

**Personalidad:** Estratégico · Autoritario · Global · Confiable · Innovador · Orientado a resultados

**Lo que SÍ se dice:**
- "Único puente especializado Europa→LatAm con presencia física en ambas regiones"
- "Modelo híbrido AI+humano para mayor eficiencia y personalización en cada interacción"
- "Soluciones 360°: BPO + marketing digital + desarrollo tech + branding bajo un mismo proveedor"
- "Expertise cultural local que elimina barreras regulatorias y económicas en LatAm"
- "Operaciones 24/7 con zonas horarias compatibles entre Europa y América Latina"

**Lo que NUNCA se dice:**
- ~~"Cheap outsourcing"~~
- ~~"Low-cost solutions"~~
- ~~"Basic call center"~~
- ~~"Simple support"~~
- ~~"Generic BPO"~~
- ~~"Soluciones estándar"~~

---

## 5. Brand Audit

**Fortalezas:**
- Especialización exclusiva en el corredor de expansión Europa → América Latina
- Modelo de servicio 360°: BPO + AI + marketing digital + web/app development + branding
- Presencia física real en Bélgica, Costa Rica, México y Colombia (inteligencia local auténtica)
- Tamaño boutique que permite agilidad, personalización y account management senior
- Integración de IA de última generación (customer service, lead gen, content) como diferencial tecnológico
- Barrera de entrada reducida para medianas empresas europeas vs. grandes BPOs

**Scores:**
- Consistencia Visual: 52/100
- Consistencia de Tono: 68/100
- Presencia Digital: 38/100
- Claridad de Marca: 72/100

---

## 6. Anti-Patterns Visuales

| Ban | Prohibición | Por qué |
|-----|-------------|---------|
| **The Globe Ban** | Globo terráqueo, mapa con puntos conectados | Cada BPO lo usa. Invisible. |
| **The Handshake Ban** | Fotos de stock, equipos sonrientes, reuniones de whiteboard | Wallpaper visual. No dice nada. |
| **The Warm Color Ban** | Coral, amber, naranja, verde (excepto mint de paleta), rojo | Destruye la identidad de precisión fría. |
| **The Three Cards Ban** | 3 elementos simétricos idénticos | Default de template. Sin criterio. |
| **The Floating UI Ban** | Cards de UI flotando sin contenedor | Estética de Dribbble, no de firma de estrategia. |
| **The Generic Copy Ban** | "Seamless", "end-to-end", "world-class" | El C-suite europeo lo ha leído 1000 veces. |

---

## 7. Component Arsenal — Elementos Visuales Aprobados

### Fondos
- **Azul eléctrico sólido** — `#091FF9` puro. Máxima declaración de marca.
- **Gradiente tonal** — `#091FF9` → `#050D6B`. Profundidad sin shock de contraste.
- **Circuit grid overlay** — líneas 1px `rgba(0,255,213,0.08)` sobre azul eléctrico. Nodos en intersecciones. Solo como fondo, nunca protagonista.

### ✅ ESTILO VISUAL APROBADO — Corner Geometry (locked)
> Aprobado en sesión de producción · 2026-06-22

El tratamiento visual oficial de Blue Bridge Global para todos los posts es **Corner Geometry**:

- **Fondo:** `#091FF9` sólido, sin gradiente
- **Corner marks:** Líneas L-shaped en las 4 esquinas, mint `#00FFD5`, opacidad 0.20, ~60px de largo, stroke fino
- **Arco decorativo:** Cuarto de círculo en esquina inferior derecha, mint `#00FFD5`, opacidad 0.07, stroke grueso
- **Estos elementos son siempre sutiles** — enmarcan sin competir con el texto
- **Headlines:** Space Grotesk 700, blanco `#FFFFFF`, left-aligned
- **Labels:** Inter 600, mint `#00FFD5`, uppercase, wide letter-spacing
- **Body / subtext:** Inter 400, blanco `#FFFFFF`
- **CTAs:** Inter 600, mint `#00FFD5`
- **Logo:** siempre esquina inferior izquierda en postproducción — PNG blanco transparente

En el prompt de Higgsfield siempre incluir:
```
BACKGROUND TREATMENT: subtle geometric corner marks in mint #00FFD5 at very low opacity 0.20
— thin L-shaped bracket lines in all four corners, each about 60px long.
Large subtle arc in bottom-right corner in mint #00FFD5 at opacity 0.07, thick stroke, quarter circle.
Background elements decorative only, never competing with text.
```

### Tipografía
- **Número display masivo** — JetBrains Mono, escala full-bleed. Una sola métrica ocupa el 70% del frame.
- **Headline solo** — Inter Tight 700, máx 2 líneas, left-aligned, grande. Sin decoración.
- **Label + headline** — Label UPPERCASE pequeño en mint `#00FFD5` + headline grande en blanco.

### Elementos gráficos (usar con economía)
- **Línea horizontal única** — 1px, mint `#00FFD5`, opacity 0.6. Separador, no decoración.
- **Corner marks** — marcas geométricas de esquina en mint. Sugieren precisión de framing.
- **Data bar** — barra horizontal delgada mostrando proporción. No un chart completo.

---

## 8. Agent Prompt Guide

Cuando generes contenido para **Blue Bridge Global**:
- **Paleta activa:** `#091FF9` (primary) · `#FFFFFF` (text) · `#00FFD5` (accent mint) · `#050D6B` (deep variant)
- **Tono:** Ejecutivo y estratégico en LinkedIn (largo aliento, datos, insights). Visual y aspiracional en Instagram. Siempre inglés como idioma primario.
- **Audiencia:** Empresas europeas de mediano y gran tamaño buscando expansión hacia América Latina.
- **CTAs:** Orientados a agendar consultoría o completar formulario de BPO inquiry.
- **Nunca:** Cheap outsourcing · Low-cost solutions · Basic call center · colores fuera de paleta.
- **Siempre:** Datos de mercado con fuente · Frases cortas · Orientación a resultado · Mint como acento máximo en 2 elementos por pieza.

---

## 9. Logo — Regla Obligatoria

**El logo de Blue Bridge va en el 100% de las publicaciones. Sin excepción. Cero tolerancia.**

### Especificaciones del logo
- **Símbolo:** Forma infinito/puente geométrico
- **Wordmark:** "BLUE BRIDGE" — bold, uppercase, letra ancha
- Siempre símbolo + wordmark juntos — nunca solo uno de los dos

### Versiones y cuándo usar cada una

| Fondo de la publicación | Versión del logo | Color |
|-------------------------|------------------|-------|
| Fondo azul eléctrico `#091FF9` | Logo BLANCO | `#FFFFFF` transparente |
| Fondo deep navy `#050D6B` | Logo BLANCO | `#FFFFFF` transparente |
| Fondo blanco o claro | Logo AZUL | `#091FF9` transparente |

**Regla de contraste absoluta:** El logo nunca puede tener el mismo color que el fondo. Azul sobre azul = invisible = inaceptable.

### Posición en cada formato

| Formato | Posición | Tamaño mínimo | Margen |
|---------|----------|---------------|--------|
| IG feed / carrusel — **4:5 (1080×1350px)** | Esquina inferior izquierda | 180px de ancho | 32px desde bordes |
| IG Story/Reel 9:16 (1080×1920) | Esquina inferior izquierda | 180px de ancho | 40px desde bordes |
| LinkedIn imagen / carrusel PDF — **4:5 (1080×1350px)** | Esquina inferior izquierda | 180px de ancho | 32px desde bordes |

### Reglas de posición
- **SIEMPRE** esquina inferior izquierda — nunca centrado, nunca derecha
- **NUNCA** sobre elementos con poco contraste — fondo limpio detrás del logo
- **NUNCA** cortado — respetar margen mínimo siempre
- **NUNCA** menor a 160px de ancho — pierde legibilidad

### Assets disponibles
- [x] `blue-bridge-logo-white.png` — PNG fondo transparente, versión blanca ✓ LISTO
- [x] `blue-bridge-logo-blue.png` — PNG fondo transparente, versión azul `#091FF9` ✓ LISTO

### En el prompt de Higgsfield — incluir SIEMPRE al final

Para fondos azules (la mayoría de los posts):
```
Blue Bridge logo (infinity bridge symbol + "BLUE BRIDGE" wordmark in bold uppercase)
placed bottom-left corner, white version #FFFFFF on transparent background,
32px margin from edges, approximately 180px wide.
Logo must be fully visible, unobstructed, complete symbol + wordmark.
```

Para fondos blancos o claros:
```
Blue Bridge logo (infinity bridge symbol + "BLUE BRIDGE" wordmark in bold uppercase)
placed bottom-left corner, blue version #091FF9 on transparent background,
32px margin from edges, approximately 180px wide.
Logo must be fully visible, unobstructed, complete symbol + wordmark.
```

### Flujo de postproducción (obligatorio)
1. Higgsfield genera la imagen base
2. Abrir en Canva o Figma
3. Superponer el PNG de logo correspondiente — esquina inferior izquierda, ~180px de ancho
4. Verificar contraste y visibilidad
5. Exportar imagen final
**No se publica ninguna imagen sin este paso completado.**
---

> ✅ Formato aprobado 2026-06-22: Feed de Instagram usa 4:5 — no 1:1. El 4:5 ocupa más espacio en el scroll, texto más legible en miniatura. El 1:1 está prohibido para posts de feed.

---

## 10. Prompt Engineering — Lecciones Aprobadas en Producción

> Documentado 2026-06-22 · Basado en pruebas reales con Recraft v4.1-vector

### Lo que funciona ✅
- Modelo: `recraftv4.1-vector` — no v3, no digital_illustration
- Referirse al mint siempre como `"cyan-green accent color #00FFD5"` — nunca "mint"
- Espacio negativo: `"large empty area on the right side"` — nunca "60% negative space"
- Template de prompt fijo — el agente solo rellena LABEL, HEADLINE y BODY
- Controls de color via API: `{"rgb": {"r": 9, "g": 31, "b": 249}}` para forzar paleta

### Lo que destruye el resultado ❌
- La palabra "mint" → el modelo genera plantas literales
- "60%" o cualquier porcentaje → aparece como número en la imagen
- "digital_illustration" como style → genera personas y diagramas
- Dejar que el agente construya el prompt libremente → resultado impredecible
- Recraft v3 → dos generaciones atrás, no soporta composición tipográfica pura
