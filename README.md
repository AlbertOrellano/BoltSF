# BoltSF – Safe Friends 🐾

Sitio web oficial del proyecto "BoltSF – Safe Friends", una aplicación web educativa que integra un chatbot con inteligencia artificial (Chatbase) para ofrecer orientación rápida sobre primeros auxilios caninos.

## 🚀 Características

- **Diseño moderno y responsivo** con enfoque mobile-first
- **Paleta de colores BoltSF** (Coral rojizo, Amarillo rayo, Verde suave)
- **Navegación suave** entre secciones
- **Integración con Chatbase** para el chatbot de IA
- **Formulario de contacto** con Formspree
- **Animaciones suaves** y efectos visuales
- **Optimizado para SEO** y accesibilidad

## 📁 Estructura del Proyecto

```
BoltSF/
├── index.html              # Página principal
├── favicon.ico             # Favicon del sitio
├── styles/
│   └── main.css            # Estilos principales
├── scripts/
│   └── main.js             # JavaScript principal
├── assets/
│   ├── logo-boltsf.svg     # Logo oficial de BoltSF
│   ├── logo.png            # Logo en formato PNG
│   └── favicon.png         # Favicon en formato PNG
└── README.md               # Este archivo
```

## 🎨 Paleta de Colores

- **Coral rojizo**: `#FF5A5F` (color principal)
- **Gris oscuro**: `#333333` (texto principal)
- **Amarillo rayo**: `#FFC107` (acento)
- **Blanco**: `#FFFFFF` (fondos y contraste)
- **Verde suave**: `#4CAF50` (resaltados opcionales)

## 🛠️ Tecnologías Utilizadas

- **HTML5** semántico
- **CSS3** con variables personalizadas
- **JavaScript ES6+** vanilla
- **Google Fonts** (Inter)
- **Responsive Design** con CSS Grid y Flexbox

## 📱 Secciones del Sitio

1. **Header** - Navegación con logo BoltSF
2. **Hero** - Título, eslogan y botón principal
3. **Información** - Explicación de las funcionalidades
4. **Chatbot** - Integración con Chatbase
5. **Contacto** - Formulario con Formspree
6. **Footer** - Créditos del proyecto

## 🚀 Despliegue

### Vercel (Recomendado)

1. Conecta tu repositorio de GitHub a Vercel
2. Vercel detectará automáticamente el proyecto
3. El sitio se desplegará automáticamente

### GitHub Pages

1. Sube los archivos a un repositorio de GitHub
2. Ve a Settings > Pages
3. Selecciona la rama principal como fuente
4. El sitio estará disponible en `https://tu-usuario.github.io/nombre-repositorio`

### Netlify

1. Arrastra la carpeta del proyecto a Netlify
2. O conecta tu repositorio de GitHub
3. El sitio se desplegará automáticamente

## ⚙️ Configuración

### Chatbase

Para configurar el chatbot:

1. Reemplaza `ID_DEL_CHATBOT` en el iframe con tu ID real de Chatbase
2. Ajusta las dimensiones del iframe si es necesario

```html
<iframe
  src="https://www.chatbase.co/chatbot-iframe/TU_ID_REAL"
  width="100%"
  height="600"
  frameborder="0"
  style="border-radius: 12px;">
</iframe>
```

### Formspree

Para configurar el formulario de contacto:

1. Crea una cuenta en [Formspree](https://formspree.io)
2. Reemplaza `tu_codigo_formspree` con tu código real

```html
<form action="https://formspree.io/f/TU_CODIGO_REAL" method="POST">
```

## 🎯 Optimizaciones

- **Performance**: Carga optimizada de fuentes y recursos
- **SEO**: Meta tags y estructura semántica
- **Accesibilidad**: Navegación por teclado y ARIA labels
- **Responsive**: Diseño adaptativo para todos los dispositivos

## 📞 Créditos

**Autores**: Albert Orellano y Abdul Laiseca – Bootcamp IA Talento Tech 2025

**© 2025 BoltSF | Hecho en Cúcuta con amor ⚡️**

## 🔧 Desarrollo Local

Para ejecutar el proyecto localmente:

1. Clona o descarga el repositorio
2. Abre `index.html` en tu navegador
3. O usa un servidor local:

```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx serve .

# Con PHP
php -S localhost:8000
```

## 📝 Notas

- El sitio está optimizado para carga rápida
- Compatible con todos los navegadores modernos
- Incluye fallbacks para navegadores antiguos
- Preparado para PWA (Progressive Web App) si se desea

---

¡Gracias por usar BoltSF – Safe Friends! 🐾❤️
