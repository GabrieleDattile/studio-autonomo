# AMASS 
è uno strumento di intelligence gathering progettato per l'analisi delle infrastrutture online, specialmente per l'individuazione e la raccolta di informazioni sui sottodomini associati a un dominio target. È utilizzato principalmente dagli esperti di cybersecurity e dagli ethical hacker per scoprire possibili punti di ingresso o vulnerabilità nelle infrastrutture online. Ecco alcuni comandi comuni utilizzati con AMASS:

# amass enum -d [dominio]
Questo è il comando base per avviare AMASS e specificare il dominio di destinazione per l'enumerazione dei sottodomini. AMASS eseguirà quindi una scansione per individuare e raccogliere informazioni sui sottodomini associati al dominio specificato.
# -o, --output [file]
Specifica un file di output dove salvare i risultati della scansione dei sottodomini. È utile per archiviare e analizzare i risultati in un secondo momento.
# -active
Esegue la scansione attiva dei sottodomini utilizzando tecniche come la trasversalità di directory, la ricerca di certificati SSL e altro ancora. Questa opzione può aumentare il numero di sottodomini identificati, ma potrebbe anche generare più rumore.
# -config [file]
Specifica un file di configurazione personalizzato per AMASS. Questo può includere impostazioni personalizzate per la scansione, come elenchi di blacklist o di whitelist per i sottodomini.
# -dir [directory]
Specifica una directory da utilizzare per l'output della scansione. È utile per organizzare i risultati della scansione in una struttura di directory specifica.
# -brute
Abilita la modalità di forza bruta per cercare sottodomini non comuni o nascosti. Questa opzione può aumentare il tempo necessario per completare la scansione, ma può anche rivelare sottodomini non identificati con altri metodi.
# -v, --verbose
Aumenta il livello di dettaglio delle informazioni di output durante la scansione dei sottodomini. Questo può essere utile per monitorare lo stato della scansione e identificare eventuali problemi o errori.
