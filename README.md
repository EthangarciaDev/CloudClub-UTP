# Cloud Club UTP - Página Web

Esta es la página web oficial del Cloud Club de la Universidad Tecnológica de Puebla.

## 🚀 Despliegue en GitHub Pages

### Pasos para configurar GitHub Pages:

1. **Sube el código a GitHub:**

   ```bash
   git add .
   git commit -m "Configurar para GitHub Pages"
   git push origin main
   ```

2. **Habilita GitHub Pages:**

   - Ve a tu repositorio en GitHub
   - Dirígete a **Settings** > **Pages**
   - En **Source**, selecciona "GitHub Actions"

3. **El despliegue es automático:**
   - Cada vez que hagas push a la rama `main`, se ejecutará automáticamente el workflow
   - El workflow construirá el CSS de Tailwind y desplegará el sitio
   - Tu sitio estará disponible en: `https://tu-usuario.github.io/nombre-repositorio`

### Desarrollo local:

Para trabajar en el proyecto localmente:

```bash
# Instalar dependencias
pnpm install

# Modo desarrollo (reconstruye CSS automáticamente)
pnpm run dev

# Construir para producción
pnpm run build

# Vista previa local
pnpm run preview
```

## 📁 Estructura del proyecto

```
├── index.html          # Página principal
├── input.css           # CSS de Tailwind (fuente)
├── assets/
│   ├── output.css      # CSS compilado (generado)
│   ├── sprite.svg      # Iconos SVG
│   └── inter.woff2     # Fuente Inter
├── image/              # Imágenes del sitio
├── .github/
│   └── workflows/
│       └── deploy.yml  # Configuración de GitHub Actions
└── .nojekyll          # Desactiva Jekyll en GitHub Pages
```

## ✨ Características

- ✅ Diseño responsivo con Tailwind CSS
- ✅ Animaciones suaves
- ✅ Optimizado para GitHub Pages
- ✅ Despliegue automático con GitHub Actions
- ✅ Enlaces a redes sociales
- ✅ Fuentes web optimizadas

## 🔧 Tecnologías utilizadas

- **HTML5** - Estructura
- **Tailwind CSS v4** - Estilos
- **GitHub Pages** - Hosting
- **GitHub Actions** - CI/CD
- **PNPM** - Gestor de paquetes

---

Desarrollado por el **Cloud Club UTP** 🌩️
