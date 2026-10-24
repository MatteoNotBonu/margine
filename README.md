# Margine

Annotatore PDF per iPad e Apple Pencil, pensato per PDF pesanti.

**Apri:** https://matteonotbonu.github.io/margine/

## Installazione su iPad
1. Apri il link in Safari.
2. Condividi → **Aggiungi alla schermata Home**.
3. Apri Margine dall'icona: schermo intero, archivio stabile, funziona anche offline.

## Come funziona
- Le pagine del PDF vengono disegnate solo quando sono visibili (massimo 4 in memoria), quindi anche file da decine di MB non bloccano l'iPad.
- Le annotazioni sono vettoriali e si salvano da sole sul dispositivo.
- **Salva in File** crea un PDF con le annotazioni dentro (annotazioni PDF standard). Riaprendolo in Margine tornano modificabili.
- I PDF non lasciano mai il dispositivo: nessun server, nessun account.

## File
- `index.html`: l'app (una sola pagina)
- `sw.js`: cache per l'uso offline
- `manifest.webmanifest`, `*.png`: installazione sulla schermata Home
