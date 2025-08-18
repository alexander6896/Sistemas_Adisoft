# 🚀 Sistemas Adisoft - Sitio Web Profesional

Un sitio web moderno y responsivo para empresas de tecnología, desarrollado con HTML5, CSS3, Bootstrap 5 y JavaScript vanilla.

## ✨ Características

- **Diseño Responsivo**: Optimizado para todos los dispositivos
- **Navegación Suave**: Scroll suave entre secciones
- **Animaciones**: Efectos visuales atractivos y modernos
- **Formulario de Contacto**: Validación y notificaciones en tiempo real
- **Modo Oscuro**: Toggle opcional para cambiar tema
- **Optimizado para SEO**: Estructura semántica y meta tags
- **Accesible**: Cumple estándares de accesibilidad web
- **Rápido**: Optimizado para rendimiento y velocidad

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica moderna
- **CSS3**: Variables CSS, Flexbox, Grid, Animaciones
- **Bootstrap 5**: Framework CSS responsivo
- **JavaScript ES6+**: Funcionalidades interactivas
- **Font Awesome**: Iconografía profesional
- **Google Fonts**: Tipografías optimizadas

## 📁 Estructura del Proyecto

```
SistemasAdisoft-Website/
├── index.html          # Página principal
├── styles.css          # Estilos CSS personalizados
├── script.js           # Funcionalidades JavaScript
└── README.md           # Este archivo
```

## 🚀 Cómo Usar

### 1. Descarga o Clona el Proyecto

```bash
# Si tienes Git instalado
git clone [URL_DEL_REPOSITORIO]

# O descarga el ZIP y extráelo
```

### 2. Abre en tu Editor

```bash
# Con VS Code
code .

# Con Cursor
cursor .

# O simplemente abre la carpeta en tu editor preferido
```

### 3. Ejecuta Localmente

```bash
# Opción 1: Servidor local simple (Python)
python -m http.server 8000

# Opción 2: Servidor local simple (Node.js)
npx serve .

# Opción 3: Abre directamente en el navegador
# Haz doble clic en index.html
```

### 4. Accede a tu Sitio

Abre tu navegador y ve a:
- **Local**: `http://localhost:8000`
- **Directo**: `file:///ruta/a/tu/proyecto/index.html`

## 🎨 Personalización

### Cambiar Colores

Edita las variables CSS en `styles.css`:

```css
:root {
    --primary-color: #007bff;      /* Color principal */
    --secondary-color: #6c757d;    /* Color secundario */
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Cambiar Contenido

Modifica el contenido en `index.html`:

```html
<!-- Cambiar título -->
<title>Tu Empresa - Soluciones Tecnológicas</title>

<!-- Cambiar logo -->
<a class="navbar-brand fw-bold" href="#">
    <i class="fas fa-laptop-code me-2"></i>
    Tu Empresa
</a>

<!-- Cambiar servicios -->
<div class="service-card">
    <h5 class="card-title fw-bold">Tu Servicio</h5>
    <p class="card-text text-muted">Descripción de tu servicio</p>
</div>
```

### Cambiar Información de Contacto

```html
<!-- En la sección de contacto -->
<div class="d-flex mb-3">
    <i class="fas fa-phone text-primary me-3 fa-lg"></i>
    <div>
        <h6 class="fw-bold">Teléfono</h6>
        <p class="text-muted mb-0">+1 (555) 123-4567</p>
    </div>
</div>
```

## 🔧 Funcionalidades JavaScript

### Navegación Inteligente
- Menú activo según sección visible
- Cierre automático en móviles
- Scroll suave entre secciones

### Animaciones
- Efectos al hacer scroll
- Contadores animados
- Hover effects en tarjetas

### Formulario
- Validación en tiempo real
- Notificaciones de éxito/error
- Auto-reset después del envío

### Características Adicionales
- Botón "Volver arriba"
- Modo oscuro opcional
- Preloader personalizado
- Optimizaciones de rendimiento

## 📱 Responsive Design

El sitio está optimizado para:

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

### Breakpoints Bootstrap

```css
/* Extra small devices */
@media (max-width: 575.98px) { }

/* Small devices */
@media (min-width: 576px) and (max-width: 767.98px) { }

/* Medium devices */
@media (min-width: 768px) and (max-width: 991.98px) { }

/* Large devices */
@media (min-width: 992px) and (max-width: 1199.98px) { }

/* Extra large devices */
@media (min-width: 1200px) { }
```

## 🚀 Despliegue

### Opciones de Hosting

1. **GitHub Pages** (Gratis)
2. **Netlify** (Gratis)
3. **Vercel** (Gratis)
4. **Hosting tradicional** (Pago)

### Pasos para GitHub Pages

```bash
# 1. Crea un repositorio en GitHub
# 2. Sube tu código
git add .
git commit -m "Initial commit"
git push origin main

# 3. Ve a Settings > Pages
# 4. Selecciona la rama main
# 5. Tu sitio estará disponible en: https://usuario.github.io/repositorio
```

## 🔍 SEO y Optimización

### Meta Tags Incluidos

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Sistemas Adisoft - Soluciones tecnológicas innovadoras">
<meta name="keywords" content="desarrollo web, software, tecnología, soluciones empresariales">
<meta name="author" content="Sistemas Adisoft">
```

### Estructura Semántica

- `<header>` para navegación
- `<main>` para contenido principal
- `<section>` para cada sección
- `<footer>` para pie de página
- `<nav>` para navegación
- `<article>` para contenido independiente

## 🎯 Próximas Mejoras

- [ ] Integración con CMS
- [ ] Blog integrado
- [ ] Sistema de portafolio
- [ ] Chat en vivo
- [ ] Analytics avanzado
- [ ] PWA (Progressive Web App)
- [ ] Multiidioma
- [ ] Integración con redes sociales

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Soporte

Si tienes preguntas o necesitas ayuda:

- **Email**: info@sistemasadisoft.com
- **Issues**: Crea un issue en GitHub
- **Documentación**: Revisa este README

## 🙏 Agradecimientos

- **Bootstrap Team** por el framework CSS
- **Font Awesome** por los iconos
- **Google Fonts** por las tipografías
- **Comunidad de desarrolladores** por el apoyo

---

**Desarrollado con ❤️ por Sistemas Adisoft**

*Última actualización: Agosto 2024*
