# Photo PromptLab Lite — Content Spec por Modo
> Versión 1.0 · Junio 2026
> Este documento define todos los textos de UI, títulos, descripciones, tips y opciones para cada uno de los tres modos de uso.

---

## Estructura del documento

Cada sección está organizada así:

```
Sección / Parámetro
  ├── Modo: General
  ├── Modo: Persona / Modelo
  └── Modo: Producto
```

Dentro de cada modo se especifica:
- **Título de sección** — el H1 que aparece en el panel principal
- **Subtítulo** — la descripción breve debajo del título
- **Tip** — el bloque de ayuda contextual (opcional por sección)
- **Opciones** — cada opción con su nombre y descripción corta en ese contexto

---

## PASO 0 — Selección de Modo

Esta es la pantalla de entrada. El usuario elige antes de ver cualquier parámetro.

### Textos de la pantalla de inicio

**Eyebrow:** `Antes de comenzar`
**Título EN:** `What kind of photo are you creating?`
**Título ES:** `¿Qué tipo de foto vas a crear?`
**Subtítulo EN:** `Your choice shapes every step that follows — parameters, options, and language will all adapt to your context.`
**Subtítulo ES:** `Tu elección define cada paso que sigue — los parámetros, opciones y lenguaje se adaptan a tu contexto.`

### Las tres opciones

---

#### Opción A — General / Scene

**Nombre EN:** `General / Scene`
**Nombre ES:** `General / Escena`
**Descripción EN:** `Landscapes, environments, abstract concepts, or any photo where the scene itself is the subject. No person, no product.`
**Descripción ES:** `Paisajes, entornos, conceptos abstractos, o cualquier foto donde la escena es el sujeto. Sin persona, sin producto.`
**Ejemplos EN:** `Forest at dawn · Desert road · Abstract light study · Empty architecture`
**Ejemplos ES:** `Bosque al amanecer · Carretera en el desierto · Estudio de luz abstracto · Arquitectura vacía`

---

#### Opción B — Person / Model

**Nombre EN:** `Person / Model`
**Nombre ES:** `Persona / Modelo`
**Descripción EN:** `Portrait, fashion, lifestyle, or any photo where a person is the primary subject. Includes reference photo support.`
**Descripción ES:** `Retrato, moda, lifestyle, o cualquier foto donde una persona es el sujeto principal. Incluye soporte para foto de referencia.`
**Ejemplos EN:** `Brand ambassador · Fashion editorial · LinkedIn headshot · Lifestyle content`
**Ejemplos ES:** `Embajadora de marca · Editorial de moda · Foto de perfil profesional · Contenido lifestyle`

---

#### Opción C — Product

**Nombre EN:** `Product`
**Nombre ES:** `Producto`
**Descripción EN:** `E-commerce, packshot, hero shot, or lifestyle product photography. The object is the star.`
**Descripción ES:** `E-commerce, packshot, hero shot, o fotografía de producto en lifestyle. El objeto es el protagonista.`
**Ejemplos EN:** `Skincare bottle · Sneaker · Coffee bag · Tech device · Jewelry`
**Ejemplos ES:** `Frasco de skincare · Tenis · Bolsa de café · Dispositivo tech · Joyería`

---

---

## SECCIÓN 1 — Cámara

### Modo: General / Scene

**Eyebrow:** `01 · Camera`
**Título EN:** `Choose your camera`
**Título ES:** `Elige tu cámara`
**Subtítulo EN:** `The camera defines the overall character of your image — its color science, resolution, and tonal quality.`
**Subtítulo ES:** `La cámara define el carácter general de tu imagen — su ciencia del color, resolución y calidad tonal.`
**Tip EN:** `For landscapes and environments, medium format sensors like the Fujix capture wider dynamic range — especially useful for scenes with bright sky and dark shadows simultaneously.`
**Tip ES:** `Para paisajes y entornos, los sensores de formato medio como el Fujix capturan mayor rango dinámico — especialmente útil en escenas con cielo brillante y sombras oscuras al mismo tiempo.`

**Opciones:**

| ID | Nombre | Descripción EN | Descripción ES |
|----|--------|---------------|---------------|
| kronos | Kronos EOS-5 Mk/IV | Warm, natural color. Reliable in any light condition. | Color cálido y natural. Confiable en cualquier condición de luz. |
| fujix | Fujix GFX-100S | Medium format. Extraordinary detail and tonal depth for large scenes. | Formato medio. Detalle y profundidad tonal extraordinarios para escenas amplias. |

---

### Modo: Person / Model

**Eyebrow:** `01 · Camera`
**Título EN:** `Choose your camera`
**Título ES:** `Elige tu cámara`
**Subtítulo EN:** `Each camera renders skin tone, texture, and depth differently. The Kronos is warm and human. The Fujix is luxurious and precise.`
**Subtítulo ES:** `Cada cámara renderiza el tono de piel, textura y profundidad de forma diferente. La Kronos es cálida y humana. La Fujix es lujosa y precisa.`
**Tip EN:** `For portraits, the Kronos EOS-5 Mk/IV produces warm, natural skin tones that have made it the standard in advertising photography for over a decade.`
**Tip ES:** `Para retratos, la Kronos EOS-5 Mk/IV produce tonos de piel cálidos y naturales que la han convertido en el estándar de la fotografía publicitaria por más de una década.`

**Opciones:**

| ID | Nombre | Descripción EN | Descripción ES |
|----|--------|---------------|---------------|
| kronos | Kronos EOS-5 Mk/IV | Warm skin tones, natural rendering. The portrait standard. | Tonos de piel cálidos, renderizado natural. El estándar del retrato. |
| fujix | Fujix GFX-100S | Medium format richness. Skin looks almost three-dimensional. | Riqueza de formato medio. La piel se ve casi tridimensional. |

---

### Modo: Product

**Eyebrow:** `01 · Camera`
**Título EN:** `Choose your camera`
**Título ES:** `Elige tu cámara`
**Subtítulo EN:** `Product photography demands precision. The right camera captures materials, textures, and finishes exactly as they are.`
**Subtítulo ES:** `La fotografía de producto exige precisión. La cámara correcta captura materiales, texturas y acabados exactamente como son.`
**Tip EN:** `For products, resolution and color accuracy matter most. The Fujix with its 102MP sensor reveals textures and surface details that lower-resolution cameras simply miss.`
**Tip ES:** `Para productos, la resolución y la precisión del color son lo más importante. El Fujix con su sensor de 102MP revela texturas y detalles de superficie que las cámaras de menor resolución simplemente pierden.`

**Opciones:**

