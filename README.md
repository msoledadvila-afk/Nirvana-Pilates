# NirVana Pilates · Design System

> Sistema de diseño para **NirVana Pilates** — academia de Pilates Reformer en Martínez, Buenos Aires. Concepto: *Nirvana como pausa contemplativa. El cuerpo como camino. El vacío como lujo.*

**Versión 1.0.0** · 7 de mayo de 2026 · Mantenido por María Soledad Vila

---

## 🌙 Posicionamiento estratégico

NirVana **no compite en la cancha del fitness**. No es un gimnasio, no es wellness genérico, no es un estudio motivacional. Es una pausa contemplativa para mujeres con criterio que buscan trabajar el cuerpo desde el detalle técnico, no desde la motivación gritada.

Esto significa que cada decisión visual del sistema sirve para **separarnos de los códigos saturados del rubro Pilates en zona norte**:

| La competencia hace | NirVana hace |
|---|---|
| Verde sage + serif fina | Crema cálido + serif editorial |
| Cuerpos completos identificables | Detalles, manos, pies, planos cenitales |
| "Strong Woman", "Glow", "Believe" | "Tu pausa entre el ruido" |
| Constelaciones decorativas cargadas | Vacío + un solo astro como acento |
| Antes-y-después de medidas | Anatomía simple y autoridad técnica |
| Posts saturados de elementos | Mucho aire, mínimo decorado |

---

## 📁 Qué hay en este paquete

```
nirvana-pilates-design-system/
├── tokens.json           ← La fuente de verdad. Colores, tipografía, espaciado.
├── design-system.html    ← Mostrador interactivo. Abrirlo en cualquier navegador.
├── prompts-para-ia.md    ← Prompts listos para v0, Lovable, Cursor, Claude.
└── README.md             ← Este archivo.
```

### `tokens.json`
**El archivo más importante.** Contiene todos los valores del sistema en formato W3C Design Tokens. Si en el futuro querés exportar a Figma, Tailwind, Style Dictionary o cualquier herramienta de design ops, todo arranca acá.

### `design-system.html`
**Mostrador autocontenido.** Doble click y se abre en el navegador. Muestra paleta, tipografía, componentes, dos modos de pieza, y los prompts copiables. Hecho en HTML + CSS vanilla — sobrevive a cualquier framework de moda.

### `prompts-para-ia.md`
**El archivo más útil en el día a día.** Pegale el bloque de identidad a cualquier IA antes de pedirle algo, y la IA va a respetar la marca en lugar de inventar paletas wellness genéricas.

---

## 🎨 Decisiones clave del sistema

### Dos modos de pieza, no uno

Es la decisión más importante del sistema. NirVana no se ve siempre igual, se ve **de dos maneras controladas**:

- **Modo Atmósfera** — para piezas aspiracionales, frases-mood, portadas. Mucho aire, Cormorant italic, una luna como acento, vacío al 60%.
- **Modo Editorial-Técnico** — para contenido educativo, anatomía, datos, CTAs. Layout funcional, paleta tierra, sin elementos cosmos, jerarquía clara.

Mezclar los dos modos en una misma pieza es lo que rompe la marca. Cada pieza elige uno y se compromete.

### Por qué Cormorant + Outfit

La cuenta actual de Instagram tiene inconsistencia tipográfica fuerte (cada post parece de otra marca). El sistema resuelve esto con dos familias y reglas claras:

- **Cormorant Garamond** (serif editorial) → solo en titulares de marca, citas, frases atmosféricas. Italic permitido. Tracking negativo en tamaños grandes.
- **Outfit** (sans humanista) → todo lo funcional. Body, UI, navegación, captions, hashtags.

Esta combinación es **coherente con el sistema MSV completo** (Portfolio, Talento Impulsa, NirVana comparten Outfit). Eso vuelve mi sello visible cuando trabajo con clientes.

### Por qué reinterpretamos el cosmos

