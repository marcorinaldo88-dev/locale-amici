# 🏠🍻 Il Nostro Locale

Mini-sito per gestire il locale con gli amici. Tre dashboard in un'unica pagina:

- **💶 Quote mensili** — segna chi ha versato la quota, un mese alla volta da *Ottobre 2026* a *Dicembre 2028*. Importo quota configurabile e totale raccolto per ogni mese.
- **🧊 Frigo bar** — inventario con scheda prodotto (costo di acquisto e prezzo di vendita). Registri vendite e rifornimenti a mano e in alto vedi sempre **Spesa totale**, **Vendite totali** e **Guadagno** (vendite − spesa), aggiornati in automatico.
- **🧹 Calendario pulizie** — clicca su un giorno e assegni il turno. Navighi tra i mesi.

All'apertura parte la schermata **"Benvenuti al locale!"** con tanto di coriandoli. 🎉

## Come usarlo in locale

È una singola pagina statica, senza server. Basta aprire `index.html` con un doppio clic nel browser.

## Dove vengono salvati i dati

I dati restano nel **`localStorage` del browser** (nessun server). Due cose da sapere:

- Sono legati a **quel browser su quel dispositivo**: se apri il sito su un altro telefono/PC, non trovi gli stessi dati.
- Per **backup o condivisione** usa i pulsanti in alto: **💾 Esporta** scarica un file `.json`, **📂 Importa** lo ricarica su un altro dispositivo. **🧨 Reset** azzera tutto.

> Se in futuro vuoi che i dati siano condivisi in tempo reale tra più persone, serve un backend (il sito statico da solo non può). In quel caso si aggiunge una piccola API.

## Pubblicare su GitHub Pages

1. Crea un repository su GitHub (es. `locale-amici`).
2. Carica `index.html` (e questo `README.md`) nella **root** del repo.
3. Vai su **Settings → Pages**.
4. In *Build and deployment* → *Source* scegli **Deploy from a branch**, branch **main**, cartella **/ (root)**, poi **Save**.
5. Dopo un minuto il sito è online all'indirizzo `https://<tuo-utente>.github.io/locale-amici/`.

Fatto! 🍺