| ID | Nombre | Descripción EN | Descripción ES |
|----|--------|---------------|---------------|
| kronos | Kronos EOS-5 Mk/IV | Reliable, accurate color. Great for lifestyle product shots. | Color confiable y preciso. Excelente para tomas de producto en contexto. |
| fujix | Fujix GFX-100S | Maximum detail. Every surface finish, material, and texture rendered perfectly. | Máximo detalle. Cada acabado de superficie, material y textura renderizado perfectamente. |

---

---

## SECCIÓN 2 — Lente

### Modo: General / Scene

**Eyebrow:** `02 · Lens`
**Título EN:** `Choose your lens`
**Título ES:** `Elige tu lente`
**Subtítulo EN:** `The lens determines your perspective — how much of the world fits in the frame and how depth is rendered.`
**Subtítulo ES:** `El lente determina tu perspectiva — cuánto del mundo cabe en el encuadre y cómo se renderiza la profundidad.`
**Tip EN:** `For environments and landscapes, wider lenses (24mm) exaggerate depth and make scenes feel vast. The 50mm gives a natural, "you are there" quality.`
**Tip ES:** `Para entornos y paisajes, los lentes más angulares (24mm) exageran la profundidad y hacen que las escenas se sientan vastas. El 50mm da una calidad natural, de "estás ahí".`

**Opciones:**

| ID | Nombre | Sub | Descripción EN | Descripción ES |
|----|--------|-----|---------------|---------------|
| l24 | 24mm f/1.4 | Ultra-Wide Prime | Captures vast environments. Strong depth perspective. | Captura entornos vastos. Perspectiva de profundidad fuerte. |
| l50 | 50mm f/1.2 | Standard Prime | Natural, human perspective. How the eye actually sees. | Perspectiva natural y humana. Como el ojo realmente ve. |
| l85 | 85mm f/1.2 | Portrait Prime | Slight compression isolates a focal point from its environment. | La leve compresión aísla un punto focal de su entorno. |
| l35 | 35mm f/1.4 | Wide Prime | Natural, documentary perspective. Subject within their world — no distortion. | Perspectiva natural y documental. Sujeto dentro de su mundo — sin distorsión. |
| l100 | 100mm f/2.8 | Macro Prime | Extreme detail — textures, surfaces, and tiny subjects at true life size. | Detalle extremo — texturas, superficies y sujetos pequeños a tamaño real. |
| l135 | 135mm f/2 | Telephoto Prime | Strong compression stacks layers beautifully. Cinematic and editorial look. | Compresión fuerte que apila capas de forma hermosa. Aspecto cinemático y editorial. |
| l1635 | 16-35mm f/2.8 | Wide Zoom | Full environment in frame. From very wide to moderately wide — maximum flexibility. | Entorno completo en el encuadre. De muy angular a moderadamente angular — flexibilidad máxima. |
| l2470 | 24-70mm f/2.8 | Standard Zoom | The all-purpose zoom. Covers wide group shots to tight portraits in one range. | El zoom todoterreno. Cubre desde planos grupales amplios hasta retratos cerrados en un solo rango. |
| l70200 | 70-200mm f/2.8 | Telephoto Zoom | Subjects pop dramatically from backgrounds. Strong compression and beautiful blur. | Los sujetos destacan dramáticamente del fondo. Fuerte compresión y hermoso desenfoque. |
| l14 | 14mm f/2.8 | Ultra-Wide / Astro | Horizon to horizon. Full night sky, vast interiors, awe-inspiring scale. | De horizonte a horizonte. Cielo nocturno completo, interiores vastos, escala impresionante. |
| l90ts | 90mm f/2.8 | Tilt-Shift | Makes scenes look like miniature models. Corrects perspective in architecture. | Hace que las escenas parezcan maquetas en miniatura. Corrige la perspectiva en arquitectura. |
| l500 | 500mm f/5.6 | Super Telephoto | Extreme reach. Background becomes a total blur. Distance subjects brought close. | Alcance extremo. El fondo se convierte en desenfoque total. Sujetos distantes traídos cerca. |
| l8fish | 8mm f/3.5 | Fisheye | Extreme 180° perspective. Environments wrap dramatically around the frame. | Perspectiva extrema de 180°. Los entornos se curvan dramáticamente alrededor del encuadre. |
| lanam | Anamorphic 50mm T2.1 | Anamorphic Cinema | Cinematic widescreen framing with horizontal flares and oval bokeh. | Encuadre cinemático panorámico con destellos horizontales y bokeh ovalado. |
| l200 | 200mm f/2 | Telephoto Prime | Extreme compression layers the scene — distant elements feel intimately close. | Compresión extrema que apila la escena — los elementos distantes se sienten íntimamente cercanos. |

---

### Modo: Person / Model

**Eyebrow:** `02 · Lens`
**Título EN:** `Choose your lens`
**Título ES:** `Elige tu lente`
**Subtítulo EN:** `Lens choice changes how a person looks — wider lenses exaggerate features, longer lenses flatter and compress. This is one of the most important decisions for portrait work.`
**Subtítulo ES:** `La elección del lente cambia cómo se ve una persona — los lentes más angulares exageran los rasgos, los más largos favorecen y comprimen. Es una de las decisiones más importantes en retrato.`
**Tip EN:** `The 85mm f/1.2 is the definitive portrait lens — its slight compression makes facial features look more proportional, and the background blur is exceptional. Most professional headshots and beauty campaigns use this focal length.`
**Tip ES:** `El 85mm f/1.2 es el lente de retrato por excelencia — su leve compresión hace que los rasgos faciales se vean más proporcionales, y el desenfoque del fondo es excepcional. La mayoría de los headshots profesionales y campañas de belleza usan esta focal.`

**Opciones:**

