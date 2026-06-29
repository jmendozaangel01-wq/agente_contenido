# Blue Bridge Global — Content Pipeline
> Actualizado · 2026-06-22 · Paleta corregida con colores reales de marca

---

## BRAND LOCK — Always active

```
Brand:        Blue Bridge Global
Tagline:      "The Strategic Bridge"
Sector:       Business Process Outsourcing (BPO) / AI & Digital Marketing
Mercado:      Europa (Bélgica, España) → América Latina (Costa Rica, México, Colombia)
Audiencia:    Empresas europeas de mediano y gran tamaño buscando expansión hacia LatAm
Idioma:       Inglés (principal) / Español (secundario)

PALETA OFICIAL (colores reales de marca):
  Primary:    #091FF9  — Azul eléctrico. Fondo dominante de todos los posts.
  Text:       #FFFFFF  — Blanco. Todo el copy sobre fondo azul.
  Accent:     #00FFD5  — Mint. Acento único. Máx 2 elementos por composición.
  Deep:       #050D6B  — Deep navy. Solo para gradientes tonales o fondos secundarios.

Personalidad: Estratégico · Autoritario · Global · Confiable · Innovador
Postura:      BPO boutique élite. Nunca vendor. Nunca startup.
```

---

## ACTIVE BASELINE DIALS

```
FORMALITY:        7
TECH_VISIBILITY:  4
HUMAN_PRESENCE:   2
TEXT_IN_IMAGE:    7
```

### Dial Inference por tipo de contenido

| Señal | FORMALITY | TECH | HUMAN | TEXT |
|-------|-----------|------|-------|------|
| Stat / métrica | 9 | 3 | 0 | 9 |
| Thought leadership | 8 | 4 | 1 | 8 |
| Servicio / producto | 7 | 5 | 2 | 7 |
| AI / tendencia | 7 | 8 | 0 | 6 |
| Psicología de negocios | 8 | 2 | 0 | 8 |
| Cultura / equipo | 5 | 2 | 8 | 5 |
| Marca / posicionamiento | 9 | 3 | 0 | 7 |

---

## VISUAL CONCEPT LIBRARY

### ◈ THE STATEMENT
**Qué comunica:** Thought leadership, posicionamiento, insights estratégicos sobre Europa→LatAm.
**Uso:** 20% del calendario
**Visual:** Fondo `#091FF9`. Headline blanco Inter Tight 700. Label en mint `#00FFD5`. Espacio negativo generoso.

### ◈ THE DATA
**Qué comunica:** Servicios, capacidades, resultados operacionales, social proof interno.
**Uso:** 22% del calendario
**Visual:** Fondo `#091FF9`. Métrica grande en JetBrains Mono blanco. Línea mint como separador.

### ◈ THE STORY
**Qué comunica:** Casos de éxito, resultados con clientes (cuando existan), evidencia tangible.
**Uso:** Crecer a medida que se acumulen casos reales. Por ahora = resultados internos.
**Visual:** Fondo `#091FF9` → `#050D6B` gradiente tonal. Quote o dato central en blanco.

### ◈ THE PROOF
**Qué comunica:** Tendencias AI, futuro del BPO, innovación tecnológica.
**Uso:** 22% del calendario
**Visual:** Fondo `#091FF9` con circuit grid overlay en `rgba(0,255,213,0.08)`. Dato o tendencia como protagonista.

### ◈ THE HOOK
**Qué comunica:** Cultura, equipo, presencia en 4 países, humanización de marca.
**Uso:** 15% del calendario (incluye psicología de negocios)
**Visual:** El más flexible. Puede tener más espacio negativo o elementos humanos.

---

## ANTI-PATTERNS — Los Bans Activos

| Ban | Prohibición |
|-----|-------------|
| Globe Ban | Globo terráqueo, mapa con puntos |
| Handshake Ban | Fotos de stock, equipos sonriendo |
| Warm Color Ban | Coral, amber, naranja, verde (excepto mint `#00FFD5`) |
| Three Cards Ban | 3 elementos simétricos idénticos |
| Floating UI Ban | Cards flotando sin contenedor |
| Generic Copy Ban | "Seamless", "end-to-end", "world-class" |
| Off-palette Ban | Cualquier color fuera de `#091FF9` / `#FFFFFF` / `#00FFD5` / `#050D6B` |

---

## WORKFLOW

### Step 0 — Referencias visuales
→ Carpeta `/references/` con mínimo 8 imágenes de marca o referentes aprobados.
→ Si no existe: proceder anclando en DESIGN.md únicamente. Documentar para completar luego.

### Step 1 — Style Reference (primera vez)
Generar imagen de referencia con Higgsfield `gpt_image_2`:
```
Fondo azul eléctrico puro #091FF9.
Headline "The Strategic Bridge" en Inter Tight 700, blanco #FFFFFF, left-aligned.
Label "BLUE BRIDGE GLOBAL" en mint #00FFD5, uppercase, letter-spacing amplio, arriba del headline.
Línea horizontal 1px en mint como separador.
Composición minimalista. 60% espacio negativo.
1080x1080. Sin personas. Sin globos. Sin elementos decorativos.
```
Guardar `style_ref_id` en `bb-config.json`.

