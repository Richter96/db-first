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

- id | INT 
- marca |VARCHART(200)
- modello |VARCHART(200)
- versione |VARCHART(200)
- carrozzeria |VARCHART(100)
- carburante |VARCHART(100)
- chilometraggio |DECIMAL(8, 2)
- potenza |FLOAT
- cambio |VARCHART(50)
- emissioni | VARCHART(50)
- numero_posti |TIKYINT
- numero_porte |TINYINT
- venditore |VARCHART(100)
- condizioni_veicolo |VARCHART(100)
- colore_esterni |VARCHART(100)
- colore_interni |VARCHART(100)
- prezzo |DECIMAL(9, 2)
- anno |YEAR
- descrizione |TEXT, NULLABLE