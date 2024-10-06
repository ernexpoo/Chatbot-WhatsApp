# Chatbot WhatsApp per Suggerimenti di Prodotti Amazon

## Descrizione

Questo progetto è un chatbot sviluppato per WhatsApp che fornisce suggerimenti personalizzati per prodotti Amazon in base alle preferenze degli utenti. Gli utenti possono interagire con il bot per ricevere raccomandazioni su prodotti, confronti e offerte speciali. Il chatbot è progettato per essere intuitivo e facile da usare, rendendo l'esperienza di acquisto più semplice e personalizzata.

## Funzionalità

- **Raccolta delle Preferenze**: Gli utenti possono impostare il loro budget e la categoria di prodotto di interesse.
- **Suggerimenti di Prodotti**: Il bot fornisce suggerimenti di prodotti Amazon basati sulle preferenze dell'utente.
- **Comparazione di Prodotti**: Gli utenti possono chiedere di confrontare diversi prodotti e ricevere informazioni dettagliate.
- **Iscrizione alla Newsletter**: Gli utenti possono iscriversi a una newsletter per ricevere aggiornamenti e offerte speciali.

## Tecnologie Utilizzate

- **Node.js**: Ambiente di esecuzione JavaScript per il server.
- **Express**: Framework per costruire applicazioni web in Node.js.
- **Twilio**: Servizio per inviare e ricevere messaggi su WhatsApp.
- **Axios**: Libreria per effettuare richieste HTTP.

## Requisiti

- Node.js (versione 12 o superiore)
- Un account Twilio con accesso alla Sandbox di WhatsApp
- Un account Amazon Associates per accedere all'API di Amazon

## Installazione

1. **Clona il repository**:
   ```bash
   git clone https://github.com/ernexpoo/Chatbot WhatsApp.git
   cd whatsapp-chatbot
   ```

2. **Installa le dipendenze**:
   ```bash
   npm install
   ```

3. **Configura le variabili d'ambiente**:
   - Crea un file `.env` nella radice del progetto e aggiungi le tue chiavi API di Twilio e Amazon.

4. **Esegui il server**:
   ```bash
   node server.js
   ```

5. **Avvia ngrok** per esporre il server locale:
   ```bash
   ngrok http 3000
   ```

6. **Aggiorna il webhook in Twilio**:
   - Copia l'URL fornito da ngrok e incollalo nel campo del webhook nella console di Twilio, aggiungendo `/webhook` alla fine.

## Utilizzo

- Invia un messaggio al tuo numero di WhatsApp collegato alla Sandbox di Twilio.
- Inizia la conversazione dicendo "preferenze" per impostare il tuo budget e la categoria di prodotto.
- Chiedi suggerimenti di prodotti o confronti per ricevere informazioni utili.

## Contribuire

Se desideri contribuire a questo progetto, sentiti libero di aprire una pull request o segnalare problemi.

## Contatti

Per domande o suggerimenti, puoi contattarmi all'indirizzo email: ernestodatri@gmail.com
