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

- id | INT, AI UNIQUE NOTNULL
- marca |VARCHART(200) NOTNULL INDEX
- modello |VARCHART(200) NOTNULL INDEX
- versione |VARCHART(200), NULLABLE INDEX
- carrozzeria |VARCHART(100), NULLABLE INDEX
- carburante |VARCHART(100), NOTNULL INDEX
- chilometraggio |DECIMAL(8, 2), NULLABLE INDEX
- potenza |FLOAT, NULLABLE INDEX
- cambio |VARCHART(50), NOTNULL INDEX
- emissioni | VARCHART(50), NULLABLE INDEX
- numero_posti |TIKYINT, NULLABLE INDEX
- numero_porte |TINYINT, NULLABLE INDEX
- venditore |VARCHART(100), NOTNULL INDEX
- condizioni_veicolo |VARCHART(100), NULLABLE INDEX
- colore_esterni |VARCHART(100), NULLABLE INDEX
- colore_interni |VARCHART(100), NULLABLE INDEX
- prezzo |DECIMAL(9, 2), NOTNULL INDEX
- anno |YEAR, NULLABLE INDEX
- descrizione |TEXT, NULLABLE