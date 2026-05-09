# NirVana Vital · Design System

> Sistema de diseño para **NirVana Pilates** — academia de Pilates Reformer en Martínez, Buenos Aires. Concepto: *Energía con cariño. Movimiento con criterio. Pilates que se siente vivo.*

**Versión 1.0.0** · 8 de mayo de 2026 · Mantenido por María Soledad Vila

---

## 🌈 Posicionamiento estratégico

NirVana **se diferencia conscientemente del premium contemplativo dominante en Martínez/Acassuso/San Isidro**. Mientras la mayoría de academias de Pilates en zona norte compiten con paletas crema-sage, serifs finas y silencio editorial, NirVana es **lo opuesto consciente**: vital, colorida, cercana, con energía.

Esto NO significa Canva templates random sin criterio. Significa **alegre con sistema**.

| Lo que hace la competencia premium | Lo que hace NirVana Vital |
|---|---|
| Sage + serif fina + silencio | Terracota + Fraunces + energía |
| "Pausa contemplativa" | "Movimiento que se siente" |
| Vacío como lujo | Color como protagonista |
| Aesop / Le Labo | Felicitas Pizarro / Reformerista |
| Frases en inglés en italic | Castellano cálido directo |
| Sin caras (premium) | Caras caricaturizadas (filtro Comic) |
| Una sola tipografía | Mezcla con criterio (display + body + acento) |

---

## 📁 Qué hay en este paquete

```
nirvana-vital-design-system/
├── tokens.json           ← La fuente de verdad: colores, tipografía, espaciado
├── design-system.html    ← Mostrador interactivo (doble click y se abre)
├── prompts-para-ia.md    ← Prompts listos para Canva AI, ChatGPT, v0, Claude
└── README.md             ← Este archivo
```

---

## 🎨 Las decisiones clave

### Una paleta de 5 colores principales (no caos)

La diferencia entre "marca vital colorida con criterio" y "Canva templates desordenados" es esto: **5 colores definidos**, no 30 al azar.

- **Terracota** — alma del sistema. Color de marca primario.
- **Coral** — para acentos juguetones, subrayados.
- **Mostaza** — para fechas, números, datos importantes.
- **Menta** — frescura, equilibrio. Inspirada en las pelotas verdes del estudio.
- **Ciruela** — sofisticación. Para que el sistema no se vea infantil.

Cada pieza usa **2-3 colores** de estos, no todos juntos. El crema cálido sostiene cualquier combinación.

### Tres tipografías con jerarquía clara

- **Fraunces** (display) — serif con personalidad amistosa, curvas blandas. Para titulares.
- **DM Sans** (body) — humanista, legible, con carácter sin distraer. Para todo lo funcional.
- **Caveat** (manuscrita) — solo para garabatos puntuales. Máximo 1 vez por pieza.

Las tres están en Google Fonts y disponibles en Canva. Coherencia gratis.

### Tres modos de pieza, no uno solo

- **Energético** (dominante) — promos, captación, anuncios.
- **Editorial cálido** — contenido educativo, técnica, anatomía.
- **Atmosférico cálido** — frases-mood, cierres. Baja frecuencia (1 de cada 10 piezas).

Mezclar los modos rompe la marca. Cada pieza elige uno y se compromete.

### Sistema de elementos decorativos definidos

Los subrayados, brushStrokes, scribbles y cintas decorativas NO son "lo que sale en el momento". Están definidos:

- **Highlight** — subrayado tipo marcador, coral o mostaza, irregular.
- **BrushStroke** — banda de fondo tipo pincelada para eyebrows.
- **Scribble** — garabato a mano alzada, terracota o ciruela.
- **Tape** — washi tape para fotos en composición tipo collage.

Máximo 2 elementos decorativos por pieza.

---

## 🚀 Cómo aplicar el sistema en Canva

### Antes de crear cualquier pieza nueva

1. **Decidí el modo** (energético / editorial / atmosférico).
2. **Elegí 2-3 colores** de la paleta brand para esa pieza.
3. **Cargá las fuentes en Canva**: Fraunces, DM Sans, Caveat (todas gratuitas en Canva).
4. **Si vas a usar foto**, aplicale primero el filtro "Comic Style" en Canva: Editar foto → Estilo → Comic.

### Checklist antes de publicar

- [ ] ¿La pieza está claramente en uno de los tres modos?
- [ ] ¿Usé máximo 3 colores de la paleta brand?
- [ ] ¿Las tipografías son Fraunces / DM Sans / Caveat (no otras)?
- [ ] ¿El texto principal está en marrón cacao (#3D2817), no en negro?
- [ ] ¿El fondo es crema (#FAF3E7), no blanco puro?
- [ ] ¿Hay máximo 2 elementos decorativos?
- [ ] ¿Si hay foto, está filtrada estilo Comic?
- [ ] ¿El CTA es pill grande con personalidad?

### Para escalar

Cuando aparezcan más piezas, web, flyers, todo arranca de `tokens.json`. No reinventar valores.

---

## 📐 Filosofía técnica

- **Una sola fuente de verdad**: `tokens.json`. El resto se deriva.
- **Sistema sin frameworks pesados**: HTML + CSS vanilla en el mostrador. Sobrevive a la moda.
- **Compatibilidad Canva**: todas las fuentes y colores están disponibles ahí, sin necesidad de plugins.

---

## 🛠️ Roadmap

- [x] v1.0 — Tokens completos, tres modos definidos, mostrador interactivo, prompts para IA
- [ ] v1.1 — Plantillas de Canva con los componentes principales pre-armados
- [ ] v1.2 — Sistema de iconografía custom (ilustraciones a mano alzada)
- [ ] v1.3 — Fotografía: guías de planos y composiciones para sesión mensual de producción
- [ ] v1.4 — Versión simplificada del logo (isotipo) para usos chicos

---

## 👤 Sobre

**María Soledad Vila** — Vibe Coder & Arquitecta Digital · Talento Impulsa Consulting.

Sistema diseñado a partir de la intuición de posicionamiento de la dueña de NirVana, articulada con criterio profesional.

---

## 📄 Licencia

Sistema propiedad de NirVana Pilates para uso exclusivo de la marca.
