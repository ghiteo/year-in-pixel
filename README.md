# 🟠 Strava Year in Pixels

> 🇮🇹 [Italiano](#italiano) | 🇬🇧 [English](#english)

---

## Italiano

### 📌 Cos'è

**Strava Year in Pixels** è uno strumento web per visualizzare le tue attività Strava in una griglia annuale colorata — un pixel (cerchio) per ogni giorno dell'anno.

Ogni tipo di attività ha il suo colore. I giorni di riposo restano bianchi. Se in un giorno hai fatto più attività, il cerchio si divide a fetta di torta proporzionalmente ai km.


### ✨ Funzionalità

- 📅 Griglia **mesi × giorni** per l'intero anno
- 🎨 Colore unico per ogni tipo di attività (corsa, bici, nuoto, ecc.)
- 🥧 Cerchio diviso a torta per giorni con attività multiple
- 📊 Statistiche: giorni attivi, km totali, dislivello, streak più lungo
- 🗓️ Supporto **multi-anno** — visualizza tutti gli anni in un'unica immagine
- 💾 Download PNG con sfondo bianco o trasparente
- 🇮🇹 Supporto nativo per CSV Strava in italiano

---

### 🚀 Come si usa

#### 1. Esporta i tuoi dati da Strava
1. Vai su [strava.com](https://www.strava.com) → **Impostazioni** → **Il mio account**
2. Clicca su **"Scarica o elimina i tuoi dati Strava"**
3. Seleziona **"Richiedi i tuoi archivi"**
4. Riceverai un'email con un link per scaricare un file `.zip`
5. Decomprimi il file e cerca `activities.csv`

#### 2. Apri la pagina web
Vai su: https://ghiteo.github.io/year-in-pixel/

#### 3. Carica il CSV
- Trascina il file `activities.csv` nell'area di upload
- Oppure clicca sull'area per selezionarlo manualmente

#### 4. Esplora e scarica
- Seleziona l'anno dal menu a tendina
- Scarica la griglia come PNG (singolo anno o tutti gli anni)

---

### 📋 Formato CSV supportato

Il file `activities.csv` esportato da Strava in italiano. Le colonne utilizzate sono:

| Colonna | Indice | Contenuto |
|---------|--------|-----------|
| Data attività | — | Formato: `1 gen 2025` |
| Distanza | idx 17 | Metri → convertiti in km |
| Dislivello | idx 20 | Metri D+ |
| Tipo attività | — | Es. `Corsa`, `Ciclismo`, `Nuoto` |

---

### 🛠️ Tecnologie

- HTML5 / CSS3 / JavaScript vanilla
- Canvas API per il rendering della griglia
- Nessuna dipendenza esterna — funziona completamente nel browser

---

### 🤝 Contribuire

Contributi, segnalazioni di bug e suggerimenti sono benvenuti!

1. Fai un **fork** del repository
2. Crea un branch: `git checkout -b feature/nuova-funzione`
3. Committa le modifiche: `git commit -m 'Aggiunge nuova funzione'`
4. Fai push: `git push origin feature/nuova-funzione`
5. Apri una **Pull Request**

Per segnalare bug o richiedere funzionalità, apri una [Issue](../../issues).

---

### 📄 Licenza

Questo progetto è distribuito sotto licenza **MIT** — libero da usare, modificare e distribuire.

---
---

## English

### 📌 What is it

**Strava Year in Pixels** is a web tool to visualize your Strava activities as a colorful annual grid — one pixel (circle) per day of the year.

Each activity type has its own color. Rest days stay white. If you did multiple activities in one day, the circle is split into pie slices proportional to the km of each activity.

---

### ✨ Features

- 📅 **Month × day** grid for the entire year
- 🎨 Unique color per activity type (running, cycling, swimming, etc.)
- 🥧 Pie-split circle for days with multiple activities
- 📊 Stats: active days, total km, elevation gain, longest streak
- 🗓️ **Multi-year** support — view all years in a single image
- 💾 PNG download with white or transparent background
- 🇮🇹 Native support for Strava CSV exported in Italian

---

### 🚀 How to use

#### 1. Export your data from Strava
1. Go to [strava.com](https://www.strava.com) → **Settings** → **My Account**
2. Click **"Download or Delete Your Strava Data"**
3. Select **"Request Your Archive"**
4. You'll receive an email with a download link for a `.zip` file
5. Unzip the file and look for `activities.csv`

#### 2. Open the web page
Go to: [**[https://yourusername.github.io/your-repo/](https://yourusername.github.io/your-repo/)**](https://ghiteo.github.io/year-in-pixel/)

#### 3. Upload the CSV
- Drag and drop `activities.csv` into the upload area
- Or click the area to select it manually

#### 4. Explore and download
- Select the year from the dropdown menu
- Download the grid as PNG (single year or all years)

---

### 📋 Supported CSV format

The `activities.csv` file exported from Strava in Italian. Columns used:

| Column | Index | Content |
|--------|-------|---------|
| Activity date | — | Format: `1 gen 2025` |
| Distance | idx 17 | Meters → converted to km |
| Elevation | idx 20 | Meters D+ |
| Activity type | — | E.g. `Corsa`, `Ciclismo`, `Nuoto` |

> ⚠️ **Note:** Currently the app supports Strava CSV exported in **Italian only**. English CSV support is planned.

---

### 🛠️ Tech stack

- HTML5 / CSS3 / Vanilla JavaScript
- Canvas API for grid rendering
- Zero external dependencies — runs entirely in the browser

---

### 🤝 Contributing

Contributions, bug reports and feature requests are welcome!

1. **Fork** the repository
2. Create a branch: `git checkout -b feature/new-feature`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push: `git push origin feature/new-feature`
5. Open a **Pull Request**

To report bugs or request features, open an [Issue](../../issues).

---

### 💡 Roadmap ideas

- [ ] Support for English Strava CSV export
- [ ] Dark mode
- [ ] Weekly view
- [ ] Shareable link with embedded data
- [ ] Mobile-optimized layout

---

### 📄 License

This project is licensed under the **MIT License** — free to use, modify and distribute.

---

*Made with 🧡 by a Strava enthusiast*
