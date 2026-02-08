# ProgettoGEP
# Cognome
Silva

# Nome
Lorenzo

# Titolo 
HoopLink

# Descrizione
Un'applicazione che permette agli utenti di creare o iscriversi a eventi sportivi di basket. Gli utenti possono registrarsi inserendo tutte le informazioni personali, comprese le certificazioni della società sportiva di appartenenza. In questo modo, altri utenti  possono visionare i profili e reclutarli per partecipare agli eventi.

# Problema
Risolve il problema del reclutamento di giocatori per eventi, sia amatoriali che competitivi, offrendo inoltre la possibilità di essere notati da enti o organizzazioni di livello superiore.

# Target
Giocatori under e senior, con la possibilità di appartenere o meno a una squadra affiliata alla FIBA 

# Competitors
CourtMapping,Revocruit,Basketball Finders,RecruitMe Sports

# Tagline
Organizza, gioca, connettiti

# Tecnologie
- Frontend: Flutter (sviluppo mobile multipiattaforma, Android/iOS).

- Backend: Node.js + Express (gestione utenti, tornei e messaggi).

- Database: PostgreSQL (archiviazione dati).

- Autenticazione: Firebase Authentication (login sicuro).

- Chat e notifiche: Socket.IO (comunicazione in tempo reale).

- Storage: Cloudinary (immagini e certificazioni).

- Hosting: Render / Firebase Hosting.

# Tabella di benchmarking
<img width="1722" height="540" alt="tabella benchmarking" src="https://github.com/user-attachments/assets/9b6be73a-facd-4131-8f1e-c0bb4e564fe1" />

# Requisiti

Funzionali
- Registrazione e login utente - Creazione di tornei di basket - Iscrizione ai tornei - Gestione profilo personale (dati giocatore) - Chat tra utenti - Visualizzazione tornei e partecipanti
Non funzionali
- Interfaccia semplice e intuitiva - Sicurezza dei dati - Tempi di risposta rapidi - Compatibilità con vari dispositivi - Database affidabile - Possibilità di aggiungere nuove funzioni
Di dominio
- Numero minimo/massimo di squadre per torneo - Regole base del basket - Ogni utente può appartenere a una sola squadra per torneo - Calendario o tabellone partite - Dati giocatore (ruolo, numero, altezza, ecc.)

# Diagramma UML Use Case 

http://yuml.me/cisti/GEP1.svg
<img width="1308" height="889" alt="UML use case " src="https://github.com/user-attachments/assets/7fb4ddbe-fc4d-4221-bff4-754a8818e9f8" />

# Timestamp JWT
1758872939

https://hooplink-connect.lovable.app

```mermaid

graph TD
    A["HoopLink<br/>(Sviluppo App Basket)"] --> B["Pianificazione & Analisi"]
    A --> C["Design UI/UX"]
    A --> D["Sviluppo Frontend (Flutter)"]
    A --> E["Sviluppo Backend (Node.js)"]
    A --> F["Database & Storage"]
    A --> G["Funzionalità Real-Time"]
    A --> H["Testing & Sicurezza"]
    A --> I["Deploy & Lancio"]
    A --> J["Supporto & Manutenzione"]

    %% Pianificazione
    B --> B1["Analisi requisiti funzionali"]
    B --> B2["Analisi competitor"]
    B --> B3["Definizione MVP"]
    B --> B4["Pianificazione sviluppo"]

    %% Design
    C --> C1["Wireframe schermate principali"]
    C --> C2["Prototipo navigazione app"]
    C --> C3["Test usabilità"]

    %% Frontend
    D --> D1["Schermata login/registrazione"]
    D --> D2["Dashboard eventi"]
    D --> D3["Creazione e iscrizione tornei"]
    D --> D4["Profilo giocatore"]
    D --> D5["Gestione squadre"]

    %% Backend
    E --> E1["API REST utenti"]
    E --> E2["API tornei ed eventi"]
    E --> E3["Gestione autenticazione Firebase"]
    E --> E4["Gestione ruoli e permessi"]

    %% Database
    F --> F1["Schema PostgreSQL"]
    F --> F2["Gestione dati giocatori"]
    F --> F3["Upload immagini e certificazioni (Cloudinary)"]

    %% Real-time
    G --> G1["Chat utenti (Socket.IO)"]
    G --> G2["Notifiche eventi"]
    G --> G3["Aggiornamenti partecipanti in tempo reale"]

    %% Testing
    H --> H1["Test funzionali"]
    H --> H2["Bug fixing"]
    H --> H3["Test performance e sicurezza"]

    %% Deploy
    I --> I1["Deploy backend su Render"]
    I --> I2["Build app Android/iOS"]
    I --> I3["Pubblicazione e documentazione"]

    %% Manutenzione
    J --> J1["Monitoraggio sistema"]
    J --> J2["Aggiornamenti funzionalità"]
    J --> J3["Supporto utenti"]
```
