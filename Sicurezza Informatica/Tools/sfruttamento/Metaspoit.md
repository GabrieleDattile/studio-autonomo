# Metasploit 
è un framework open source per i test di penetrazione che consente agli hacker di identificare, sfruttare e convalidare le vulnerabilità dei sistemi informatici
È uno strumento versatile che consente agli hacker di accedere a una vasta gamma di exploit, payload e moduli ausiliari

Ecco come si può utilizzare Metasploit:
# Console Metasploit
È possibile lanciare Metasploit da console o da interfaccia grafica Per lanciare la console basta utilizzare da una shell il comando:
# msfconsole

Altrimenti per l’interfaccia grafica:
# msfgui

# Comandi Metasploit
Vediamo adesso alcuni dei comandi più utili
Il primo dei quali è sicuramente connect che permette di connetterci ad un host remoto (similmente a netcat o telnet):
# msf > connect www.html.it 80

Esistono poi comandi come ping e nmap che non hanno bisogno di grandi presentazioni:
# msf > ping www.html.it
# msf > nmap -T5 -A www.html.it

per altri comandi consultare il comando msfconsole -h
