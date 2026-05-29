# Instrucciones para Subir a Google Sites

## Opción 1: Embed HTML (Recomendada)

Google Sites no permite subir HTML directamente, pero puedes usar estas alternativas:

### Paso 1: Hospedar los archivos
Sube los archivos a uno de estos servicios gratuitos:
- **GitHub Pages** (recomendado): Crea un repositorio y activa GitHub Pages
- **Netlify**: Arrastra la carpeta `sitio_angel` al dashboard
- **Vercel**: Conecta tu repositorio

### Paso 2: Embeber en Google Sites
1. Ve a [sites.google.com](https://sites.google.com)
2. Crea un nuevo sitio o abre uno existente
3. Inserta > Embed > Por URL
4. Pega la URL de tu sitio hospedado
5. Ajusta el tamaño al 100% del ancho

---

## Opción 2: Google Sites Nativo (Sin código custom)

Si prefieres usar Google Sites directamente sin código:

### Estructura sugerida:
1. **Página principal**: Usa la sección Hero como banner
2. **Sección Sobre Mí**: Agrega texto + imagen
3. **Sección Servicios**: Usa layout de columnas (3 columnas)
4. **Sección Skills**: Agrega como texto formateado
5. **Sección Portfolio**: Usa carrusel de imágenes
6. **Sección Experiencia**: Usa acordeones o texto
7. **Contacto**: Inserta un Google Form

### Pasos:
1. Crea un nuevo Google Site
2. Elige un tema limpio (sin mucho color)
3. Personaliza los colores:
   - Primario: #6c63ff
   - Fondo: blanco
   - Texto: #333333
4. Sube las imágenes de la carpeta `images/`
5. Copia el contenido de cada sección del HTML

---

## Opción 3: GitHub Pages (La más fiel al diseño)

### Pasos:
1. Crea un repositorio en GitHub (ej: `mi-portfolio`)
2. Sube todos los archivos de `sitio_angel/`:
   - `index.html`
   - `styles.css`
   - `script.js`
   - Carpeta `images/` con todas las imágenes
3. Ve a Settings > Pages
4. Source: Deploy from branch > `main` > `/ (root)`
5. Tu sitio estará en: `https://tu-usuario.github.io/mi-portfolio/`

### Luego en Google Sites:
1. Inserta > Embed > Por URL
2. Pega: `https://tu-usuario.github.io/mi-portfolio/`
3. Marca "Página completa"

---

## Archivos del Proyecto

```
sitio_angel/
├── index.html              ← Página principal
├── styles.css              ← Estilos del sitio
├── script.js               ← Interactividad
├── images/                 ← Carpeta de imágenes (ver README dentro)
│   ├── README.md           ← Lista de imágenes necesarias
│   ├── banner.png          ← Imagen hero
│   ├── profile.jpg         ← Foto de perfil
│   ├── project1-6.jpg      ← Imágenes de proyectos
│   └── logo-*.png          ← Logos de tecnologías
├── tema_ui_portfolio.md    ← Documentación del tema
└── README_GOOGLE_SITES.md  ← Este archivo
```

## Notas Importantes

- Las imágenes deben colocarse en la carpeta `images/` antes de publicar
- El formulario de contacto es solo visual; para funcionalidad real usa Google Forms
- El sitio es completamente responsive (se adapta a móvil, tablet y desktop)
- Los CDN de Google Fonts y Font Awesome requieren conexión a internet
- Para Google Sites embed, el sitio debe estar hospedado en HTTPS