| ID | Nombre | Sub | Descripción EN | Descripción ES |
|----|--------|-----|---------------|---------------|
| l24 | 24mm f/1.4 | Ultra-Wide Prime | Environmental portrait — person within their world. Strong, dramatic perspective. | Retrato ambiental — persona dentro de su mundo. Perspectiva fuerte y dramática. |
| l50 | 50mm f/1.2 | Standard Prime | Natural, honest rendering. Person looks exactly as they are — no distortion. | Renderizado natural y honesto. La persona se ve exactamente como es — sin distorsión. |
| l85 | 85mm f/1.2 | Portrait Prime | The flattering lens. Slight compression, beautiful bokeh, most used in beauty and fashion. | El lente favorecedor. Leve compresión, bokeh hermoso, el más usado en belleza y moda. |
| l35 | 35mm f/1.4 | Wide Prime | Candid, documentary feel. Person in context, natural and unposed. | Aspecto candid y documental. Persona en contexto, natural y sin posar. |
| l100 | 100mm f/2.8 | Macro Prime | Revealing detail — skin texture, jewelry, makeup. Also a flattering portrait distance. | Detalle revelador — textura de piel, joyería, maquillaje. También una distancia de retrato favorecedora. |
| l135 | 135mm f/2 | Telephoto Prime | Natural and relaxed. Subject unaware of the camera. Painterly, cinematic bokeh. | Natural y relajado. El sujeto no siente la cámara. Bokeh pictórico y cinemático. |
| l1635 | 16-35mm f/2.8 | Wide Zoom | Person and their environment equally important. Wide context, strong narrative. | Persona y entorno igualmente importantes. Contexto amplio, narrativa fuerte. |
| l2470 | 24-70mm f/2.8 | Standard Zoom | Total versatility — from wide lifestyle shots to tight portrait crops in one session. | Versatilidad total — desde tomas lifestyle amplias hasta retratos cerrados en una sola sesión. |
| l70200 | 70-200mm f/2.8 | Telephoto Zoom | Subject isolated beautifully. Natural compression across the entire zoom range. | Sujeto aislado de forma hermosa. Compresión natural en todo el rango del zoom. |
| l14 | 14mm f/2.8 | Ultra-Wide / Astro | Immersive environmental portrait. Person dwarfed by a spectacular setting. | Retrato ambiental inmersivo. La persona empequeñecida por un entorno espectacular. |
| l90ts | 90mm f/2.8 | Tilt-Shift | Creative selective focus — only a thin slice of the person is sharp. Artistic and conceptual. | Enfoque selectivo creativo — solo una fina franja de la persona está nítida. Artístico y conceptual. |
| l500 | 500mm f/5.6 | Super Telephoto | Completely candid. Subject unaware, background a painted blur. Total compression. | Completamente candid. Sujeto desprevenido, fondo como pintura difuminada. Compresión total. |
| l8fish | 8mm f/3.5 | Fisheye | Immersive distortion. Subject dominates the frame with exaggerated foreground presence. | Distorsión inmersiva. El sujeto domina el encuadre con presencia en primer plano exagerada. |
| lanam | Anamorphic 50mm T2.1 | Anamorphic Cinema | Hollywood portrait rendering. Horizontal flares, oval bokeh, unmistakably filmic. | Renderizado de retrato Hollywood. Destellos horizontales, bokeh ovalado, inconfundiblemente fílmico. |
| l200 | 200mm f/2 | Telephoto Prime | Maximum subject isolation. Background dissolves into a painterly blur — the most cinematic portrait possible. | Aislamiento máximo del sujeto. El fondo se disuelve en un desenfoque pictórico — el retrato más cinemático posible. |

---

### Modo: Product

**Eyebrow:** `02 · Lens`
**Título EN:** `Choose your lens`
**Título ES:** `Elige tu lente`
**Subtítulo EN:** `For product photography, the lens determines how the object is presented — wide for context and environment, longer for isolation and detail.`
**Subtítulo ES:** `En fotografía de producto, el lente determina cómo se presenta el objeto — angular para contexto y entorno, más largo para aislamiento y detalle.`
**Tip EN:** `The 85mm is the most versatile for products — it isolates the object beautifully from the background without distorting its shape. Use 24mm only when the environment is as important as the product itself.`
**Tip ES:** `El 85mm es el más versátil para productos — aísla el objeto del fondo de manera hermosa sin distorsionar su forma. Usa el 24mm solo cuando el entorno es tan importante como el producto mismo.`

**Opciones:**

| ID | Nombre | Sub | Descripción EN | Descripción ES |
|----|--------|-----|---------------|---------------|
| l24 | 24mm f/1.4 | Ultra-Wide Prime | Product in environment. Wide context, strong spatial depth. Best for lifestyle scenes. | Producto en entorno. Contexto amplio, profundidad espacial fuerte. Ideal para escenas lifestyle. |
| l50 | 50mm f/1.2 | Standard Prime | Balanced, natural rendering. Product looks proportional and honest. | Renderizado equilibrado y natural. El producto se ve proporcional y honesto. |
| l85 | 85mm f/1.2 | Portrait Prime | Clean isolation. Product pops off the background. The packshot standard. | Aislamiento limpio. El producto destaca del fondo. El estándar del packshot. |
| l35 | 35mm f/1.4 | Wide Prime | Product with generous environment. Lifestyle and in-use context. Natural scale. | Producto con entorno generoso. Contexto lifestyle y de uso. Escala natural. |
| l100 | 100mm f/2.8 | Macro Prime | Ultimate detail. Every surface finish, material texture, and micro-element perfectly sharp. | Detalle máximo. Cada acabado de superficie, textura de material y micro-elemento perfectamente nítido. |
| l135 | 135mm f/2 | Telephoto Prime | Premium isolation with cinematic compression. Background layers create depth. | Aislamiento premium con compresión cinemática. Las capas del fondo crean profundidad. |
| l1635 | 16-35mm f/2.8 | Wide Zoom | Product in full scene. Wide environment integration — spatial storytelling. | Producto en escena completa. Integración ambiental amplia — narrativa espacial. |
| l2470 | 24-70mm f/2.8 | Standard Zoom | Covers every product scenario from context to hero shot in a single flexible range. | Cubre cada escenario de producto, desde contexto hasta hero shot, en un rango flexible. |
| l70200 | 70-200mm f/2.8 | Telephoto Zoom | Strong compression separates product from its surroundings. Excellent for lifestyle context. | Fuerte compresión separa el producto de su entorno. Excelente para contexto lifestyle. |
| l14 | 14mm f/2.8 | Ultra-Wide / Astro | Product as part of a spectacular or dramatic environment. Scale contrast. | Producto como parte de un entorno espectacular o dramático. Contraste de escala. |
| l90ts | 90mm f/2.8 | Tilt-Shift | Selective focus on specific product zones. Toy-scale miniature effect for creative campaigns. | Enfoque selectivo en zonas específicas del producto. Efecto miniatura en escala de juguete para campañas creativas. |
| l500 | 500mm f/5.6 | Super Telephoto | Extreme isolation. Background completely eliminated. Product against a pure, blurred wash. | Aislamiento extremo. Fondo completamente eliminado. Producto sobre una capa difuminada pura. |
| l8fish | 8mm f/3.5 | Fisheye | Extreme environment immersion. Product in dramatic distorted context — unconventional and unforgettable. | Inmersión ambiental extrema. Producto en contexto distorsionado dramático — inconvencional e inolvidable. |
| lanam | Anamorphic 50mm T2.1 | Anamorphic Cinema | Cinematic product story. Object framed like a film prop — widescreen atmosphere and distinctive flares. | Historia cinemática de producto. Objeto encuadrado como prop de película — atmósfera panorámica y destellos característicos. |
| l200 | 200mm f/2 | Telephoto Prime | Complete isolation. Product against a totally smooth, painterly background — premium and cinematic. | Aislamiento completo. Producto sobre un fondo totalmente suave y pictórico — premium y cinemático. |

---

---

## SECCIÓN 3 — Iluminación

### Sub-sección: Fuente de Luz

