# jasp.github.io

Portfolio personal de José Ángel Sánchez Pérez — Software Architect & Full Stack Developer.

## Despliegue en GitHub Pages

Este sitio está optimizado para funcionar directamente con GitHub Pages sin necesidad de build tools.

### Pasos para publicar:

1. **Crear repositorio en GitHub** con el nombre `mtroangelsanchez.github.io`
2. **Subir los archivos** de este directorio al repositorio
3. **Agregar imágenes** en la carpeta `images/` (ver `images/README.md` para detalles)
4. **Configurar GitHub Pages:**
   - Ve a Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` (o `master`), carpeta: `/ (root)`
   - Guardar
5. **Configurar formulario de contacto:**
   - Regístrate en [Formspree](https://formspree.io)
   - Reemplaza `YOUR_FORM_ID` en `index.html` con tu ID real
6. **Actualizar links de redes sociales** en `index.html` con tus perfiles reales

### Estructura del proyecto

```
├── index.html          # Página principal
├── styles.css          # Estilos del sitio
├── script.js           # Interactividad (navbar, animaciones)
├── 404.html            # Página de error personalizada
├── .nojekyll           # Evita procesamiento Jekyll
├── images/             # Imágenes del sitio
│   ├── banner.png      # Hero image
│   ├── profile.jpg     # Foto de perfil
│   ├── favicon.ico     # Favicon
│   ├── apple-touch-icon.png
│   └── og-image.png    # Open Graph image
└── README.md           # Este archivo
```

### Tecnologías

- HTML5 semántico
- CSS3 (variables, grid, flexbox, animaciones)
- JavaScript vanilla (sin dependencias)
- Google Fonts (Poppins)
- Font Awesome 6 (iconos)
- Formspree (formulario de contacto)

### Personalización

- **Colores:** Modifica las variables CSS en `:root` dentro de `styles.css`
- **Contenido:** Edita directamente `index.html`
- **Dominio personalizado:** Crea un archivo `CNAME` con tu dominio

## Licencia

Ver archivo [LICENSE](LICENSE).
