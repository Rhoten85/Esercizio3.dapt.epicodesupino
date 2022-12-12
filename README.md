# Esercizio3.dapt.epicodesupino

Nel creare i dataset in CSV, per l'esercizio 2, ho riscontrato una serie di difficoltà inerenti all'interruzione di riga, che mi ha portato alle
seguenti deduzioni sotto elencate, per Excel e Google Sheet ho trascritto il risultato determinato dalla modalità di apertura/importazione del file, 
dove NO sta ad indicare che non riconosce l'interruzione di riga e SI dove il software la riconosce, nelle modalità Importa Dati o Doppio click sul file per Excel, e nelle modalità Apri con upload da browser o Importa di Google Sheet con upload da browser.


Dataset 1, separatore [,]: 
Excel = Importa dati da testo/csv SI, Doppio click > Testo in colonne NO. 
GSheet = Apri  SI, Importa > Suddividi Testo in colonne SI.

Dataset 2, Separatore [;]: 
Excel = Importa dati da testo/csv NO, Doppio Click Si. 
GSheet = Apri & Importa > Suddividi Testo in colonne SI (ma non riconosce la virgola nella cella regista film il Postino).

Dataset 3, Separatore[TAB]:
Excel = Importa dati da testo/csv NO, Doppio click > Testo in colonne NO. (motivo per il quale ho fatto il Dataset3micro senza interruzione di riga)
GSheet = Apri  SI (ma non riconosce gli apici all'interno dei doppi apici), Importa SI (riconosce gli apici all'interno dei doppi apici).
