# Recon-ng 
è un framework di penetration testing progettato per l'analisi delle informazioni e la raccolta di dati durante le fasi di ricognizione e intelligence gathering. Consente agli utenti di eseguire una varietà di attività di raccolta di informazioni, come l'enumerazione dei sottodomini, l'acquisizione di indirizzi email, la scansione delle vulnerabilità e molto altro ancora. Ecco alcuni comandi comuni utilizzati con Recon-ng:

# show modules
Mostra l'elenco dei moduli disponibili nel framework Recon-ng. I moduli includono strumenti per diverse attività di raccolta di informazioni, come l'enumerazione dei sottodomini, l'acquisizione di indirizzi email, la scansione delle vulnerabilità e altro ancora.
# use [modulo]
Seleziona un modulo specifico per l'utilizzo. Sostituisci [modulo] con il nome del modulo che desideri utilizzare. Ad esempio, use recon/domains-contacts/pgp_search seleziona il modulo per la ricerca di indirizzi email PGP associati ai sottodomini.
# set [opzione] [valore]
Imposta le opzioni per il modulo corrente. Ad esempio, set SOURCE cnn.com imposta il dominio di origine per la ricerca di indirizzi email PGP.
# run
Esegue il modulo corrente con le opzioni impostate. Questo comando avvia l'esecuzione del modulo selezionato, che può includere la raccolta di dati, l'analisi delle informazioni e altro ancora.
# back
Ritorna al menu principale. Questo comando consente di tornare al menu principale di Recon-ng dopo aver selezionato e utilizzato un modulo specifico.
# help
Visualizza l'elenco dei comandi disponibili e le relative descrizioni. Questo comando è utile per ottenere informazioni su come utilizzare specifici comandi o moduli.
workspaces: Visualizza l'elenco dei workspaces attualmente disponibili. I workspaces sono spazi di lavoro separati utilizzati per organizzare e archiviare i dati raccolti durante le attività di penetration testing.
