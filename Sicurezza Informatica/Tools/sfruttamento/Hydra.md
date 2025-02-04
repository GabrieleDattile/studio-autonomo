# Hydra 
è uno strumento che permette di effettuare attacchi di forza bruta su vari protocolli di rete, come FTP, HTTP, SSH, Telnet e altri. Per usare Hydra, devi seguire questi passi:

Apri un terminale e digita 
# hydra 
per vedere le opzioni principali. Puoi anche usare 
# ./xhydra 
per avviare l’interfaccia grafica.


Scegli il protocollo da attaccare, il target, il nome utente o la lista dei nomi utente, la password o la lista delle password, e il numero di thread da usare. Puoi anche usare opzioni aggiuntive per personalizzare l’attacco, come il timeout, il proxy, i cookie, i parametri HTTP e altri.


Lancia l’attacco e aspetta i risultati. Hydra ti mostrerà quali credenziali sono state trovate valide per il protocollo scelto.

Per esempio, se vuoi attaccare il protocollo SSH del server 192.168.1.1 con il nome utente root e la lista delle password /usr/share/lista/password.txt, puoi usare questo comando:

hydra -l root -P /usr/share/lista password.txt 192.168.1.1 -t 4 ssh

Questo significa:

# -l root
usa il nome utente root
# -P /usr/share/lista/password.txt
usa la lista delle password /usr/share/lista/password.txt
# 192.168.1.1 
usa il target 192.168.1.1
# -t 4
usa 4 thread
# ssh
usa il protocollo ssh
