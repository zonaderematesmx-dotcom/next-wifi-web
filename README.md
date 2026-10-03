# Next Wifi TV — Sitio web oficial

Sitio estático de la marca **Next Wifi TV** y estudio **Skel Labs**.

## Estructura

```
/
├── index.html            → Landing de Next Wifi TV
├── skellabs/index.html   → Página de Skel Labs (desarrollo de apps)
├── privacy/index.html    → Política de privacidad   → /privacy
├── terms/index.html      → Términos de uso          → /terms
├── css/style.css         → Estilos (paleta de marca)
└── images/logo.png       → Logo oficial
```

## Despliegue en Render (Static Site)

1. Subir este repo a GitHub.
2. En [Render](https://dashboard.render.com): **New → Static Site**.
3. Conectar el repositorio.
4. Configuración:
   - **Build Command:** *(vacío)*
   - **Publish Directory:** `.`
5. **Create Static Site**. La URL quedará en `https://<nombre>.onrender.com`

URLs resultantes:

- Inicio: `https://<nombre>.onrender.com/`
- Privacidad: `https://<nombre>.onrender.com/privacy`
- Términos: `https://<nombre>.onrender.com/terms`
- Skel Labs: `https://<nombre>.onrender.com/skellabs`

## Nota

No editar el contenido legal sin revisión: `privacy/` y `terms/` son los
documentos oficiales vinculados al formulario de certificación de Roku.
