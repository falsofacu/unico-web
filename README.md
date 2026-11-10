# ÚNICO Agencia

Sitio web de ÚNICO, agencia de redes a medida para emprendimientos (Montevideo, Uruguay).

Página estática de un solo archivo: `index.html`. No necesita build.

## Ver en local

```bash
python -m http.server 5173
```

Después abrir http://localhost:5173

## Reels

Los videos van en la carpeta `media/` con estos nombres:

| Archivo | Dónde aparece |
|---|---|
| `media/yipio-1.mp4` | Tarjeta de Yipio y primer reel |
| `media/yipio-2.mp4` | Reels |
| `media/yipio-3.mp4` | Reels |
| `media/matu-1.mp4` | Tarjeta de Matu Venao y segundo reel |
| `media/matu-2.mp4` | Reels |
| `media/matu-3.mp4` | Reels |

Si un archivo no está, la página muestra una tarjeta de reemplazo con el link al reel en Instagram. Formato recomendado: MP4 (H.264), vertical 9:16, 720p, sin audio o con audio (se reproduce en silencio), idealmente menos de 8 MB.

## Pendiente

- Datos de contacto reales (WhatsApp, email, Instagram son de ejemplo).
- Videos de los reels.
