# Car Dealer db

## Tablename: Cars

- id | BIGINT - PRIMARY_KEY AUTO_INCREMENT NOTNULL UNIQUE
- model | VARCHAR(200) - NOTNULL 
- year | YEAR (YYYY) - NOTNULL
- kms | INT - NOTNULL 
- engine | VARCHAR (100) NULL
- paint | VARCHAR (50) NULL
- weight | SMALLINT UNSIGNED - NULL
- transmission | VARCHAR (20) - NOTNULL INDEX
- plate | CHAR (7) - NOTNULL
- ownership | VARCHAR (100) -  NOTNULL
- fuel_type | VARCHAR (30) - NOTNULL
- emission_class | CHAR (6) - DEFAULT('Euro 3')
- horsepower | SMALLINT UNSIGNED - NULL
- doors_number | TINYINT UNSIGNED - NULL
- seats_number | TINYINT UNSIGNED - NULL
- revision_date | DATE (YYYY-MM-GG) - NULL
- insurance_expiry| DATE (YYYY-MM-GG) - NOTNULL
- car_condition | VARCHAR(30) - NULL
- price | DECIMAL(10,2) - NOTNULL
- notes | TEXT - NULL
