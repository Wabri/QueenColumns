# QueenColumns
**Questa repository si autodistruggerà tra meno di 24h**

## Testo dell'esercizio
![esercizio][resources/exercise.jpg]

## Soluzione degli esempi
![soluzione][resources/soluzione.jpg]

## Elaborazione della soluzione
L'esercizio chiede la creazione di un metodo di risoluzione di questo problema prendendo in input la matrice e la riga da esaminare.
Quello che conviene fare è di analizzare prima se esistono delle colonne che non contengono 1, se non ce ne sono ci si ferma e si restituisce l'array vuoto.
Se ci sono useremo un array booleano di lunghezza pari al numero di colonne della matrice: il valore vero indicherà che non ci sono 1 in quella colonna, valore falso se ci sono.
Prendendo quindi solo le colonne con valore vero dobbiamo eseguire 2 cicli per analizzare la diagonale sinistra e la diagonale destra dell'elemento considerato.
Con annessi controlli interni la soluzione è questa:
```

```
