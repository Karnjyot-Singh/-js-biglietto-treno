Il programma dovrà chiedere all'utente il numero di chilometri che vuole percorrere e l'età del passeggero.
Sulla base di queste informazioni dovrà calcolare il prezzo totale del viaggio, secondo queste regole:
il prezzo del biglietto è definito in base ai km (0.21 € al km)
va applicato uno sconto del 20% per i minorenni
va applicato uno sconto del 40% per gli over 65.
L'output del prezzo finale va stampato in forma umana (con massimo due decimali, per indicare centesimi sul prezzo). Ricordatevi un metodo che abbiamo visto durante le lezioni precedenti.
### Dato
prezzo per km
sconto minorenni
sconto over65
Chiedere all'utente:
km da percorrere ---> number
età ---> number
### Esecuzione logica
1. trasformare gli input dell'utente in tipo di dato number
2. calcolare prezzo base
3. imposto la condizione
dichiaro la variabile per lo sconto da applicare
SE età < 18
  sconto da applicare = sconto minorenni
ALTRIMENTI SE età >= 65
  sconto da applicare = sconto over 65
ALTRIMENTI
  sconto da applicare è 0
4. 
calcolo lo sconto = prezzo base / 100 * sconto da applicare
prezzo finale = prezzo base - (sconto)
### OUTPUT
Il tuo sconto è [sconto]
Il prezzo finale è [prezzo finale] 