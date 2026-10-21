# Ghisa 🏋️

A simple gym log: log your sets in a few taps, rest timer between sets, progress charts and import from your notes. With Bell, the kettlebell mascot.

Funziona interamente nel browser: niente server, niente account. I dati restano salvati sul telefono (usa **Notes → Export backup** ogni tanto).

## Pubblicare con GitHub Pages

1. Crea un repository pubblico, ad esempio `ghisa`.
2. Carica **tutti i file** di questa cartella nella radice del repository (non la cartella intera, non lo zip).
3. Vai su **Settings → Pages**, scegli **Deploy from a branch**, branch `main`, cartella `/ (root)`, poi **Save**.
4. Dopo un paio di minuti l'app è su `https://TUONOME.github.io/ghisa/`.

## Installarla sul telefono

- **iPhone**: apri il link in Safari → Condividi → *Aggiungi alla schermata Home*.
- **Android**: apri il link in Chrome → menu ⋮ → *Installa app*.

## Aggiornare l'app

1. Sostituisci `index.html` nel repository con la nuova versione.
2. In `sw.js` cambia `VERSION` (es. da `ghisa-v7` a `ghisa-v8`), così i telefoni scaricano la nuova versione.

## Spostare i dati

I dati sono legati all'indirizzo da cui apri l'app. Per portarli da un'altra versione: **Notes → Export backup** nella vecchia, poi **Notes → Restore backup** nella nuova.
