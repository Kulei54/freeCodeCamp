---
id: 5e444136903586ffb414c94d
title: Calcolatore di tempi
challengeType: 10
forumTopicId: 462360
dashedName: time-calculator
---

# --description--

Lavorerai a <a href="https://replit.com/github/freeCodeCamp/boilerplate-time-calculator" target="_blank" rel="noopener noreferrer nofollow">questo progetto con il nostro codice d'inizio su Replit</a>.

-   Start by importing the project on Replit.
-   Next, you will see a `.replit` window.
-   Select `Use run command` and click the `Done` button.

# --instructions--

Scrivi una funzione denominata `add_time` che richieda due parametri obbligatori e uno opzionale:

- a start time in the 12-hour clock format (ending in AM or PM)
- a duration time that indicates the number of hours and minutes
- (optional) a starting day of the week, case insensitive

La funzione dovrebbe sommare la durata all'ora di inizio e restituire il risultato.

Se il risultato sarà il giorno successivo, dovrebbe mostrare `(next day)` dopo l'ora. Se il risultato sarà più di un giorno dopo, dovrebbe mostrare `(n days later)` dopo il tempo, dove "n" è il numero di giorni dopo.

Se alla funzione viene passato il parametro opzionale del giorno di inizio della settimana, l'output dovrebbe visualizzare il giorno della settimana del risultato. Il giorno della settimana in output dovrebbe comparire dopo l'ora e prima del numero di giorni successivi.

Di seguito sono riportati alcuni esempi di casi diversi che la funzione dovrebbe gestire. Presta molta attenzione alla spaziatura e punteggiatura dei risultati.

```py
add_time("3:00 PM", "3:10")
# Returns: 6:10 PM

add_time("11:30 AM", "2:32", "Monday")
# Returns: 2:02 PM, Monday

add_time("11:43 AM", "00:20")
# Returns: 12:03 PM

add_time("10:10 PM", "3:30")
# Returns: 1:40 AM (next day)

add_time("11:43 PM", "24:20", "tueSday")
# Returns: 12:03 AM, Thursday (2 days later)

add_time("6:30 PM", "205:12")
# Returns: 7:42 AM (9 days later)
```

Non importare nessuna libreria Python. Supponi che gli orari di inizio siano validi. I minuti nel tempo di durata saranno un numero intero inferiore a 60, ma l'ora può essere qualsiasi numero intero.

## Sviluppo

Scrivi il tuo codice in `time_calculator.py`. Per lo sviluppo, puoi usare `main.py` per testare la tua funzione `time_calculator()`. Usa il bottone "run" e `main.py` sarà eseguito.

## Test

I test unitari per questo progetto sono in `test_module.py`. Abbiamo importato i test da `test_module.py` in `main.py` per tua convenienza. I test saranno eseguiti automaticamente quando usi il bottone "run".

## Invio

Copia l'URL del tuo progetto e consegnalo nell'input qua sotto.

# --hints--

Dovrebbe sommare correttamente dei tempi e superare tutti i test.

```js

```

# --solutions--

```js
/**
  Backend challenges don't need solutions,
  because they would need to be tested against a full working project.
  Please check our contributing guidelines to learn more.
*/
```
