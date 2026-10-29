# 🎂 Feliz Cumpleaños – Erizo Dashboard

## Estructura
```
cumpleanos-erizo/
├── index.html          ← la app
├── videoplayback.mp4   ← PEGA AQUÍ tu video (mismo nombre exacto)
├── .nojekyll
├── .gitattributes
└── README.md
```

## Personalizar
Abre `index.html`, busca `✏️ PERSONALIZA AQUÍ` y cambia `nombre`, `firma` y `mensaje`.

## Publicar en GitHub Pages (sin consola)
1. Crea un repo **público** en GitHub (ej. `cumpleanos-erizo`).
2. *Add file → Upload files* → arrastra TODO el contenido de esta carpeta + `videoplayback.mp4` → *Commit*.
3. *Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save*.
4. En 1–2 min tu link: `https://TU_USUARIO.github.io/cumpleanos-erizo/`

## Publicar con Git (consola)
```bash
git init
git add .
git commit -m "Cumpleaños erizo 🎉"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/cumpleanos-erizo.git
git push -u origin main
```
Luego activa Pages como en el paso 3.

## ⚠️ Tamaño del video
- Subida por la web: máx. **25 MB**.
- Por git: máx. **100 MB** por archivo.
- Si pesa más, comprímelo (HandBrake, preset "Fast 720p30") o usa Git LFS
  (ojo: GitHub Pages no sirve archivos LFS, mejor comprimir).

## Probar en local
VS Code → clic derecho en `index.html` → *Open with Live Server*.
(Con video local también funciona con doble clic.)
