# protocollo di rete 
è un insieme di regole e procedure che definisce come i dispositivi comunicano tra loro su una rete. Esistono diversi protocolli di rete per svolgere compiti specifici, come trasferire dati, stabilire connessioni, risolvere nomi e così via. Ecco una breve descrizione di alcuni protocolli comuni:

# TCP 
(Transmission Control Protocol) è un protocollo che garantisce la consegna affidabile dei dati, controllando che tutti i pacchetti inviati siano ricevuti correttamente dal destinatario. TCP stabilisce una connessione tra i dispositivi prima di trasmettere i dati e li suddivide in segmenti numerati. TCP richiede anche una conferma di ricezione per ogni segmento e, in caso di perdita o errore, lo invia nuovamente. TCP è usato per applicazioni che richiedono una trasmissione dati accurata, come il web, la posta elettronica e il trasferimento di file.

# UDP 
(User Datagram Protocol) è un protocollo che trasmette i dati senza garantirne l’affidabilità, senza controllare se i pacchetti inviati sono arrivati a destinazione. UDP non stabilisce una connessione tra i dispositivi e non richiede una conferma di ricezione per i datagrammi inviati. UDP è usato per applicazioni che richiedono una trasmissione dati veloce e che possono tollerare la perdita o l’alterazione di alcuni pacchetti, come la voce, il video e i giochi online.
![1627941441-header](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/227b34cf-d919-49ff-8a55-cc5904c6e80e)


# ICMP 
(Internet Control Message Protocol) è un protocollo che trasmette messaggi di controllo e di errore tra i dispositivi su una rete. ICMP non trasporta dati utente, ma serve a monitorare e diagnosticare lo stato della rete. ICMP è usato per funzioni come il ping, il traceroute e la notifica di errori come la destinazione irraggiungibile, il tempo scaduto e la ridirezione del percorso.
![icmp_ping_example](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/697ec2d8-11d4-4725-885e-445cc976aca5)

![how_icmp_works](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/3df033a6-3dc0-4f3e-9766-d2421910466a)


# DHCP 
(Dynamic Host Configuration Protocol) è un protocollo che assegna automaticamente gli indirizzi IP ai dispositivi che si connettono a una rete. DHCP permette di gestire in modo efficiente lo spazio degli indirizzi IP, evitando conflitti e duplicazioni. DHCP è usato per configurare i parametri di rete come l’indirizzo IP, la subnet mask, il gateway e i server DNS.
![DHCP-protocol](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/7740d5ba-279a-498b-9ec2-196a45935c86)



# DNS 
(Domain Name System) è un protocollo che traduce i nomi di dominio in indirizzi IP e viceversa. DNS permette di usare nomi facili da ricordare per identificare i siti web e i servizi online, invece di usare numeri. DNS è usato per risolvere le richieste dei client e indirizzarli verso i server appropriati.

![744f05243c41e658909b26ac02a82dc2ec2017f0](https://github.com/GabrieleDattile/Percorso-da-Zero-a-Pentester/assets/137740496/6742fbd6-2bde-40e5-b14a-ca85ce0dda2c)


# FTP
(File Transfer Protocol) è un protocollo di comunicazione che serve per il trasferimento di file tra un server e un client su una rete informatica. FTP si basa su un'architettura di tipo client-server e usa connessioni separate per gestire i comandi e i dati. Il client si connette al server tramite la porta 21 TCP e stabilisce il canale comandi, attraverso il quale si scambiano comandi e risposte. Per lo scambio effettivo di dati, come un esempio un file, si apre il canale dati, che può essere di due tipi: attivo o passivo. Nel canale dati attivo, il client apre una porta casuale e la comunica al server, che si connette a essa. Nel canale dati passivo , il server apre una porta casuale e la comunica al client, che si connette e essa. FTP richiede l'autorizzazione del client tramite nome utente e password, ma il server 
