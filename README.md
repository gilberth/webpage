# 🌐 Personal Webpage

Mi página web personal desarrollada con HTML puro, desplegada en GitHub Pages.

## 🚀 Características

- 🎨 Diseño minimalista y elegante
- 📱 Totalmente responsivo
- ⚡ Carga ultra rápida (HTML puro)
- 🌐 Desplegado en GitHub Pages
- 🔗 Dominio personalizado configurado
- 🎯 SEO optimizado

## 🛠️ Tecnologías

- **Frontend**: HTML5, CSS3, JavaScript
- **Hosting**: GitHub Pages
- **Dominio**: Configurado con CNAME
- **CDN**: Automático con GitHub Pages

## 📁 Estructura

```
webpage/
├── index.html          # Página principal
├── CNAME              # Configuración de dominio personalizado
└── assets/            # Recursos (imágenes, CSS, JS)
```

## 🎨 Secciones de la Página

- **Hero/Inicio** - Presentación principal
- **Acerca de** - Información personal y profesional
- **Proyectos** - Portfolio de trabajos realizados
- **Habilidades** - Tecnologías y competencias
- **Contacto** - Información de contacto y redes sociales

## 🌐 Despliegue

La página está automáticamente desplegada en GitHub Pages:

- **URL Principal**: Configurada en CNAME
- **URL GitHub**: `https://gilberth.github.io/webpage`
- **Actualización**: Automática con cada push a main

### Configuración de GitHub Pages

1. Ve a Settings del repositorio
2. Selecciona Pages en el menú lateral
3. Configura Source como "Deploy from a branch"
4. Selecciona branch: `main` y folder: `/ (root)`

## 🔧 Desarrollo Local

Para trabajar localmente:

1. Clona el repositorio:
```bash
git clone https://github.com/gilberth/webpage.git
cd webpage
```

2. Abre con Live Server o servidor local:
```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx serve .

# O simplemente abre index.html en el navegador
```

3. Haz tus cambios y push para actualizar automáticamente

## 📝 Personalización

### Actualizar contenido:
1. Edita `index.html` con tu información
2. Modifica estilos en las secciones `<style>` 
3. Actualiza enlaces a redes sociales
4. Cambia información de contacto

### Agregar nuevas secciones:
```html
<section id="nueva-seccion">
    <h2>Nueva Sección</h2>
    <p>Contenido de la nueva sección</p>
</section>
```

### Estilos CSS:
El CSS está embebido en el HTML para optimizar la carga. Para proyectos más grandes, considera separar en archivos CSS externos.

## 🎯 SEO y Performance

- ✅ Metaetiquetas optimizadas
- ✅ Estructura semántica HTML5
- ✅ Imágenes optimizadas
- ✅ Carga rápida (sin frameworks)
- ✅ Mobile-first responsive design

### Metaetiquetas incluidas:
```html
<meta name="description" content="Página personal de [Tu Nombre]">
<meta name="keywords" content="desarrollador, programador, portfolio">
<meta name="author" content="[Tu Nombre]">
<meta property="og:title" content="[Tu Nombre] - Desarrollador">
<meta property="og:description" content="Portfolio personal">
```

## 📱 Responsive Design

La página es completamente responsiva con breakpoints para:

- 📱 **Mobile**: < 768px
- 📊 **Tablet**: 768px - 1024px  
- 🖥️ **Desktop**: > 1024px

## 🔗 Configuración de Dominio

El archivo `CNAME` configura el dominio personalizado. Para cambiar:

1. Edita el archivo `CNAME`
2. Coloca tu dominio (ej: `midominio.com`)
3. Configura los DNS de tu dominio:
   ```
   Tipo: CNAME
   Nombre: www (o @)
   Valor: gilberth.github.io
   ```

## 📊 Analytics (Opcional)

Para agregar Google Analytics:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🚀 Optimizaciones Futuras

- [ ] PWA (Progressive Web App)
- [ ] Modo oscuro/claro
- [ ] Animaciones CSS
- [ ] Formulario de contacto funcional
- [ ] Blog integrado
- [ ] Galería de proyectos ampliada

## 🤝 Contribución

Si quieres sugerir mejoras:

1. Fork el repositorio
2. Crea una rama feature
3. Haz tus cambios
4. Submit un Pull Request

## 📞 Contacto

Puedes contactarme a través de:

- 🌐 **Website**: [Configurado en CNAME]
- 📧 **Email**: [Tu email]
- 💼 **LinkedIn**: [Tu LinkedIn]
- 🐙 **GitHub**: [gilberth](https://github.com/gilberth)

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de usar el código como base para tu propia página web.

---

**¡Gracias por visitar mi página web!** 🌟