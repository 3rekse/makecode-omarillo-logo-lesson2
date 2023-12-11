### @explicitHints true

# Omarillo - Lesson #2

## Omarillo - Lezione #2 @unplugged
**Fare muovere la omarillo.**

In questa lezione insegnerai le mosse all' **Omarillo**.
![Ciao mondo!](https://github.com/Mr-Coxall/makecode-arcade-omarillo-logo-lesson2/raw/main/assets/move_screenshot.png)

## Passo 1
** Follow Along**

Ancora una volta, tutti i nostri programmi iniziano con un ⇢``on start``⇠ block. Quindi devi aggiungere l' **omarillo** utilizzando il blocco ⇢``show omarillo``⇠.
```blocks
omarillo.showOmarillo()
```

## Passo 2
** Follow Along**

Per spostare l' **Omarillo** utilizzerai il blocco ⇢``sposta l'omarillo avanti di 25 passi``⇠ e posizionalo all'interno del blocco ⇢``all'avvio``⇠ dopo il blocco ⇢``show omarillo``⇠.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 25)
```

## Passaggio 3
** Try it Out**

Notare il numero 25 nel blocco. Il numero può essere modificato per spostare l' **Omarillo** a una distanza diversa. Prova a spostare l' **Omarillo** a distanze diverse.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Forward, 75)
```

## Passaggio 4
** Follow Along**

Potresti anche aver notato che la parola "avanti/Forward" è in realtà un menu. Se lo selezioni, hai la possibilità di andare avanti o indietro.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Backward, 25)
```

## Passaggio 5
** Try it Out**

Prova a spostare indietro l' **Omarillo** di alcune distanze diverse.
```blocks
omarillo.showOmarillo()
omarillo.moveOmarilloDirection(OmarilloDirection.Backward, 30)
```

## Passaggio 6
**Success!**

Ora puoi far muovere l' **Omarillo** avanti e indietro.

## Passaggio 7
**Your Turn**

Ottieni la tua **Omarillo** per:
- andare avanti
- muoversi indietro
- poi dì: "Mi sono appena trasferito!"

## Passaggio 8
**Done**

Hai completato con successo la tua seconda lezione a Omarillo.

```ghost
omarillo.say("Ciao mondo!")
```
