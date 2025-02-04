# Nikto 
è uno strumento open source per la valutazione delle vulnerabilità dei server web. È molto popolare e facile da usare per trovare rapidamente potenziali problemi e vulnerabilità. Nikto esegue test completi su server web per diversi elementi, inclusi oltre 6.700 file/programmi potenzialmente pericolosi, verifica la presenza di versioni obsolete di oltre 1.250 server e problemi specifici della versione su oltre 270 server

Ecco come si può utilizzare Nikto:

Scansione di base: La scansione più semplice che si può effettuare con Nikto richiede un hostname o IP come parametro. Ecco un esempio di comando di base:
# nikto -h 192.168.0.2 
Questo comando esegue una scansione sulla porta 80 (HTTP) dell’host 192.168.0.2

Scansione su porte diverse: Per specificare una porta diversa, si usa il parametro -p. Ecco un esempio:

# nikto -h 192.168.0.2 -p 443
Questo comando esegue una scansione sulla porta 443 dell’host 192.168.0.2

Scansione su più porte: Se si vogliono specificare più porte, si usa la seguente sintassi
# nikto -h 192.168.0.2 -p 80,88,443
Questo comando esegue una scansione sulle porte 80, 88 e 443 dell’host 192.168.0.2

Scansione su più host: Se abbiamo più host da scansionare, possiamo passare un file al parametro -h. Ecco un esempio:
# nikto -h lista_siti.txt
In questo caso, lista_siti.txt deve contenere un host per ogni linea
