---
version: alpha
name: Luu García Studio
description: >-
  Sistema de diseño de la marca de Luu García: estética moderna, experimental y
  versátil, con una estructura editorial dinámica, tres colores vibrantes (rosa,
  azul y naranja) y dos colores estructurales (beige y negro), tipografía en
  ITTrivane (expresiva) y Franie (funcional), y retícula de 12/8/4 columnas.
colors:
  primary: "#D84582"
  secondary: "#007CBA"
  tertiary: "#F95C4B"
  neutral: "#E4DED2"
  ink: "#000000"
typography:
  display:
    fontFamily: ITTrivane
    fontSize: 96px
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: -0.02em
  title-1:
    fontFamily: ITTrivane
    fontSize: 64px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: -0.01em
  title-2:
    fontFamily: ITTrivane
    fontSize: 44px
    fontWeight: 400
    lineHeight: 1.15
  title-3:
    fontFamily: Franie
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.3
  text-highlight:
    fontFamily: Franie
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.3
  body:
    fontFamily: Franie
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
  nav:
    fontFamily: Franie
    fontSize: 18px
    fontWeight: 600
  button:
    fontFamily: Franie
    fontSize: 18px
    fontWeight: 600
  label:
    fontFamily: Franie
    fontSize: 14px
    fontWeight: 600
  metadata:
    fontFamily: Franie
    fontSize: 14px
    fontWeight: 400
  caption:
    fontFamily: Franie
    fontSize: 14px
    fontWeight: 400
spacing:
  unit: 8px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  section: 96px
  section-xl: 128px
  section-2xl: 160px
rounded:
  none: 0px
  md: 24px
  full: 999px
  circle: 999px
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.neutral}"
    typography: "{typography.button}"
    rounded: "{rounded.full}"
    padding: 14px 24px
    height: 44px
  button-primary-hover:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.ink}"
  button-primary-hover-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.ink}"
  button-primary-hover-tertiary:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.ink}"
  button-secondary:
    textColor: "{colors.ink}"
    typography: "{typography.button}"
  link:
    textColor: "{colors.secondary}"
    typography: "{typography.nav}"
  link-hover:
    textColor: "{colors.primary}"
  navigation-item:
    textColor: "{colors.ink}"
    typography: "{typography.nav}"
  navigation-item-active:
    textColor: "{colors.primary}"
  chip:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.full}"
    padding: 8px 16px
  card:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 24px
  decorative-block:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
  contact-section:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.ink}"
---

## Overview

La marca encarna una estética moderna, experimental y versátil, diseñada para
reflejar una práctica creativa que explora diferentes lenguajes, estilos y
formatos. Su identidad combina una composición gráfica poco convencional con una
paleta intensa de rosa, azul y naranja, equilibrada mediante beige y negro.

Los colores vibrantes transmiten energía, curiosidad y una actitud audaz,
mientras que los tonos neutros aportan claridad y estructura. La intención es
generar una identidad visual expresiva y reconocible, capaz de experimentar sin
convertirse en una composición caótica.

La dirección visual toma como referencia principal una estructura editorial
dinámica: grandes titulares, imágenes protagonistas, cambios marcados de escala,
alternancia entre secciones densas y espacios abiertos, numeraciones, listados y
composiciones que pueden cambiar de ritmo a lo largo de la página.

La experimentación no depende de acumular elementos. Cada sección debe tener
**una idea visual dominante** y suficiente espacio para desarrollarla: algunas
pueden ser principalmente tipográficas; otras se construyen alrededor de una
imagen, una galería, una lista o un gran bloque de color.

La página puede cambiar de composición entre proyectos para mostrar
versatilidad, pero conserva como constantes la paleta, las tipografías, los
patrones de interacción, la escala de espaciado y ciertas formas de organizar la
información.

La marca busca sentirse creativa, dinámica, segura, contemporánea y ligeramente
irreverente. Está dirigida a estudios de diseño, agencias, directores
creativos, reclutadores y clientes interesados en propuestas visuales con
personalidad.

## Colors

La paleta se construye a partir de tres colores vibrantes y dos colores
estructurales. Los colores pueden ocupar tanto pequeños acentos como superficies
completas, pero cada sección debe establecer una jerarquía cromática clara.

