# I Sistemi Numerici

I **sistemi numerici** sono metodi o schemi utilizzati per rappresentare i numeri e gestire le operazioni matematiche. Ogni sistema numerico utilizza un insieme specifico di simboli (cifre) e una base, che determina quanti simboli sono disponibili e come vengono organizzati.

- **Sistema decimale (base 10)**
- Sistema binario (base 2)
- Sistema ottale (base 8)
- Sistema esadecimale (base 16)

### Differenze principali tra i sistemi numerici:

- **Base**: Ogni sistema numerico ha una base diversa (es. 10, 2, 8, 16), che determina quanti simboli utilizza e come vengono interpretati i numeri.
- **Rappresentazione**: Lo stesso numero può essere rappresentato in modo diverso a seconda del sistema numerico. Ad esempio, il numero **10** in decimale corrisponde a **1010** in binario, **12** in ottale, e **A** in esadecimale.

### Conversioni tra sistemi numerici:

Per convertire un numero da un sistema numerico a un altro, è possibile seguire alcuni passaggi specifici. Ad esempio:

- **Decimale a binario**: Si divide il numero decimale per 2, prendendo i resti finché il quoziente non diventa 0. I resti letti dall'alto verso il basso costituiscono il numero binario.
- **Binario a esadecimale**: Si raggruppano le cifre binarie in gruppi di quattro, partendo dalla destra, e si sostituiscono con le rispettive cifre esadecimali.

i sistemi numerici sono fondamentali per la rappresentazione dei numeri e sono utilizzati in vari ambiti, dal calcolo quotidiano alla programmazione e all'elettronica avanzata.

## Addizione e Sottrazione in sistema binario

L’addizione e la sottrazione in binario ha le stesse proprietà del sistema decimale.

- Ecco l’addizione:

 

![image.png](I%20Sistemi%20Numerici%20128b5f4b9b53803c8f49f3f02aab5517/dbb9da77-bc6c-4f6c-af16-7a10b4ce5863.png)

- Invece la sottrazione:

![image.png](I%20Sistemi%20Numerici%20128b5f4b9b53803c8f49f3f02aab5517/15542a5c-6cda-449c-8a08-5ebc23f72ec5.png)

L'addizione e la sottrazione in binario seguono regole simili a quelle del sistema decimale, ma con alcune peculiarità:

### Regole per l'addizione binaria:

- 0 + 0 = 0
- 0 + 1 = 1
- 1 + 0 = 1
- 1 + 1 = 0 con riporto di 1

### Regole per la sottrazione binaria:

- 0 - 0 = 0
- 1 - 0 = 1
- 1 - 1 = 0
- 0 - 1 = 1 con prestito di 1

È importante notare che quando si effettua un'addizione o una sottrazione in binario, si procede da destra a sinistra, proprio come nel sistema decimale. Tuttavia, poiché si lavora solo con 0 e 1, i riporti e i prestiti diventano più frequenti.

### Esempi pratici:

Addizione: 1011 + 1101

```
1011
+ 1101
------
 11000
```

Sottrazione: 1100 - 1001

```
1100
- 1001
------
  0011
```

Questi esempi mostrano come i riporti e i prestiti vengono gestiti in binario. La pratica è essenziale per padroneggiare queste operazioni, che sono fondamentali in informatica e elettronica digitale.