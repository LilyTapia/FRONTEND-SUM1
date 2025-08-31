# Store Evolution VideoGames

Una tienda online moderna de videojuegos desarrollada con HTML5 y CSS3 puro, sin dependencias de JavaScript.

## 🎮 Descripción del Proyecto

Store Evolution VideoGames es una aplicación web estática que simula una tienda de videojuegos con un diseño moderno, responsivo y accesible. El proyecto está desarrollado exclusivamente con HTML semántico y CSS moderno, demostrando las capacidades actuales de estas tecnologías.

Actualización reciente: se refactorizó el CSS/HTML con clases descriptivas, utilidades de espaciado/estilo y se optimizó el banner del header para móviles sin degradados superpuestos.

## ✨ Características

- **Diseño Responsivo**: Adaptable a dispositivos móviles, tablets y desktop
- **Tema Oscuro**: Interfaz moderna con esquema de colores profesional
- **Accesibilidad**: Cumple con estándares WCAG para navegación por teclado y lectores de pantalla
- **SEO Optimizado**: Estructura semántica y meta tags apropiados
- **Sin JavaScript**: Funcionalidad completa usando solo HTML y CSS
- **Animaciones CSS**: Transiciones suaves y efectos hover
- **Grid Layout**: Sistema de grillas moderno para organización de contenido

## 🏗️ Estructura del Proyecto

```
Exp1_S3_Liliana_Tapia/
├── index.html                    # Página principal
├── productos.html                # Catálogo de productos
├── contacto.html                 # Formulario de contacto
├── producto-*.html               # Páginas de detalle (9 productos)
├── css/
│   └── styles.css               # Estilos principales
├── img/
│   ├── banner.gif               # Banner animado del header
│   └── *.jpg|*.png|*.webp|*.avif # Imágenes de productos
└── README.md                    # Este archivo
```

## 🧭 Convenciones de Clases (BEM-like, descriptivas)

- Header: `header-banner`, `site-navbar`, `site-nav`
- Listados: `product-grid`
- Fichas de producto: `product-detail`
- Contacto: `contact-info`, `form__actions`
- Botones: `btn`, `btn success`, `button-group`
- Utilidades: `mt-1`, `mt-2`, `mb-1`, `mb-2`, `py-2`, `text-center`, `muted`, `small`, `lead`, `icon-xl`, `callout`, `heading-success`, `heading-accent`

Clases antiguas como `brandbar`, `navbar`, `main-nav`, `grid`, `detail-grid`, `info-contacto`, `form-actions` y `btn-row` fueron eliminadas en CSS y sustituidas por las anteriores en HTML.

## 📱 Páginas Incluidas

### Páginas Principales
- **Inicio** (`index.html`): Landing page con productos destacados
- **Productos** (`productos.html`): Catálogo completo de videojuegos
- **Contacto** (`contacto.html`): Formulario de contacto con validación HTML5

### Páginas de Productos (9 títulos)
- Kingdom Come: Deliverance 2
- Donkey Kong Bonanza
- Clair Obscur: Expedition 33
- Final Fantasy VII Rebirth
- Elden Ring
- Marvel's Spider-Man 2
- Mario Kart 8 Deluxe
- The Witcher 3: Wild Hunt
- Minecraft

## 🎨 Tecnologías Utilizadas

- **HTML5**: Estructura semántica moderna
- **CSS3**: Estilos avanzados con:
  - CSS Grid y Flexbox
  - Custom Properties (variables CSS)
  - Media Queries para responsividad
  - Pseudo-selectores avanzados
  - Animaciones y transiciones
  - Utilidades reutilizables (espaciado, tipografía, callouts)

## 🚀 Instalación y Uso

1. **Clonar o descargar** el proyecto
2. **Abrir** `index.html` en cualquier navegador web moderno
3. **Navegar** por las diferentes secciones usando el menú principal

No se requiere servidor web ni instalación de dependencias.

## 📐 Diseño Responsivo

El proyecto incluye breakpoints para diferentes dispositivos:

- **Desktop**: > 900px (3 columnas en grid)
- **Tablet**: 600px - 900px (2 columnas en grid)
- **Móvil**: < 600px (1 columna en grid)

Notas:
- El banner (`header-banner`) usa `background-size: cover`; en < 600px pasa a `contain` para evitar cortes del GIF.
- El foco del menú se renderiza con `box-shadow` dentro del navbar para no desbordar el banner.

## 🎯 Características Técnicas

### CSS Moderno
- Variables CSS para theming consistente
- Grid Layout para estructuras complejas
- Flexbox para alineación de componentes
- `clamp()` para tipografía fluida
- `backdrop-filter` para efectos de cristal
- Estados hover/focus accesibles sin “saltos” visuales

### Accesibilidad
- Navegación por teclado completa
- Estados de foco visibles
- Etiquetas ARIA apropiadas
- Contraste de colores optimizado
- Soporte para `prefers-reduced-motion`

### Performance
- Imágenes optimizadas en múltiples formatos
- CSS eficiente sin frameworks externos
- Carga rápida sin dependencias JavaScript

## 🎨 Paleta de Colores

```css
--bg: #0f172a          /* Fondo principal */
--card: #111827        /* Tarjetas y secciones */
--text: #e5e7eb        /* Texto principal */
--muted: #9ca3af       /* Texto secundario */
--brand: #38bdf8       /* Color de marca */
--brand-2: #22c55e     /* Acento secundario */
```

## 📝 Formulario de Contacto

El formulario incluye:
- Validación HTML5 nativa
- Campos requeridos y opcionales
- Patrones de validación para teléfono
- Límites de caracteres en textarea
- Checkbox de aceptación de políticas

## 🔧 Personalización

Para personalizar el proyecto:

1. **Colores**: Modificar las variables CSS en `:root`
2. **Tipografía**: Cambiar la familia de fuentes en `body`
3. **Layout**: Ajustar las grillas en `.product-grid` y `.product-detail`
4. **Contenido**: Editar los archivos HTML individuales

## 📱 Compatibilidad

- ✅ Chrome 88+
- ✅ Firefox 85+
- ✅ Safari 14+
- ✅ Edge 88+

## 👨‍💻 Autor

**Liliana Tapia**  
Proyecto desarrollado para DUOC UC - Frontend I, Semana 3.

## 📄 Licencia

Este proyecto es de uso educativo y está disponible bajo licencia MIT.

---

*Desarrollado con ❤️ usando solo HTML5 y CSS3*
