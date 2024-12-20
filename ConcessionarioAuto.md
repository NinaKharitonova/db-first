# Concessionario Auto Usate

| name                         | type          | attributes                          | key     | note |
| ---------------------------- | ------------- | ----------------------------------- | ------- | ---- |
| id                           | BIGINT(25)    | NOT NULL - AUTOINCREMENT - UNSIGNED | PRIMARY |      |
| Car_License_Plate            | VARCHAR(50)   | NOT NULL - UNSIGNED                 |         |      |
| Year_of_production           | YEAR          | NOT NULL                            |         |      |
| Model                        | VARCHAR(50)   | NOT NULL                            |         |      |
| Mileage                      | MEDIUMINIT    | NOT NULL - AUTOINCREMENT            |         |      |
| Specifications_and_equipment | MEDIUMTEXT    | NOT NULL                            |         |      |
| Ravages                      | MEDIUMTEXT    | NOT NULL                            |         |      |
| Theft_documents              | MEDIUMTEXT    | NOT NULL                            |         |      |
| Conditions                   | MEDIUMTEXT    | NOT NULL                            |         |      |
| Price                        | DECIMAL(10,2) | NOT NULL - UNSIGNED                 |         |      |
