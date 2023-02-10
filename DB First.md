Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario!

| CARS                       | TYPES        | INDICI      | ATTRIBUTI                        |
| -------------------------- | ------------ | ----------- | -------------------------------- |
| id                         | INT          | PRIMARY KEY | NOT NULL, UNIQUE, AUTO INCREMENT |
| marca                      | VARCHAR(50)  |             | NOT NULL                         |
| modello                    | VARCHAR(50)  |             | NOT NULL                         |
| anno di produzione         | YEAR         |             | NOT NULL                         |
| chilometraggio             | MEDIUMINT    |             | NOT NULL                         |
| colore                     | VARCHAR(25)  |             | NOT NULL                         |
| cilindrata                 | SMALLINT     |             | NOT NULL                         |
| carburante                 | CHAR(1)      |             | NOT NULL                         |
| condizione                 | CHAR(1)      |             | NOT NULL                         |
| costo                      | FLOAT(9,2)   |             | NOT NULL                         |
| prezzo di vendita          | FLOAT(9,2)   |             | NOT NULL                         |
| tipo di auto               | VARCHAR(60)  |             | NOT NULL                         |
| tipo di cambio             | CHAR(1)      |             | NOT NULL                         |
| potenza in cavalli         | SMALLINT     |             | NOT NULL                         |
| anno di immatricolazione   | YEAR         |             | NOT NULL                         |
| revisione                  | TINYINT(1)   |             | NOT NULL                         |
| garanzia                   | TINYINT(1)   |             | NOT NULL                         |
| nr. telaio                 | CHAR(17)     |             | NOT NULL, UNIQUE                 |
| nr. passeggeri             | TINYINT(12)  |             | NOT NULL                         |
| nr. porte                  | TINYINT(6)   |             | NOT NULL                         |
| nr. proprietari precedenti | TINYINT(30)  |             | NOT NULL                         |
| disponibilità              | TINYINT(1)   |             | NOT NULL                         |
| foto                       | VARCHAR(255) |             | NOT NULL                         |
| note                       | TEXT         |             | NULL                             |
| parcheggio                 | CHAR(1)      |             | NULL                             |
| magazzino                  | CHAR(1)      |             | NULL                             |
