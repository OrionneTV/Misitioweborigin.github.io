# ElectrOriginc - Un Solo Origen

## Descripción
Sitio web corporativo de ElectrOriginc, una empresa comprometida con la excelencia e innovación en el sector tecnológico y energético de Costa Rica.

## Características

✅ **Diseño Responsivo** - Compatible con todos los dispositivos
✅ **Navegación Intuitiva** - Menú fácil de usar
✅ **Secciones Principales:**
- Inicio (Hero Section)
- Nosotros (About)
- Servicios (Services)
- Equipo (Team)
- Contacto (Contact)
- Footer con enlaces rápidos

✅ **Tecnologías Usadas:**
- HTML5
- CSS3 (Variables CSS, Grid, Flexbox)
- JavaScript Vanilla
- Google Fonts (Poppins y Raleway)

## Estructura del Proyecto

```
Mi-sitio-web-Origin/
├── index.html              # Página principal
├── styles/
│   └── main.css           # Estilos principales
├── js/
│   └── main.js            # JavaScript funcionalidad
├── assets/                # Carpeta de recursos
│   ├── logo-main.png      # Logo con fondo claro
│   ├── logo-dark.png      # Logo con fondo oscuro
│   ├── jonathan-zamora.webp # Foto del ejecutivo
│   ├── favicon.png        # Icono navegador
│   └── social-preview.jpg # Preview redes sociales
├── robots.txt             # Archivo para motores de búsqueda
├── sitemap.xml            # Mapa del sitio
├── _redirects             # Configuración de redirecciones
├── package.json           # Metadatos del proyecto
└── README.md              # Este archivo
```

## Instalación y Uso

### Opción 1: Abrir en el navegador
```bash
# Solo abre index.html directamente en tu navegador
```

### Opción 2: Usar un servidor local (Python)
```bash
python -m http.server 8000
# Luego abre http://localhost:8000
```

### Opción 3: Usar Node.js
```bash
npm start
```

## Personalización

### Cambiar colores
Edita las variables CSS en `styles/main.css`:
```css
:root {
    --primary-color: #007AFF;    /* Color principal */
    --secondary-color: #34C759;  /* Color secundario */
    --dark-color: #1C1C1C;       /* Color oscuro */
    --light-color: #F5F5F5;      /* Color claro */
}
```

### Actualizar contenido
- **Textos**: Edita los `<h1>`, `<p>`, etc. en `index.html`
- **Imágenes**: Reemplaza los archivos en la carpeta `assets/`
- **Información del equipo**: Actualiza la sección de equipo en `index.html`

## Recursos necesarios (Assets)

Coloca estas imágenes en la carpeta `assets/`:
- `logo-main.png` - Logo principal (200x100px recomendado)
- `logo-dark.png` - Logo para footer (200x100px recomendado)
- `jonathan-zamora.webp` - Foto ejecutivo (300x300px)
- `favicon.png` - Icono navegador (192x192px)
- `social-preview.jpg` - Preview redes (1200x630px)

## Despliegue

Esta página está lista para ser desplegada en:
- ✅ GitHub Pages
- ✅ Netlify
- ✅ Vercel
- ✅ Cualquier servidor web estático

### Desplegar en GitHub Pages:
1. Ve a Settings > Pages
2. Selecciona "Deploy from a branch"
3. Elige la rama `main`
4. Guarda y espera el despliegue

## Soporte para navegadores
- Chrome (últimas 2 versiones)
- Firefox (últimas 2 versiones)
- Safari (últimas 2 versiones)
- Edge (últimas 2 versiones)

## Licencia
MIT License - Libre para usar y modificar

## Contacto
**ElectrOriginc**
- Email: info@electroriginc.cr
- Ubicación: Costa Rica

---

**Última actualización:** Enero 2024
**Versión:** 1.0.0
