
# Onboarding WeSpeak Payment Links

This is a code bundle for Onboarding WeSpeak Payment Links. The original project is available at https://www.figma.com/design/wE8oO1EQguoazbNPXNJjB7/Onboarding-WeSpeak-Payment-Links.

## Running the code

Run `npm i` to install the dependencies.

Run `npm run dev` to start the development server.

## Deploy to GitHub Pages

Este proyecto está configurado para desplegarse automáticamente en GitHub Pages.

### Configuración inicial en GitHub:

1. **Habilita GitHub Pages en tu repositorio:**
   - Ve a Settings → Pages en tu repositorio de GitHub
   - En "Source", selecciona "GitHub Actions"
   - Guarda los cambios

2. **Sube el código:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
   git push -u origin main
   ```

3. **El despliegue automático:**
   - Cada vez que hagas push a la rama `main` o `master`, el workflow se ejecutará automáticamente
   - El sitio estará disponible en: `https://TU-USUARIO.github.io/TU-REPOSITORIO/`
   - Si tu repositorio se llama `TU-USUARIO.github.io`, estará en: `https://TU-USUARIO.github.io/`

### Notas importantes:

- El workflow detecta automáticamente el nombre del repositorio
- Si necesitas probar el build localmente con el mismo path que GitHub Pages, ejecuta:
  ```bash
  GITHUB_REPOSITORY_NAME=nombre-de-tu-repo npm run build
  npm run preview
  ```
  