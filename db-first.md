## Data Types:
- Stirngs: VARCHAR(), CHAR(), TEXT, LONGTEXT.
- Numbers: TINYINT, SMALLINT, MEDIUMINT, INT, BIGINT.
- Decimals: FLOAT(n, d), DOUBLE(n, d), DECIMAL(n, d)

## Attributes:
- PRIMARY_KEY (PK)
- AUTO_INCREMENT (AI)
- UNIQUE (U)
- NULL (N)
- NOTNULL(NN)

# Database Car Dealer

## Entity name: Car

## Table Names: Cars

## table Columns: 

- id | BIGINT, PK, AI, NN, U, INDEX
- car brand | VARCHAR(50), NN, INDEX
- car model | VARCHAR(100), NN, INDEX
- car version | VARCHAR(100), N,
- car body | VARCHAR(50), N, INDEX
- fuel | VARCHAR(50), N, INDEX
- matriculation | DATE, NN, INDEX
- price | DECIMAL(9 ,2), NN, INDEX
- kilometres | MEDIUMINT, NN, INDEX
- CV | TINYINT, N, INDEX
- car doors | TINYINT, N
- transmission | VARCHAR(15), NN, INDEX
- n° optionals | TINYINT, N
- optionals | TEXT, N 
- color | VARCHAR(150), N
- interior color | VARCHAR(150), N
- precedent owners | TINYINT, DEFAULT(1)
- qty stoke | TINYINT, DEFAULT(1)