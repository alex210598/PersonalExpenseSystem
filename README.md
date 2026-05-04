Requisiti per l’esecuzione. 

Per garantire il corretto funzionamento del software sono necessari i seguenti componenti:

Interprete necessario:
Python 3.x: Il codice è scritto in Python 3 ed è compatibile con le versioni più recenti (3.8+). 
Non è necessario un compilatore, trattandosi di un linguaggio interpretato.

Librerie standard utilizzate:
Il progetto è stato sviluppato utilizzando esclusivamente la Standard Library di Python per massimizzare la portabilità e facilitare la correzione.
Non è necessario installare pacchetti esterni.

- sqlite3: Utilizzata per creare, connettere e interrogare il database relazionale spese_personali.db.
- os: Utilizzata per gestire i percorsi dei file (percorsi relativi/assoluti) in modo che il programma funzioni correttamente su diversi sistemi operativi (Windows, macOS, Linux).
- datetime: Fondamentale per la validazione dei dati.


Istruzioni dettagliate per eseguire il programma
1. Istruzioni di compilazione:
Il sistema è sviluppato in Python, un linguaggio di programmazione interpretato.
Pertanto, non è richiesta alcuna fase di compilazione preventiva.
Il codice sorgente viene eseguito direttamente dall'interprete Python.

2. Istruzioni di avvio: 
Per avviare correttamente l'applicazione, segui questi passaggi:
Apertura Terminale: Apri il terminale (o Prompt dei comandi su Windows, Terminale su Linux).
Ambiente: Assicurati di avere Python 3 installato digitando python --version oppure python3 --version oppure py --version.
Posizionamento: Naviga fino alla cartella principale del progetto (quella che contiene le cartelle src e sql).
Esempio: cd percorso/della/cartella/PersonalExpenseSystem

4. Dalla cartella principale del progetto, digita uno dei seguenti comandi e premi Invio:
python src/main.py oppure py src/main.py

5. Inizializzazione:
Al primo avvio, il programma individuerà automaticamente lo script sql/database.sql e creerà il file del database src/spese_personali.db.
Interfaccia: Comparirà immediatamente il menu principale testuale con le 5 opzioni di gestione.
