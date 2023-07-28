**Descrizione**

Questa cartella contiene il codice sorgente per il training di pazienti affetti da disturbi dello spettro
autistico (DSA). Nello specifico sono stati realizzati ed implementati due test molto diffusi:

• Test sulla Discriminazione uditiva
• Test della Torre di Londra (TOL)

**Requisiti di sistema**

Per eseguire correttamente il progetto, sono necessari i seguenti requisiti di sistema:

- **Sistema operativo**: Windows 10/11 (preferibile), Linux, MacOS (scarsa compatibilità a partire dai chip M1).
- **Software**: Choregraphe (consigliata versione 2.5)
- **Pacchetti**: PepperSDK

## **Struttura del progetto**
Il progetto è organizzato secondo la seguente struttura:

- **\SomministrazioneTest:** contiene il codice per Pepper implementato in Choregraphe per la somministrazione dei due test citati prima.
- **\fotoTOL:** cartella contenente le foto mostrate sul tablet di Pepper durante la somministrazione del test della Torre di Londra (TOL)

## **Utilizzo**
Per avviare il progetto, segui i seguenti passaggi:

1. Avvia il sw Choregraphe
1. Controlla che il tuo pc sia collegato sulla stessa sottorete di Pepper
1. Clicca sul pulsante verde “Connect to…” per connettere il Pepper
1. Comparirà una nuova schermata che permetterà di cliccare la tua versione di pepper e di poter immettere l’ip del robot e la sua porta. Consiglio di mantenere la porta settata su default. Mentre l’IP deve essere pronunciato da pepper, premendo il pulsante che ha sotto il tablet. 

1. Fatto questo, clicca sul pulsante “*Select*” e il programma verrà connesso al robot. Te ne accorgerai che sarà connesso solo quando noterai in alto a sinistra la frase (Connected to “IPaddres”). Il tuo robot poi apparirà nella **vista Robot** (Robot view).
1. A questo punto puoi caricare la cartella *SomministrazioneTest* in alto a sinistra cliccando l’icona della cartella (Open Project) e ti verrà caricato nel programma.
1. Il file specifico da aprire è **SomministrazioneTest.pml**


