# Instrucciones para tus Videos 📹

¡Hola! Ya he configurado tu portafolio para soportar videos reales en la sección de Reels y he actualizado los logos.

## Cómo agregar tus videos

Actualmente he colocado etiquetas `<video>` en el código HTML. Para que se vean tus videos, tienes dos opciones principales:

### Opción 1: Hosting en Cloudinary (Recomendado para calidad y velocidad)
1. Sube tus 5 videos a [Cloudinary](https://cloudinary.com/) (es gratis).
2. Copia la URL que te dan (enlace directo .mp4 o .webm).
3. Abre el archivo `index.html`.
4. Busca las líneas donde dice `<source src="url_del_video_01.mp4" ...>`.
5. Reemplaza `url_del_video_01.mp4` por tu enlace de Cloudinary.
   - Ejemplo: `<source src="https://res.cloudinary.com/tu-usuario/video/upload/v123/mi-reel.mp4" ...>`

### Opción 2: Subirlos junto con la página (Solo si son livianos)
1. Si tus videos pesan poco (menos de 4MB cada uno), puedes ponerlos en una carpeta `videos/` dentro de `beluPortfolio`.
2. En el `index.html`, cambia el `src` a: `src="videos/video1.mp4"`.
3. Al subir a Vercel, asegúrate de no exceder los límites del plan gratuito.

### Despliegue en Vercel ▲
Una vez que hayas actualizado los enlaces de los videos:
1. Sube este código a tu repositorio de GitHub.
2. Conecta tu repositorio a Vercel.
3. ¡Listo! Vercel detectará el archivo `index.html` y hará el deploy automáticamente.

¡Tus logos de Canva, CapCut, Hugging Face y After Effects ya están actualizados! 🦋
