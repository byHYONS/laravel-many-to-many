# ESERCIZIO: Laravel Boolfolio - Project Technology

> [!NOTE]
>
> nome repo: laravel-many-to-many


### DESCRIZIONE:

Continuiamo a lavorare sul codice dei giorni scorsi, ma in una nuova repo e aggiungiamo una **nuova entità Technology**.
Questa entità rappresenta le tecnologie utilizzate ed è in relazione` many to many` con i **progetti**.

I task da svolgere sono diversi, ma alcuni di essi sono un ripasso di ciò che abbiamo fatto nelle lezioni dei giorni scorsi:

- creare la **migration** per la tabella technologies;

- creare il **model** Technology;

- creare la migration per la tabella **pivot** project_technology;

- aggiungere ai model Technology e Project i metodi per **definire la relazione** many to many;

- visualizzare nella pagina di dettaglio di un progetto le tecnologie utilizzate, se presenti.

#### Bonus 1:
creare il seeder per il model Technology.

#### Bonus 2:
aggiungere le operazioni CRUD per il model Technology, in modo da gestire le tecnologie utilizzate nei progetti direttamente dal pannello di amministrazione.

#### Continuazione esercizio:

Continuiamo a lavorare sul codice di ieri, stessa repo.I task sono:

1. permettere all’utente di associare le tecnologie nella pagina di creazione e modifica di un progetto;
2. gestire il salvataggio dell’associazione progetto-tecnologie con opportune regole di validazione;
3. eliminare opportunamente le relazioni alla cancellazione del progetto/technology.



##### © byHYONS™
