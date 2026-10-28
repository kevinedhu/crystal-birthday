# Guía de Música: Cómo agregar tus canciones para GitHub y la Web

El reproductor ahora tiene **triple compatibilidad automática**:
1. **Archivos Locales en esta carpeta (`audio/`)** *(Recomendado para GitHub)*
2. **URLs directas de Internet (`onlineUrl`)**
3. **Respaldo automático a YouTube (`ytId`) y sintetizador Web Audio**

---

### Opción 1: Colocar archivos MP3 en la carpeta `audio/` (Recomendado para GitHub)
Para subir tu proyecto a **GitHub Pages** u otro hosting, la forma más limpia y sin anuncios en el celular es colocar tus canciones en esta carpeta con estos nombres:

- `la_la_land.mp3` *(Para el tema de La La Land)*
- `cancion1.mp3`
- `cancion2.mp3`
- `cancion3.mp3`
- `cancion4.mp3`
- `cancion5.mp3`

> **Nota:** Ya dejamos generado un archivo de piano de estudio `audio/la_la_land.wav` de respaldo, por lo que *Mia & Sebastian's Theme* funciona de inmediato incluso si aún no has copiado tu archivo MP3.

---

### Opción 2: Usar un link directo de Internet (onlineUrl)
Si no deseas guardar archivos pesados en tu repositorio de GitHub, puedes alojar los MP3 en un servicio externo (como Cloudinary, Dropbox con enlace directo, Firebase Storage, o un release de GitHub) y pegar la URL en `code.html`.

Abre `code.html` y en la sección `crystalSongs` agrega tu URL:
```javascript
{
  id: 'la_la_land',
  onlineUrl: 'https://tu-servidor.com/mia_and_sebastian.mp3', // <-- Pega tu link directo aquí
  title: "Mia & Sebastian's Theme (La La Land)",
  ...
}
```

---

### Opción 3: Con ID de video de YouTube (Fallback)
Si no pones archivo local ni URL, el reproductor cargará automáticamente el video oficial de YouTube usando el `ytId`:
```javascript
{
  id: 'video_1',
  ytId: 'mRi6RS38eHc', // <-- El código que sale al final del link de YouTube: youtube.com/watch?v=mRi6RS38eHc
  title: 'Nombre de tu canción',
  artist: 'Artista',
  ...
}
```

---

### ¿Cómo funciona al entrar a "Destino Astral"?
Cuando Crystal o tú toquen **"Descubrir Destino Astral de Escorpio"** (Acto 2), la canción **Mia & Sebastian's Theme** empezará a sonar inmediatamente en alta fidelidad y aparecerá una insignia flotante dorada con el nombre de la canción que permite pausar o reanudar en cualquier momento.
