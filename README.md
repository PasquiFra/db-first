# Esercizio: DB First
nome repo: db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.

Colonne |   Tipo |  Attributi
 ---| ---|  ---|
id | int | auto_increment
targa| varchar(10) |  primary_key 
marca | varchar | notnull
modello | varchar | notnull
cilindrata | small int | notnull
potenza |  small int | notnull 
carburante | varchar(3) | notnull
chilometraggio | medium Int | notnull
cambio  | varchar(1) | notnull
immatricolazione | year | notnull
proprietari prec. | tinyInt | notnull, default(1)
classe veicolo | varchar(15) | notnull
colore | varchar(30) | notnull
prezzo  | mediumInt | null
Classe di emissioni | varchar (6) | notnull, default('n.d.')
Trazione | varchar(10) | notnull 
foto | varchar(255) | null
descrizione | text | null
motore originale | tinyInt/bool | notnull, default(1)