#### Modo: General / Scene

**Eyebrow:** `03 · Lighting`
**Título EN:** `Set the light`
**Título ES:** `Configura la luz`
**Subtítulo EN:** `Light transforms any scene. The same environment at golden hour vs. flat overcast tells completely different stories.`
**Subtítulo ES:** `La luz transforma cualquier escena. El mismo entorno a la hora dorada versus cielo nublado cuenta historias completamente distintas.`

**Fuentes de luz:**

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| golden | Golden Hour | Hora Dorada | Warm directional light. Long shadows, golden tones. The most cinematic natural light. | Luz natural cálida y direccional. Sombras largas, tonos dorados. La luz natural más cinemática. |
| overcast | Overcast Diffused | Nublado Difuso | Even light with no harsh shadows. Perfect for scenes needing detail everywhere. | Luz uniforme sin sombras duras. Perfecta para escenas que necesitan detalle en todas partes. |
| softbox | Studio Softbox | Softbox de Estudio | Controlled, clean light. Removes the environment — scene becomes the focus. | Luz controlada y limpia. Elimina el entorno — la escena se convierte en el foco. |
| rim | Rim / Backlight | Contraluz | Light from behind creates atmosphere, depth, and separation from background. | La luz desde atrás crea atmósfera, profundidad y separación del fondo. |

---

#### Modo: Person / Model

**Eyebrow:** `03 · Lighting`
**Título EN:** `Light your subject`
**Título ES:** `Ilumina a tu sujeto`
**Subtítulo EN:** `Lighting is the single most powerful variable in portrait photography. The same person under different light becomes a completely different image.`
**Subtítulo ES:** `La iluminación es la variable más poderosa en la fotografía de retrato. La misma persona bajo diferente luz se convierte en una imagen completamente distinta.`

**Fuentes de luz:**

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| golden | Golden Hour | Hora Dorada | The most flattering natural light. Warm tones, soft shadows. Makes skin glow. | La luz natural más favorecedora. Tonos cálidos, sombras suaves. Hace que la piel resplandezca. |
| overcast | Overcast Diffused | Nublado Difuso | Perfectly even light. No harsh shadows. Skin looks smooth — favored by beauty photographers. | Luz perfectamente uniforme. Sin sombras duras. La piel se ve suave — preferida por fotógrafos de belleza. |
| softbox | Studio Softbox | Softbox de Estudio | Classic commercial portrait light. Clean, professional, fully controlled. | Luz de retrato comercial clásica. Limpia, profesional, completamente controlada. |
| rim | Rim / Backlight | Contraluz | Glowing outline around hair and shoulders. Ethereal and cinematic. | Contorno luminoso alrededor del cabello y hombros. Etéreo y cinematográfico. |

---

#### Modo: Product

**Eyebrow:** `03 · Lighting`
**Título EN:** `Light your product`
**Título ES:** `Ilumina tu producto`
**Subtítulo EN:** `Product lighting is about revealing materials, finishes, and form. The wrong light hides what makes a product desirable.`
**Subtítulo ES:** `La iluminación de producto consiste en revelar materiales, acabados y forma. La luz incorrecta oculta lo que hace deseable a un producto.`

**Fuentes de luz:**

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| golden | Golden Hour | Hora Dorada | Warm lifestyle feel. Makes products look inviting and aspirational. | Ambiente lifestyle cálido. Hace que los productos se vean atractivos y aspiracionales. |
| overcast | Overcast Diffused | Nublado Difuso | Clean, even light reveals surface details without distracting reflections. | Luz limpia y uniforme que revela detalles de superficie sin reflejos distorsionantes. |
| softbox | Studio Softbox | Softbox de Estudio | The packshot standard. Precise, controlled light that shows the product as it truly is. | El estándar del packshot. Luz precisa y controlada que muestra el producto tal como es. |
| rim | Rim / Backlight | Contraluz | Creates a premium glow around edges. Makes glass, metal, and liquid look extraordinary. | Crea un brillo premium en los bordes. Hace que el vidrio, el metal y los líquidos se vean extraordinarios. |

---

### Sub-sección: Dirección de Luz

*(Las opciones son las mismas en los tres modos — solo cambia el contexto del tip)*

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| frontal | Frontal / Flat | Frontal / Plano | Even, shadowless light. Clean and accurate. | Luz uniforme, sin sombras. Limpia y precisa. |
| side45 | 45° Side | Lateral 45° | Classic angle. Creates gentle shadows that reveal shape and depth. | Ángulo clásico. Crea sombras suaves que revelan forma y profundidad. |
| wrap | Wraparound Soft | Envolvente Suave | Light from multiple directions. Shadows almost disappear. Maximum flattery. | Luz desde múltiples direcciones. Las sombras casi desaparecen. Máximo efecto favorecedor. |

**Tip — General EN:** `Direction creates the illusion of three-dimensionality. Frontal light is flat but accurate. 45° side light gives depth to any subject.`
**Tip — General ES:** `La dirección crea la ilusión de tridimensionalidad. La luz frontal es plana pero precisa. La luz lateral a 45° da profundidad a cualquier sujeto.`

**Tip — Persona EN:** `For portraits, 45° side is the universally flattering starting point — like afternoon light through a window. Wraparound is the choice for beauty and skincare when even the subtlest shadow is undesirable.`
**Tip — Persona ES:** `Para retratos, el lateral a 45° es el punto de partida universalmente favorecedor — como la luz de la tarde a través de una ventana. El envolvente es la elección para belleza y skincare cuando incluso la sombra más sutil es indeseable.`

**Tip — Producto EN:** `For products, direction reveals or hides texture. Side light at 45° brings out surface details — perfect for fabric, leather, or any tactile material. Frontal light is cleaner but flatter.`
**Tip — Producto ES:** `Para productos, la dirección revela u oculta textura. La luz lateral a 45° resalta los detalles de superficie — perfecta para tela, cuero o cualquier material táctil. La luz frontal es más limpia pero más plana.`

---

### Sub-sección: Modificadores de Luz

*(Solo Catchlights en Lite — contexto varía)*

| ID | Nombre EN | Nombre ES | Descripción — Persona EN | Descripción — Persona ES |
|----|-----------|-----------|--------------------------|--------------------------|
| catchlights | Catchlights | Destellos en ojos | The spark of light in the eyes that makes a person look alive and engaged. Always recommended for portraits. | El destello de luz en los ojos que hace que una persona se vea viva y presente. Siempre recomendado en retratos. |

> **Nota:** Catchlights solo aplica en modo Persona/Modelo. En modo General y Producto esta subsección no aparece.

---

---

## SECCIÓN 4 — Composición

### Sub-sección: Tipo de Plano

#### Modo: General / Scene

