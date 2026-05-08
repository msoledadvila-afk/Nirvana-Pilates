# Prompts listos para IAs · NirVana Pilates

> **Cómo usar este archivo:** Cada bloque de abajo está pensado para copiarse y pegarse en un prompt. La idea es que el design system de NirVana viaje con vos cuando construyas en v0.dev, Lovable, Bolt, Cursor o conversaciones nuevas con Claude.
>
> **Regla de oro:** siempre pegá primero el bloque "Identidad de marca", después tu pedido específico. Eso evita que la IA invente colores, tipografías o se vaya a una estética genérica wellness/fitness.

---

## 📦 BLOQUE 1 — Identidad de marca · NirVana Pilates

> Pegar al inicio de cualquier prompt cuando trabajes en algo de NirVana.

```
Trabajo bajo el design system "NirVana Pilates — academia de Pilates Reformer en Martínez, BS AS".

CONCEPTO CENTRAL: "Nirvana como pausa contemplativa. El cuerpo como camino. El vacío como lujo."
NirVana NO es un gimnasio fitness. NO es wellness genérico. Es una pausa contemplativa para mujeres con criterio que buscan trabajar el cuerpo desde el detalle técnico, no desde la motivación gritada.

PALETA (usar exactos, no improvisar):
- Marca primaria (dorado mostaza): #B8995A
- Marca suave: #D4BD8A (hover, gradientes)
- Marca profunda: #8C7035 (énfasis, texto destacado)
- Fondo principal (crema cálido): #F5EFE4
- Fondo alterno: #EBE2D2
- Card / superficie elevada: #FFFCF6 (blanco con tinte crema, NUNCA blanco puro)
- Bloque editorial: #F0E8D8
- Borde: #D8CDB8
- Texto principal: #2A2520 (marrón muy oscuro, NUNCA negro puro)
- Texto secundario: #6B5F4E
- Acento atmosférico (luna/astro): #D4B062 (usar con moderación)
- Modo dark dramático: #1F1810 (solo en portadas hero)

ESCALA TIERRA (para piezas técnicas/editoriales):
- Tier 1 (claro): #E8DCC8
- Tier 2: #C9B591
- Tier 3: #9A7F5C
- Tier 4 (profundo, autoridad): #5C4632
- Tier 5 (cacao oscuro, contraste): #2E2218

TIPOGRAFÍA:
- Display (titulares de marca, citas): 'Cormorant Garamond', serif — pesos 400/500/600, italic permitido
- Body + UI: 'Outfit', sans-serif — pesos 300/400/500/600/700
- Cargar: https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400;1,500;1,600&family=Outfit:wght@300;400;500;600;700&display=swap

PERSONALIDAD VISUAL:
- Contemplativa, terrenal, premium — NUNCA fitness fluo, NUNCA motivacional gritado
- Mucho aire — el vacío es protagonista (mínimo 50-60% del lienzo libre en piezas atmosféricas)
- Bordes: 16px en cards default, 24px en cards grandes, pill SOLO en CTAs principales
- Sombras cálidas con tinte dorado-marrón, NUNCA grises puras: 0 8px 20px rgba(140,112,53,0.10)
- Layout: max-width 1100px, padding generoso (96px sección desktop, 64px mobile)
- Animaciones lentas y respiradas (350-600ms), curvas suaves, NUNCA bouncy
- Tracking negativo (-0.03em) en titulares grandes Cormorant — la serif respira mejor

DOS MODOS DE PIEZA (CRÍTICO — respetar siempre):

MODO ATMÓSFERA (piezas aspiracionales, contemplativas, frases-mood):
- Mucho aire, mínimo decorado
- Cormorant en italic permitido, peso regular o medium
- Un solo astro como acento (luna creciente, estrella, sol) — NO constelaciones cargadas
- Sin íconos funcionales, sin CTAs visibles
- Paleta: crema + dorado + un toque #D4B062

MODO EDITORIAL-TÉCNICO (carruseles educativos, anatomía, técnica, datos):
- Jerarquía clara, layout funcional
- Cormorant solo en titular, body en Outfit
- Paleta tierra (#9A7F5C, #5C4632) para autoridad — SIN elementos cosmos
- Iconografía de línea fina dorada
- Datos y números legibles
- Espaciado funcional, no contemplativo

EVITAR ABSOLUTAMENTE:
- Verde sage + serif fina (cliché wellness 2020-2024)
- Rosa millennial, rosa baby, fucsia, dorado brillante metálico
- Inter, Roboto, Montserrat, Poppins, Helvetica
- Frases motivacionales tipo "BELIEVE" "GLOW" "STRONG WOMEN"
- Imágenes de cuerpos completos identificables (la dueña/alumnas no quieren cara — usar manos, pies, detalles, planos cenitales)
- Antes-y-después, contadores de calorías, mediciones de peso
- Constelaciones cargadas o estrellitas decorativas por todas partes (REINTERPRETAMOS el cosmos: vacío + un astro)
- Gradientes saturados, sombras de colores raros
- Layouts con todo centrado y simétrico — preferir asimetría editorial cálida
```

