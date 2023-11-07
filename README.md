# PROVA C
## CREAZIONE DI UN DATABASE ED INSERIMENTO DI DUMMY DATAS

> L'esercitazione consiste nel creare un database per mezzo di Sqlite3 e inserire al suo interno una tabella "compagni" con una decina di dummy datas.

### Creazione del database
> Nella cartella esDatabase creo il file "crea_tabella.sql" in cui inserisco questo codice:
```
CREATE TABLE IF NOT EXISTS compagni (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    Nome TEXT NOT NULL,
    Cognome TEXT NOT NULL,
    Email TEXT NOT NULL
);
```
- Creo una tabella "compagni"
- Inserisco una colonna "id" di interi come chiave primaria e che si incrementano automaticamente
- Inserisco le colonne "Nome", "Cognome", "Email" di stringhe.

### Inserimento dei Dummy Datas
> Sempre nella stessa cartella creo il file "inserisci_dati.sql" in cui scrivo questo codice:
```
INSERT INTO compagni (Nome, Cognome, Email) VALUES ('Andrea', 'Alvigini', 'andre@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES('Simone', 'Cognome1', 'simone@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES ('Greta', 'Di Fabio', 'greta@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES('Tiziano', 'Cognome2', 'tiziano@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES('Giorgio', 'Cognome3', 'giorgio@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES('Davide', 'Cognome4', 'davide@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES('Alessandro', 'Cognome5', 'alessandro@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES('Christopher', 'Cognome6', 'christopher@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES('Emanuele', 'Cognome7', 'emanuele@example');
INSERT INTO compagni (Nome, Cognome, Email) VALUES ('Gianluca', 'Ciceri', 'gianluca@example');
```

- Inserisco nella tabella "compagni", rispettivamente nelle colonne "Nome", "Cognome", "Email" i valori specificati.

