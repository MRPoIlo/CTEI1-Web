# 🎨 Portafolio Digital - MRPoIlo

Bienvenido a mi portafolio digital profesional. Este proyecto es una página web moderna y responsiva que showcasea mis proyectos, habilidades y experiencia.

## ✨ Características

- 🎯 **Diseño Moderno**: Interfaz limpia y profesional
- 📱 **Responsive**: Adapta perfectamente a cualquier dispositivo
- ⚡ **Rendimiento**: Carga rápida y optimizada
- 🎨 **Animaciones Suaves**: Transiciones elegantes y fluidas
- 🔗 **Navegación Intuitiva**: Menú de navegación fácil de usar
- 📝 **Formulario de Contacto**: Para que te comuniques conmigo
- 🎭 **Secciones Completas**:
  - Inicio con presentación
  - Sobre mí
  - Galería de proyectos
  - Habilidades profesionales
  - Formulario de contacto
  - Enlaces sociales

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos y responsive
- **JavaScript Vanilla**: Interactividad sin dependencias
- **Git & GitHub**: Control de versiones

## 📁 Estructura del Proyecto

```
CTEI1-Web/
├── index.html          # Página principal
├── styles.css          # Estilos globales
├── script.js           # Lógica y interactividad
├── .gitignore          # Archivos a ignorar
└── README.md           # Este archivo
```

## 🚀 Características del Código

### Navegación
- Menú sticky que permanece visible al hacer scroll
- Enlaces suaves que navegan a las secciones
- Diseño responsive que se adapta a móviles

### Animaciones
- Efectos de flotación en el héroe
- Animaciones de entrada para elementos
- Transiciones suaves en botones y tarjetas
- Intersection Observer para animaciones al hacer scroll

### Formulario
- Validación de campos
- Mensaje de confirmación al enviar
- Reseteo automático del formulario

## 📝 Cómo Personalizar

### 1. Editar la Información Personal
Abre `index.html` y busca:
- `MRPoIlo` - Cambia por tu nombre
- "Desarrollador Full Stack" - Cambia por tu profesión
- Secciones de "Sobre Mí"

### 2. Agregar Proyectos
En la sección de proyectos, copia el bloque `.project-card` y personaliza:
```html
<div class="project-card">
    <div class="project-header">Tu Proyecto</div>
    <h3>Nombre del Proyecto</h3>
    <p>Descripción...</p>
    <div class="project-tags">
        <span class="tag">Tecnología</span>
    </div>
    <a href="#" class="btn btn-secondary">Ver Proyecto</a>
</div>
```

### 3. Modificar Colores
En `styles.css`, busca `:root` y personaliza las variables:
```css
:root {
    --primary-color: #6c5ce7;      /* Color principal */
    --secondary-color: #a29bfe;    /* Color secundario */
    --dark-color: #2d3436;         /* Color oscuro */
    --light-color: #f5f6fa;        /* Color claro */
}
```

### 4. Actualizar Enlaces Sociales
En `index.html`, sección de contacto:
```html
<a href="https://github.com/tu-usuario" class="social-link">GitHub</a>
<a href="https://linkedin.com/in/tu-perfil" class="social-link">LinkedIn</a>
```

## 🎯 Próximas Mejoras

- [ ] Integrar backend para el formulario de contacto
- [ ] Agregar más proyectos
- [ ] Implementar dark mode
- [ ] Agregar blog
- [ ] Optimizar para SEO
- [ ] Agregar certificaciones
- [ ] Implementar multi-idioma

## 📱 Compatibilidad

- ✅ Chrome/Edge (Últimas versiones)
- ✅ Firefox (Últimas versiones)
- ✅ Safari (Últimas versiones)
- ✅ Dispositivos móviles (iOS/Android)

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🤝 Contacto

- **GitHub**: [@MRPoIlo](https://github.com/MRPoIlo)
- **Email**: Agregado en el formulario de contacto

---

**Hecho con ❤️ por MRPoIlo**