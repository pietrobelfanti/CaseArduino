# DIARIO
### LUOGO
Trevano
### DATA
02.09.2016
## LAVORI SVOLTI
Ore 8.20 - 11.35: Introduzione al Modulo 306, lettura degli obbiettivi del modulo, presentazione del primo progetto, teoria sul versioning, introduzione a Git e GitHub. 
Ore 13.15 - 16.00: Creazione profilo GitHub, installazione di Git e SourceTree, creazione e modifica del file ".gitconfig" prova di creazione di un progetto su GitHub più la connessione a questo progetto tramite SourceTree.
## PROBLEMI RISCONTRATI E SOLUZIONI
Ho riscontrato un problema di proxy, quando da SourceTree dovevo connettermi al mio progetto situato su GitHub, l'errore in questione era il 443 (https).
In pratica il mio file ".gitconfig" non veniva visto da SourceTree. Per risolvere il problema è bastato settare il proxy da linea di comando con i seguenti comandi: 
"git config --global http.proxy http://nomeutente:password@proxy.server.com:8080" 
"git config --global http.proxy https://nomeutente:password@proxy.server.com:8080"
## PUNTO DELLA SITUAZIONE RISPETTO ALLA PIANIFICAZIONE
## PROGRAMMA DI MASSIMA PER LA PROSSIMA GIORNATA