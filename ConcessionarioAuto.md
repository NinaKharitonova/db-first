# Concessionario Auto Usate

| name                         | type       | attributes                          | key | note |
| ---------------------------- | ---------- | ----------------------------------- | --- | ---- |
| id                           | BIGINT(25) | NOT NULL - AUTOINCREMENT - UNSIGNED |     |      |
| Car_License_Plate            | BIGINT     | NOT NULL - UNSIGNED                 |     |      |
| Year_of_production           | YEAR       | NOT NULL                            |     |      |
| Model                        | CHAR(50)   | NOT NULL                            |     |      |
| Mileage                      | SMALLINT   | NOT NULL - AUTOINCREMENT            |     |      |
| Specifications_and_equipment | MEDIUMTEXT | NOT NULL                            |     |      |
| Ravages                      | MEDIUMTEXT | NOT NULL                            |     |      |
| Theft_documents              | MEDIUMTEXT | NOT NULL                            |     |      |
| Conditions                   | MEDIUMTEXT | NOT NULL                            |     |      |