**Eyebrow:** `04 · Composition`
**Título EN:** `Frame your scene`
**Título ES:** `Encuadra tu escena`
**Subtítulo EN:** `Framing determines the relationship between the viewer and the scene — intimate or epic, detailed or expansive.`
**Subtítulo ES:** `El encuadre determina la relación entre el espectador y la escena — íntima o épica, detallada o expansiva.`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| cu | Close-Up | Primer Plano | A single detail fills the frame — a flower, a texture, a fragment. | Un solo detalle llena el encuadre — una flor, una textura, un fragmento. |
| mcu | Medium Close-Up | Plano Medio Corto | A specific element in context — close enough to read detail, wide enough for setting. | Un elemento específico en contexto — suficientemente cerca para el detalle, suficientemente amplio para el entorno. |
| ms | Medium Shot | Plano Medio | Balanced view — subject and environment share equal weight. | Vista equilibrada — sujeto y entorno comparten igual peso. |
| full | Wide / Establishing | Plano General | The full scene. Environment is the subject. Scale and vastness. | La escena completa. El entorno es el sujeto. Escala y vastedad. |

---

#### Modo: Person / Model

**Eyebrow:** `04 · Composition`
**Título EN:** `Frame your subject`
**Título ES:** `Encuadra a tu sujeto`
**Subtítulo EN:** `Shot type controls intimacy. Close shots feel personal and emotional. Wide shots put the person in their world.`
**Subtítulo ES:** `El tipo de plano controla la intimidad. Los planos cerrados se sienten personales y emocionales. Los abiertos ponen a la persona en su mundo.`
**Tip EN:** `For social media and advertising content, the medium shot (waist up) is the most versatile framing — it shows the face, expression, and outfit without losing the environment entirely.`
**Tip ES:** `Para contenido de redes sociales y publicidad, el plano medio (hasta la cintura) es el encuadre más versátil — muestra el rostro, expresión y atuendo sin perder completamente el entorno.`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| cu | Close-Up | Primer Plano | Face fills the frame. Maximum emotional impact. Every detail of expression visible. | El rostro llena el encuadre. Máximo impacto emocional. Cada detalle de la expresión visible. |
| mcu | Medium Close-Up | Plano Medio Corto | Mid-chest upward. The natural conversation distance — personal but not overwhelming. | Desde el pecho hacia arriba. La distancia natural de conversación — personal sin ser abrumador. |
| ms | Medium Shot | Plano Medio | Waist up. Face, arms, and gesture. Versatile for lifestyle and commercial. | Desde la cintura. Rostro, brazos y gesto. Versátil para lifestyle y comercial. |
| full | Full Body | Plano General | Head to toe. Complete person — outfit, posture, and presence. | De cabeza a pies. Persona completa — atuendo, postura y presencia. |

---

#### Modo: Product

**Eyebrow:** `04 · Composition`
**Título EN:** `Frame your product`
**Título ES:** `Encuadra tu producto`
**Subtítulo EN:** `How you frame a product changes its perceived value. Tight frames feel premium. Wide frames tell a lifestyle story.`
**Subtítulo ES:** `Cómo encuadras un producto cambia su valor percibido. Los encuadres cerrados se sienten premium. Los amplios cuentan una historia de lifestyle.`
**Tip EN:** `For e-commerce hero shots, a close-up or medium close-up with clean background creates the highest conversion. For lifestyle and social content, a medium or wide shot with environment adds context and desirability.`
**Tip ES:** `Para hero shots de e-commerce, un primer plano o plano medio corto con fondo limpio genera la mayor conversión. Para lifestyle y contenido social, un plano medio o general con entorno añade contexto y deseabilidad.`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| cu | Detail / Macro | Detalle / Macro | One specific feature fills the frame — texture, logo, material finish. The premium reveal. | Una característica específica llena el encuadre — textura, logo, acabado de material. La revelación premium. |
| mcu | Hero Shot | Hero Shot | Product centered, background secondary. The e-commerce standard — product is everything. | Producto centrado, fondo secundario. El estándar del e-commerce — el producto lo es todo. |
| ms | Product in Context | Producto en Contexto | Product with props or setting. Tells a usage story. Strong for social and lifestyle campaigns. | Producto con props o entorno. Cuenta una historia de uso. Poderoso para campañas social y lifestyle. |
| full | Full Scene | Escena Completa | Product as part of a larger scene. Environment carries as much narrative as the object. | El producto como parte de una escena más amplia. El entorno lleva tanto peso narrativo como el objeto. |

---

### Sub-sección: Ángulo de Cámara

*(Mismo contenido en los tres modos — solo cambia el tip)*

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| eye | Eye Level | Nivel de Ojos | Natural, neutral perspective. The viewer is an equal. | Perspectiva natural y neutral. El espectador es un igual. |
| low | Low Angle | Ángulo Bajo | Camera below looking up. Makes subjects appear powerful, tall, imposing. | Cámara abajo mirando arriba. Hace que los sujetos parezcan poderosos, altos, imponentes. |

**Tip — General EN:** `Angle changes the emotional relationship between viewer and subject. Eye level feels honest. Low angle makes anything look monumental.`
**Tip — General ES:** `El ángulo cambia la relación emocional entre espectador y sujeto. El nivel de ojos se siente honesto. El ángulo bajo hace que cualquier cosa parezca monumental.`

**Tip — Persona EN:** `Eye level is the default for authentic portraits — the viewer and subject feel like equals. Low angle elongates the body and projects confidence — a classic choice in fashion.`
**Tip — Persona ES:** `El nivel de ojos es el predeterminado para retratos auténticos — el espectador y el sujeto se sienten iguales. El ángulo bajo alarga el cuerpo y proyecta confianza — una elección clásica en moda.`

**Tip — Producto EN:** `Eye level shows products as they naturally exist. Low angle makes even a small product look monumental — great for hero shots where you want the object to feel impressive.`
**Tip — Producto ES:** `El nivel de ojos muestra los productos como existen naturalmente. El ángulo bajo hace que incluso un producto pequeño parezca monumental — excelente para hero shots donde quieres que el objeto se sienta imponente.`

---

---

## SECCIÓN 5 — Exposición

### Sub-sección: Apertura

*(Opciones iguales en los tres modos — los tips varían)*

| Valor | Descripción EN | Descripción ES |
|-------|---------------|---------------|
| f/1.2 | Maximum blur. Only the focus point is sharp — everything else melts. | Desenfoque máximo. Solo el punto de enfoque es nítido — todo lo demás se disuelve. |
| f/1.8 | Beautiful background blur with more tolerance. The portrait sweet spot. | Desenfoque hermoso del fondo con más tolerancia. El punto ideal para retrato. |
| f/2.8 | Good separation with more of the subject in focus. Standard for versatile work. | Buena separación con más del sujeto en foco. Estándar para trabajo versátil. |

