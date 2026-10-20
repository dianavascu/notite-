Django include un sistem ORM (Object-Relational Mapper) care îți permite să lucrezi cu baze de date relaționale (SQLite, PostgreSQL, MySQL) scriind cod Python, fără a fi nevoie de interogări SQL complexe.
 Baze de Date & SQL (Structured Query Language)
Ce este o Bază de Date: Un sistem organizat pentru stocarea, gestionarea și regăsirea rapidă a informațiilor (de exemplu: lista de utilizatori, produse, articole).
Baze de Date Relaționale (RDBMS): Datele sunt organizate în tabele formate din rânduri și coloane interconectate între ele (ex: PostgreSQL, MySQL, SQLite).
Ce este SQL: Limbajul internațional standard folosit pentru a comunica cu o bază de date relațională.
Comenzi de bază (Operațiunile CRUD):
CREATE / INSERT: Adăugarea de înregistrări noi (INSERT INTO utilizatori ...).
READ / SELECT: Căutarea și extragerea de date (SELECT * FROM utilizatori WHERE varsta > 18;).
UPDATE: Modificarea datelor existente (UPDATE utilizatori SET nume = ...).
DELETE: Ștergerea datelor (DELETE FROM utilizatori WHERE id = 1;).
