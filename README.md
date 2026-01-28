# 📅 TSC Turni - Shift Management System (v3.6)

Piattaforma Web App (PWA) per la gestione operativa dei turni del **Tabacchi San Clemente**, dotata di **sincronizzazione Cloud in tempo reale** e interfaccia utente responsive ottimizzata per dispositivi mobili.

Il sistema facilita il coordinamento tra l'Amministrazione e il Personale, gestendo l'assegnazione dei turni, le ferie e le richieste di sostituzione con un flusso di lavoro automatizzato.

## ✨ Novità della Versione 3.1ì6 (International & UI Update)

* **🌐 Supporto Multilingua (i18n):** L'intera interfaccia è ora localizzata in **Italiano**, **Inglese** e **Spagnolo**, con rilevamento automatico e persistenza delle preferenze utente.
* **📱 PWA Avanzata & Icone Dedicate:** Implementazione di icone applicative distinte per **Admin** e **Dipendenti** per migliorare la riconoscibilità sulla Home Screen. Supporto nativo per **Dark Mode** e icone iOS trasparenti.
* **🎨 UI/UX Refactoring:** Interfaccia "Glassmorphism" modernizzata per migliorare la leggibilità e l'accessibilità, con modali di conferma nativi (eliminazione degli alert del browser).
* **🤖 Algoritmo di Assegnazione Automatica:** Funzione "Auto-Fill" ottimizzata per riempire i turni vuoti rispettando la rotazione e le festività.

## 🚀 Funzionalità Principali

### ☁️ Core System
* **Cloud Sync (JSONBin):** Architettura serverless che garantisce la sincronizzazione istantanea dei dati tra tutti i dispositivi connessi.
* **Smart Auto-Save:** Sistema di salvataggio automatico con debounce per prevenire la perdita di dati e ridurre le chiamate API.

### 👮 Modulo Amministratore (`admin.html`)
* **Gestione Turni Granulare:** Assegnazione rapida tramite interazione click/tap (Ciclo: Mattina / Pomeriggio / Entrambi).
* **Gestione Richieste:** Dashboard centralizzata per approvare o rifiutare le richieste di ferie/cambio turno con risoluzione automatica dei conflitti.
* **Profili Utente Personalizzabili:** Configurazione anagrafica (Nome, Colore) e impostazione di genere (M/F/NB) per l'adattamento dinamico degli avatar.
* **Stampa Report:** Layout di stampa A4 ottimizzato per la generazione di copie cartacee del calendario mensile.

### 👷 Modulo Dipendenti (`index.html`)
* **Visualizzazione Read-Only:** Accesso al calendario turni in modalità sola lettura.
* **Sistema di Segnalazione:** Interfaccia semplificata per inviare richieste di:
    * Assenza (Mattina/Pomeriggio/Giornaliera).
    * Cambio Turno.
* **Stato Richieste:** Feedback visivo sullo stato della richiesta (In Attesa / Accettata / Rifiutata).

## 📦 Installazione e Accesso

L'applicazione è distribuita come Progressive Web App (PWA) e non richiede installazione tramite Store.

### 🔗 Link di Accesso

* **Pannello Amministratore (Accesso Riservato):**
    👉 `https://marchi2005.github.io/TSC-Turni/admin.html`
    *(Salvare questo link e non condividerlo con il personale)*

* **Portale Dipendenti (Accesso Pubblico):**
    👉 `https://marchi2005.github.io/TSC-Turni/`

### 📲 Installazione su Dispositivi Mobili
Per un'esperienza ottimale, si consiglia di aggiungere la Web App alla schermata Home:
1.  Aprire il link in **Chrome** (Android) o **Safari** (iOS).
2.  Selezionare "Aggiungi a schermata Home" dal menu del browser.
3.  L'app verrà installata con l'icona specifica (**Admin** o **Dipendenti**) in base al link utilizzato.

## 🛠️ Stack Tecnologico

* **Frontend:** HTML5, CSS3 (CSS Variables, Flexbox, Grid), Vanilla JavaScript (ES6+).
* **Backend/Storage:** JSONBin.io (REST API).
* **Localizzazione:** Implementazione JS custom basata su dizionari JSON.
* **Hosting:** GitHub Pages.

---
*Developed for Tabacchi San Clemente Caffè*
