# 💍 Boda Esteban & Erika — 26.04.2026

Invitación digital personalizada por invitado.

---

## 📁 Estructura del proyecto

```
boda-esteban-erika/
├── index.html              ← Invitación principal
├── README.md               ← Este archivo
├── img/
│   ├── portada.jpg         ← Foto principal del sobre y hero (reemplazar)
│   ├── galeria-1.jpg       ← Foto galería 1 (reemplazar)
│   ├── galeria-2.jpg       ← Foto galería 2 (reemplazar)
│   └── galeria-3.jpg       ← Foto galería 3 (reemplazar)
└── invitados/
    ├── _lista.txt          ← Lista de todos los invitados
    └── (links de ejemplo)
```

---

## 🔗 Cómo personalizar los links

Cada invitado recibe un link único así:

```
https://TU-USUARIO.github.io/boda-esteban-erika/?para=Nombre+Apellido
```

### Ejemplos reales:
```
https://TU-USUARIO.github.io/boda-esteban-erika/?para=Hector+y+Lorena
https://TU-USUARIO.github.io/boda-esteban-erika/?para=Maria+Gonzalez
https://TU-USUARIO.github.io/boda-esteban-erika/?para=Familia+Ramirez
```

Los espacios se escriben como `+` en la URL.

---

## 🖼️ Cómo reemplazar las fotos

1. Pon tus fotos en la carpeta `/img/`
2. Nómbralas exactamente: `portada.jpg`, `galeria-1.jpg`, `galeria-2.jpg`, `galeria-3.jpg`
3. Abre `index.html` en VS Code
4. Busca `src="https://images.unsplash.com/..."`
5. Reemplaza por `src="img/portada.jpg"` (o el nombre correspondiente)

---

## 🚀 Cómo subir a internet (GitHub Pages) — paso a paso

### Paso 1: Crear cuenta en GitHub
- Ve a https://github.com y crea una cuenta gratuita si no tienes

### Paso 2: Crear repositorio
- Clic en "New repository"
- Nombre: `boda-esteban-erika`
- Márcalo como **Public**
- Clic en "Create repository"

### Paso 3: Subir los archivos
- En el repositorio, clic en "uploading an existing file"
- Arrastra toda la carpeta del proyecto
- Clic en "Commit changes"

### Paso 4: Activar GitHub Pages
- Ve a Settings → Pages
- En "Source" selecciona: **Deploy from a branch**
- Branch: **main** / carpeta: **/ (root)**
- Clic en "Save"

### Paso 5: Obtener el link
- Espera 2-3 minutos
- Tu link será: `https://TU-USUARIO.github.io/boda-esteban-erika/`

---

## 📋 Lista de invitados (editar en invitados/_lista.txt)

Abre el archivo `invitados/_lista.txt` y agrega un invitado por línea.
Cada línea genera un link diferente.

---

## ❓ Ayuda rápida

| Problema | Solución |
|----------|----------|
| El nombre no aparece | Verifica que el link tenga `?para=Nombre` |
| Las fotos no cargan | Verifica que estén en la carpeta `/img/` |
| La página no abre | Espera 5 min después de activar GitHub Pages |
