# 🚀 Come Pubblicare Affari Tuoi su GitHub Pages

Questa guida ti mostra come mettere online il gioco Affari Tuoi su GitHub in pochi minuti!

---

## 📋 Prerequisiti

- Un account GitHub (gratuito su [github.com](https://github.com))
- Git installato sul tuo computer (opzionale, puoi usare l'interfaccia web)

---

## 🌐 Metodo 1: Upload Web (Più Facile)

### Passo 1: Crea il Repository

1. Vai su [github.com](https://github.com) e accedi
2. Click sul pulsante **"New"** (verde) o vai su [github.com/new](https://github.com/new)
3. Compila i campi:
   - **Repository name:** `affari-tuoi` (o il nome che preferisci)
   - **Description:** `Gioco Affari Tuoi - Edizione 2025-2026 PWA`
   - Seleziona **Public** (per GitHub Pages gratuito)
   - ✅ Spunta **"Add a README file"**
4. Click su **"Create repository"**

### Passo 2: Carica i File

1. Nel tuo nuovo repository, click su **"Add file"** → **"Upload files"**
2. Trascina TUTTI i file di questa cartella:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`
   - `.gitignore`
3. Scrivi un messaggio: `"Initial commit - Affari Tuoi PWA"`
4. Click su **"Commit changes"**

### Passo 3: Attiva GitHub Pages

1. Nel tuo repository, vai su **Settings** (in alto)
2. Nel menu laterale sinistro, click su **"Pages"**
3. Sotto **"Source"**, seleziona:
   - Branch: **main** (o master)
   - Folder: **/ (root)**
4. Click su **"Save"**
5. Aspetta 1-2 minuti... 🎉

### Passo 4: Accedi al Gioco!

Il tuo gioco sarà disponibile su:
```
https://tuo-username.github.io/affari-tuoi
```

Sostituisci `tuo-username` con il tuo nome utente GitHub!

---

## 💻 Metodo 2: Git da Terminale (Per Sviluppatori)

### Passo 1: Inizializza il Repository

```bash
cd /percorso/alla/cartella/affari-tuoi-github
git init
git add .
git commit -m "Initial commit - Affari Tuoi PWA"
```

### Passo 2: Collega a GitHub

```bash
# Crea il repository su GitHub (via web o GitHub CLI)
# Poi esegui:
git remote add origin https://github.com/tuo-username/affari-tuoi.git
git branch -M main
git push -u origin main
```

### Passo 3: Attiva GitHub Pages

Segui il **Passo 3** del Metodo 1 (via interfaccia web)

---

## 🔧 Aggiornamenti Futuri

Quando modifichi il gioco:

### Via Web:
1. Vai nel repository su GitHub
2. Click sul file da modificare
3. Click sull'icona della matita ✏️
4. Modifica il file
5. **"Commit changes"** in fondo

### Via Git:
```bash
git add .
git commit -m "Descrizione delle modifiche"
git push
```

GitHub Pages si aggiorna automaticamente in 1-2 minuti! ⚡

---

## 🎨 Personalizzazione URL

### Opzione 1: Dominio GitHub
```
https://tuo-username.github.io/affari-tuoi
```
✅ Gratuito e immediato

### Opzione 2: Dominio Personalizzato
1. Compra un dominio (es. `affari-tuoi.com`)
2. In **Settings → Pages → Custom domain**
3. Inserisci il tuo dominio
4. Configura i DNS secondo le istruzioni GitHub

---

## 🐛 Risoluzione Problemi

### Il sito non appare dopo l'attivazione
- Aspetta 2-3 minuti (GitHub impiega tempo)
- Controlla che il branch sia "main" o "master"
- Ricarica la pagina con CTRL+F5 (cancella cache)

### Errore 404 Not Found
- Assicurati che il file si chiami `index.html`
- Verifica che tutti i file siano nella root del repository
- Controlla che GitHub Pages sia attivato in Settings

### Le icone non si caricano
- Controlla che i file `.png` siano caricati correttamente
- Verifica i nomi file: `icon-192.png` e `icon-512.png`

### La PWA non si installa
- Apri in **HTTPS** (GitHub Pages usa automaticamente HTTPS)
- Verifica che `manifest.json` e `service-worker.js` siano presenti
- Prova in modalità incognito

---

## 📊 Statistiche (Opzionale)

### Aggiungi Google Analytics:

1. Crea un account su [analytics.google.com](https://analytics.google.com)
2. Ottieni il tuo tracking ID
3. Aggiungi questo codice prima di `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

Sostituisci `GA_TRACKING_ID` con il tuo ID!

---

## 🔒 Sicurezza e Privacy

- ✅ GitHub Pages usa **HTTPS automaticamente**
- ✅ Il gioco **non raccoglie dati personali**
- ✅ Tutto funziona **offline** dopo il primo caricamento
- ✅ **Nessun cookie** di terze parti

---

## 🌍 Condivisione

Condividi il tuo gioco:
- **Link diretto:** `https://tuo-username.github.io/affari-tuoi`
- **QR Code:** Genera su [qr-code-generator.com](https://www.qr-code-generator.com/)
- **Social:** Condividi su Facebook, Twitter, WhatsApp

---

## 📱 Test PWA

Dopo la pubblicazione, testa su:

1. **Chrome (Desktop):** Cerca l'icona "Installa" nella barra
2. **Chrome (Android):** Menu → "Aggiungi a schermata Home"
3. **Safari (iOS):** Condividi → "Aggiungi a Home"

---

## 🎯 Checklist Pre-Pubblicazione

- [ ] Tutti i file caricati su GitHub
- [ ] Repository pubblico
- [ ] GitHub Pages attivato
- [ ] Aspettato 2-3 minuti
- [ ] Testato il link
- [ ] PWA installabile
- [ ] Funziona su mobile
- [ ] Musica e suoni funzionanti

---

## 💡 Consigli Extra

1. **README.md:** Già incluso con tutte le info
2. **Licenza:** Aggiungi un file LICENSE se vuoi (es. MIT)
3. **Issues:** Attiva gli Issues per ricevere feedback
4. **Star:** Chiedi agli amici di mettere una ⭐ al repository!

---

## 🆘 Supporto

Problemi? Opzioni:

1. **GitHub Issues:** Apri un issue nel repository
2. **GitHub Docs:** [docs.github.com/pages](https://docs.github.com/pages)
3. **Community:** [GitHub Community](https://github.community/)

---

## 🎉 Fatto!

Il tuo gioco Affari Tuoi è ora online e accessibile da tutto il mondo! 🌍

**Link da condividere:**
```
https://tuo-username.github.io/affari-tuoi
```

Buon divertimento! 🎮💰

---

*Creato da **Ciro Torelli** - Affari Tuoi Edizione 2025-2026*
