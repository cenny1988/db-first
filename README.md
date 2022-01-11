# db-first
GOAL: Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

ID: int - primary key\
Marca: varchar(20) - \
Modello: varchar(30) - \
Versione:(es. Plus, Gti, Abarth..) varchar(20) - null\
Carrozzeria:(es. SUV, Monovolume, Berlina..) varchar(30) - null - default(Berlina)\
Cilindrata: smallint\
CV: smallint\
Alimentazione: varchar(20) - default(Benzina)\
Cambio:(es. Manuale, Automatico..) varchar(30) - default(Manuale)\
NumPorte:(es. 3porte, 5porte..) varchar(20) - default(5porte)\
KM: int - default(0)\
PrezzoAcquisto: int - (oppure decimal) \
PrezzoVendita: int - (oppure decimal) \
AnnoImmatricolazione: year \
Proprietari: varchar(60) - default(Nome Concessionaria)\
Stato: varchar(30) - default(Italia)\
Descrizione: text - null\
Optional: text - null\
Targa: varchar(10) - unique null\
