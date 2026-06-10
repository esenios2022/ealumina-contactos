# 📤 Cómo subir ealumina-contactos a GitHub

## Opción 1: Crear repositorio DIRECTAMENTE en GitHub (Recomendado)

1. Ve a [github.com](https://github.com)
2. Haz clic en **+** (arriba a la derecha) → **New repository**
3. Completa:
   - **Repository name:** `ealumina-contactos`
   - **Description:** `Plataforma colaborativa para gestionar contactos integrada con Supabase`
   - **Public** (marcar)
   - **Add a README file** (NO marcar)
   - Haz clic en **Create repository**

4. Ya estás dentro del repo. Haz clic en **"Add file"** → **"Upload files"**
5. Descarga el ZIP que te di
6. Descomprime la carpeta
7. **Arrastra los archivos** a la página de GitHub:
   - `index.html`
   - `README.md`
   - `package.json`
   - `vercel.json`
   - `.gitignore`

8. Escribe en el mensaje: `Initial commit - ealumina-contactos`
9. Haz clic en **Commit changes**

✅ **¡Listo! Tu repo está en GitHub**

---

## Opción 2: Si prefieres usar terminal

```bash
cd ruta/del/ZIP/descomprimido
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/ealumina-contactos.git
git push -u origin main
```

---

## Siguiente: Deploy a Vercel

1. Ve a [vercel.com](https://vercel.com)
2. Haz clic en **Add New** → **Project**
3. Selecciona tu repo `ealumina-contactos`
4. Haz clic en **Import**
5. Haz clic en **Deploy**

⏳ Espera 30 segundos...

✅ Tu sitio estará en: `https://ealumina-contactos.vercel.app`

---

¡Listo! 🚀
