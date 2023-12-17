Progetto ChatCriptata

Il progetto si basa sulla comunicazione criptata su una rete privata/pubblica tra due postazioni con una elevata sicurezza di codifica.

Alla base di questo progetto c’è un algoritmo da me scoperto nel 2021 a cui ho dato il nome di GC57

Questo algoritmo pone la sua sicurezza sulla fattorizzazione di semiprimi grandi e la sua più grande capacità è quella di riuscire a risolvere tale fattorizzazione in tempo zero, e cioè all’istante e indipendentemente dalla grandezza del semiprimo

Nella prima interfaccia grafica si trova la realizzazione di un nuovo codice o il caricamento del codice da penna USB. Questo per avvalersi di una ulteriore sicurezza dovuta al fatto che solo con i dati della chiavetta possiamo scambiare informazioni con l’altra postazione e decifrarne il contenuto. Senza la chiavetta si può creare un altro codice ma questo non permetterà di comunicare con un’altra postazione che non abbia lo stesso codice


																																		
Se si dispone già dei dati memorizzati su chiavetta basterà premere Carica Dati per recuperare i dati relativi alla postazione con cui vogliamo comunicare. Bisogna assolutamente caricare i dati prima di avviare la Chat.

Se vogliamo creare un nuovo codice perché vogliamo cambiare la sicurezza della comunicazione o semplicemente perché ne vogliamo creare uno nuovo, dobbiamo inserire nella parte superiore a sinistra un numero digitato in modo casuale o un numero di cui conosciamo gli attributi di sicurezza, Esempio: Numeri RSA. Se poi vogliamo trasformare il nostro numero casuale in un numero primo, premiamo sul tasto Trasforma in Primo 
NB: Se vogliamo mantenere lo stesso numero digitato sarebbe consigliato scrivere un numero dispari e che non finisca con il 5, ma questo comunque non cambierà il risultato pur anche questo numero sia un numero pari.

Nella parte Inserisci i Bit, noi andremo a mettere indicativamente quanto dovrà essere grande in Bit questo semiprimo.
Per chi ha bisogno di una scala di riferimento possiamo dire che un numero di 2^1000 è un numero di circa 302 cifre, perciò se noi inseriamo 1000 avremo un semiprimo all’incirca di 302 cifre e due fattori primi che saranno tra  le 130 e le 170 cifre.

NB:Come scritto a metà della finestra, prima di creare il codice dovremo inserire i dati dell’IP del computer con cui vogliamo dialogare e della porta di comunicazione e verificare che la porta USB corrisponda alla lettera della nostra porta. NB: questo della USB deve essere verificato anche nel caso si volesse solo caricare i dati

Premiamo su Crea Nuovo Codice e se tutto va bene troveremo nelle caselle “Codice Creato Bit” la reale dimensione del codice in Bit,  in “Esponente” il valore dell’esponente usato per creare la chiave, e in “Test di campo” il valore dell’esponente del campo espresso sulla base di 2, dove il programma sceglierà due fattori primi casuali ogni volta che verrà spedito un messaggio via chat.
NB: per campo intendo una dimensione di 2^n perciò due elevato alla potenza del valore inserito automaticamente dentro “Test di campo”. Questo vuol dire che ogni volta che si codifica il testo da mandare, questo verrà codificato in modo casuale prendendo due fattori primi sempre differenti da quelli usati in precedenza nel campo indicato

Se tutto è andato per il verso giusto premete Carica Dati per attivarli e Apri Chat per iniziare a spedire o ricevere dati criptati.


Questo procedimento deve essere fatto anche sul secondo computer usando lo stesso numero e la stessa dimensione parziale che sono inseriti in “Inserisci un numero” e “Inserisci i Bit” in alto, e nell’indirizzo IP, naturalmente, inseriremo ognuno l’indirizzo del computer con cui intendiamo comunicare. Il programma poi troverà gli stessi codici per poter comunicare e codificare i dati

Postazione Chat

Naturalmente questa chat non è pensata per scambiarsi messaggi di auguri o cose simili, ma più verosimilmente per mandare codici, password, o testi che devono assolutamente rimanere segreti.

La chat è divisa in quattro finestre:
La prima in alto a sinistra serve per scrivere il messaggio, la seconda in alto a destra serve per codificare e inviare il messaggio, la terza in basso a sinistra riceve il messaggio codificato e la quarta in basso a destra decodifica il messaggio ricevuto.

Essendo una chat particolare ha bisogno di alcuni accorgimenti:

Quando si codifica un messaggio automaticamente viene passato nella finestra in alto a destra. Il tasto Invio produrrà automaticamente la cancellazione di questa finestra e invierà il suo contenuto all’altra postazione.
Per scrivere un nuovo messaggio pulire prima la finestra in alto a sinistra.

Quando si riceve un messaggio questo viene stampato nella finestra in basso a sinistra.
Premendo il tasto decodifica la finestra in basso a sinistra si cancella e appare il messaggio decodificato nella finestra in basso a destra.
Prima di decodificare un nuovo messaggi premere pulizia 


NB: Inizializzato i due computer il codice può essere cambiato creando un numero nuovo e una dimensione di bit nuova, ma prima di creare il nuovo codice dobbiamo mandare all’altro computer il “numero” e i “Bit” utilizzando la chat criptata, dopodiché si può entrambi creare un codice nuovo come descritto sopra 


Alcuni esempi di inserimento: 209872359086778692340679763451  Bit 4000,
653872568237 Bit 2000, 765654265487090761237986271356487687623458763246876837678623879 Bit 6000.

I numeri possono essere trasformati in numeri primi o lasciati come sono. Per quanto riguarda i Bit, questi non sono legati alla grandezza dei numeri ma teniamo presente che un Bit alto, come per esempio 6000, può comportare un tempo di qualche minuto. Sono sempre tempi molto bassi ma quando vediamo il nostro computer bloccarsi per qualche minuto, ci sembra una eternità. Per esempio, il numero grande con 6000Bit restituisce 6058Bit in un tempo di un minuto e 27 secondi.
Ciò nonostante la decodificazione verrà eseguita sempre a tempo zero
