# DarkKitchen - Versión CSS Externo

Versión mejorada del sitio web **DarkKitchen**, un proyecto de delivery de hamburguesas artesanales con tema oscuro premium.

## Descripción

Este proyecto migra los estilos inline a un archivo CSS externo (`general.css`) para mejorar la mantenibilidad, reutilización y organización del código. La identidad visual se mantiene con:

- **Paleta de colores**: Tema oscuro (#121212, #1e1e1e, #2a2a2a) con acentos naranja (#ff6200)
- **Tipografía**: Segoe UI, Geneva, Verdana, sans-serif
- **Diseño**: Moderno, responsivo y profesional

## Estructura del Proyecto

```
DarkKitchen-CSS/
├── css/
│   └── general.css          # Estilos generales centralizados
├── pages/
│   ├── nosotros.html       # Página sobre la empresa
│   ├── menu.html           # Menú de productos
│   ├── promociones.html    # Promociones especiales
│   ├── contacto.html       # Formulario de pedidos
│   ├── login.html          # Inicio de sesión
│   └── registro.html       # Registro de usuario
├── img/                     # Imágenes del sitio
├── index.html              # Página principal
└── README.md               # Este archivo
```

## Archivo CSS

El archivo `general.css` está organizado en **10 bloques temáticos** de comentarios:

1. **BLOQUE 1**: Configuración General (reset CSS, body)
2. **BLOQUE 2**: Títulos, Párrafos y Enlaces (h1-h3, p, a)
3. **BLOQUE 3**: Elementos Semánticos Principales (header, nav, main, section, article, aside, footer)
4. **BLOQUE 4**: Menú de Navegación (estilos para nav)
5. **BLOQUE 5**: Contenido y Secciones (section, articles con efectos hover)
6. **BLOQUE 6**: Imágenes y Multimedia (img, figure, figcaption, video, audio, iframe)
7. **BLOQUE 7**: Listas (ul, ol, li)
8. **BLOQUE 8**: Formularios (form, label, input, textarea, select, button)
9. **BLOQUE 9**: Tablas (table, thead, tbody, tr, th, td)
10. **BLOQUE 10**: Pie de Página (footer)

### Características del CSS

- ✅ Selectores universales, de etiqueta y de ubicación (sin clases ni IDs)
- ✅ Propiedades de color, fondo, fuentes, tamaño y alineación de texto
- ✅ Márgenes, padding, bordes y dimensiones
- ✅ Efecto hover y transiciones suaves
- ✅ Interlineado profesional (line-height: 1.6)
- ✅ Diseño responsivo y accesible

## Uso

1. Descargar o clonar el repositorio:
   ```bash
   git clone https://github.com/Daqu3/DarkKitchen-CSS.git
   ```

2. Abrir cualquier página HTML en el navegador web

3. El archivo `css/general.css` se cargará automáticamente en todas las páginas

## Paleta de Colores

| Color | Código | Uso |
|-------|--------|-----|
| Negro Oscuro | #121212 | Fondo principal |
| Gris Oscuro | #1e1e1e | Headers, sections |
| Gris Más Oscuro | #2a2a2a | Elementos, artículos |
| Naranja | #ff6200 | Títulos, acciones, acentos |
| Gris Claro | #cccccc | Textos secundarios |
| Gris Muy Claro | #ffffff | Textos principales |

## Navegación

- **Inicio**: Página principal con destacados
- **Nosotros**: Información sobre DarkKitchen
- **Menú**: Catálogo completo de productos
- **Promociones**: Ofertas especiales
- **Pedir Ahora**: Formulario de compra
- **Iniciar Sesión**: Acceso a cuenta

## Requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexión a internet (para Font Awesome icons)
- No requiere servidor backend

## Notas

- Este proyecto es completamente HTML y CSS (sin JavaScript)
- Todos los formularios son estáticos (sin funcionalidad backend)
- Compatible con dispositivos móviles y desktop
- Sigue estándares web HTML5 y CSS3

## Autor

Desarrollado como proyecto práctico de Desarrollo Web.

## Licencia

Proyecto libre para uso educativo.
