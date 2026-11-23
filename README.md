# Prompts del Proyecto — CaféCampus

Registro de prompts utilizados para diseñar, estructurar y generar el sitio web de **CaféCampus** como proyecto final de la Electiva de Inteligencia Artificial, integrando **Claude** (estructura, copy y código), **Adobe Firefly** (identidad visual / fotografías) y **Notion** (gestión del proyecto).

- **Repositorio:** `simonTAGDD/cafe-campus` (rama `main`)
- **Sitio web / nuevo `index.html`:** `./index.html` *(o la URL de GitHub Pages del nuevo `index.html`, por ejemplo `https://simontagdd.github.io/cafe-campus/`)*
- **WhatsApp oficial:** `+573154312808` (`https://wa.me/573154312808`)

---

## 1. Prompt profesional para generar / actualizar el nuevo `index.html` (con logo e identidad)

> Actúa como diseñador web y desarrollador frontend senior. Genera y actualiza el archivo `index.html` (`lang="es"`) para **CaféCampus**, una cafetería universitaria de café de origen colombiano pensada para estudiantes y docentes con poco tiempo entre clases, manteniendo la estética editorial, cálida y responsiva del proyecto.
>
> **Identidad visual, logo y estilos:**
> - Integra de forma visible y cuidada el logo `logo.jpg` en la barra de navegación superior (`<header class="nav">`) y en el pie de página (`<footer id="contacto">`), acompañado del logotipo tipográfico **CaféCampus**.
> - Usa las fuentes de Google Fonts: `Bricolage Grotesque` (títulos y display) y `Figtree` (cuerpo).
> - Conserva las variables CSS `--espresso: #3E2723`, `--latte: #D7CCC8`, `--crema: #F5F5F0`, `--naranja: #E65100`, soporte para `prefers-color-scheme: dark` y `safe-area-inset` en dispositivos móviles.
> - Configura todos los enlaces de pedidos, suscripción, botones rápidos y formulario de contacto hacia WhatsApp usando el número `573154312808` (`https://wa.me/573154312808?text=...`) y el número visible `+57 315 431 2808`.
> - Asegura que la navegación interna apunte correctamente a las secciones del nuevo `index.html` (`#inicio`, `#pilares`, `#catalogo`, `#suscripcion`, `#escribenos`, `#contacto`).
>
> **Secciones y contenido:**
> 1. **Navegación (`<header class="nav">`):** Logo circular (`logo.jpg`) + marca **CaféCampus**, menú responsiva (`Servicio`, `Menú`, `Suscripción`, `Contacto`) y botón *"Pedir por WhatsApp"* hacia `https://wa.me/573154312808`.
> 2. **Hero (`#inicio`):** Badge *"☕ Pequeños sorbos, grandes historias"*, titular *"Café colombiano de origen, listo entre clase y clase."*, propuesta de valor (tostado en lotes pequeños, pedido desde el celular, recogida en 5 minutos, precios universitarios), botones a WhatsApp (`573154312808`) y suscripción (`#suscripcion`), nota de pagos (Nequi, Daviplata o caja) y horarios (Lunes a viernes, 6:30 a. m. a 6:30 p. m.). En el bloque visual: `cafe-1.jpg` y tarjeta *"⚡ Pedido Express #104 · Listo en 5 min"*.
> 3. **Pilares (`#pilares`):** *Pedidos Express por WhatsApp*, *Suscripción 20 Cafés / Mes* y *Combos para Madrugadores* (10% de descuento con carné).
> 4. **Catálogo (`#catalogo`):** Granos 100% colombianos (Quindío, Huila, Nariño y Sierra Nevada) y leches vegetales (avena o almendra) por `+$1.500`.
>    - *1. Cafés de Origen y Opciones Veganas:* Huila al Amanecer (Espresso) `$3.500` (`cafe-3.jpg`), Cappuccino Cafetal `$6.500` (`cafe-1.jpg`), Café del Quindío `$5.500` (`cafe-4.jpg`), Americano Sierra Nevada `$4.000` (`cafe-3.jpg`).
>    - *2. Bebidas Frías:* Cold Brew Madrugón `$7.500` (`cafe-2.jpg`), Iced Latte Parcial `$7.500` (`cafe-1.jpg`), Frappé Final de Semestre `$9.500` (`cafe-7.jpg`).
>    - *3. Combos de Desayuno Estudiante:* Combo 1 · Primer Semestre `$6.500` (`cafe-5.jpg`), Combo 2 · Madrugador `$12.500` (`cafe-6.jpg`).
>    - Banner de 4 promos: *Café #10 Gratis*, *Happy Hour 3–5 p. m.* (2x1 en bebidas frías seleccionadas), *Semana de Parciales* (recarga de tinto de origen a `$2.000`) y *Trae tu Termo* (`$500` de descuento).
> 5. **Suscripción (`#suscripcion`):** 20 cafés al mes por `$89.000 / mes` (`$4.450` por café vs `$6.500`, ahorro hasta `$41.000` al mes), beneficios, botón de suscripción a `https://wa.me/573101234567` → `https://wa.me/573154312808` y **Tarjeta Digital Mensual** interactiva de 20 sellos (`☕`).
> 6. **Formulario (`#escribenos`):** Envía nombre, tipo de solicitud y mensaje directamente a `https://wa.me/573154312808?text=...`.
> 7. **Footer (`#contacto`):** Logo (`logo.jpg`) + **CaféCampus**, ubicación (*Plazoleta Central · Frente a Biblioteca*), horarios (L–V 6:30 a. m. – 6:30 p. m.; Sábados 7:30 a. m. – 1:00 p. m.), contacto `WhatsApp: +57 315 431 2808` (`https://wa.me/573154312808`) y crédito legal del proyecto con IA (Claude, Adobe Firefly & Notion).

---

## 2. Prompt para generar imágenes visuales (Adobe Firefly / IA generativa)

> Genera fotografía comercial cálida y editorial para una cafetería universitaria en Colombia llamada **CaféCampus**. Estilo luminoso o acogedor de cafetería artesanal, tonos cálidos espresso, crema y tostado suave, composición limpia y lista para recorte en `4:3` o `16:10`, sin textos superpuestos ni marcas de agua:
> - **Logo (`logo.jpg`):** Emblema circular limpio de cafetería universitaria colombiana con taza de café y elemento académico minimalista, fondo cálido crema/naranja suave.
> - **Cafés y bebidas (`cafe-1.jpg` a `cafe-7.jpg`):** Cappuccino con arte latte en mesa de estudio, cold brew con hielo, espresso y americano de origen, café de altura en taza cerámica, combo con pan de queso recién horneado, sándwich/tostada matutina y frappé frío.

---

## 3. Prompt para sincronizar el nuevo `index.html`, `README.md` y `PROMPTS.md`
