# 🎾 Padel Score PWA

Segnapunti vocale per partite di padel - Progressive Web App

## Installazione su Server

1. **Carica tutti i file** su un server web con HTTPS (richiesto per le PWA)
2. La struttura deve essere:
   ```
   /
   ├── index.html
   ├── manifest.json
   ├── sw.js
   └── icons/
       ├── icon-72.png
       ├── icon-96.png
       ├── icon-120.png
       ├── icon-128.png
       ├── icon-144.png
       ├── icon-152.png
       ├── icon-180.png
       ├── icon-192.png
       ├── icon-384.png
       └── icon-512.png
   ```

## Hosting Gratuito

Puoi usare uno di questi servizi gratuiti:

### GitHub Pages
1. Crea un repository su GitHub
2. Carica tutti i file
3. Vai in Settings → Pages → Attiva
4. L'app sarà su `https://tuousername.github.io/nomerepository`

### Netlify
1. Vai su netlify.com
2. Trascina la cartella sul sito
3. Ottieni subito un URL HTTPS

### Vercel
1. Vai su vercel.com
2. Connetti il repository o carica i file
3. Deploy automatico con HTTPS

## Installazione come App

### Android (Chrome)
1. Apri l'URL nel browser
2. Clicca "Aggiungi a schermata Home" o il banner che appare
3. L'app sarà installata come un'app nativa

### iOS (Safari)
1. Apri l'URL in Safari
2. Clicca l'icona "Condividi" (quadrato con freccia)
3. Seleziona "Aggiungi a schermata Home"
4. Dai un nome e conferma

## Funzionalità

- ✅ **Funziona offline** - Una volta caricata, funziona senza internet
- 🎤 **Controllo vocale** - Dì il nome della squadra per assegnare punti
- 🔊 **Annunci vocali** - Annuncia automaticamente il punteggio
- 🌍 **Multilingua** - Italiano, Inglese, Spagnolo, Francese
- 💾 **Salva preferenze** - Ricorda nomi squadre e impostazioni
- 📱 **Installabile** - Si comporta come un'app nativa

## Comandi Vocali

| Comando | Azione |
|---------|--------|
| "[Nome Squadra 1]" | Punto per squadra 1 |
| "[Nome Squadra 2]" | Punto per squadra 2 |
| "Annulla" / "Undo" | Annulla ultimo punto |
| "Nuova partita" / "Reset" | Ricomincia partita |

## Personalizzazione Icone

Le icone nella cartella `icons/` sono placeholder. Per icone personalizzate:
1. Crea un'immagine 512x512 pixel
2. Usa un tool come https://realfavicongenerator.net
3. Sostituisci i file nella cartella icons

---

Creato con ❤️ per gli amanti del padel