La marca actual usa constelaciones, lunas y estrellas en abundancia. Visualmente está cargada y se acerca al riesgo new-age. La reinterpretación toma el concepto Nirvana pero lo lleva a **vacío contemplativo + un astro puntual**, más cerca de Aesop o cerámica japonesa que de tarot. Esto:

1. Conecta mejor con público premium-introspectivo (mayor LTV).
2. Se diferencia más de la competencia.
3. Es más fácil y barato de producir.
4. Envejece mejor.

### Por qué la paleta es cálida sin verde

El verde sage es **el color más usado en wellness 2020-2024**. Usarlo es invisibilizarse. La paleta de NirVana se mueve en el eje crema → dorado mostaza → cacao oscuro, con acentos puntuales en moonGold. Esto da:

- Diferenciación inmediata en el feed de Instagram.
- Coherencia con el universo "cuerpo como camino".
- Versatilidad para los dos modos (cálida en atmósfera, autoritaria en editorial).

---

## 🚀 Cómo aplicar el sistema en el día a día

### Para crear un post nuevo

1. Decidí el modo (atmósfera o editorial).
2. Abrí `prompts-para-ia.md` y copiá el prompt correspondiente.
3. Pegale el bloque de identidad + el prompt en Canva AI / v0 / la herramienta que uses.
4. Si no usás IA, abrí `design-system.html` y consultá la paleta y tipografía.

### Para revisar una pieza antes de publicar

Checklist rápido:
- ¿Está claramente en uno de los dos modos? (sino, revisar)
- ¿La tipografía respeta Cormorant solo en titulares?
- ¿El fondo es crema cálido (nunca blanco puro)?
- ¿Hay al menos 50% de aire en la pieza?
- ¿Hay alguna frase motivacional gritada? (sacar)
- ¿Hay verdes sage o rosas millennial? (sacar)

### Para escalar a futuro

Cuando aparezca la web, los flyers físicos, los emails, el merchandising — todo arranca de `tokens.json`. No reinventar valores. Si falta algo, agregarlo al token con criterio y actualizar la versión.

---

## 📐 Filosofía técnica del sistema

- **Una sola fuente de verdad**: `tokens.json`. El resto se deriva o sincroniza.
- **Sub-marca como caso de estudio**: NirVana es la primera marca cliente formalizada bajo la metodología de Talento Impulsa Consulting (sub-marcas hermanas con estructura compartida).
- **Sin frameworks pesados** en el showroom. HTML + CSS + JS vanilla. El sistema vive más allá de la moda de un framework.
- **Nombre de archivo y nombre de variable predecibles**. Cualquier IA que lea estos archivos puede operar sobre ellos sin contexto adicional.

---

## 🛠️ Roadmap

- [x] v1.0 — Tokens completos, dos modos definidos, mostrador interactivo, prompts para IA
- [ ] v1.1 — Iconografía propia de línea fina dorada (mínimo 12 íconos base)
- [ ] v1.2 — Plantillas de Canva con los componentes principales pre-armados
- [ ] v1.3 — Versión simplificada del logo (isotipo) para usos chicos: WhatsApp, favicon, highlights
- [ ] v1.4 — Sistema de fotografía: guías de planos, encuadres y luz para la sesión mensual de producción

---

## 👤 Sobre

**María Soledad Vila** — Vibe Coder & Arquitecta Digital · Fundadora de Talento Impulsa Consulting.

Construyo identidades visuales sistematizadas para marcas que quieren escalar sin perder coherencia. NirVana Pilates es el primer cliente formalizado bajo este método.

- 💬 WhatsApp: +54 9 11 6958-0303
- ✉️ Email: msoledadvila@gmail.com

---

## 📄 Licencia y uso

Este design system es **propiedad de NirVana Pilates** para uso exclusivo de la marca. La metodología y la estructura del sistema son de María Soledad Vila / Talento Impulsa Consulting.

No reproducir el sistema completo para otras marcas sin acuerdo previo.