**Tip — General EN:** `For landscapes and scenes, higher f-numbers (f/2.8 or above) keep more of the environment in focus — from the foreground detail to the horizon. Low f-numbers are useful when you want a single element to stand out from an abstract background.`
**Tip — General ES:** `Para paisajes y escenas, números f más altos (f/2.8 o más) mantienen más del entorno en foco — desde el detalle del primer plano hasta el horizonte. Los números f bajos son útiles cuando quieres que un solo elemento destaque de un fondo abstracto.`

**Tip — Persona EN:** `f/1.2 creates the dreamy, subject-only focus that makes portraits feel cinematic. f/1.8 is more practical — slightly more forgiving on focus while still producing beautiful background separation.`
**Tip — Persona ES:** `f/1.2 crea el enfoque solo en el sujeto, onírico, que hace que los retratos se sientan cinemáticos. f/1.8 es más práctico — ligeramente más tolerante en el enfoque mientras aún produce una hermosa separación del fondo.`

**Tip — Producto EN:** `For isolated packshots, f/1.8–f/2.8 creates beautiful background separation while keeping the entire product sharp. For product in environment, f/2.8 balances subject sharpness with enough context.`
**Tip — Producto ES:** `Para packshots aislados, f/1.8–f/2.8 crea una hermosa separación del fondo mientras mantiene todo el producto nítido. Para producto en entorno, f/2.8 equilibra la nitidez del sujeto con suficiente contexto.`

---

### Sub-sección: ISO

*(Opciones iguales en los tres modos)*

| Valor | Descripción EN | Descripción ES |
|-------|---------------|---------------|
| ISO 100 | Cleanest image. No grain. Needs good light. The studio standard. | Imagen más limpia. Sin grano. Necesita buena luz. El estándar de estudio. |
| ISO 400 | Clean with slightly more sensitivity. Works in moderate ambient light. | Limpio con un poco más de sensibilidad. Funciona con luz ambiental moderada. |

---

### Sub-sección: Motion & Time Style

#### Modo: General / Scene

**Eyebrow / Título subsección:** `Motion & Time Style`
**Subtítulo EN:** `How does time appear in this image? Still and frozen, or flowing and temporal?`
**Subtítulo ES:** `¿Cómo aparece el tiempo en esta imagen? Quieto y congelado, o fluyendo y temporal?`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| still | Perfectly Still | Totalmente Inmóvil | Everything frozen in time. Maximum sharpness. Classic landscape and architecture look. | Todo congelado en el tiempo. Máxima nitidez. El aspecto clásico de paisaje y arquitectura. |
| frozen | Frozen Action | Acción Congelada | Stops fast movement invisible to the eye — waves mid-crash, leaves in wind. | Detiene movimiento rápido invisible al ojo — olas a mitad de impacto, hojas en el viento. |
| silky | Silky Water / Smooth Flow | Agua Sedosa / Flujo Suave | Waterfalls, rivers, and ocean become smooth silk. The signature look of fine art landscape. | Cascadas, ríos y océano se convierten en seda suave. El aspecto distintivo del paisaje de arte fino. |

---

#### Modo: Person / Model

**Subtítulo EN:** `Should the person appear frozen in a precise moment, or does movement add energy and life to the image?`
**Subtítulo ES:** `¿Debe la persona aparecer congelada en un momento preciso, o el movimiento añade energía y vida a la imagen?`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| still | Perfectly Still | Totalmente Inmóvil | Person is sharp and present. Every detail of expression and styling clear. | La persona está nítida y presente. Cada detalle de expresión y styling claro. |
| frozen | Frozen Action | Acción Congelada | Movement arrested mid-motion — hair in wind, mid-laugh, fabric caught in movement. | Movimiento detenido a mitad — cabello en el viento, a mitad de risa, tela atrapada en movimiento. |
| silky | Silky Water / Smooth Flow | Agua Sedosa / Flujo Suave | Background elements blur while person stays sharp. Dreamy, editorial quality. | Los elementos del fondo se difuminan mientras la persona permanece nítida. Calidad editorial y onírica. |

---

#### Modo: Product

**Subtítulo EN:** `Most product photography is perfectly still — but motion can create drama for liquids, splashes, and dynamic lifestyle shots.`
**Subtítulo ES:** `La mayoría de la fotografía de producto es perfectamente inmóvil — pero el movimiento puede crear drama para líquidos, salpicaduras y tomas de lifestyle dinámicas.`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| still | Perfectly Still | Totalmente Inmóvil | Product is sharp and precise. Every detail visible. The e-commerce standard. | El producto está nítido y preciso. Cada detalle visible. El estándar del e-commerce. |
| frozen | Frozen Action | Acción Congelada | Freeze a dynamic moment — liquid splash, powder burst, product in motion. High energy. | Congela un momento dinámico — salpicadura de líquido, explosión de polvo, producto en movimiento. Alta energía. |
| silky | Silky Water / Smooth Flow | Agua Sedosa / Flujo Suave | Flowing elements around the product — silk fabric, water, smoke — while the product stays sharp. | Elementos fluyendo alrededor del producto — tela de seda, agua, humo — mientras el producto permanece nítido. |

---

---

## SECCIÓN 6 — Color y Estilo

### Sub-sección: Color Grade

#### Modo: General / Scene

**Eyebrow:** `06 · Color & Style`
**Título EN:** `Define the look`
**Título ES:** `Define el aspecto`
**Subtítulo EN:** `Color grade sets the emotional temperature of your scene — warm and inviting, cold and dramatic, or neutral and honest.`
**Subtítulo ES:** `El grado de color establece la temperatura emocional de tu escena — cálida e invitadora, fría y dramática, o neutral y honesta.`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| natural | Natural | Natural | Honest, accurate colors. What was there is what you see. | Colores honestos y precisos. Lo que había es lo que ves. |
| warm | Warm / Golden | Cálido / Dorado | Golden tones. Inviting and organic. The feeling of late afternoon. | Tonos dorados. Acogedor y orgánico. La sensación de última hora de la tarde. |
| cool | Cool / Cinematic | Frío / Cinemático | Blue-tinted shadows, crisp highlights. Modern and cinematic. | Sombras con tintes azules, luces nítidas. Moderno y cinemático. |

---

#### Modo: Person / Model

**Subtítulo EN:** `Color grade changes how skin looks and what emotion the image carries. Warm grades feel human and inviting. Cool grades feel sharp and editorial.`
**Subtítulo ES:** `El grado de color cambia cómo se ve la piel y qué emoción transmite la imagen. Los grados cálidos se sienten humanos y acogedores. Los fríos se sienten nítidos y editoriales.`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| natural | Natural | Natural | True skin tones. No manipulation — what the person actually looks like. | Tonos de piel verdaderos. Sin manipulación — cómo se ve realmente la persona. |
| warm | Warm / Golden | Cálido / Dorado | Warm, glowing skin. The lifestyle and beauty standard — flattering and aspirational. | Piel cálida y radiante. El estándar de lifestyle y belleza — favorecedor y aspiracional. |
| cool | Cool / Cinematic | Frío / Cinemático | Crisp, editorial feel. Skin tones slightly desaturated. Fashion and high-end editorial look. | Aspecto nítido y editorial. Tonos de piel ligeramente desaturados. Look de moda y editorial de alto nivel. |

