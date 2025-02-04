# L’indirizzamento IP
è il sistema che permette di identificare e comunicare tra i dispositivi connessi a una rete. Ogni dispositivo ha un indirizzo IP univoco, che è una sequenza di numeri o lettere, che lo distingue dagli altri. Gli indirizzi IP possono essere di due tipi: IPv4 e IPv6.

# IPv4 
è la versione più usata e consiste di quattro gruppi di numeri da 0 a 255, separati da un punto. Ad esempio, 192.168.1.1 è un indirizzo IPv4. Ci sono circa 4,3 miliardi di indirizzi IPv4 possibili, ma molti di essi sono riservati per usi speciali, come le reti private o i servizi di internet.

# IPv6 
è la versione più recente e consiste di otto gruppi di quattro cifre esadecimali, separati da due punti. Ad esempio, 2001:0db8:85a3:0000:0000:8a2e:0370:7334 è un indirizzo IPv6. Ci sono circa 340 undecilioni di indirizzi IPv6 possibili, il che rende molto improbabile che si esauriscano.
![Principali-differenze-tra-IPv4-e-IPv6-nelle-reti-960x480](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/67f836cb-dbe5-4ea0-8ad5-e882fe5c0563)


# Il subnetting
è il processo di suddividere una rete in sottoreti più piccole, per gestire meglio il traffico e la sicurezza. Ogni sottorete ha un indirizzo di rete, che identifica la sottorete, e una maschera di sottorete, che indica quanti bit dell’indirizzo IP sono usati per la rete e quanti per gli host. Ad esempio, 192.168.1.0/24 è un indirizzo di rete con una maschera di sottorete di 24 bit, il che significa che i primi 24 bit dell’indirizzo IP sono usati per la rete e gli ultimi 8 bit per gli host. In questo caso, ci sono 256 indirizzi IP possibili nella sottorete, da 192.168.1.0 a 192.168.1.255.
![lettera_tcpip](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/44c8369d-589e-487d-b9ac-3129b47197c4)


Gli indirizzi IP funzionano in combinazione con i protocolli di rete, come il TCP/IP, che stabiliscono le regole e le procedure per la trasmissione dei dati. Quando un dispositivo vuole comunicare con un altro, deve prima risolvere il suo indirizzo IP, usando un servizio di nome di dominio (DNS), che traduce i nomi di dominio, come www.google.com, in indirizzi IP. Poi, il dispositivo invia i dati in pacchetti, che sono unità di informazione con un’intestazione e un contenuto.
L’intestazione contiene l’indirizzo IP di origine e di destinazione, oltre ad altre informazioni utili per il routing. Il contenuto contiene i dati effettivi da trasmettere. I pacchetti viaggiano attraverso la rete, passando da un router all’altro, fino a raggiungere la destinazione, dove vengono ricomposti in un messaggio completo.
