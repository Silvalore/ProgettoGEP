# HoopLink
Autore: Silva Lorenzo

# Descrizione
Un'applicazione che permette agli utenti di creare o iscriversi a eventi sportivi di basket. Gli utenti possono registrarsi inserendo tutte le informazioni personali, comprese le certificazioni della società sportiva di appartenenza. In questo modo, altri utenti  possono visionare i profili e reclutarli per partecipare agli eventi.

# Problema
Risolve il problema del reclutamento di giocatori per eventi, sia amatoriali che competitivi, offrendo inoltre la possibilità di essere notati da enti o organizzazioni di livello superiore.

# Target
Giocatori under e senior, con la possibilità di appartenere o meno a una squadra affiliata alla FIBA 

# Competitors
- CourtMapping
- Revocruit
- Basketball Finders
- RecruitMe Sports

# Tabella comparativa   
| Caratteristica              | HoopLink                        | CourtMapping          | Revocruit           | Basketball Finders  | RecruitMe Sports      |
| --------------------------- | ------------------------------- | --------------------- | ------------------- | ------------------- | --------------------- |
| 🎯 Focus principale         | Eventi + community + recruiting | Networking e scouting | Recruiting sportivo | Placement giocatori | Recruiting accademico |
| 🏀 Specifico per basket     | ✅ Sì                            | ✅ Sì                  | ❌ Multi-sport       | ✅ Sì                | ❌ Multi-sport         |
| 📅 Creazione eventi         | ✅ Sì                            | ⚠️ Limitato           | ❌ No                | ❌ No                | ❌ No                  |
| 👥 Iscrizione a partite     | ✅ Sì                            | ❌ No                  | ❌ No                | ❌ No                | ❌ No                  |
| 👤 Profilo giocatore        | ✅ Completo                      | ✅ Completo            | ✅ Completo          | ⚠️ Base             | ✅ Completo            |
| 💬 Chat tra utenti          | ✅ Sì                            | ⚠️ Limitata           | ❌ No                | ❌ No                | ❌ No                  |
| 🌍 Community locale         | ✅ Sì                            | ❌ No                  | ❌ No                | ❌ No                | ❌ No                  |
| 🎥 Video / highlight        | ⚠️ Possibile                    | ✅ Sì                  | ✅ Sì                | ✅ Sì                | ✅ Sì                  |
| 🧑‍🏫 Connessione con coach | ⚠️ Sì                           | ✅ Sì                  | ✅ Sì                | ✅ Sì                | ✅ Sì                  |
| 💸 Prezzo medio             | 🟢 Basso (3–5€/mese)            | 🔴 Alto (~40$/mese)   | 🔴 Medio/Alto       | 🔴 Alto             | 🔴 Alto               |
| 🚀 Facilità d’uso           | 🟢 Alta                         | ⚠️ Media              | ⚠️ Media            | ⚠️ Media            | ⚠️ Media              |


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


# Requisiti

Funzionali
- Registrazione e login utente - Creazione di tornei di basket - Iscrizione ai tornei - Gestione profilo personale (dati giocatore) - Chat tra utenti - Visualizzazione tornei e partecipanti

User story
  
| Attore        | Requisito / Azione                       | Beneficio                                                  |
| ------------- | ---------------------------------------- | ---------------------------------------------------------- |
| Utente        | Registrarsi e creare un profilo sportivo | Mostrare le proprie informazioni e partecipare agli eventi |
| Giocatore     | Cercare eventi e tornei                  | Trovare facilmente partite a cui partecipare               |
| Giocatore     | Iscriversi a eventi                      | Giocare e prendere parte alle partite                      |
| Organizzatore | Creare eventi o tornei                   | Trovare giocatori e organizzare partite                    |
| Utente        | Visualizzare profili di altri giocatori  | Scegliere con chi giocare o chi invitare                   |
| Utente        | Utilizzare la chat                       | Comunicare e organizzarsi con altri giocatori              |
| Giocatore     | Rendere visibile il proprio profilo      | Essere notato da squadre o organizzatori                   |
| Organizzatore | Gestire partecipanti e squadre           | Organizzare eventi in modo semplice ed efficace            |
| Utente        | Ricevere notifiche sugli eventi          | Restare aggiornato su inviti e modifiche                   |
| Giocatore     | Caricare certificazioni e dati sportivi  | Aumentare affidabilità e credibilità                       |



Non funzionali
- Interfaccia semplice e intuitiva - Sicurezza dei dati - Tempi di risposta rapidi - Compatibilità con vari dispositivi - Database affidabile - Possibilità di aggiungere nuove funzioni

Di dominio
- Numero minimo/massimo di squadre per torneo - Regole base del basket - Ogni utente può appartenere a una sola squadra per torneo - Calendario o tabellone partite - Dati giocatore (ruolo, numero, altezza, ecc.)

# Diagramma UML Use Case 

