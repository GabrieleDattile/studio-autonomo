# Netcat 
è uno strumento a riga di comando, responsabile della scrittura e della lettura dei file in rete. 
Utilizza i protocolli di rete TCP/IP e UDP per lo scambio di dati

Netcat può essere utilizzato per una varietà di funzioni, tra cui:

Diagnosi di errori e problemi che mettono a rischio la funzionalità e la sicurezza di una rete.
Port scanning.
Streaming dei dati.
Trasmissioni di dati più semplici.
Impostazione di server web e di chat.
Avvio di richieste tramite e-mail.

Netcat come client-server
Netcat può essere utilizzato come server e lasciato in ascolto su una certa porta. Ad esempio, per ascoltare sulla porta 2389, si può usare il comando:
# nc -l 2389

Per connettersi a una porta (ad esempio, la 2389), si può usare il comando:
# nc localhost 2389
Se si scrive sul lato del client, arriverà accanto al server

Trasferimento di file con Netcat: Netcat può essere utilizzato per trasferire file. Ad esempio, per trasferire un file chiamato ‘testfile’ dal client al server, si può usare il comando:
# cat testfile | nc localhost 2389
sul lato del client, e il comando:
# nc -l 2389 > test
sul lato del server

# Timeout con Netcat
A volte, quando si apre una connessione, non si vuole che rimanga aperta a tempo indeterminato. Per risolvere questo problema, si può usare l’opzione -w per chiudere la connessione tra client e server dopo un certo numero di secondi


# Supporto IPV6 con Netcat
Le opzioni -4 e -6 forzano Netcat ad utilizzare rispettivamente il protocollo IPv4 o IPv6
