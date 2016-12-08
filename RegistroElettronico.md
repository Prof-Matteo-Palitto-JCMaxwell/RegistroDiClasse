#<b>Registro elettronico</b>
##<b>Descrizione programma</b>
###Richiesta del cliente
<p>Siamo una piccola scuola (1 classe sola), e vorremmo trasformare il registro da cartaceo a elettronico. Il registro viene usato per il tracciamento e memorizzazione dei voti di ogni singolo studente. Vorremmo che ci fossero due tipologie distinte di utenti (studenti e professori). I professori hanno la possibilità di consultare le votazioni di tutta la classe per studente e per materia, mentre gli studenti solamente i propri voti per materia. Per entrambi i professori e studenti, per ogni materia, viene visualizzato la media della votazione di tutta la classe. Per entrambi professori e studenti, viene calcolata la media di tutti i voti di tutte le materie per ogni studente e viene indicato la stato: PROMOSSO o A RISCHIO DI BOCCIATURA (naturalmente nel caso l'utente sia uno studente, verrebbero visualizzati solo i dati che lo riguardano). Sarà necessario che i professori possano inserire le votazioni della loro materia. Ogni utente per poter accedere al registro dovrà inserire User Name e PASSWORD. Sarebbe bello, ma non necessario, anche una interfaccia grafica, ma solo se non costasse troppo, perché andrebbe benissimo un interfaccia a linea di comando (da terminale).</P>

Versione 1 avrà interfaccia utente da linea di comando.</br>
Versione 2 avrà autenticazione con PASSWORD dell'utente.</br>
Versione 3 (Opzionale) offrirà una interfaccia grafica.</br>

###Domande ulteriori per il cliente
D1. Quanti utenti possono accedere al registro contemporaneamente?</br> 
Nella classe c'e' solo un computer da cui accedere al registro, quindi un utente alla volta potrà accedere al registro.

###Specifiche ESTERNE
E1. Registro Elettronico deve memorizzare in maniera non volatile le votazioni di ogni studente per ogni materia.</br>
E2. Due tipologie distinte di utenti: studente e professore.</br> 
E3. Ogni utente studente può vedere la media di tutti gli utenti studente, ma può vedere solo le proprie valutazioni e il proprio stato (Promosso/Rischio di bocciatura).</br>
E4. Ogni utente professore può vedere i voti e le medie di tutti i gli utenti studente, può aggiungere voti della sua materia e può vedere lo stato di ogni utente studente (Promosso/Rischio di bocciatura).</br>
E5. Ogni utente avrà un proprio account con username e password.</br>
E6. L’accesso può essere eseguito da un utente per volta.</br>

###Specifiche INTERNE
I1. Il Registro Elettronico verrà realizzato usando JAVA come linguaggio di programmazione.</br>
I2. I dati degli utenti verranno salvati su file.</br>

###Architettura
- Macro Blocchi
Interfaccia utente
Struttura dati
- Scomposizione in componenti semplici
I macro blocchi corrispondono ai componenti semplici.

##<b>Istruzioni di installazione</b>
Il programma non necessita di installazione.

##<b>Manuale d’uso</b>
###Versione 1-2:
In tutti i menù ad ogni opzione è attribuito un numero, per selezionare una opzione è necessario premere il numero corrispondente alla opzione desiderata.
Appena aperto il programma verrà visualizzato un menù con le voci: “Registrati” e “Accedi”.</br>
<b>1.Registrazione:</b> selezionare la voce “Registrati” per registrarsi al registro elettronico.</br>
Selezionare il tipo di utente (Professore, Studente).</br>
<i>1.a. Studente:</i> inserire il proprio username (consigliato nome.cognome) e premere invio, poi inserire una password (min 8 caratteri) e premere invio.</br>
<i>1.b. Professore:</i> inserire il proprio username (consigliato nome.cognome)e premere invio, inserire una password (min 8 caratteri) e premere invio, selezionare la propria materia di insegnamento.</br>
<b>2. Accesso:</b> selezionare la voce “Accedi” per accedere al registro elettronico.</br>
Inserire il proprio username e la propria password.</br>
<b>3.Home:</b> qui verrà visualizzato un menù in cui è possibile scegliere un opzione.</br>
<i>3.a. Studente:</i> le voci del menu sono: “Valutazioni”(dove saranno presenti le valutazioni e le medie per ogni materia e lo stato dello studente), “Media classe”(dove saranno presenti le medie di tutti gli studenti della classe) e “Esci” (ritorna al menù di accesso).</br>
<i>3.b. Professore:</i> le voci del menù sono: “Valutazioni studenti” (dove saranno presenti le valutazioni e le medie per ogni materia e lo stato di tutti gli studenti della classe), “Aggiungi valutazione” (dove si potrà aggiungere una valutazione per la propria materia) e “Esci” (ritorna al menù di accesso).</br>

##<b>Autori</b>
Serena D’Ambrosio</br>
Roberta Gulmini</br>
Luca Ronca</br>
Sara Sgreccia</br>

##<b>Ringraziamenti</b>



