# Fantalega 2.2

Questa applicazione serve per gestire una lega di fantacalcio.
E' possibile gestire piu' leghe ed e' compresa anche la gestione
dell'Asta iniziale.
Vengono usate le librerie wx per la grafica e django come ORM.

## Operazioni preliminari

Dopo aver installato django e le librerie wx, creare il database,
o utilizzato il file requirements.txt con pip:

Creazione database:

```
python manage.py makemigrations fantalega
```

in seguito:

```
python manage.py migrate
Operations to perform:
  Apply all migrations: fantalega
Running migrations:
  Applying fantalega.0001_initial... OK
```

una volta creato il database fantalega.db, lanciare l'applicazione.

```
>python main.py
```

### 1. Creare la stagione

Dal menu Season, creare una nuova stagione


### 2. Importare i giocatori

Dal menu Evaluation, eseguire l'import dei voti scegliendo il file di giornata es. MCC1.txt.
I file di giornata seguono la formattazione Gazzetta.

### 3. Creare la Lega

Dal menu League, creare una nuova Lega


### 4. Creare le squadre

Prima di iniziare l'asta, creare le squadre che vi partecipano, dal menu Teams


### 5. Asta

Dal menu Auction, iniziare l'asta.

### 6. Calendario

Terminata l'asta creare il calendario dal menu Calendar.

### 7. Consegna Formazioni, Punteggi

Prima di ogni inizio giornata, consegnare le formazioni dal menu Lineup.
Una volta usciti i voti, importarli dal menu Evaluation e controllare il
punteggio. Dal menu Calendar -> All Scores e' possibile calcolare i risultati
di giornata, salvandoli sul database. I punti delle singole formazioni sono 
consultabili dal menu Lineup.

### 8. Classifica

Consultabile dal menu League -> Chart


### Modifiche

Dai menu Players e Teams si possono editare e modificare squadre e calciatori

### Mercato

E' possibile effettuare scambi con altre squadre.
 Si accede a questa operazione dal menu Teams -> Trades

## Licenza

GPL