http://yuml.me/cisti/GEP1.svg
<img width="1308" height="889" alt="UML use case " src="https://github.com/user-attachments/assets/7fb4ddbe-fc4d-4221-bff4-754a8818e9f8" />

# Timestamp JWT
1758872939

# Lovable web page
https://hooplink-connect.lovable.app
<img width="1316" height="927" alt="image" src="https://github.com/user-attachments/assets/a8e0c34a-abc8-4354-96b6-a069139ebc31" />
<img width="962" height="766" alt="image" src="https://github.com/user-attachments/assets/020992b5-01bc-44da-9c65-81cc6dd516a6" />
<img width="1229" height="882" alt="image" src="https://github.com/user-attachments/assets/a380aef2-1dd7-488c-9597-2088cf4391c0" />


# Elevator pitch

Ciao, sono Lorenzo Silva, fondatore di HoopLink.
Sapete che uno dei principali problemi nel basket amatoriale è la difficoltà di trovare giocatori, organizzare partite e dare visibilità agli atleti? Oggi la maggior parte degli eventi viene gestita tramite chat o social, in modo poco efficiente.

Abbiamo creato HoopLink per risolvere questo problema.

HoopLink è una piattaforma mobile che permette ai giocatori di creare e partecipare a eventi, mostrare il proprio profilo sportivo e comunicare in tempo reale con squadre e organizzatori. A differenza delle soluzioni generiche, HoopLink è progettata esclusivamente per il basket e integra organizzazione, reclutamento e community in un’unica applicazione.

L’infrastruttura tecnologica è già progettata, con app multipiattaforma, backend scalabile, autenticazione sicura e sistema di notifiche e chat in tempo reale. Il modello di business è freemium, con funzionalità premium per maggiore visibilità e strumenti dedicati a società e organizzatori.

Oggi cerchiamo un investimento iniziale di 50.000€ per completare lo sviluppo dell’MVP, avviare il lancio sul mercato e avviare le prime attività di promozione.

Il nostro obiettivo è diventare il punto di riferimento digitale per la community del basket.
Siete pronti a connettere con noi il futuro del basket?


<img width="800" height="449" alt="image" src="https://github.com/user-attachments/assets/92c994d1-af1c-425b-80f7-ad56a72dcd0b" />
<img width="802" height="446" alt="image" src="https://github.com/user-attachments/assets/09609373-4218-4602-85c8-22532a5fb7ea" />
<img width="799" height="450" alt="image" src="https://github.com/user-attachments/assets/603bbcff-b9f6-4729-b4b2-33e82cc3ae17" />
<img width="803" height="451" alt="image" src="https://github.com/user-attachments/assets/c7f3295a-03f3-4ea2-804e-900cf8d1559f" />
<img width="799" height="454" alt="image" src="https://github.com/user-attachments/assets/904763c2-1f0e-4d00-ba20-862f08d6e9f6" />
<img width="800" height="451" alt="image" src="https://github.com/user-attachments/assets/e21590fb-3ef7-4373-a584-b2600bdadfaa" />
<img width="797" height="451" alt="image" src="https://github.com/user-attachments/assets/7eb2fa87-6f5e-4360-a640-9bb8337fcfbc" />
<img width="805" height="447" alt="image" src="https://github.com/user-attachments/assets/1117eed1-dd1a-4436-9b92-ab66a06f3d79" />
<img width="803" height="450" alt="image" src="https://github.com/user-attachments/assets/669ab35e-4e00-4ce3-8e86-f13d31c73fc0" />
<img width="799" height="456" alt="image" src="https://github.com/user-attachments/assets/10b7ca6c-d383-4256-a681-e47803aeabf9" />


# HoopLink WBS
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
# HoopLink Cronoprogramma

```mermaid
gantt
    title HoopLink - Cronoprogramma Sviluppo MVP (6 mesi)
    dateFormat  YYYY-MM-DD
    axisFormat  %b

    section Analisi e Pianificazione
    Analisi requisiti           :a1, 2026-01-01, 2w
    Definizione MVP             :a2, after a1, 2w

    section Design UI/UX
    Wireframe                   :b1, after a2, 2w
    Prototipi e mockup          :b2, after b1, 2w

    section Backend
    Progettazione database      :c1, after a2, 3w
    Sviluppo API REST           :c2, after c1, 4w
    Autenticazione Firebase     :c3, after c2, 2w
    Chat e notifiche            :c4, after c3, 3w

    section Frontend (Flutter)
    Struttura app               :d1, after b1, 3w
    UI schermate principali     :d2, after d1, 4w
    Integrazione API            :d3, after c2, 4w

    section Testing
    Test funzionali             :e1, after d3, 2w
    Bug fixing                  :e2, after e1, 2w

    section Deploy e Lancio
    Deploy backend              :f1, after e2, 1w
    Pubblicazione app           :f2, after f1, 1w
```
