Come funziona

Un solo file HTML che gira direttamente nel browser — nessun server, 
nessuna connessione internet necessaria.
Salvataggio — due livelli:
Memoria del browser (localStorage): ogni volta che aggiungi o modifichi un contatto, 
i dati vengono salvati automaticamente nel browser. Se chiudi e riapri il file nello stesso browser, 
i tuoi contatti sono ancora lì senza fare nulla.
Il file .txt (il tuo vero archivio): 
i dati JSON vivono in un semplice file di testo sul tuo computer. Decidi tu quando leggere o scrivere, 
con due pulsanti — Carica .txt (importa i dati nell'app) e Salva .txt (scrive i contatti aggiornati sul file).

Uso tipico:

Apri crm-artigiano.html in Chrome o Edge → clicca Carica .txt 
e scegli il tuo crm_clienti.txt → i contatti appaiono → aggiungi o modifica → clicca Salva .txt → chiudi. 

Condivisione / più dispositivi:

Metti crm_clienti.txt in una cartella Dropbox condivisa. Chiunque abbia il file HTML 
e accesso a quella cartella può lavorare sugli stessi dati. Attenzione: non modificare 
in due contemporaneamente — non c'è gestione dei conflitti, vince l'ultimo che salva.

⚠️ Importante: il file .txt è l'unica cosa che conta nel lungo periodo. 
La cache del browser può essere svuotata in qualsiasi momento e perderesti le modifiche non salvate. 
Fai copie regolari di crm_clienti.txt (ogni settimana, o prima di sessioni di lavoro importanti) 
rinominandole con la data: crm_clienti_2026-06-29.txt.