---

## 🛠️ PROMPTS POR CASO DE USO

### Post de Instagram · MODO ATMÓSFERA (frase de marca)

```
[Pegar BLOQUE 1 arriba]

Diseñame un post cuadrado 1080x1080 para Instagram en MODO ATMÓSFERA.

Contenido: una frase corta de marca, máximo 6 palabras (ej: "El cuerpo también necesita silencio").

Estructura:
- Fondo crema #F5EFE4
- 60% del lienzo vacío (aire dorado, sin nada)
- Frase centrada en Cormorant Garamond italic, peso 400, color #2A2520, tracking -0.03em, tamaño grande
- Una luna creciente muy fina (línea 1.5px, dorado #D4B062) como único elemento decorativo, ubicada arriba a la derecha o abajo a la izquierda — nunca centrada con la frase
- Eyebrow opcional muy chiquito en uppercase Outfit 500, tracking 0.2em, color #8C7035: "NIRVANA · MARTÍNEZ"
- Sin logo en la pieza (el logo va en la cuenta, no en cada post)
- Sin emojis, sin íconos funcionales
- Composición ASIMÉTRICA, nunca todo centrado y formal
```

### Carrusel de Instagram · MODO EDITORIAL-TÉCNICO (anatomía / técnica)

```
[Pegar BLOQUE 1 arriba]

Diseñame un carrusel de 5 slides 1080x1350 (formato vertical) en MODO EDITORIAL-TÉCNICO sobre [TEMA: ej. "Por qué el suelo pélvico importa después de los 35"].

Slide 1 (portada):
- Fondo crema #F5EFE4
- Eyebrow uppercase Outfit 500 en #8C7035: "ANATOMÍA SIMPLE · 01"
- Titular Cormorant Garamond 600, color #2E2218 (tier5), tamaño grande
- Subtitular Outfit 400 en #6B5F4E
- Indicador "1/5" abajo a la derecha en Outfit 400, color #A89980
- SIN luna ni elementos cosmos (modo editorial)

Slides 2-4 (contenido):
- Layout asimétrico: título a la izquierda en Cormorant 500, texto explicativo a la derecha en Outfit 400
- 1 dato destacado por slide en número grande Cormorant 600 dorado #B8995A + label en Outfit
- Una línea divisoria fina dorada como separador (no usar cajas ni bordes)
- Iconografía de línea fina opcional, máximo 1 ícono por slide

Slide 5 (cierre + CTA):
- Frase de cierre en Cormorant italic 500
- CTA pill rounded-full color #B8995A con texto blanco crema Outfit 500: "Reservá tu primera clase"
- @pilates.nirvana abajo en Outfit 400 muted

Toda la paleta del carrusel debe usar tierra (tier3, tier4) + dorado de marca, SIN moonGold ni elementos atmosféricos.
```

### Story de Instagram · plantilla rituales offline (sin caras)

```
[Pegar BLOQUE 1 arriba]

Diseñame una story 1080x1920 que muestre un ritual de la academia SIN mostrar caras.

Concepto: foto/video de [DETALLE: ej. "manos sobre el reformer al inicio de clase", "té después de clase", "agenda con el nombre de la alumna escrito a mano"].

Layout:
- Foto ocupa el 70% inferior del frame
- Tercio superior: fondo crema sólido #F5EFE4 con eyebrow uppercase Outfit 600 tracking 0.2em color #8C7035: "RITUAL · MARTES 9HS"
- Frase corta en Cormorant italic 400 centrada debajo del eyebrow, color #2A2520
- Línea fina dorada divisoria entre el bloque crema y la foto
- Esquina inferior derecha: @pilates.nirvana en Outfit 400 muy chico, color crema con sombra suave
- NO usar stickers de Instagram, NO usar emojis
- Si hay sticker funcional (link, encuesta), ubicarlo abajo izquierda, integrado a la composición
```