---

#### Modo: Product

**Subtítulo EN:** `For products, color accuracy is often more important than mood. Choose natural unless a specific emotional tone is part of the brand.`
**Subtítulo ES:** `Para productos, la precisión del color suele ser más importante que el estado de ánimo. Elige natural a menos que un tono emocional específico sea parte de la marca.`

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| natural | Natural | Natural | Accurate colors. Product looks exactly as it does in real life — critical for e-commerce trust. | Colores precisos. El producto se ve exactamente como en la vida real — fundamental para la confianza en e-commerce. |
| warm | Warm / Golden | Cálido / Dorado | Golden, premium feel. Makes products look desirable and artisanal. Ideal for food, beauty, lifestyle. | Aspecto dorado y premium. Los productos se ven deseables y artesanales. Ideal para alimentos, belleza y lifestyle. |
| cool | Cool / Cinematic | Frío / Cinemático | Clean, modern, high-tech feel. Ideal for electronics, sportswear, and contemporary brands. | Aspecto limpio, moderno y de alta tecnología. Ideal para electrónica, ropa deportiva y marcas contemporáneas. |

---

### Sub-sección: Técnica Visual

*(Opciones iguales — descripciones varían por modo)*

#### Modo: General / Scene

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| photo | Photorealistic | Fotorrealista | Indistinguishable from a real photograph. Physically accurate light and detail. | Indistinguible de una fotografía real. Luz y detalle físicamente precisos. |
| grain | Film Grain / Analog | Grano de Película / Analógico | Organic grain and warmth of photographic film. Timeless, human, slightly imperfect. | Grano orgánico y calidez de la película fotográfica. Atemporal, humano, ligeramente imperfecto. |
| fashion | Editorial / Commercial | Editorial / Comercial | Polished and intentional. Every element art-directed. Clean, premium, purposeful. | Pulido e intencional. Cada elemento dirigido artísticamente. Limpio, premium, con propósito. |

---

#### Modo: Person / Model

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| photo | Photorealistic | Fotorrealista | Looks like an actual photograph — natural skin, real lighting behavior, authentic. | Parece una fotografía real — piel natural, comportamiento de luz real, auténtico. |
| grain | Film Grain / Analog | Grano de Película / Analógico | The analog film look — grain, warmth, and the imperfections that make images feel human. | El aspecto de película analógica — grano, calidez y las imperfecciones que hacen que las imágenes se sientan humanas. |
| fashion | Fashion / Commercial | Moda / Comercial | High-production, flawless finish. The look of major fashion and beauty campaigns. | Alta producción, acabado impecable. El aspecto de las grandes campañas de moda y belleza. |

---

#### Modo: Product

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| photo | Photorealistic | Fotorrealista | Product looks like a real photograph — accurate materials, correct light behavior. | El producto parece una fotografía real — materiales precisos, comportamiento de luz correcto. |
| grain | Film Grain / Analog | Grano de Película / Analógico | Adds warmth and character — excellent for artisanal, food, and heritage brands. | Añade calidez y carácter — excelente para marcas artesanales, de alimentos y heritage. |
| fashion | Commercial / Campaign | Comercial / Campaña | High-end campaign finish. Polished, premium, and immediately brand-ready. | Acabado de campaña de alta gama. Pulido, premium e inmediatamente listo para la marca. |

---

### Sub-sección: Extras Técnicos

*(Igual en todos los modos)*

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| 8k | 8K Resolution | Resolución 8K | Maximum detail. Every texture sharp. Scalable to billboard without losing quality. | Detalle máximo. Cada textura nítida. Escalable a cartelera sin perder calidad. |

---

---

## SECCIÓN 7 — Escena y Sujeto

### Sub-sección: Descripción del Sujeto

#### Modo: General / Scene

**Label EN:** `Scene description`
**Label ES:** `Descripción de la escena`
**Placeholder EN:** `An empty road disappearing into a fog-covered forest at dawn, wet asphalt reflecting grey light...`
**Placeholder ES:** `Una carretera vacía que desaparece en un bosque cubierto de niebla al amanecer, asfalto mojado reflejando luz gris...`
**Helper EN:** `Describe the scene in your own words. Focus on what you want to see — environment, atmosphere, specific elements, time of day, mood.`
**Helper ES:** `Describe la escena con tus propias palabras. Enfócate en lo que quieres ver — entorno, atmósfera, elementos específicos, hora del día, estado de ánimo.`

---

#### Modo: Person / Model

**Label EN:** `Subject description`
**Label ES:** `Descripción del sujeto`
**Placeholder EN:** `A woman in her early 30s, short dark hair, wearing an oversized cream linen blazer, looking off-camera to the left...`
**Placeholder ES:** `Una mujer de unos 30 años, cabello corto oscuro, usando un blazer de lino crema oversize, mirando fuera de cámara hacia la izquierda...`
**Helper EN:** `Describe the person — age, hair, expression, clothing, pose, energy. The more specific, the more accurate the result.`
**Helper ES:** `Describe a la persona — edad, cabello, expresión, ropa, pose, energía. Cuanto más específico, más preciso el resultado.`

---

#### Modo: Product

**Label EN:** `Product description`
**Label ES:** `Descripción del producto`
**Placeholder EN:** `A 50ml amber glass perfume bottle with a brushed gold cap, minimalist label, half full...`
**Placeholder ES:** `Un frasco de perfume de vidrio ámbar de 50ml con tapa dorada cepillada, etiqueta minimalista, a medio llenar...`
**Helper EN:** `Describe the product — material, color, size, finish, any distinctive features. Include the brand or label if relevant.`
**Helper ES:** `Describe el producto — material, color, tamaño, acabado, cualquier característica distintiva. Incluye la marca o etiqueta si es relevante.`

---

### Sub-sección: Tags de Tipo de Sujeto

#### Modo: General / Scene

| ID | Nombre EN | Nombre ES |
|----|-----------|-----------|
| landscape | Landscape | Paisaje |
| architecture | Architecture | Arquitectura |
| abstract | Abstract / Conceptual | Abstracto / Conceptual |
| nature | Nature / Wildlife | Naturaleza / Fauna |

---

#### Modo: Person / Model

| ID | Nombre EN | Nombre ES |
|----|-----------|-----------|
| portrait | Portrait | Retrato |
| fashion | Fashion / Outfit | Moda / Atuendo |
| lifestyle | Lifestyle | Lifestyle |
| beauty | Beauty / Close-Up | Belleza / Primer Plano |

