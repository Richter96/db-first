## data Types:

- strings: [varchar(number), char(number), text, longtext]
- numbers: [tinyint, small/medium int, int, bigint]
- decimals: [float(i, d), duble(i,,d), decimal(i,d)]
- date: [datatime, date, year, time, timestamp]

## attributes:

- NULL/ NOTNULLL
- DEFOULT
- AUTO_INCREMENT
- UNIQUE

# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## entity name: car

## Table name: cars

## Table columns: 

- id | BIGINT, AUTO_INCREMENT UNIQUE NOTNULL
- marca |VARCHAR(50) NOTNULL INDEX
- modello |VARCHAR(80) NOTNULL INDEX
- versione |VARCHAR(100), NULLABLE INDEX
- carrozzeria |VARCHAR(100), NULLABLE INDEX
- carburante |VARCHAR(100), NOTNULL INDEX
- chilometraggio |DECIMAL(8, 2), NULLABLE INDEX
- potenza |FLOAT, NULLABLE INDEX
- cambio |VARCHAR(50), NOTNULL INDEX 
- emissioni | VARCHAR(50), NULLABLE INDEX
- numero_posti |TIKYINT, NULLABLE INDEX
- numero_porte |TINYINT, NULLABLE INDEX
- venditore |VARCHAR(50), DEFAULT('concessonaria') INDEX
- condizioni_veicolo |VARCHAR(50), NULLABLE INDEX
- colore_esterni |VARCHAR(50), NULLABLE INDEX
- colore_interni |VARCHAR(50), NULLABLE INDEX
- prezzo |DECIMAL(9, 2), NOTNULL INDEX
- anno |YEAR, NULLABLE INDEX
- descrizione |TEXT, NULLABLE
