# CMSmap 
è uno strumento progettato per eseguire una scansione automatica e una valutazione della sicurezza su siti web che utilizzano sistemi di gestione dei contenuti (CMS). Questo strumento identifica la versione del CMS utilizzata e cerca vulnerabilità conosciute, consentendo agli utenti di valutare la sicurezza del sito e prendere le misure appropriate per mitigare i rischi. Ecco alcuni comandi comuni utilizzati con CMSmap:
# cmsmap [URL]
Questo è il comando base per avviare CMSmap e specificare l'URL del sito web da analizzare. CMSmap eseguirà quindi una scansione per identificare il CMS utilizzato e cercare vulnerabilità conosciute.
# -t, --target [URL]
Specifica l'URL del sito web da analizzare. Questo comando è equivalente al comando base cmsmap [URL].
# -v, --verbose
Aumenta il livello di dettaglio delle informazioni di output durante la scansione del sito web. Questo può essere utile per monitorare lo stato della scansione e identificare eventuali problemi o errori.
# -F, --fingerprint
Esegue solo il rilevamento della versione del CMS senza eseguire la scansione di vulnerabilità. Questo comando può essere utile se si desidera solo identificare la versione del CMS senza eseguire un'analisi approfondita delle vulnerabilità.
# -f, --force
Forza la scansione anche se il CMS non viene rilevato automaticamente. Questo può essere utile se si sa con certezza quale CMS è utilizzato sul sito web e si desidera eseguire una scansione specifica per quel CMS.
# -m, --modules
Visualizza un elenco dei moduli disponibili per la scansione. I moduli includono vulnerabilità specifiche del CMS e tecniche di enumeration.
# -h, --help
isualizza l'elenco dei comandi disponibili e le relative descrizioni.
