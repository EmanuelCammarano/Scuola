# La codifica degli algoritmi

Per affrontare la tematica sui **linguaggi per descrivere gli algoritmi** e le modalità con cui possiamo comunicarli sia agli esseri umani che alle macchine, partiamo da un concetto chiave: **l'algoritmo** è una sequenza ordinata e finita di istruzioni che, se seguite correttamente, risolvono un problema o eseguono un compito.

### Linguaggi per descrivere gli algoritmi

Esistono diversi modi per rappresentare un algoritmo, a seconda del destinatario (uomo o macchina).

1. **Linguaggi per l'uomo:**
    - **Linguaggio naturale (pseudocodice):** Questo è un modo informale per descrivere un algoritmo utilizzando il linguaggio comune. Non richiede formalismi rigidi e può essere adattato in vari modi. L'obiettivo è far capire i passi dell'algoritmo a una persona, senza preoccuparsi di dettagli tecnici come la sintassi di un linguaggio di programmazione. Ad esempio, la sequenza di passi per inviare un messaggio con il cellulare, descritta in pseudocodice, sarebbe:
        1. Accendi il telefono.
        2. Seleziona l'app di messaggistica.
        3. Trova il numero del destinatario (se presente) o inseriscilo manualmente.
        4. Scrivi il messaggio.
        5. Invia il messaggio.
    - **Rappresentazione grafica (flow chart o diagrammi di flusso):** È una rappresentazione visiva di un algoritmo tramite simboli grafici che rappresentano i vari passaggi. Ad esempio:
        - **Blocco di inizio/fine:** Indica l'inizio o la fine dell'algoritmo (forma ovale).
        - **Blocco di input/output:** Utilizzato per inserire o visualizzare dati (parallelogramma).
        - **Blocco di elaborazione:** Indica operazioni come calcoli o trasformazioni (rettangolo).
        - **Blocco di decisione:** Usato per prendere decisioni o ramificare l'algoritmo (rombo).
        
        ![2c61c235-1ba7-4523-9bf7-e991184990ad.png](La%20codifica%20degli%20algoritmi/2c61c235-1ba7-4523-9bf7-e991184990ad.png)
        
2. **Linguaggi per le macchine:**
Le macchine (come computer, smartphone, elettrodomestici ecc.) non possono comprendere i linguaggi naturali o i diagrammi di flusso. Per eseguire gli algoritmi su una macchina, dobbiamo tradurli in un **linguaggio di programmazione**.
    - **Codice binario (linguaggio macchina):** È il linguaggio nativo dei microprocessori, composto esclusivamente da 0 e 1. Ogni istruzione che un processore esegue è tradotta in una serie di bit. Tuttavia, scrivere direttamente in codice binario è estremamente complesso e poco pratico per gli esseri umani.
    - **Linguaggi di programmazione ad alto livello:** Sono stati sviluppati per facilitare la scrittura di algoritmi in un formato più comprensibile agli umani, mantenendo la capacità di essere tradotti in codice binario tramite compilatori o interpreti. Alcuni esempi di linguaggi di programmazione ad alto livello sono C, Python, Java, Pascal, ecc.
        - **Compilatori:** Programmi che traducono il codice scritto in un linguaggio di programmazione ad alto livello in codice macchina (binario). Questa traduzione genera il cosiddetto **codice eseguibile**, che può essere direttamente eseguito dal processore.
        - **Interpreti:** Diversamente dai compilatori, un interprete esegue le istruzioni di un programma linea per linea, senza tradurre l'intero programma in anticipo.

## Variabili

Le variabili sono contenitori in cui vengono memorizzati dati necessari per eseguire operazioni in un programma. Ogni variabile occupa uno spazio nella memoria RAM e può contenere informazioni che il programmatore usa e gestice. Per identificare e richiamare le variabili, il programmatore assegna loro un nome unico per ogni variabile.

## Le costanti

Esistono casi in cui alcune variabili contengono dati che devono cambiare e si mantengono uguali per tutta l’esecuzione del programma, queste si chiamano Costanti. Di solito si distinguono sempre dalle variabili nei programmi cosi che il programmatore non le cambi neanche per errore.

## Conclusione

Alcuni algoritmi richiedono anche altri tipi di operazioni: la **scelta** (selezione) tra due alternative e la **ripetizione** (iterazione) di una o più operazioni.
(guadare prossima pagina)

![image.png](La%20codifica%20degli%20algoritmi/image.png)