# Il modello OSI
(Open Systems Interconnection) è uno standard stabilito dall’ISO (International Organization for Standardization) nel 1984, che divide le funzioni di rete in 7 livelli. Ogni livello ha una funzionalità specifica e si basa sui livelli sottostanti. 

# I livelli del modello OSI sono:


![438px-Rm-osi_parallel_it svg](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/152015ed-bbef-4433-93b0-9ab044325f3c)


# Livello 1
# fisico
Si occupa della trasmissione dei bit sul mezzo fisico, come cavi, fibre ottiche o onde radio.

# Livello 2 
# collegamento dati
Si occupa della suddivisione dei dati in unità chiamate frame e della gestione degli errori e del controllo di flusso tra i dispositivi collegati.

# Livello 3
# rete 
Si occupa della suddivisione dei dati in unità chiamate pacchetti e della determinazione del percorso migliore per inviarli tra le reti.

# Livello 4
# trasporto
Si occupa della suddivisione dei dati in unità chiamate segmenti e della garanzia della consegna affidabile e ordinata dei dati tra le applicazioni.

# Livello 5
# sessione
Si occupa della gestione delle connessioni logiche tra le applicazioni e della sincronizzazione dei dati.

# Livello 6
# presentazione
Si occupa della conversione dei dati tra i formati usati dalle applicazioni e i formati usati dalla rete, come la codifica, la compressione e la cifratura.

# Livello 7
# applicazione
Si occupa della fornitura dei servizi di rete alle applicazioni, come il trasferimento di file, la posta elettronica e il web.

# Il modello TCP/IP
(Transmission Control Protocol/Internet Protocol) è uno standard de fatto usato per tutte le reti, incluso Internet, che divide le funzioni di rete in 4 livelli. Ogni livello ha un insieme di protocolli specifici che definiscono le regole di comunicazione. 
# I livelli del modello TCP/IP sono:


![1](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/e66f9c16-f95b-4e61-8630-ada5ebdc2f18)

# Livello 1
# collegamento
Corrisponde ai livelli fisico e collegamento dati del modello OSI e si occupa della trasmissione dei dati tra i dispositivi collegati alla stessa rete locale.

# Livello 2
# internet
Corrisponde al livello rete del modello OSI e si occupa della trasmissione dei dati tra le reti diverse, usando il protocollo IP (Internet Protocol) per assegnare un indirizzo univoco a ogni dispositivo e il protocollo ICMP (Internet Control Message Protocol) per gestire gli errori e i messaggi di controllo.

# Livello 3
# trasporto
Corrisponde al livello trasporto del modello OSI e si occupa della trasmissione dei dati tra le applicazioni, usando il protocollo TCP (Transmission Control Protocol) per garantire la consegna affidabile e ordinata dei dati e il protocollo UDP (User Datagram Protocol) per garantire la consegna rapida e senza connessione dei dati.

# Livello 4
# applicazione
Corrisponde ai livelli sessione, presentazione e applicazione del modello OSI e si occupa della fornitura dei servizi di rete alle applicazioni, usando protocolli come FTP (File Transfer Protocol), SMTP (Simple Mail Transfer Protocol) e HTTP (Hypertext Transfer Protocol)

