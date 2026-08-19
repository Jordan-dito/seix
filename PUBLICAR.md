# Publicar la página de SEIX en GitHub Pages

Dos archivos: `index.html` (todo va adentro, incluido el logo) y `favicon.ico`.

## Pasos

1. Crea un repositorio nuevo en GitHub. Si lo llamas `TU-USUARIO.github.io`, la página queda en la raíz; con cualquier otro nombre queda en `TU-USUARIO.github.io/NOMBRE-DEL-REPO`.
2. Sube los dos archivos a la raíz del repositorio (arrastrándolos en la web de GitHub o con git):

   ```bash
   git init
   git add index.html favicon.ico
   git commit -m "Página de venta SEIX"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/NOMBRE-DEL-REPO.git
   git push -u origin main
   ```

3. En el repositorio: **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. En uno o dos minutos la página queda publicada en la URL que muestra esa misma pantalla.

## Después de publicar

- Verifica el botón de WhatsApp desde un celular: debe abrir el chat a 099 012 2698 con el mensaje precargado.
- Cuando tengas un correo del negocio, agrégalo en la sección de contacto (hoy solo hay WhatsApp y teléfono, a propósito: mejor ningún correo que uno inventado).
- Cuando la firma XAdES esté certificada ante el SRI, actualiza la sección "Facturación" con la versión que está comentada en `pagina-venta.md` del material de marca.
- Si cambias precios, recuerda que están en dos lugares por plan: el mensual y el anual (atributos `data-mes` y `data-ano`).
