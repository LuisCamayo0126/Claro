# Claro (NetNova redesign)

Repositorio de demostración con un diseño web estático (index.html) — rediseño futurista inspirado en Claro.

Contenido
- `index.html` — página principal con estilos y widget de chat n8n.

Cómo ver localmente
1. Abrir `index.html` en tu navegador (doble clic o servidor local).
2. Para un servidor local rápido con PowerShell:

```powershell
# Desde la carpeta del proyecto
# Si tienes Python 3.x instalado
python -m http.server 8000
# Luego abre http://localhost:8000
```

Notas
- El chat utiliza un webhook temporal (ngrok). Reemplázalo por un endpoint estable en producción.
- Las imágenes usan `loading="lazy"` para mejorar el rendimiento.

Licencia
Este proyecto es demostrativo.
