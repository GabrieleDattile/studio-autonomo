# Sqlmap

Questo strumento permette di automatizzare il rilevamento e lo sfruttamento di difetti nelle SQL injection, consentendo di prendere il controllo dei server DBMS
Ecco come si può utilizzare SQLmap:

Scansione di base: La scansione più semplice che si può effettuare con SQLmap richiede un hostname o IP come parametro. Ecco un esempio di comando di base:
# sqlmap -u http://sito.com
Questo comando esegue una scansione sulla porta 80 (HTTP) dell’host specificato

Scansione su porte diverse: Per specificare una porta diversa, si usa il parametro -p. Ecco un esempio:
# sqlmap -u http://sito.com -p 443
Questo comando esegue una scansione sulla porta 443 dell’host specificato

Scansione su più porte: Se si vogliono specificare più porte, si usa la seguente sintassi
# sqlmap -u http://sito.com -p 80,88,443
Questo comando esegue una scansione sulle porte 80, 88 e 443 dell’host specificato

Scansione su più host: Se abbiamo più host da scansionare, possiamo passare un file al parametro -u. Ecco un esempio:
# sqlmap -u lista_siti.txt
In questo caso, lista_siti.txt deve contenere un host per ogni linea