---

#### Modo: Product

| ID | Nombre EN | Nombre ES |
|----|-----------|-----------|
| packshot | Packshot / Hero | Packshot / Hero |
| lifestyle_prod | Lifestyle Product | Producto Lifestyle |
| detail | Detail / Macro | Detalle / Macro |
| flat_lay | Flat Lay | Flat Lay |

---

### Sub-sección: Scene Preset

*(Los presets son los mismos en los tres modos — solo cambia cuál es relevante y el tip)*

| ID | Nombre EN | Nombre ES | Descripción EN | Descripción ES |
|----|-----------|-----------|---------------|---------------|
| urban | Urban Street | Calle Urbana | City, concrete, architecture, urban context. | Ciudad, concreto, arquitectura, contexto urbano. |
| nature | Nature / Forest | Naturaleza / Bosque | Trees, organic, outdoor greenery, natural environment. | Árboles, orgánico, vegetación exterior, entorno natural. |
| studio | Studio / Seamless | Estudio / Fondo Liso | Clean studio background, seamless backdrop, no environment. | Fondo limpio de estudio, fondo sin costuras, sin entorno. |
| interior | Interior | Interior | Indoor architectural space, designed interior, lifestyle context. | Espacio arquitectónico interior, interior diseñado, contexto de lifestyle. |

**Tip — General EN:** `For scene-focused photography, combining a preset with weather and mood modifiers creates the most complete environments. Try Urban + Rain + Blue Hour + Cinematic.`
**Tip — General ES:** `Para fotografía enfocada en la escena, combinar un preset con modificadores de clima y estado de ánimo crea los entornos más completos. Prueba Urbano + Lluvia + Hora Azul + Cinemático.`

**Tip — Persona EN:** `The scene creates context for your subject. Studio gives maximum control. Urban and Interior add lifestyle narrative. The best choice depends on whether the environment is part of the story.`
**Tip — Persona ES:** `La escena crea contexto para tu sujeto. El estudio da máximo control. Urbano e Interior añaden narrativa de lifestyle. La mejor elección depende de si el entorno es parte de la historia.`

**Tip — Producto EN:** `Studio / Seamless is the standard for e-commerce — the product has nowhere to hide and everything is focused on it. Interior and Urban add lifestyle context for brand campaigns and social content.`
**Tip — Producto ES:** `Estudio / Fondo Liso es el estándar para e-commerce — el producto no tiene dónde esconderse y todo está enfocado en él. Interior y Urbano añaden contexto de lifestyle para campañas de marca y contenido social.`

---

### Sub-sección: Modificadores de Escena

*(Time of Day, Weather, Mood — iguales en todos los modos, mismas opciones)*

#### Time of Day

| ID | Nombre EN | Nombre ES |
|----|-----------|-----------|
| golden | Golden Hour | Hora Dorada |
| bluehour | Blue Hour / Dusk | Hora Azul / Crepúsculo |

#### Weather & Atmosphere

| ID | Nombre EN | Nombre ES |
|----|-----------|-----------|
| clear | Clear Sky | Cielo Despejado |
| rain | Rain / Wet | Lluvia / Mojado |

#### Mood

| ID | Nombre EN | Nombre ES |
|----|-----------|-----------|
| cinematic | Cinematic | Cinemático |
| intimate | Intimate / Quiet | Íntimo / Tranquilo |

---

### Sub-sección: Referencia de Modelo

> **Solo aparece en Modo: Persona / Modelo**
> No aparece en General ni en Producto (la referencia de producto es Pro)

**Toggle label EN:** `Use a reference photo`
**Toggle label ES:** `Usar una foto de referencia`
**Toggle sub EN:** `Add instructions to preserve a person's appearance in the generated image`
**Toggle sub ES:** `Añade instrucciones para preservar la apariencia de una persona en la imagen generada`

**Panel description EN:** `When activated, your prompt will include instructions for the AI to follow your reference photo. Attach the photo when pasting into your AI generator (ChatGPT, Midjourney, etc.).`
**Panel description ES:** `Al activarlo, tu prompt incluirá instrucciones para que la IA siga tu foto de referencia. Adjunta la foto al pegar en tu generador de IA (ChatGPT, Midjourney, etc.).`

**Fidelity Level — High:**
- **Nombre EN:** `High Fidelity`
- **Nombre ES:** `Alta Fidelidad`
- **Descripción EN:** `Maintain recognizable likeness, skin tone, and hair. Adapt clothing, expression, and pose to the scene.`
- **Descripción ES:** `Mantén el parecido reconocible, el tono de piel y el cabello. Adapta la ropa, expresión y pose a la escena.`
- **Prompt instruction:** `Use the attached person as the primary visual reference. Maintain recognizable likeness, skin tone, and hair. Adapt clothing, expression, and pose to the scene. Minor lighting adjustments are acceptable.`

---

---

## Textos de la Barra de Selecciones (Output Panel)

*(Igual en los tres modos)*

| Elemento | EN | ES |
|----------|----|----|
| Panel title | Generated Prompt | Prompt Generado |
| Selections title | Current Selections | Selecciones Actuales |
| Empty state | Your prompt will appear here as you make selections. | Tu prompt aparecerá aquí conforme hagas selecciones. |
| Copy button | Copy prompt — paste anywhere | Copiar prompt — pegar en cualquier lugar |
| Copy button ES | Copy in Spanish | Copiar en español |
| Copied confirmation | ✓ Copied! | ✓ Copiado! |
| Word count | {n} words | {n} palabras |
| Char count | {n} chars | {n} caracteres |
| Reference reminder | Attach your reference photo when pasting into your AI generator. | Adjunta tu foto de referencia al pegar en tu generador de IA. |

---

## Textos del Header Global

| Elemento | EN | ES |
|----------|----|----|
| Reset button | ↺ Reset | ↺ Reiniciar |
| Mode indicator prefix | Mode: | Modo: |
| Mode: General | General / Scene | General / Escena |
| Mode: Person | Person / Model | Persona / Modelo |
| Mode: Product | Product | Producto |
| Change mode link | Change mode | Cambiar modo |

---

## Textos de Navegación (Sidebar)

| # | Nombre EN | Nombre ES |
|---|-----------|-----------|
| 1 | Camera | Cámara |
| 2 | Lens | Lente |
| 3 | Lighting | Iluminación |
| 4 | Composition | Composición |
| 5 | Exposure | Exposición |
| 6 | Color & Style | Color y Estilo |
| 7 | Scene & Subject | Escena y Sujeto |

---

*Este documento es la fuente de verdad para todos los textos de UI de Photo PromptLab Lite v2. Cualquier cambio de copy debe hacerse aquí primero antes de implementarse en el HTML.*
