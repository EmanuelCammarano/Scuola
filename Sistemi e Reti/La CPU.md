# CPU
Il microprocessore che costituisce l'hardware della CPU è un circuito integrato 
(chip) costituito da un monocristallo di silicio estremamente puro, sezionato finemente, e infine trattato ad altissime temperature in forni che contengono vari 
tipi di impurità allo stato gassoso. 
Queste impurità devono legarsi alla struttura reticolare del cristallo, influenzandone la capacità di condurre elettricità. 
Il silicio diventa così un semiconduttore ed è in grado quindi di resistere al passaggio di corrente elettrica in misura maggiore rispetto ai normali conduttori come il rame, ma non tanto quanto gli isolanti
### Parti della CPU
- L'unita di Controllo (CU, Control Unit)
- L'unita aritmetico logica (ALU, Arithmetic-Logic Unit)
- Registri di memoria (Per il controllo di istruzioni)
### Il ciclo macchina
Il funzionamento di una CPU inizia con il prelevamento dalla memoria del codice 
macchina dell'istruzione da eseguire; tale operazione viene eseguita dalla Control 
Unit. L'istruzione prelevata viene trasferita in un registro specifico e quindi codificata. Dopo aver codificato, cioè tradotto, l'istruzione, la CPU emette i segnali necessari all'esecuzione dell'istruzione
#### Fasi del ciclo macchina
1. fase di Fetch dell'istruzione.
2. fase di Decode dell'istruzione.
3. fase di Fetch degli operandi.
4. fase di Execute dell'istruzione.
#### Fetch dell'istruzione
Il termine Fetch significa **"prelevamento"** e identifica la fase in cui la CPU deve reperire l'istruzione da eseguire. 
In questa fase la CPU deve dialogare con la memoria RAM per ottenere il codice macchina dell'istruzione da eseguire.
#### Decode dell'istruzione
La fase di Decode rappresenta una fase interna alla CPU durante la quale avviene l'interpretazione dell'istruzione e 
la preparazione dei dispositivi necessari. In questa fase infatti, il codice macchina dell'istruzione viene codificato in 
operazioni da eseguire da parte della CPU. 
#### Fetch degli operandi
In base alla codifica dell'istruzione, il processore riconosce se è necessario o meno prelevare dalla memoria o da un 
registro interno un altro dato per completare l'esecuzione dell'istruzione. In tal caso viene eseguita un'operazione 
di lettura, dalla memoria o da un registro, chiamata appunto Fetch degli operandi
#### Execute dell'istruzione
Nella fase di Execute la Control Unit invia segnali che rappresentano opportuni comandi per l'esecuzione.
1. Preleva il codice macchina dell'istruzione di indirizzo uguale al contenuto del registro PC e inseriscilo nel registro IR.
2. Incrementa il contenuto del registro PC per puntare all'istruzione seguente.
3. Decodifica l'istruzione appena prelevata.
4. Se l'istruzione necessita di operandi, determina dove si trovano (memoria oppure registri).
5. Se necessario, preleva dalla memoria gli operandi e ponili nei registri della CPU.
6. Esegui l'istruzione.
7. Salva il risultato in un registro o in una cella di memoria.
8. Torna al punto 1.

Il processo di esecuzione di un'istruzione nella CPU avviene in quattro fasi principali:

1. Fetch: La CPU preleva l'istruzione dall'indirizzo memorizzato nel registro PC (Program Counter), in questo caso 0100h. L'istruzione è una sequenza di 6 byte, rappresentata come 00 05 0A 00 00 00. Questa istruzione viene poi inserita nel registro IR (Instruction Register).

2. Decode: In questa fase, il codice macchina contenuto nel registro IR viene decodificato per capire quale operazione deve essere eseguita.

3. Fetch degli operandi: La CPU recupera i dati necessari per l'operazione, in questo caso il valore dalla cella di memoria 000Ah, che è 05h.

4. Execute: La CPU esegue l'operazione. In questo esempio, il valore 05h viene sommato al contenuto del registro AL (che ipotizziamo sia 0Fh). Il risultato, 14h, viene poi memorizzato nuovamente nella cella 000A.

Queste operazioni richiedono diversi cicli del data path, la parte della CPU che gestisce l'elaborazione dei dati e include l'ALU (Arithmetic Logic Unit) e i registri. Ogni istruzione può richiedere uno o più cicli di data path per essere completata, e la velocità di questi cicli influisce sulla rapidità generale della CPU.
## Nell'architettura della CPU
L'architettura interna di un'unità centrale di elaborazione (CPU) può essere schematizzata:
1. unità di controllo (CU, Control Unit)
2. registro PC (Program Counter)
3. registro IR (Instruction Register)
4. registro PSW (Process Status Word)
5. ALU
6. registri generali
7. registro MAR (Memory Address Register)
8. registro MDR (Memory Data Register)
9. BUS di controllo
10. BUS indirizzi
11. BUS dati
### Il BUS interno
Si tratta di un BUS che collega tutti gli elementi che fanno parte della CPU. Sono generalmente BUS di controllo, senza distinzione tra dati e indirizzi e non sono da confondere con i BUS esterni.
### I Registri interni
Un registro può essere paragonato a una lavagna: è uno spazio dove si scrivono informazioni per un breve periodo. Al contrario, una cella di memoria è simile a un quaderno o a un blocco note, utilizzata per memorizzare informazioni per un tempo più lungo.

Ecco alcune differenze chiave:

- Registri: Non hanno un indirizzo, ma un nome specifico. Sono usati per operazioni rapide e temporanee.
- Celle di memoria: Hanno indirizzi specifici e possono memorizzare dati per periodi più lunghi.

Esistono anche due tipi di registri:

- Registri accessibili al programmatore: Questi possono essere utilizzati nei programmi e sono visibili al programmatore.

- Registri non accessibili al programmatore: Questi sono utilizzati internamente dalla CPU per operazioni di controllo e non possono essere modificati direttamente dal programmatore.

### MDR (Memory Data Register)
È un registro interno collegato direttamente al BUS dati attra-
verso un BUFFER BIDIREZIONALE TRI-STATE ().
Questo tipo di registro non è visibile al programmatore e con-
tiene i dati che la CPU vuole inviare oppure ricevere dalla memo-
ria o dai dispositivi di I/O.

### MAR (Memory Address Register)
Il MAR (Memory Address Register) è un registro interno della CPU, collegato direttamente al BUS degli indirizzi. Non è visibile al programmatore e ha un ruolo fondamentale nella gestione della memoria.
il MAR è essenziale per indirizzare correttamente le operazioni di lettura e scrittura in memoria, assicurando che la CPU possa accedere ai dati necessari per eseguire le istruzioni.

### IR (Instruction Register)
È il registro interno che riceve il codice operativo dell9istruzione prelevata durante la fase di fetch. È invisibile al 
programmatore e contiene temporaneamente il codice operativo dell9istruzione durante la sua codifica.

