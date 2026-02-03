# Q&W Projects

Página web estática generada desde Adobe Express.

## Deployment en Netlify

### Opción 1: Conectar GitHub

1. Sube este repositorio a GitHub
2. Ve a [Netlify](https://app.netlify.com)
3. Haz clic en "New site from Git"
4. Selecciona tu repositorio
5. Netlify detectará automáticamente `netlify.toml` y desplegará

### Opción 2: Deploy Manual

```bash
# Instala Netlify CLI
npm install -g netlify-cli

# Inicia sesión en Netlify
netlify login

# Deploy desde esta carpeta
netlify deploy --prod
```

## Estructura del Proyecto

```
.
├── Q&W Projects.html        # Página principal
├── Q&W Projects_files/      # Assets (CSS, JS, fuentes, imágenes)
├── netlify.toml             # Configuración de Netlify
├── .gitignore               # Archivos a ignorar en Git
└── README.md                # Este archivo
```

## Características

- Página estática optimizada para Netlify
- Cache inteligente para assets estáticos
- Soporte para gzip en archivos comprimidos
- Redirecciones configuradas

## Notas

- La página es un cliente rico generado desde Adobe Express
- Todos los assets están incluidos en la carpeta `Q&W Projects_files/`
- No requiere base de datos ni procesamiento backend
