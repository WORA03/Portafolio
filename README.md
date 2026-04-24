# Portfolio Static - Versión para GitHub Pages

Este es el portfolio estático de Wellin Romero, optimizado para despliegue en GitHub Pages.

## 🚀 Características

- **100% Vanilla HTML/CSS/JavaScript** - Sin dependencias de frameworks
- **Diseño Responsivo** - Compatible con todos los dispositivos
- **GitHub Pages Ready** - Estructura optimizada para despliegue estático
- **SEO Optimizado** - Meta tags y estructura semántica
- **Interactivo** - Animaciones suaves y efectos hover

## 📁 Estructura del Proyecto

```
portafolio static/
├── index.html          # Página principal
├── styles.css          # Estilos completos
├── script.js           # Funcionalidad JavaScript
├── profile.png         # Foto de perfil
├── favicon.ico         # Icono del navegador
├── hero.svg            # Imagen de fondo del hero
└── README.md           # Este archivo
```

## 🎨 Secciones del Portfolio

1. **Hero Section** - Presentación con ventana de código animada
2. **Acerca de Mí** - Información personal y profesional
3. **Experiencia** - Trayectoria laboral
4. **Habilidades** - 16 tecnologías con iconos
5. **Educación** - Formación académica
6. **Proyectos** - 3 proyectos destacados con enlaces
7. **Contacto** - Formulario funcional y datos de contacto

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con Grid y Flexbox
- **JavaScript Vanilla** - Interactividad sin frameworks
- **Font Awesome** - Iconos profesionales
- **Google Fonts** - Tipografías modernas

## 📱 Diseño Responsivo

- **Desktop** (1024px+) - Grid 2 columnas, experiencia completa
- **Tablet** (768px-1023px) - Layout adaptado
- **Mobile** (<768px) - Menú hamburguesa, diseño vertical

## 🚀 Despliegue en GitHub Pages

### Opción 1: Desde la rama principal

1. Sube todos los archivos a la rama `main` o `master`
2. Ve a Settings > Pages en tu repositorio
3. Selecciona "Deploy from a branch"
4. Elige la rama `main` y la carpeta `/ (root)`
5. Guarda y espera el despliegue

### Opción 2: Desde una rama específica

1. Crea una rama `gh-pages`
2. Sube todos los archivos a esa rama
3. GitHub Pages desplegará automáticamente

### Opción 3: Usando GitHub Actions

```yaml
# .github/workflows/deploy.yml
name: Deploy to GitHub Pages

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

jobs:
  deploy:
    runs-on: ubuntu-latest
    
    steps:
    - uses: actions/checkout@v3
    
    - name: Deploy to GitHub Pages
      uses: peaceiris/actions-gh-pages@v3
      with:
        github_token: ${{ secrets.GITHUB_TOKEN }}
        publish_dir: ./
```

## ⚙️ Personalización

### Cambiar Información Personal

Edita los siguientes archivos:

**`index.html`**:
- Nombre en el hero section
- Enlaces de redes sociales
- Información de contacto
- Proyectos y tecnologías

**`styles.css`**:
- Colores y gradientes
- Tipografías y tamaños
- Animaciones y efectos

### Agregar Nuevos Proyectos

```html
<div class="project-card">
    <div class="project-image">
        <img src="project-image.jpg" alt="Nombre del Proyecto" class="project-img">
    </div>
    <div class="project-info">
        <h3>Nombre del Proyecto</h3>
        <p>Descripción breve del proyecto</p>
        <div class="project-tech">
            <span><i class="fab fa-react"></i> React</span>
            <span><i class="fab fa-node-js"></i> Node.js</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/user/repo" target="_blank" class="project-link">
                <i class="fas fa-code"></i> Código
            </a>
            <a href="https://demo-url.com" target="_blank" class="project-link">
                <i class="fas fa-play"></i> Demo
            </a>
        </div>
    </div>
</div>
```

### Modificar Colores

En `styles.css`, busca las variables principales:

```css
:root {
    --primary-color: #ec4899;
    --secondary-color: #16f2b3;
    --background-color: #000000;
    --text-color: #ffffff;
    --card-bg: linear-gradient(90deg, #281e57, #201435);
}
```

## 📊 Optimización SEO

El sitio incluye:

- **Meta tags** optimizados
- **Open Graph** para redes sociales
- **Estructura semántica** HTML5
- **URLs amigables**
- **Imagenes optimizadas**

## 🐛 Solución de Problemas

### Problemas Comunes

1. **Iconos no aparecen**: Verifica la conexión a Font Awesome
2. **Imágenes no cargan**: Confirma las rutas de los archivos
3. **Formulario no funciona**: Revisa la configuración del servidor
4. **Animaciones lentas**: Reduce la complejidad CSS

### Depuración

Abre la consola del navegador (F12) para detectar errores.

## 🚀 Rendimiento

- **Tiempo de carga**: < 2 segundos
- **Puntuación Lighthouse**: 90+
- **Optimización de imágenes**: WebP recomendado
- **CSS/JS minificado**: Para producción

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Puedes usarlo libremente.

## 👤 Contacto

- **Email**: wellinromero03@outlook.com
- **GitHub**: https://github.com/WORA03
- **LinkedIn**: https://www.linkedin.com/in/wellin-romero-567523286/

---

**¡Gracias por visitar mi portfolio!** 🚀
# Portafolio
