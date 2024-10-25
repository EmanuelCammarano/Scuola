# Il Computer

# Architettura dei Sistemi di elaborazione

Un sistema di elaborazione può essere definito come l’insieme di hardware e software.

L’obbiettivo dell’architettura è di avere le migliori prestazioni.

I componenti elettronici che formano un computer si dividono in due categorie principali:

- Porte logiche;
- Generatori di segnale.

## Porte Logiche

Le porte logiche sono circuiti elettronici in grado di svolgere operazioni logiche dell’algebra booleana, basata sui valori logici di VERO o FALSO (TRUE & FALSE), che corrispondono al passaggio e al non passaggio di corrente elettrica in tali circuiti basati sul sistema binario (0 e 1)

![image.png](Il%20Computer%20128b5f4b9b53808c8e6ed3ecefcd54be/0d3095b3-4cfe-4cc8-8fce-0793755bfcef.png)

## Generatori di Segnale

Attraverso l’assemblaggio delle porte logiche vengono realizzate macchine elementari, suddivise in combinatorie e sequenziali.

i generatori sequenziali sono componenti in grado di produrre un segnale periodico utile a sincronizzare gli elementi hardware

![image.png](Il%20Computer%20128b5f4b9b53808c8e6ed3ecefcd54be/03b4997f-527c-4810-af60-f0f7ba86be3a.png)

# Modello di von Neumann

Il modello di von Neumann descrive il comportamento di una
macchina che il suo inventore chiamò stored-program computer.

Questo modello è la struttura e il funzionamento della CPU.

- Computer: rappresenta la CPU che compie azioni di elaborazione come, per esempio, prelevare o modificare il contenuto della memoria (memory), prelevare o modificare le
informazioni dai dispositivi di input/output fornendo informazioni in uscita oppure leggendo informazioni in ingresso
- Stored-program: indica le istruzioni che la CPU deve eseguire. Tali istruzioni sono collocate  nella memoria del computer e l’insieme delle istruzioni rappresenta il programma (program) che deve essere eseguito.
Nella memoria risiedono, oltre alle istruzioni in linguaggio Assembly dei programmi in corso di esecuzione,
anche i dati sui quali tali programmi operano.

La frequenza si indica con: “GHz”, che indica i cicli di macchina.

# Diagramma a Blocchi

Questi concetti sono sintetizzati nel seguente diagramma a blocchi, determinato da von Neumann molti anni fa.
Il diagramma a blocchi evidenzia alcuni componenti principali:

- CPU
- Input/Output
- Memoria centrale

Tutti loro sono collegati dai “Bus”

![image.png](Il%20Computer%20128b5f4b9b53808c8e6ed3ecefcd54be/16566f96-d396-4266-9d7e-652a0e6408d4.png)

# La Memoria

La memoria si divide in più gruppi, questi sono:

- RAM (Random Access Memory)

È una memoria volatile, ovvero perde il suo contenuto quando viene spenta. Viene utilizzata per memorizzare temporaneamente dati e istruzioni durante l'esecuzione dei programmi. La RAM è caratterizzata da un accesso rapido e casuale ai dati.

- ROM (Read-Only Memory)

È una memoria non volatile che contiene istruzioni e dati permanenti che non possono essere modificati. Generalmente, la ROM viene utilizzata per memorizzare il firmware del computer, come il BIOS. A differenza della RAM, la ROM mantiene il suo contenuto anche quando il computer è spento.

- BIOS (Basic Input/Output System)

Il BIOS è un software di sistema fondamentale che viene memorizzato in un chip ROM sulla scheda madre del computer. Esso fornisce le istruzioni di base per l'avvio del sistema e gestisce l'interazione tra il sistema operativo e l'hardware del computer. Il BIOS esegue il POST (Power-On Self-Test) all'accensione del computer, inizializza l'hardware e carica il sistema operativo dalla memoria di massa.

- Memoria Centrale

La Memoria Centrale è il componente principale del sistema di memoria di un computer. È una memoria ad accesso rapido e casuale, tipicamente implementata come RAM. La Memoria Centrale svolge un ruolo cruciale nell'esecuzione dei programmi, memorizzando temporaneamente dati e istruzioni che il processore utilizza frequentemente.

# Input/Ouput

L'**input** è un termine che indica un **dato** o un **segnale** fornito a un sistema, un dispositivo o un programma affinché questo possa elaborarlo e produrre un risultato o un'azione. È l'**informazione in ingresso** che un sistema riceve per eseguire una funzione specifica.

L'output, invece, è un segnale inviato dal computer verso l'utente. Questi segnali vengono gestiti attraverso dispositivi specifici, come tastiere e mouse per l'input, e monitor o stampanti per l'output. La comunicazione tra questi dispositivi e la CPU avviene attraverso i bus di sistema, che fungono da canali di trasmissione dati.

# La CPU

La **CPU** (Central Processing Unit), o processore, è il componente principale di un computer che esegue l'elaborazione dei dati e controlla le operazioni del sistema. In pratica, è il **"cervello"** del computer, responsabile di eseguire le istruzioni dei programmi e gestire il flusso di informazioni all'interno del sistema.

Il **linguaggio macchina** è il linguaggio comprensibile dalla CPU, composto da sequenze di 0 e 1 (codice binario). Ogni programma scritto in un linguaggio di programmazione evoluto (come C o Python) deve essere tradotto in linguaggio macchina per poter essere eseguito. Questa traduzione avviene tramite un **compilatore** (che traduce l'intero programma) o un **interprete** (che traduce ed esegue riga per riga). Le istruzioni in linguaggio macchina sono specifiche per ogni tipo di processore e consentono alla CPU di eseguire operazioni direttamente sull’hardware.

## Modello di Harvard

Il **modello di Harvard** è un'architettura utilizzata nella progettazione di processori, che separa fisicamente la memoria per i **dati** da quella per le **istruzioni**. Questo è diverso dal **modello di von Neumann**, dove dati e istruzioni condividono la stessa memoria. La distinzione tra le due memorie nel modello di Harvard offre diversi vantaggi in termini di efficienza e velocità.

Harvard usa **due memorie separate**: una per le istruzioni e una per i dati. Questo permette al processore di accedere contemporaneamente sia alle istruzioni che ai dati, migliorando la velocità e l'efficienza delle operazioni, poiché le operazioni di lettura o scrittura dei dati non devono competere con quelle delle istruzioni.

il **modello Harvard** offre prestazioni migliori rispetto al modello di von Neumann grazie alla separazione tra la memoria per i dati e quella per le istruzioni, anche se questo comporta una maggiore complessità e costi di realizzazione.