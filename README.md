Buongiorno, 
La mia tesi riguarda l'analisi della disparità di genere in ambito scientifico presso l’Università degli studi di Genova

In particolare ho analizzato i dati riguardanti il dipartimento di informatica Triennale negli anni dal 2010 al 2023 per le lauree, mentre dal 1997 sino a giugno 2024 per i voti
I dati raccolti provengono dal CEDIA, Centro Dati, Informatica di Ateneo

Per le analisi ho utilizzato il linguaggio di programmazione python, in particolare con l'aiuto delle librerie pandas, seaborn, scipy, ..

Nella pulizia dei dati ho dovuto considerare solo esami superati positivamente perchè non avevo dati sufficienti ad un'analisi completa
Ho inoltre rimosso gli esami e i corsi con meno di 50 partecipanti, quindi i corsi a scelta
Le idoneità, gli ofa e gli esami di inglese non sono stati considerati
Per alcune analisi ho aggregato i dati in modo da avere un unico esame per insegnamenti vecchi e nuovi, ad esempio BASI DI DATI 2, aggregato con BASI DI DATI. Non ho mantenuto questa scelta per le analisi specifiche sulla tipologia di corso. Ho quindi utilizzato due database principali per tutto il progetto.

Le analisi effettuate si riferiscono ai seguenti argomenti
1- Studenti per corso
2- Voti per genere
3- Lauree: per anno, durata, valutazione
4- Diploma superiore: voto
5- Voto diploma superiore e Laurea
6- Voti nel Periodo Pandemia
7- Esami scritti o orali
8- Singolo esame
9- Voti per anno di corso
10- Voti per genere del docente

-----------------------------------------------------------
Considerazioni:

-L'analisi si rifersisce solo alla laurea triennale

-Avendo preso solo esami con almeno 50 studdenti passati, alcuni corsi vengono esclusi a prescindere, come SEI2
Abbasso la soglia? forse posso fare l'analisi degli esami dei corsi con pt_vecchi
