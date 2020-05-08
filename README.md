# Scriviamo un RepoGame: esercitazione sull'uso di GitHub

Avete mai giocato ad un gioco di ruolo cartaceo, in cui un master presenta agli altri giocatori al tavolo delle sfide da affrontare con i loro personaggi? Ecco: in un librogame il giocatore è uno solo, il lettore, e il master è il libro stesso!

I librogame sono libri-gioco nati negli anni ottanta. Invece di essere letti dall'inizio alla fine come dei normali libri, alla fine di ogni capitolo il lettore viene comunemente posto davanti ad un *bivio*, una scelta da compiere per determinare il prossimo capitolo da leggere e il destino del protagonista. Un esempio di bivio è il seguente: "se decidi di inoltrarti nella foresta, vai al capitolo 56; se dicidi invece di rimanere sulla strada principale, val al capitolo 38". 

In questo esercizio costruiremo un **repogame**, un librogame scritto collaborativamente utilizzando un repository git. Ogni capitolo sarà costituito da una cartella numerata da 01 a 99, e il contenuto sarà solo un README.md contenente il titolo del capitolo, il testo e i collegamnti ai capitoli successivi. Ogni capitolo può avere uno o più possibili capitoli successivi, o anche nessuno, determinando così la fine dell'avventura dell'eroe con una gloriosa vittoria o una terribile disfatta.

I README.md seguono la sintassi markdown. Puoi trovare un'ottima guida [qui](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Per poter contribuire alla scrittura del repogame dovrai:
- controllare le issue aperte con le richieste dei capitoli da scrivere, scegliendone uno. Supponiamo il capitolo *99*;
- creare un nuovo branch per la scrittura del capitolo, es. *capitolo-99*;
- creare una cartella nominata con il numero del capitolo e contenente solo un README.md: es. */99/README.md*;
- scrivere il contenuto del capitolo nel README.md prendendo spunto dai capitoli precedenti;
- a meno che la storia non sia conclusa, aggiungere dei link a dei capitoli successivi (possibilmente non ancora esistenti);
- creare uno (o più) commit sul branch creato, completando il capitolo;
- creare una *merge request*, ovvero una pull request per richiedere il merge del branch nel master;
- attendere una review da parte di un revisore;
- se richiesto, aggiungere eventuali altri *follow-up commit* sul branch per soddisfare le richieste del revisore;
- soddisfatte le richieste del revisore, la pull request verrà chiusa con un merge. Il nuovo capitolo è ora visibile sul master!
- chiudere la issue per il capitolo appena scritto (issue risolta)
- creare una issue per ognuno dei capitoli non ancora scritti ma indicati come successivi, chiedendo così ad altri di continuare la storia

***********************

La storia che scriveremo narra di un giovane avventuriero nelle terre di Havalance. Come da buona tradizione dei giochi di ruolo cartacei, l'avventuriero si guadagna da vivedere come mercenario, prendendo commissioni per ritrovare cittadini misteriosamente scomparsi, uccidere creature che minacciano i villaggi, o recuperare preziosi manufatti da antichi sotterranei.

Insomma, le solite cose! Per iniziare la tua avventura, vai al capitolo [**01**](/01/README.md).
