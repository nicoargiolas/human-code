# human-code
Esercizio 13/12

Fare la spesa seguendo una lista
Fatti mandare dalla mamma a prendere il latte
Nel frigo si inizia a sentire l’eco, perciò è ora di fare rifornimenti!
Visto che dimentico sempre qualcosa, decido di appuntarmi tutto ciò che manca in una lista, così una volta al supermercato, girando
tra gli scaffali, posso verificare di aver preso tutto e Ricky non rimane senza crocchette come l’ultima volta, povero! Devo
ricordarmi di usare il coupon che scade a fine mese, per il resto dovrebbero bastarmi i contanti che ho in portafogli, sempre se non
mi faccio prendere la mano con gli snack extra! 


------- Svolgimento dell' esercizio -------

- Preparo il foglio per scrivere la lista
- aggiungo le crocchette per Ricky alla lista
- Apro il frigo
- Finchè non ho controllato tutto il frigo
        - SE trovo alimenti mancanti:
            - Lo aggiungo alla lista
- Mi dirigo verso il supermercato
 --------------------------------------------------
- Finchè la lista non è vuota 
(X USCIRE DAL LOOP
andava messo "finchè ho tenuto conto di tutta la lista" o
tener conto che potrei non trovare alimenti della lista al supermercato)
        - giro tra gli scaffali del supermercato
        - SE trovo alimenti mancanti
           - Lo metto nel carello
           - Lo cancello dalla lista
 --------------------------------------------------
- Mi dirigo alla cassa
- Mi ricordo di utilizzare il coupon
- Controllo se ho preso degli snack extra
- Controllo il totale 
- Controllo il portafoglio
        - SE i contanti non sono sufficienti per il pagamento della spesa
                - Finchè non ho abbastanza contanti per il pagamento  
                   - Tolgo uno degli snack in eccesso 
        - ALTRIMENTI 
                - Pago