### Landing page para captar primera clase

```
[Pegar BLOQUE 1 arriba]

Construime una landing page de una sola página para captar reservas de clase de prueba.

Estructura:
1. Hero a pantalla completa, modo atmósfera:
   - Fondo crema con halo dorado pulsando lentamente arriba a la derecha (animación breathe 6s)
   - Eyebrow uppercase muy chico: "PILATES REFORMER · MARTÍNEZ"
   - Titular Cormorant italic 500 grande (5rem desktop, 3rem mobile): "Tu pausa entre el ruido"
   - Subtitular Outfit 400 max-width 50ch: explicación corta del concepto
   - Una luna creciente fina como acento puntual
   - CTA pill dorado #B8995A: "Reservar primera clase"
   - Sin imagen de personas

2. Sección "Qué es NirVana" — modo editorial:
   - Asimétrica: título a la izquierda en Cormorant, párrafo a la derecha en Outfit
   - Lista de 3 valores con dots dorados, NO bullets
   - Fondo #EBE2D2

3. Sección "Cómo trabajamos" — 3 cards con números grandes:
   - Cards bg #FFFCF6, radius 16px, sombra soft
   - Número en Cormorant 600 dorado tamaño 4rem
   - Título corto + descripción en Outfit
   - Sin íconos

4. Sección testimonio sin rostro:
   - Bloque editorial fondo #F0E8D8
   - Cita en Cormorant italic 500 centrada, max-width 50ch
   - Atribución muy discreta debajo en Outfit muted: "— Alumna desde 2024"

5. Footer minimalista:
   - Solo: dirección Martínez, horarios, WhatsApp, @pilates.nirvana
   - Tipografía Outfit 300, todo en color textDim
   - Línea fina dorada arriba

Animaciones: solo fade-up en scroll, duración 600ms, easing breathe. Nada bouncy. El sitio debe sentirse como respirar despacio.
```

### Caption de Instagram (texto del post)

```
[Pegar BLOQUE 1 arriba]

Escribime el caption para un post de NirVana sobre [TEMA].

Tono de voz:
- Pausado, contemplativo, técnico cuando corresponde
- NO motivacional, NO gritado, NO "amigui te re banco"
- Frases cortas, mucho punto y aparte (respira como la marca)
- Usar segunda persona singular (vos), nunca "ustedes" ni "chicas"
- Cero emojis decorativos. Si va emoji, máximo uno funcional al final (📍 ubicación, 🌙 luna sutil)
- Hashtags al final en bloque, máximo 8, sin mezclar con el texto
- Si hay CTA, va al final, una sola línea, sin "👉 link en bio!!!"

Estructura sugerida:
- Línea 1: gancho corto, intrigante o reflexivo (no pregunta retórica gastada)
- 2-3 párrafos breves de desarrollo
- Cierre con micro-CTA discreto
- Bloque de hashtags

Hashtags base de la marca: #PilatesReformer #PilatesMartinez #NirVanaPilates #PausaContemplativa
```

---

## 💡 NOTAS DE USO ESTRATÉGICO

**Cuándo NO usar el MODO ATMÓSFERA:**
- Posts educativos con datos
- Carruseles de anatomía o técnica
- Anuncios con CTA fuerte
- Contenido para Meta Ads (necesita gancho funcional)

**Cuándo NO usar el MODO EDITORIAL:**
- Frases de marca pure
- Reels lentos sin texto sobreimpreso
- Stories de "atmósfera del estudio"
- Portadas de highlights

**Si la pieza no encaja claramente en uno de los dos modos:** probablemente no debería existir. La marca pierde fuerza cuando se vuelve "un poco de cada cosa". Mejor decidir el modo, comprometerse, y dejar piezas con criterio fuerte que muchas piezas tibias.
