# construyoTuProyecto.com 🚀

Landing page personal de **Juan Paulo Jiménez** — Desarrollador Web, experto Shopify y especialista en Power Platform y Python.

---

## 📋 Descripción

Sitio web de presentación de servicios profesionales orientado a emprendedores y empresas en Costa Rica y Latinoamérica. Diseño oscuro moderno con animaciones CSS, totalmente responsive y sin dependencias externas (excepto Google Fonts).

---

## 🗂️ Estructura del proyecto

```
construyoTuProyecto/
│
├── index.html          # Archivo principal (todo en un solo archivo)
└── README.md           # Este archivo
```

> Todo el CSS y JavaScript está embebido dentro del `index.html` para facilitar el despliegue.

---

## 🧩 Secciones

| Sección | ID | Descripción |
|---|---|---|
| Hero | `#inicio` | Presentación principal con tarjeta de código animada |
| Servicios | `#servicios` | 6 tarjetas de servicios ofrecidos |
| Proceso | `#proceso` | 4 pasos del flujo de trabajo |
| Sobre Mí | `#sobre-mi` | Biografía y stack de tecnologías |
| Portafolio | `#portafolio` | 4 proyectos destacados |
| Testimonios | `#testimonios` | 3 reseñas de clientes |
| Contacto | `#contacto` | Botones de WhatsApp y Email |

---

## ✨ Características técnicas

- **100% HTML/CSS/JS** — sin frameworks ni librerías externas
- **Responsive completo** — mobile, tablet y desktop
- **Menú hamburguesa funcional** — con animación X, overlay oscuro, cierre con Escape y bloqueo de scroll
- **Scroll reveal** — animaciones de entrada usando `IntersectionObserver`
- **Marquee infinito** — banner de tecnologías con CSS puro
- **Floating tags** — etiquetas flotantes animadas en la hero card
- **Google Fonts** — tipografías Syne (display) + DM Sans (body)
- **Accesibilidad** — atributos `aria-label` y `aria-expanded` en el menú

---

## 🛠️ Tecnologías del stack mostradas

`Shopify` · `Python` · `Power Apps` · `Power BI` · `Power Automate` · `HTML/CSS/JS` · `SQL` · `SEO` · `Responsive Design`

---

## 🚀 Despliegue

Por ser un archivo HTML estático, se puede desplegar en cualquier plataforma:

**GitHub Pages**
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/pausherl/construyotuproyecto.git
git push -u origin main
# Activar GitHub Pages en Settings > Pages
```

**Netlify / Vercel**
Simplemente arrastra el archivo `index.html` al panel de control o conecta el repositorio de GitHub.

**Hosting tradicional (cPanel)**
Sube `index.html` a la carpeta `public_html/` vía FTP o el administrador de archivos.

---

## ✏️ Personalización rápida

### Cambiar colores principales
En el bloque `:root` al inicio del CSS:
```css
--accent: #00e5a0;        /* Color verde principal */
--bg-primary: #0a0a0f;    /* Fondo oscuro */
```

### Actualizar datos de contacto
```html
<!-- WhatsApp -->
href="https://wa.me/50660072890?text=..."

<!-- Email -->
href="mailto:tu@email.com"
```

### Cambiar estadísticas del Hero
```html
<div class="stat-number">50+</div>   <!-- Proyectos -->
<div class="stat-number">98%</div>   <!-- Satisfacción -->
<div class="stat-number">5+</div>    <!-- Años Exp. -->
```

---

## 🐛 Correcciones aplicadas

- **Menú hamburguesa**: reescrito con `transform + opacity` para animación fluida de slide-in
- **Botón X**: las 3 líneas se transforman en X al abrir el menú (CSS puro)
- **Overlay**: capa semitransparente que cierra el menú al hacer clic fuera
- **`body.menu-open`**: bloquea el scroll del fondo mientras el menú está abierto
- **Tecla Escape**: cierra el menú desde el teclado
- **`aria-expanded`**: accesibilidad correcta en el botón hamburguesa
- **`--nav-height`**: variable CSS compartida para posicionamiento consistente del menú

---

## 📄 Licencia

© 2026 Juan Paulo Jiménez — Todos los derechos reservados.
