# Sublist3r
è uno strumento di enumerazione dei sottodomini progettato per individuare sottodomini associati a un dominio target. È uno strumento utile per gli analisti di sicurezza informatica e gli amministratori di sistema per identificare potenziali punti di ingresso o vulnerabilità nel perimetro di sicurezza di un dominio.

Ecco alcuni comandi comuni utilizzati con Sublist3r:

# sublist3r -d [dominio]
Questo è il comando base per avviare Sublist3r e specificare il dominio di destinazione. Sublist3r eseguirà quindi una scansione per individuare i sottodomini associati al dominio specificato.
# -o, --output [file]
Questo comando consente di specificare un file di output dove salvare i risultati della scansione dei sottodomini. È utile per archiviare e analizzare i risultati in un secondo momento.
# -b, --bruteforce
Abilita la modalità di forza bruta per cercare sottodomini non comuni o nascosti. Questa opzione può aumentare il tempo necessario per completare la scansione, ma può anche rivelare sottodomini non identificati con altri metodi.
# -p, --ports [ports]
Specifica una lista di porte da esaminare per ciascun sottodominio identificato. Questo può essere utile per individuare servizi o applicazioni in esecuzione su specifiche porte nei sottodomini.
# -e, --engines [engines]
Specifica una lista di motori di ricerca da utilizzare per la scansione dei sottodomini. Sublist3r può utilizzare diversi motori di ricerca (come Google, Bing, Yahoo, etc.) per individuare i sottodomini associati a un dominio.
# -t, --threads [threads]
Imposta il numero di thread da utilizzare per eseguire la scansione dei sottodomini. Un numero maggiore di thread può accelerare la scansione, ma potrebbe anche aumentare il carico sul sistema.
# -v, --verbose
Aumenta il livello di dettaglio delle informazioni di output durante la scansione dei sottodomini.
# -h, --help
Visualizza l'elenco dei comandi disponibili e le relative descrizioni.
