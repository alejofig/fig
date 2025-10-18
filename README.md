# Fig - Landing Page

Landing page profesional y minimalista para una aplicación móvil de gestión financiera inteligente, inspirada en el diseño de Tailus Oxymor.

## 🚀 Características

- **Diseño Moderno**: Inspirado en las mejores prácticas de diseño SaaS
- **Mockup Interactivo**: Preview realista de la aplicación móvil
- **Secciones Completas**: Hero, Features, How it Works, Testimonials, CTA
- **Responsive**: Perfectamente adaptado para móviles, tablets y desktop
- **Rápido**: Construido con Astro para máxima velocidad
- **Paleta Profesional**: Azul eléctrico (#3B82F6) + Violeta (#8B5CF6)

## 🛠️ Tecnologías

- [Astro](https://astro.build) - Framework web moderno
- TypeScript - Tipado estático
- CSS Nativo - Animaciones y estilos personalizados

## 📦 Instalación

```bash
npm install
```

## 🔧 Comandos

```bash
# Iniciar servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Vista previa de la build
npm run preview
```

## 📁 Estructura del Proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro          # Header fijo con logo y CTA
│   │   ├── Hero.astro             # Hero con mockup de la app
│   │   ├── Features.astro         # Grid de 6 características
│   │   ├── HowItWorks.astro      # 3 pasos simples
│   │   ├── Testimonials.astro    # Testimonios de usuarios
│   │   ├── CTASection.astro      # Call to action final
│   │   └── Footer.astro           # Footer completo con links
│   ├── layouts/
│   │   └── Layout.astro           # Layout base + estilos globales
│   └── pages/
│       └── index.astro            # Página principal
└── package.json
```

## 🎨 Paleta de Colores

Los colores principales se definen en `src/layouts/Layout.astro`:

```css
:root {
  --color-bg: #000000;
  --color-text: #ffffff;
  --color-accent: #3B82F6;              /* Azul eléctrico */
  --color-accent-secondary: #8B5CF6;    /* Violeta */
  --color-accent-rgb: 59, 130, 246;
  --color-gray: #9CA3AF;
}
```

## ✨ Secciones

### Hero
- Título impactante con mockup real de la app
- Botón de descarga para Android
- Preview interactivo mostrando balance, transacciones y estadísticas

### Features
- 6 características principales en grid
- Iconos SVG personalizados
- Hover effects suaves

### How It Works
- 3 pasos numerados
- Diseño card-based
- Gradientes en números

### Testimonials
- 3 testimonios de usuarios reales
- Avatares y roles
- Diseño tipo tarjeta

### CTA Section
- Diseño centrado con borde
- Botón principal destacado
- Mensaje sobre disponibilidad iOS

### Footer
- Links organizados por categorías
- Redes sociales
- Copyright y legal

## 📱 Sobre la Aplicación

**Fig** es una aplicación móvil que:

- ✉️ Convierte automáticamente correos y SMS bancarios en registros financieros
- 🤖 Incluye un asistente de IA para consultar y agregar información
- ⚡ Categoriza transacciones de forma inteligente
- 📊 Muestra análisis en tiempo real
- 🔒 Garantiza privacidad y seguridad total

## 🎯 Inspiración de Diseño

Esta landing está inspirada en [Oxymor de Tailus](https://tailus.io/preview/oxymor-yv/), siguiendo principios de:
- Espaciado generoso
- Tipografía clara y legible
- Jerarquía visual clara
- Menos animaciones, más contenido
- Mockups realistas del producto

## 📄 Licencia

Este proyecto está disponible para uso personal y comercial.
