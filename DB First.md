Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario!

| CARS                 | TYPES        | INDICI      | ATTRIBUTI                        |
| -------------------- | ------------ | ----------- | -------------------------------- |
| id                   | INT          | PRIMARY KEY | NOT NULL, UNIQUE, AUTO INCREMENT |
| brand                | VARCHAR(50)  |             | NOT NULL                         |
| modello              | VARCHAR(50)  |             | NOT NULL                         |
| year_of_production   | YEAR         |             | NOT NULL                         |
| kms                  | MEDIUMINT    |             | NOT NULL                         |
| color                | VARCHAR(25)  |             | NOT NULL                         |
| displacement         | VARCHAR(5)   |             | NOT NULL                         |
| fuel                 | CHAR(1)      |             | NOT NULL                         |
| condition            | CHAR(1)      |             | NOT NULL                         |
| cost                 | FLOAT(9,2)   |             | NULL, UNSIGNED                   |
| price                | FLOAT(9,2)   |             | NULL, UNSIGNED                   |
| type_of_car          | VARCHAR(60)  |             | NOT NULL                         |
| type_of_change       | CHAR(1)      |             | NOT NULL                         |
| horsepower           | VARCHAR(4)   |             | NOT NULL                         |
| year_of_registration | YEAR         |             | NOT NULL                         |
| revision             | TINYINT(1)   |             | NOT NULL                         |
| warranty             | TINYINT(1)   |             | NOT NULL                         |
| vin_number           | CHAR(17)     |             | NOT NULL, UNIQUE                 |
| passenger_number     | TINYINT      |             | NOT NULL, UNSIGNED               |
| doors                | TINYINT      |             | NOT NULL, UNSIGNED               |
| previous_owners      | TINYINT      |             | NOT NULL, DEFAULT(1)             |
| availability         | TINYINT(1)   |             | NOT NULL                         |
| photo                | VARCHAR(255) |             | NOT NULL                         |
| notes                | TEXT         |             | NULL                             |
| parking_space        | CHAR(1)      |             | NULL                             |
| warehouse            | CHAR(1)      |             | NULL                             |
