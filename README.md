# ✅ Organizador de Tareas por Prioridad

App web sencilla para organizar tareas según prioridad y fecha.

## Funcionalidades

- Añadir tareas con **nombre, fecha, prioridad y comentarios**.
- Prioridades: `muy baja`, `baja`, `media`, `alta`, `crítica`.
- **Orden automático**: de más prioritaria (crítica) a menos prioritaria (muy baja), y a igual prioridad por fecha más próxima.
- Marcar como completada / reabrir, editar y eliminar.
- Buscador por nombre o comentario.
- Filtros por prioridad y estado.
- Aviso de tareas vencidas.
- Guardado local en el navegador (`localStorage`).
- Sin dependencias, sin build.

## Estructura

```text
.
├── index.html   # App completa (HTML + CSS + JS)
├── README.md
├── LICENSE
└── .gitignore
```

## Uso en local

Al ser una app estática, basta con abrir el archivo:

1. Doble clic en `index.html`, o
2. Servir la carpeta:

```bash
# Python 3
python -m http.server 8000
# abrir http://localhost:8000
```

```bash
# Node
npx serve .
```

## Subir a GitHub

```bash
cd "App organización tareas"
git init
git add .
git commit -m "Initial commit: organizador de tareas"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main
```

O con GitHub CLI:

```bash
gh repo create TU-REPO --public --source=. --push
```

## Activar GitHub Pages

1. Ve a tu repo en GitHub → **Settings → Pages**.
2. En **Source** elige **Deploy from a branch**.
3. Branch: `main` / carpeta `/ (root)`.
4. Guarda. Tu app quedará en:

```text
https://TU-USUARIO.github.io/TU-REPO/
```

## Licencia

MIT — ver [LICENSE](LICENSE).
