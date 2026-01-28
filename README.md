# 📅 TSC Turni - Cloud Edition (v3.0 - Magic & Kittens Update)

Web App per la gestione operativa dei turni del **Tabacchi San Clemente**, aggiornata con **sincronizzazione Cloud**, interfaccia **Glassmorphism** e nuove animazioni interattive.

Progettata per semplificare la comunicazione tra Amministrazione e Dipendenti con un tocco di magia.

## ✨ Novità della Versione 3.0

* **🎨 UI Premium:** Design completamente ridisegnato in stile "Glassmorphism" con sfocature, ombre e pulsanti 3D.
* **🧙‍♂️ Magic Auto-Fill:** Generazione automatica dei turni con animazione "Esplosione Magica" dalla bacchetta.
* **🐱 Kitten Reset:** Vuoi cancellare tutto? Preparati a una pioggia di gattini nel cestino!
* **🌈 Inclusività:** Nuove opzioni per gli Avatar. Nelle impostazioni è possibile scegliere il sesso (Uomo 👨, Donna 👩, Non-Binary 🧑) per ogni dipendente.
* **💾 Smart Auto-Save:** Salvataggio automatico intelligente per evitare errori durante l'inserimento rapido.
* **🚫 Zero Browser Alerts:** Tutti i messaggi di conferma (accetta, rifiuta, conflitti) sono ora gestiti tramite modali personalizzati eleganti.

## 🚀 Funzionalità Principali

* **☁️ Cloud Sync (JSONBin):** I dati sono sincronizzati in tempo reale. Le modifiche dell'Admin appaiono istantaneamente sui telefoni dei dipendenti.
* **👮 Interfaccia Admin (`admin.html`):**
    * Gestione completa turni (click singolo/doppio).
    * Gestione richieste con feedback visivo immediato (Modali Verde/Rosso).
    * Risoluzione conflitti guidata.
* **👷 Interfaccia Client (`index.html`):**
    * Visualizzazione turni in sola lettura.
    * Sistema di richiesta ferie/cambio turno semplificato.
    * Icone dinamiche basate sulla scelta di genere.
* **🚩 Sistema Segnalazioni:**
    * **Controllo Conflitti:** Il sistema avvisa se un collega è già assente.
    * **Workflow:** L'Admin accetta (aggiornamento automatico calendario) o rifiuta.
* **🖨️ Stampa A4:** Layout pulito e ottimizzato per la stampa cartacea (senza elementi dell'interfaccia).

## 📦 Installazione / Accesso

L'applicazione è accessibile via browser (non richiede installazione dagli store).

### 👮 Per l'Amministratore
Link privato per la gestione (**Salvare nei preferiti e non condividere**):
👉 `https://marchi2005.github.io/TSC-Turni/admin.html`

### 👷 Per i Dipendenti
Link pubblico da distribuire allo staff:
👉 `https://marchi2005.github.io/TSC-Turni/`

**Installazione su Smartphone (PWA):**
1.  Apri il link con **Chrome** (Android) o **Safari** (iOS).
2.  Premi il tasto Condividi (iOS) o Menu (Android).
3.  Seleziona **"Aggiungi a schermata Home"**.

## 🛠️ Tecnologie

* **Frontend:** HTML5, CSS3 (CSS Variables, Flexbox, Grid, Animations), Vanilla JS.
* **Backend/Database:** JSONBin.io (API REST).
* **Hosting:** GitHub Pages.

---
*Developed for Tabacchi San Clemente Caffè*