### Step 2 — Brief del post (preguntar de a una)

**Q1:** ¿El post es sobre Blue Bridge (servicio/posicionamiento) o sobre industria (tendencia comentada)?
**Q2:** ¿Tipo? Thought Leadership · Showcase Servicios · AI/Tendencia · Psicología Negocios · Cultura
**Q3:** ¿Formato? IG feed 4:5 (1080×1350px) · IG Story/Reel 9:16 · LinkedIn 1:1
**Q4:** ¿Tema o dato central? (o decir "investigar" + tema)
**Q5:** ¿Copy específico? (opcional — si no, se escribe desde cero)

### Step 3 — Research (si Q4 = "investigar")
Usar web search para:
- Estadísticas con fuente verificable
- Contexto del sector BPO/AI en Europa→LatAm
- Ángulo Blue Bridge: qué significa para su audiencia

### Step 4 — Brand Read
Declarar antes de cualquier dirección visual.

### Step 5 — Dos Direcciones Visuales
Siempre exactamente 2. Una contenida, una que empuje más. Esperar elección.

### Step 6 — Copy
```
HEADLINE:  Space Grotesk 700. Sentence case. Máx 8 palabras. Blanco #FFFFFF.
LABEL:     Inter 600. UPPERCASE + tracking amplio. Mint #00FFD5.
BODY:      Inter 400/500. 2-3 oraciones específicas. Blanco #FFFFFF.
CTA:       Inter 600. Mint #00FFD5. Verbo primero. Específico.
MÉTRICA:   Space Grotesk 700. Numeral grande + unidad pequeña.
```

### Step 7 — Approval Gate
Mostrar brief completo. Esperar "sí" antes de generar.

### Step 8 — Generar con Higgsfield `gpt_image_2`
Pre-flight checklist:
- [ ] Fondo `#091FF9` — no otro azul
- [ ] Texto en `#FFFFFF`
- [ ] Mint `#00FFD5` en máx 2 elementos
- [ ] Sin colores fuera de paleta
- [ ] Sin personas en poses de stock
- [ ] Sin globo terráqueo ni mapa
- [ ] Formato declarado en el prompt
- [ ] Usuario aprobó (Step 7 no saltado)

Naming: `blue_bridge_{YYYYMMDD}_{N}`

### Step 9 — Learning Log
Después de cada post publicado, registrar en `learning-log.md`:
- Tipo, concepto, copy usado
- Métricas: alcance, guardados, shares, comentarios
- Nota: qué funcionó / qué no

---

## ITERATION PROTOCOL

| El usuario dice | El pipeline hace |
|-----------------|-----------------|
| "más formal" | FORMALITY +1 |
| "más limpio" | Quitar elementos secundarios, más espacio negativo |
| "diferente concepto" | Volver a Step 5, proponer 2 nuevas direcciones |
| "cambia el copy" | Solo copy, mantener visual |
| "perfecto, genera" | Confirmar prompt final → Higgsfield |

---

## QUALITY STANDARD

Antes de cualquier output:
1. ¿El fondo es `#091FF9`? (no navy, no celeste — azul eléctrico)
2. ¿El mint `#00FFD5` aparece en máximo 2 elementos?
3. ¿Un ejecutivo europeo encontraría esto creíble?
4. ¿Propuse exactamente 2 direcciones?
5. ¿Esperé aprobación antes de generar?
6. ¿Hay al menos un elemento genuinamente no-genérico?

**El estándar: indistinguible del mejor contenido B2B en Europa.**

---

## LOGO — Regla de Oro (no negociable)

**El logo va en el 100% de las publicaciones. Sin excepción. Cero tolerancia.**

- Posición: esquina inferior izquierda, 32px de margen mínimo (40px en Stories)
- Tamaño: ~180px de ancho — nunca menor a 160px
- Siempre: símbolo infinito + wordmark "BLUE BRIDGE" juntos

### Qué versión usar

| Fondo del post | Logo a usar |
|----------------|-------------|
| Azul eléctrico `#091FF9` (mayoría de posts) | `blue-bridge-logo-white.png` |
| Deep navy `#050D6B` | `blue-bridge-logo-white.png` |
| Blanco o claro | `blue-bridge-logo-blue.png` |

### Assets listos
- [x] `blue-bridge-logo-white.png` — PNG transparente, logo blanco ✓
- [x] `blue-bridge-logo-blue.png` — PNG transparente, logo azul `#091FF9` ✓

### Snippet para prompt Higgsfield (fondo azul — la mayoría)
```
Blue Bridge logo (infinity bridge symbol + "BLUE BRIDGE" wordmark in bold uppercase)
placed bottom-left corner, white version #FFFFFF on transparent background,
32px margin from edges, approximately 180px wide.
Logo must be fully visible, unobstructed, complete symbol + wordmark.
```

### Flujo de postproducción obligatorio
1. Higgsfield genera imagen base
2. Abrir en Canva o Figma
3. Superponer PNG de logo correcto — esquina inferior izquierda, ~180px
4. Verificar contraste
5. Exportar y publicar
**Ninguna imagen se publica sin este paso.**
