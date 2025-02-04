# DnsRecon

DNSRecon è uno script Python che fornisce la possibilità di eseguire diverse operazioni relative ai record DNS.
Ecco come si usa:

# dnsrecon -d DOMAIN -D DICTIONARY -t TYPE --xml FILE

# -d 
DOMAIN specifica il dominio target.
# -D 
DICTIONARY specifica il file di dizionario da utilizzare per il brute force dei nomi host.
# -t 
TYPE specifica il tipo di scansione da eseguire.
# --xml
FILE salva l’output in un file XML

# Espansione del dominio di primo livello
DNSRecon può cercare tutti i possibili domini di primo livello per un dato dominio. Ad esempio, se il tuo dominio è “esempio”, DNSRecon può cercare “esempio.com”, “esempio.net”, “esempio.org”, ecc.

# Ricerca inversa su intervalli IP
Se hai un intervallo di indirizzi IP, DNSRecon può cercare quali nomi di dominio sono associati a quegli indirizzi IP.

# Enumerazione generale dei record DNS
DNSRecon può cercare vari tipi di record DNS per un dato dominio. Questi record includono:
MX (Mail Exchange): Indica a quale server di posta inviare le email per quel dominio.
SOA (Start of Authority): Fornisce informazioni generali sul dominio.
NS (Name Server): Indica quali server DNS contengono le informazioni del dominio.
A e AAAA: Indicano l’indirizzo IP del dominio.
SPF (Sender Policy Framework): Utilizzato per validare i server di posta elettronica.
TXT: Può contenere varie informazioni in formato di testo.

# Enumerazione comune dei record SRV
I record SRV sono utilizzati per indicare quali servizi sono disponibili per un dominio. DNSRecon può cercare i record SRV più comuni

# Verifica di tutti i record NS per i trasferimenti di zona
Un trasferimento di zona è un modo per ottenere tutte le informazioni DNS di un dominio. DNSRecon può verificare se è possibile eseguire un trasferimento di zona.
