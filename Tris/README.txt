Musone Mattia

Progetto Tris

Per la creazione di questo progetto sono state utilizzate due Activity

- ActivityMain: Gestisce la parte della tabella del tris
- ChooserActivity: � la Activity principale che sia avvia inizialmente

La seconda permette all'utente di scegliere tra due differenti modalit�:
- uomo vs uomo

- uomo vs ai che a sua volta si divide in

	- facile
	- medio
	- difficile
	- extreme

Queste modalit� prevedono algoritmi diversi per la risoluzione della partita.
Tra modalit� difficile ed extreme non cambia molto. 
L'intelligenza dell'algoritmo extreme non � troppo "smart" in quanto non prevede le sue stesse future mosse, tuttavia tiene testa al giocatore.
Il turno iniziale tra il giocatore e la macchina � casuale.

Per creare la tabella del tris ho impiegato nove imageview che setter� con delle immagini in base al tipo di giocatore.

Al termine della partita verr� notificato il giocatore vincente tramite un AlertDialog che permetter� una nuova partita o di uscire dal gioco.

E' stata utilizzata qualche semplice animazione.