- **{colors.primary} — Rosa (#D84582):** color expresivo. Fondos completos de
  sección, palabras destacadas, etiquetas, elementos gráficos, numeraciones y
  estados interactivos. Puede ser protagonista, pero no debe usarse
  simultáneamente con azul y naranja en la misma proporción.
- **{colors.secondary} — Azul (#007CBA):** color principal de identidad. Grandes
  superficies, secciones destacadas, enlaces, elementos interactivos y recursos
  gráficos. Por su contraste con rosa y naranja crea cambios fuertes de ritmo.
- **{colors.tertiary} — Naranja coral (#F95C4B):** color de mayor energía.
  Llamadas a la acción, detalles puntuales, números, elementos de navegación,
  palabras destacadas y secciones de alto impacto. Debe usarse de forma
  intencional, no como relleno recurrente.
- **{colors.neutral} — Beige (#E4DED2):** principal neutro claro. Fondo general,
  superficie de secciones editoriales y zona de descanso entre composiciones
  intensas. Permite mantener una apariencia cálida sin depender constantemente
  del blanco.
- **{colors.ink} — Negro (#000000):** color estructural de mayor contraste.
  Texto, navegación, líneas divisorias, fondos oscuros, botones y grandes
  titulares. También puede ocupar secciones completas para generar pausas
  fuertes.

**Combinaciones principales:** negro sobre beige; beige sobre negro; negro
sobre rosa; negro sobre naranja; beige sobre azul; negro sobre fondos claros.

Los tres colores vibrantes no deben competir dentro de una misma sección:
normalmente uno funciona como protagonista y los demás permanecen fuera de esa
composición o aparecen solo como pequeños acentos. El cambio de color de fondo
se usa como herramienta para separar secciones sin necesidad de tarjetas ni
contenedores adicionales.

## Typography

Dos familias con roles claramente diferenciados: **ITTrivane** (expresiva) y
**Franie** (funcional).

- **ITTrivane** es la principal tipografía de identidad. Se usa en títulos display,
  nombres de proyectos, encabezados principales, frases breves, palabras
  destacadas y composiciones tipográficas de gran escala. Puede ocupar una parte
  considerable de la pantalla y funcionar casi como un elemento gráfico; su
  tamaño y posición varían entre secciones. **No** se usa para cuerpo de texto,
  navegación, botones ni información extensa.
- **Franie** es la tipografía funcional y mantiene la claridad del sistema.
  Pesos habituales: Regular (cuerpo y metadatos), SemiBold (navegación,
  botones, enlaces, categorías y etiquetas), Bold (subtítulos, números, años,
  datos importantes) e Italic (captions, créditos, notas). Las variantes Hair,
  ExtraLight, Light, SemiLight, ExtraBold y Black quedan fuera de la jerarquía
  habitual y solo se usan excepcionalmente.

**Escala tipográfica:**

| Nivel | Token | Familia / peso | Tamaño |
| --- | --- | --- | --- |
| Display | `{typography.display}` | ITTrivane | 96–128px |
| Título 1 | `{typography.title-1}` | ITTrivane | 64–80px |
| Título 2 | `{typography.title-2}` | ITTrivane | 44–56px |
| Título 3 | `{typography.title-3}` | Franie Bold | 24–28px |
| Texto destacado | `{typography.text-highlight}` | Franie Bold | 20–24px |
| Cuerpo | `{typography.body}` | Franie Regular | 18px, interlineado 26–28px |
| Navegación | `{typography.nav}` | Franie SemiBold | 16–18px |
| Botones | `{typography.button}` | Franie SemiBold | 16–18px |
| Etiquetas | `{typography.label}` | Franie SemiBold | 13–14px |
| Metadatos | `{typography.metadata}` | Franie Regular | 13–14px |
| Captions | `{typography.caption}` | Franie Italic | 13–14px |

La jerarquía se construye mediante familia, escala, peso, **espacio y color**.
ITTrivane concentra la personalidad visual; Franie mantiene estable toda la
información funcional. Los titulares pueden ser muy grandes, pero el cuerpo de
texto debe permanecer cómodo y legible: la experimentación tipográfica nunca
dificulta la comprensión del contenido.

## Layout

El layout utiliza una retícula estructurada como punto de partida, pero permite
variaciones entre secciones para evitar que todo el portafolio se sienta
construido sobre una sola plantilla.

El sistema parte de una unidad de **8px** ({spacing.unit}). La escala principal
de espaciado es `{spacing.sm}`, `{spacing.md}`, `{spacing.lg}`, `{spacing.xl}`,
`{spacing.2xl}`, `{spacing.3xl}`, `{spacing.section}`, `{spacing.section-xl}` y
`{spacing.section-2xl}` (8, 16, 24, 32, 48, 64, 96, 128 y 160px).

En escritorio se usan **12 columnas**, en tableta **8** y en móvil **4**. El
ancho máximo de contenido es aproximadamente 1600px, con márgenes exteriores
amplios. Las secciones principales se separan normalmente entre
`{spacing.section}` (96px) y `{spacing.section-2xl}` (160px); los elementos
relacionados dentro de una sección usan distancias entre `{spacing.md}` (16px) y
`{spacing.3xl}` (64px).

### Ritmo

No todas las secciones tienen la misma densidad: una puede estar dominada por un
gran titular, otra por una imagen a casi pantalla completa y otra por una
composición pequeña de texto, numeración e imagen. El cambio de ritmo es parte
fundamental de la identidad. Se usan grandes diferencias de escala, imágenes de
distintas proporciones, títulos de gran formato, numeraciones, listados, cambios
de alineación, alternancia de fondos, secciones a ancho completo, repeticiones
tipográficas puntuales, grandes espacios vacíos y composiciones divididas entre
imagen y texto.

### Superposición

Los grandes contenedores **no** se superponen. Cada sección ocupa un espacio
claramente definido dentro del flujo. No se usan dos rectángulos grandes
montados uno sobre otro, ni márgenes negativos, ni `position: absolute` para
organizar los bloques estructurales principales. La superposición queda limitada
a elementos pequeños y deliberados (una palabra sobre una imagen, una
numeración, un símbolo, una etiqueta o un pequeño elemento decorativo) y nunca
cubre información importante ni hace competir a dos grandes componentes. La
sensación experimental proviene del ritmo de la composición, no de elementos
encimados.

## Elevation & Depth

El diseño es principalmente **plano**. La profundidad se construye mediante
escala, color, movimiento, fotografía y relaciones entre elementos, no mediante
sombras constantes.

- **Plano:** texto, navegación, imágenes, galerías y contenido general sin
  sombra.
- **Cambio de superficie:** las secciones se distinguen mediante fondos beige,
  negros o de colores vibrantes.
- **Elemento destacado:** una imagen o titular gana protagonismo por tamaño,
  ubicación o contraste cromático.
- **Interacción:** los elementos interactivos pueden desplazarse ligeramente,
  cambiar de color, escalar o revelar información al pasar el cursor.

Las sombras se usan únicamente cuando es necesario distinguir un elemento
interactivo flotante; deben ser suaves y discretas. No se usan grandes tarjetas
flotantes ni capas de profundidad artificial alrededor del contenido.

## Shapes

La identidad usa principalmente formas simples; no todos los elementos
necesitan estar dentro de un contenedor.

| Radio | Token | Uso |
| --- | --- | --- |
| 0px | `{rounded.none}` | Imágenes, galerías, bloques editoriales y grandes superficies |
| 16–24px | `{rounded.md}` (24px) | Componentes especiales que necesitan suavidad |
| 999px (píldora) | `{rounded.full}` | Botones, etiquetas y chips |
| 50% | `{rounded.circle}` | Elementos circulares e indicadores |

Las grandes superficies de color prefieren el cambio directo del fondo de la
sección en lugar de añadir un rectángulo decorativo sobre otro fondo. Los
rectángulos redondeados grandes se usan con moderación: cuando aparecen,
funcionan como un único elemento autónomo y nunca se cruzan ni se montan sobre
otro contenedor de tamaño similar. Las píldoras se reservan principalmente para
componentes pequeños e interactivos.

### Bordes

El sistema es mayoritariamente plano: los componentes no usan borde
(`{border.none}`) y el énfasis se traslada a la repetición tipográfica, la escala
y el cambio de superficie. La única excepción es `{border.hairline}`: una línea
fina de `{colors.ink}` de 1px que funciona como divisor (numeraciones, filas de
listados, líneas entre párrafos largos) y como separación del pie de página.
No se usan bordes decorativos alrededor de imágenes ni tarjetas flotantes.

## Components

### Navegación

Sencilla y directa, para equilibrar el carácter experimental del resto de la
página. Usa Franie SemiBold a 16–18px (`{typography.nav}`) y puede incluir
Work — About — Contact, con el nombre o identificador en el extremo opuesto. La
navegación puede invertir su color según el fondo de la sección. En hover los
enlaces cambian de color, muestran subrayado, se desplazan ligeramente o
incorporan una pequeña flecha (`{colors.secondary}` → `{colors.primary}`). No se
usan cajas individuales alrededor de cada opción.

### Hero

Principalmente tipográfico: ITTrivane a gran escala (`{typography.display}`) con
una descripción breve de la práctica. Puede combinar un gran titular, una frase
secundaria en Franie, una imagen o pieza de trabajo, un pequeño elemento gráfico
e información de disciplina o ubicación. Tiene espacio para respirar y no
depende de varias tarjetas ni de grandes cuadros superpuestos para crear
impacto.

### Botones

- **Primario** (`button-primary`): Franie SemiBold 16–18px, altura mínima 44px,
  padding 14px × 24px y forma de píldora (`{rounded.full}`). Puede tener fondo
  `{colors.ink}` con texto `{colors.neutral}`, o uno de los colores vibrantes con
  texto de alto contraste. En hover invierte colores, cambia de fondo
  (`button-primary-hover` → rosa, `button-primary-hover-secondary` → azul,
  `button-primary-hover-tertiary` → naranja) o produce un pequeño desplazamiento;
  el texto permanece `{colors.ink}` cuando el fondo lo requiere.
- **Secundario** (`button-secondary`): únicamente texto
  (`{typography.button}`) acompañado de una flecha.
- Se evitan demasiadas variantes: la interfaz se siente editorial antes que como
  una aplicación.

### Enlaces

Los enlaces del contenido usan subrayado, flecha o cambio cromático
(`{colors.secondary}` → `{colors.primary}`). Las interacciones son breves y
visibles; no dependen exclusivamente de cambios de opacidad.

### Proyectos destacados

Los proyectos son los protagonistas. Cada entrada incluye nombre, categoría o
disciplina, año, imagen principal y una breve descripción cuando sea necesaria.
Las imágenes cambian de proporción y tamaño: un proyecto puede usar imagen a
ancho completo y el siguiente una composición dividida en dos columnas. La
consistencia se consigue mediante tipografía, información, espaciado e
interacción, no repitiendo el mismo rectángulo.

### Imágenes

Pueden ocupar todo el ancho, media pantalla, aparecer en pares, formar pequeñas
galerías o alternar formatos horizontales y verticales. No se colocan dentro de
marcos innecesarios: la fotografía, ilustración, motion o mockup conserva el
protagonismo.

### Listados y numeraciones

Para experiencia, disciplinas, habilidades o servicios se usan listas amplias y
sencillas. Cada elemento puede separarse con una línea horizontal e incluir una
numeración (01 — Branding, 02 — Editorial, 03 — UX/UI): los números usan
`{typography.title-3}` (Franie Bold) y los títulos ITTrivane o Franie Bold según la
jerarquía. En hover, el elemento puede cambiar de color o revelar una imagen
relacionada. Los números (índices, listados, proyectos, procesos, categorías y
secciones) aparecen normalmente en `{typography.title-3}`.

### Etiquetas

Indican categorías o disciplinas. Usan Franie SemiBold a 13–14px
(`{typography.label}`). Pueden tener formato de píldora (`chip`), aunque también
pueden aparecer como texto pequeño en mayúsculas o acompañado por una línea: no
todas las categorías deben estar encerradas en una forma.

### Marquesinas

Líneas de texto repetitivo con movimiento horizontal para generar transiciones
entre secciones. Pueden incluir disciplinas, frases, palabras clave, el nombre
de la marca o invitaciones a explorar el trabajo, en ITTrivane (normalmente
`{typography.title-2}`) o `{typography.title-3}`. No aparecen constantemente:
funcionan como momentos puntuales del recorrido.

### Página de proyecto

Cada proyecto puede adaptar su estructura al contenido. La introducción incluye
rol y una breve descripción; después se prioriza la presentación visual con
imágenes grandes, videos, detalles, mockups y composiciones editoriales. Los
textos largos se mantienen en columnas más estrechas para conservar legibilidad.
La página puede alternar imágenes a pantalla completa con grupos más pequeños
para generar ritmo.

### About

Combina un titular expresivo en ITTrivane (`{typography.title-1}` o
`{typography.display}`) con información más extensa en Franie. Puede incorporar
una fotografía, una presentación breve, disciplinas, experiencia y datos de
contacto, organizados con columnas, listas y jerarquía tipográfica, evitando
dividir todo en pequeñas tarjetas.

### Contacto

Cierre visual fuerte: un fondo completo rosa, azul, naranja o negro
(`contact-section`) y un gran titular en ITTrivane. La llamada a la acción es
directa y los enlaces de correo y redes usan `{typography.nav}`. Se siente como
una conclusión del recorrido, no como un formulario corporativo complejo.

## Do's and Don'ts

### Sí

- Usa ITTrivane para los momentos de mayor impacto.
- Usa Franie para toda la información funcional.
- Mantén beige y negro como estructura principal.
- Usa rosa, azul y naranja como colores protagonistas en momentos específicos.
- Cambia el ritmo entre secciones.
- Usa imágenes de gran tamaño.
- Permite que cada proyecto tenga una composición adaptada a su contenido.
- Utiliza contrastes fuertes de escala.
- Deja espacio vacío de manera intencional.
- Usa fondos completos para separar secciones.
- Utiliza numeraciones y listados como recursos editoriales.
- Mantén la navegación sencilla.
- Utiliza movimiento breve y funcional.
- Mantén una idea visual dominante por sección.
- Prioriza siempre el contenido del portafolio.

### No

- No superpongas grandes cuadros o contenedores.
- No hagas que una sección invada accidentalmente a la siguiente.
- No utilices márgenes negativos para crear superposiciones estructurales.
- No conviertas todos los proyectos en tarjetas iguales.
- No encierres cada elemento dentro de un rectángulo.
- No utilices los tres colores vibrantes con la misma intensidad al mismo tiempo.
- No utilices efectos únicamente para hacer la página parecer experimental.
- No uses sombras pesadas.
- No utilices demasiados radios diferentes.
- No uses ITTrivane en textos largos.
- No utilices todos los pesos disponibles de Franie.
- No sacrifiques legibilidad por una composición llamativa.
- No permitas que los elementos decorativos compitan con los proyectos.
- No escondas información o navegación esencial detrás de interacciones difíciles
  de descubrir.
- No repitas exactamente la misma composición en todas las secciones.

La regla general: la experimentación debe sentirse **intencional**, no
accidental.

## Comportamiento responsivo

El diseño mantiene su personalidad experimental en todos los tamaños, pero la
complejidad de las composiciones disminuye progresivamente en pantallas
pequeñas.

| Dispositivo | Columnas | Márgenes | Separación de secciones | Títulos display |
| --- | --- | --- | --- | --- |
| Móvil (320–599px) | 4 | 16px | 64–96px | 48–64px |
| Tableta (600–1023px) | 8 | 32–48px | — | aprox. 64–80px |
| Escritorio (1024–1439px) | 12 | 48–64px | 96–128px | 80–112px |
| Escritorio amplio (1440px+) | 12 | — | hasta 160px | hasta 128px |

En móvil, las composiciones de varias columnas pasan a una sola, las imágenes
mantienen su protagonismo y los elementos decorativos menos importantes pueden
desaparecer. No se mantienen superposiciones que provoquen problemas de lectura.
El cuerpo se mantiene entre 16 y 18px.

El responsive no consiste en reducir proporcionalmente el diseño de escritorio:
cada composición debe reorganizarse para el espacio disponible. En pantallas
pequeñas se priorizan contenido, legibilidad, navegación, jerarquía y
personalidad visual. Los recursos experimentales que funcionen en escritorio
pero provoquen cruces o solapamientos en móvil deben simplificarse o eliminarse.
Los elementos interactivos mantienen un área mínima de 44 × 44px.

## Notas de revisión

Valores asumidos con sentido razonable para completar el formato; revísalos:

- **Fuentes:** ITTrivane y Franie se cargan desde `assets/fonts`. Franie carga
  Light (300), Regular (400), Italic, SemiBold (600) y Bold (700) para énfasis
  y composiciones editoriales.
- **Tamaños tipográficos:** elegí los valores base de cada rango (display 96px,
  título 1 64px, título 2 44px, título 3 28px y texto destacado 24px); ajusta a
  tu configuración real.
- **Radio medio:** asumí 24px para el rango 16–24px (token `rounded.md`).
- **Altura del botón:** definida en 44px (mínimo táctil indicado en el
  documento).
- **Tarjeta:** padding asumido de 24px; las tarjetas se usan con moderación, sin
  decorar los proyectos.
- **"Beige sobre azul"** aparece como combinación de superficies (fondo) en el
  documento; como par de texto no alcanza WCAG AA (≈3.4:1), por lo que no se usa
  para texto pequeño.
- **Bordes:** `border.none` (0px) y `border.hairline` (1px, `{colors.ink}`) se
  documentan en la prosa de Shapes. El linter del paquete npm (0.4.0) no admite
  aún un grupo `border` en el front matter; el lint lo mantiene en 0 errores y
  0 advertencias referenciándolos en texto. Cuando la GitHub Action de design.md
  (que sí controla la regla `missing-border-token`) emita el formato definitivo,
  ese grupo puede promoverse al front matter.