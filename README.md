# DocEats

## Hospital Menu

Prenotazione rapida e personalizzata del menù ospedaliero per medici e personale sanitario

## Descrizione Progetto

L'applicazione è progettata per semplificare la prenotazione dei pasti in ospedale, con particolare attenzione ai bisogni di medici e personale sanitario. Grazie a un'interfaccia semplice e intuitiva, l'app consente di selezionare i piatti preferiti, personalizzarli in base alle proprie esigenze alimentari e ricevere notifiche sulla disponibilità del pasto.

## Obiettivo del Progetto

All’interno degli ospedali, il personale medico deve spesso affrontare lunghe attese e code per prenotare i pasti, sottraendo tempo prezioso alle attività di cura dei pazienti. Questa applicazione mira a ottimizzare il processo, riducendo i tempi di attesa.

## Competitors
- **Meal Manager**: Soluzione per la gestione dei pasti in ambito ospedaliero, permette la selezione di menù dietetici, ma risulta meno agile per prenotazioni rapide
- **Cibos**: Piattaforma per l'ordinazione dei pasti negli ospedali, con limitazioni nella personalizzazione e nelle funzionalità di notifica per il personale

## Requisiti Funzionali

- **Registrazione e Accesso**
   - Creazione di un account con nome utente, email, password e codice fiscale
   - Possibilità di accedere con nome utente e password
   - Modifica successiva dell'account con possibilità di cambiare email, password e nome utente

- **Gestione del Menù**
   - Selezione del Menù: Possibilità di scegliere un menù predefinito, modificabile successivamente
   - Personalizzazione del Menù: Opzione per aggiungere modifiche in base a preferenze ( allergie, intolleranze, bevande, e orario di consumo)
   - Ordini Multipli: Possibilità di ordinare più menù

- **Gestione dei Pasti Disponibili**
   - Inserimento dei pasti disponibili da parte del personale di cucina

- **Prenotazione e Consegna**
   - Prenotazione Rapida: Permette di selezionare e prenotare il menù
   - Impostazione Orario di Consegna: Opzione per indicare l’orario in cui si desidera ricevere il pasto

- **Notifiche**
   - Notifica automatica quando il pasto è pronto
   - Notifica circa 2 minuti prima del pasto pronto per dare al personale il tempo di prepararsi

- **Interfaccia Utente**
   - Visualizzazione Menù con Icone: Ogni piatto è rappresentato con un’icona e include le opzioni di personalizzazione
   - Facilità di utilizzo: Design intuitivo e comprensibile per l’uso rapido da parte di tutti gli utenti

- **Disponibilità**
   - App scaricabile dagli store digitali (App Store, Google Play) <br /><br />


## Requisiti non Funzionali

- **Sicurezza**
   - Verifica che l’utente che richiede il menu sia un medico, tramite autenticazione e controllo delle credenziali
   - Protezione e sicurezza dei dati: i dati degli utenti non possono essere condivisi esternamente 
   - Accessibilità limitata all’orario specifico (5:00 - 19:30) 


- **Manutenibilità**
   - Manutenzione continua dell’applicazione tramite aggiornamenti regolari, per garantire efficienza e correzione di eventuali bug

- **Compatibilità**
   - Supporto per dispositivi Android e iOS 
   - Compatibilità con vari dispositivi 

- **Usabilità**
   - Tempi di risposta ottimali
   - Possibilità di gestione simultanea di più utenti <br /><br />


## Funzionalità di Dominio 

- **Accessibilità alla Rete Interna**
   - L’applicazione deve essere accessibile tramite la rete interna dell'ospedale

- **Riservatezza e Sicurezza dei Dati Sensibili**
   - Implementazione di meccanismi di autenticazione robusti, come login tramite user-id e password, per garantire che solo gli utenti autorizzati (es. medici, personale sanitario) possano accedere al menu
   - Protezione dei dati degli utenti attraverso in conformità con le normative di protezione dei dati (es. GDPR)

- **Integrazione con Sistemi Esistenti**
   - Il sistema deve essere compatibile e integrabile con altri sistemi informatici già in uso nell'ospedale, facilitando lo scambio di informazioni senza ridondanze

- **Gestione della Capacità e delle Performance**
   - Il sistema deve essere progettato per gestire un alto volume di utenti simultanei, garantendo tempi di risposta rapidi e affidabili, in particolare durante i picchi di utilizzo <br /><br /><br /><br />


## Diagramma

![immagine_2024-11-01_091024557](https://github.com/user-attachments/assets/268af09c-1ae2-44ba-b837-717f79685787)

