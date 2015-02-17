# InformationTheory
Progetto di Teoria dell'Informazione

Per questo progetto bisogna implementare la codifica aritmetica e una delle varianti della codifica Lempel-Ziv che non siano LZ77 o LZ78 (ma che ci possono stare di straforo).
Bisogna comparare le due codifiche e le loro performance.

Per la trasmissione sul canale bisogna utilizzare dei codici concatenati da specificare a runtime, tramite input.

La sorgente può prelevare i dati da file e la simulazione deve essere effettuata su almeno 4 file con caratteristiche differenti: in particolare devono essere di almeno due lingue diverse e di tipi diversi, cioè un romanzo e un articolo scientifico o cose del genere.

Il canale deve avere un modello di errore isolato e a raffica, da fornire tramite input.
Esso deve inoltre essere modellato come se si trasmettesse su una rete wireless, come ad esempio una rete di sensori o satellitari. Ognuna ha le proprie specifiche e quindi il modello varia.
Si può pensare ad una modellazione tramite catene di Markov.

Il trasmettitore può ritrasmettere un numero arbitrario (da inserire da input) di volte se il ricevitore rileva l’errore e richiede quindi la ritrasmissione.


Le grandezze da valutare sono: fattore di compressione, entropia, errore di compressione ed eventualmente il ritardo. Per tale parametro cercare un modello che calcoli il ritardo in maniera proporzionale alla quantità di dati. _“Si può scegliere la modalità virtuale o reale”. Chiedere a De Rango cosa significa la frase tra apici. Dovrebbe riguardare l'analisi dell'errore con determinate specifiche, quindi condizionato da parametri (virtuale) oppure sul ritardo effettivo nella macchina (reale)._
Le grandezze da valutare dipendono dal file, dalla codifica e così via. Anche la modalità d’errore può essere una variabile.
