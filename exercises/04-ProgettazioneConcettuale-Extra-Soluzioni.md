***1. Un dottore può seguire interventi diversi?***
Sì, la partecipazione di dottore alla relazione responsabilità ha cardinalità (1, N).

***2. Due pazienti possono prenotare un appuntamento nello stesso giorno e alla stessa ora?***
No, l'identificativo di appuntamento è determinato dall'attributo giorno e dall'attributo ora; ergo, non ci possono essere due appuntamenti con giorno e ora uguali.

***3. Un dottore può seguire due interventi che si verificano nello stesso giorno e alla stessa ora?***
Secondo 1., un dottore può avere la responsabilità di più interventi (di questi, non è specificato né il giorno né l'ora).
D'altro canto, un intervento è associato ad uno (e uno soltanto) appuntamento, il quale (secondo 2.) non permette di avere appuntamenti allo stesso giorno e stessa ora.
Possiamo quindi concludere che: un dottore non può seguire interventi lo stesso giorno e nella stessa ora.

***4. Come possiamo rendere i punti 2. e 3. veri?***
Dobbiamo aggiungere all'identificatore di appuntamento un ulteriore attributo (o una partecipazione ad una relazione). Per esempio, potremmo aggiungere una nuova entità: Stanza. In [04-ProgettazioneConcettuale-Extra-Soluzioni.pdf](https://github.com/josephgiovanelli/2022-fitstic-database/blob/main/exercises/04-ProgettazioneConcettuale-Extra-Soluzioni.pdf), un appuntamento (in un giorno e in un'ora) è univoco solo rispetto alla stanza (non ci possono essere due appuntamenti nella stesso giorno e ora, nella stessa stanza; però, su stanze diverse sì).
In questo modo è anche possibile che un dottore possa avere la responsabilità di più interventi che si verificano nello stesso giorno e ora (ma su stanze diverse).

