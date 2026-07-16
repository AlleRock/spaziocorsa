# ⚙️ Spazio Corsa

**Spazio Corsa** è una Web App leggera, veloce e ottimizzata per dispositivi mobili, progettata per la gestione dell'inventario dei ricambi per biciclette da corsa. Consente di monitorare le scorte minime in officina ed evitare di rimanere senza componenti cruciali durante i montaggi.

## 🚀 Caratteristiche principali
- **Allerta Sottoscorta:** Monitoraggio visivo dei pezzi in esaurimento in base a soglie personalizzate.
- **Configurazione Flessibile:** Gestione di Scatole/Posizioni fisiche, Macro-Famiglie e Marchi con possibilità di modifica in tempo reale.
- **Import/Export Dati:** Esportazione e importazione dell'intero database in formato JSON per non perdere mai i dati.
- **Esportazione PDF:** Generazione di report dettagliati dell'inventario pronti da stampare o condividere.
- **Supporto PWA (Progressive Web App):** Installabile su smartphone e utilizzabile offline grazie al Service Worker integrato.

---

## 🛠️ Come pubblicare l'app su GitHub Pages (Gratis)

Puoi ospitare la tua applicazione direttamente su GitHub senza spendere un centesimo. Segui questi passaggi:

1. **Crea un Repository su GitHub:**
   - Vai su GitHub e crea un nuovo repository pubblico (chiamalo ad esempio `spazio-corsa`).

2. **Carica i File:**
   - Carica nella cartella principale (root) del repository i seguenti file:
     - `index.html`
     - `manifest.json`
     - `sw.js`
     - `logo.png`

3. **Abilita GitHub Pages:**
   - Entra nelle **Settings** (Impostazioni) del tuo repository su GitHub.
   - Nel menu a sinistra, clicca su **Pages** (sotto la sezione *Code and automation*).
   - Sotto la voce **Build and deployment**, imposta la sorgente su **Deploy from a branch**.
   - Sotto **Branch**, seleziona `main` (o `master`) e la cartella `/ (root)`. Clicca su **Save**.

4. **Accedi all'App:**
   - Attendi circa 1-2 minuti. GitHub ti mostrerà un link del tipo: `https://tuo-username.github.io/spazio-corsa/`.
   - Apri il link dal tuo smartphone (Safari su iOS o Chrome su Android) e seleziona **"Aggiungi a schermata Home"** per installare l'applicazione come PWA.