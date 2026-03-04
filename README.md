# 🎮 AFFARI TUOI - Progressive Web App

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![PWA](https://img.shields.io/badge/PWA-Ready-orange.svg)
![Mobile](https://img.shields.io/badge/Mobile-Optimized-success.svg)

**Edizione 2025-2026**  
Creato da **Ciro Torelli**

> 🎲 Gioca ad Affari Tuoi direttamente nel browser! Scegli i pacchi, ricevi offerte dal Dottore e vinci fino a €300.000!

## 🌐 [▶️ GIOCA ORA](https://tuonome.github.io/affari-tuoi)

*(Sostituisci con il tuo link GitHub Pages)*

---

## 🎯 Caratteristiche

- 🎮 **Gioco Completo** - Tutte le meccaniche di Affari Tuoi 2025-2026
- 📱 **PWA Installabile** - Gioca come un'app nativa
- 🎵 **Audio Sintetici** - Musica e effetti sonori integrati
- 📞 **Pop-up Dottore** - Offerte drammatiche con suono telefono
- 🏆 **Pop-up Vittoria** - Celebra le tue vincite con stile
- 💾 **Funziona Offline** - Gioca senza connessione
- 📱 **Mobile First** - Ottimizzato per smartphone
- 🎨 **Design Italiano** - Colori vivaci e animazioni fluide

---

## 🚀 Avvio Rapido

### Giocare Online
Visita semplicemente: [tuonome.github.io/affari-tuoi](https://tuonome.github.io/affari-tuoi)

### Installare come App

**📱 Android:**
1. Apri il link in Chrome
2. Menu → "Aggiungi a schermata Home"
3. Gioca! 🎉

**📱 iOS:**
1. Apri il link in Safari  
2. Condividi → "Aggiungi a Home"
3. Gioca! 🎉

**💻 Desktop:**
1. Apri in Chrome/Edge
2. Click sull'icona "Installa" nella barra
3. Gioca! 🎉

---

## 🎮 Come Si Gioca

1. **Scegli il tuo pacco** tra i 20 disponibili (ogni pacco rappresenta una regione italiana)
2. **Apri i pacchi** degli altri concorrenti uno alla volta
3. **Ricevi offerte** dal Dottore tramite pop-up con squillo telefono 📞
4. **Decidi:** Accettare l'offerta o continuare a giocare?
5. **Vinci** fino a €300.000 in gettoni d'oro!

### 🎁 Meccaniche Speciali

- **🎯 Trova Gennarino** - Aprilo nei primi 6 pacchi per vincere il Jackpot (parte da €1.000!)
- **⚫ Pacco Nero** - Contiene un valore segreto sorteggiato
- **🔄 Cambio Pacco** - Il Dottore ti propone di scambiare il tuo pacco
- **🌟 Regione Fortunata** - Indovina la regione estratta per bonus extra

---

## 📦 Struttura del Progetto

```
affari-tuoi/
├── index.html           # 🎮 File principale del gioco
├── manifest.json        # 📱 Configurazione PWA
├── service-worker.js    # 💾 Cache e funzionamento offline
├── icon-192.png         # 🖼️ Icona piccola (192x192)
├── icon-512.png         # 🖼️ Icona grande (512x512)
├── README.md            # 📄 Questo file
├── GITHUB_GUIDE.md      # 🚀 Guida pubblicazione GitHub
├── LICENSE              # 📜 Licenza MIT
└── .gitignore          # 🚫 File da ignorare
```

---

## 🛠️ Tecnologie Utilizzate

- **HTML5** - Struttura
- **CSS3** - Animazioni e design responsivo
- **JavaScript (ES6+)** - Logica di gioco
- **Web Audio API** - Musica e suoni sintetici
- **Service Worker** - Cache e offline
- **PWA Manifest** - Installabilità app

---

## 🎨 Design

- **Font:** Oswald (titoli) + Montserrat (testo)
- **Colori:** Palette italiana con oro (#FFD700), rosso (#DC143C), blu (#1E3A8A)
- **Animazioni:** Transizioni fluide, effetti glow, coriandoli
- **Layout:** Mobile-first con grid e flexbox

---

## 📱 Compatibilità

| Browser | Desktop | Mobile | PWA Install |
|---------|---------|--------|-------------|
| Chrome | ✅ | ✅ | ✅ |
| Edge | ✅ | ✅ | ✅ |
| Safari | ✅ | ✅ | ✅ |
| Firefox | ✅ | ✅ | ⚠️ |
| Samsung Internet | - | ✅ | ✅ |

*⚠️ Firefox supporta PWA con limitazioni*

---

## 🚀 Pubblicazione su GitHub Pages

Segui la guida dettagliata in [GITHUB_GUIDE.md](GITHUB_GUIDE.md)

**Passi rapidi:**
1. Carica tutti i file su GitHub
2. Settings → Pages → Source: main
3. Aspetta 2 minuti
4. Visita: `https://tuo-username.github.io/affari-tuoi`

---

## 🔊 Audio

Il gioco include un sistema audio completo con **Web Audio API**:

- 🎵 **Musica di sottofondo** - Melodia piacevole in loop continuo
- 📞 **Squillo telefono** - Quando il Dottore chiama con un'offerta
- 🎊 **Effetti speciali** - Click, aperture pacchi, vittorie, jackpot
- 🔇 **Controlli** - Pulsanti in alto a destra per musica/suoni

*Nessun file audio esterno - tutto generato in tempo reale!*

---

## 🎯 Regolamento

Il gioco segue fedelmente il **Regolamento Ufficiale Affari Tuoi Edizione 2025-2026**:

- 20 pacchi con premi da 0€ a 300.000€
- Sequenza apertura: 6-3-3-3-3 pacchi per fase
- Offerte del Dottore calcolate sulla media dei premi rimasti
- Pacco Nero con valore sorteggiato
- Trova Gennarino con jackpot progressivo
- Premio minimo garantito: 50€ (per vincite 1-50€)

---

## 🐛 Segnalazione Bug

Hai trovato un bug? [Apri una Issue](https://github.com/tuonome/affari-tuoi/issues)

---

## 🤝 Contribuire

I contributi sono benvenuti! 

1. Fork il progetto
2. Crea un branch (`git checkout -b feature/MiglioriaFantastica`)
3. Commit le modifiche (`git commit -m 'Aggiunge funzione X'`)
4. Push al branch (`git push origin feature/MiglioriaFantastica`)
5. Apri una Pull Request

---

## 📄 Licenza

Questo progetto è sotto licenza **MIT** - vedi il file [LICENSE](LICENSE) per dettagli.

---

## 👤 Autore

**Ciro Torelli**

- 🎮 Creatore del gioco
- 💻 Sviluppo completo
- 🎨 Design e animazioni

---

## 🙏 Ringraziamenti

- RAI per il format originale Affari Tuoi
- Community open-source per gli strumenti utilizzati
- Beta tester per il feedback

---

## 📊 Statistiche

![GitHub stars](https://img.shields.io/github/stars/tuonome/affari-tuoi?style=social)
![GitHub forks](https://img.shields.io/github/forks/tuonome/affari-tuoi?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/tuonome/affari-tuoi?style=social)

---

## 🎉 Buon Divertimento!

Che la fortuna sia con te! 🍀💰

**[▶️ INIZIA A GIOCARE](https://tuonome.github.io/affari-tuoi)**

---

*Made with ❤️ in Italy by Ciro Torelli*

### **Android (Chrome/Edge):**

1. Apri il file `affari-tuoi.html` nel browser
2. Clicca sul menu (⋮) in alto a destra
3. Seleziona **"Aggiungi a schermata Home"** o **"Installa app"**
4. Conferma l'installazione
5. L'icona apparirà nella schermata home! 🎉

### **iPhone/iPad (Safari):**

1. Apri il file `affari-tuoi.html` in Safari
2. Tocca il pulsante **Condividi** (quadrato con freccia)
3. Scorri e tocca **"Aggiungi a Home"**
4. Dai un nome all'app e tocca **"Aggiungi"**
5. L'icona apparirà nella schermata home! 🎉

---

## 🌐 Come Installare su Desktop

### **Chrome/Edge:**

1. Apri `affari-tuoi.html` nel browser
2. Nella barra degli indirizzi, clicca sull'icona **"Installa"** (⊕)
3. Clicca **"Installa"** nella finestra di conferma
4. L'app si aprirà in una finestra dedicata! 🎉

---

## 📂 File Necessari per la PWA

Assicurati di avere tutti questi file nella stessa cartella:

```
📁 Affari Tuoi/
├── 📄 affari-tuoi.html       (File principale del gioco)
├── 📄 manifest.json           (Configurazione PWA)
├── 📄 service-worker.js       (Funzionamento offline)
├── 🖼️ icon-192.png            (Icona piccola)
├── 🖼️ icon-512.png            (Icona grande)
└── 📄 README.md               (Questo file)
```

---

## ✨ Caratteristiche della PWA

### ✅ **Funziona Offline**
Una volta caricato, puoi giocare anche senza connessione internet!

### ✅ **App Installabile**
Si installa come un'app vera sul telefono o computer

### ✅ **Schermo Intero**
L'app si apre senza barre del browser per un'esperienza immersiva

### ✅ **Icona Personalizzata**
Icona bella con pacco rosso e scritta "AT" in oro

### ✅ **Aggiornamenti Automatici**
Quando ricarichi l'app, scarica automaticamente gli aggiornamenti

---

## 🎮 Come Giocare

1. **Scegli il tuo pacco** tra i 20 disponibili
2. **Apri i pacchi** degli altri concorrenti
3. **Ricevi offerte** dal Dottore tramite pop-up con squillo telefono
4. **Decidi:** Accettare l'offerta o continuare?
5. **Vinci** fino a €300.000!

### 🎯 Bonus Speciali:
- **Trova Gennarino** nei primi 6 pacchi → Vinci il Jackpot!
- **Pacco Nero** → Valore segreto sorteggiato
- **Cambio Pacco** → Il Dottore ti propone di cambiare

---

## 🔊 Audio e Musica

- **🎵 Musica di sottofondo** - Melodia piacevole in loop
- **📞 Suono telefono** - Quando il Dottore chiama
- **🎊 Effetti sonori** - Click, aperture, vittorie
- **Controlli** in alto a destra per attivare/disattivare

---

## 🌐 Hosting Online

### **Opzione 1: GitHub Pages** (Gratuito)

1. Crea un repository su GitHub
2. Carica tutti i file
3. Vai su Settings → Pages
4. Seleziona "main" branch
5. Il tuo gioco sarà online su: `https://tuonome.github.io/affari-tuoi`

### **Opzione 2: Netlify** (Gratuito)

1. Vai su [netlify.com](https://netlify.com)
2. Trascina la cartella sul sito
3. Il gioco sarà online in pochi secondi!

### **Opzione 3: Vercel** (Gratuito)

1. Vai su [vercel.com](https://vercel.com)
2. Importa il progetto
3. Deploy automatico!

---

## 🐛 Risoluzione Problemi

### **L'app non si installa:**
- Assicurati che tutti i file siano nella stessa cartella
- Prova a ricaricare la pagina (CTRL+F5 o CMD+R)
- Controlla che il browser supporti le PWA

### **La musica non si sente:**
- Clicca sui pulsanti 🎵 e 🔊 in alto a destra
- Prova a premere "INIZIA A GIOCARE"
- Alcuni browser bloccano l'audio finché non interagisci

### **Il pop-up esce dallo schermo:**
- Già risolto! Ora ha scroll automatico
- Se persiste, ricarica la pagina

---

## 📱 Requisiti Browser

### ✅ **Supportati:**
- Chrome 67+
- Edge 79+
- Safari 11.1+
- Firefox 90+ (installazione limitata)
- Samsung Internet 8.2+
- Opera 54+

### ❌ **Non Supportati:**
- Internet Explorer (qualsiasi versione)
- Browser molto vecchi

---

## 🎨 Personalizzazione

Puoi modificare i colori nel file `affari-tuoi.html` nelle variabili CSS:

```css
:root {
    --gold: #FFD700;        /* Colore oro */
    --red: #DC143C;         /* Colore rosso */
    --blue: #1E3A8A;        /* Colore blu */
    --bg-dark: #0a0e27;     /* Sfondo */
}
```

---

## 📄 Licenza

Questo gioco è stato creato da **Ciro Torelli** per scopo educativo e di intrattenimento.  
Basato sul regolamento ufficiale di Affari Tuoi Edizione 2025-2026.

---

## 🆘 Supporto

Per problemi o domande, contatta il creatore:  
**Ciro Torelli**

---

## 🎉 Divertiti!

Buona fortuna con i tuoi affari! 💰🎲

**Ricorda:** È solo un gioco, gioca responsabilmente! 😊
