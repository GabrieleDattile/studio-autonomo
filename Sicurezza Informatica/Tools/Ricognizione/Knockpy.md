# Knockpy
è uno strumento di enumerazione dei sottodomini che consente agli utenti di individuare e analizzare i sottodomini associati a un dominio target. Utilizza una varietà di fonti e tecniche per raccogliere informazioni sui sottodomini, compresi i record DNS, i servizi di hosting di terze parti e altro ancora. Ecco alcuni comandi comuni utilizzati con Knockpy:

# knockpy [dominio]
Questo è il comando base per avviare Knockpy e specificare il dominio di destinazione. Knockpy eseguirà quindi una scansione per individuare e analizzare i sottodomini associati al dominio specificato.
# -w, --wordlist [file_wordlist]
Specifica un file di wordlist contenente una lista di possibili sottodomini da cercare. Knockpy utilizzerà questa wordlist per generare una lista di sottodomini da testare.
# -o, --output [file_output]
Specifica un file di output dove salvare i risultati della scansione dei sottodomini. È utile per archiviare e analizzare i risultati in un secondo momento.
# -j, --json
Abilita il formato di output JSON per i risultati della scansione. Questo può essere utile se si desidera integrare i risultati di Knockpy con altri strumenti o script.
# -c, --csv
Abilita il formato di output CSV per i risultati della scansione. Questo può essere utile se si desidera importare i risultati di Knockpy in un foglio di calcolo o in un database.
# -n, --no-ip
Esclude l'analisi degli indirizzi IP associati ai sottodomini durante la scansione. Questo può essere utile se si desidera concentrarsi solo sui nomi dei sottodomini senza considerare gli indirizzi IP.
# -v, --verbose
Aumenta il livello di dettaglio delle informazioni di output durante la scansione dei sottodomini. Questo può essere utile per monitorare lo stato della scansione e identificare eventuali problemi o errori.
# -h, --help
Visualizza l'elenco dei comandi disponibili e le relative descrizioni.
