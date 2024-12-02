# lang-it_IT

### LEGGERE QUESTO SE SI DESIDERA EFFETTUARE TRADUZIONI IN UN'ALTRA LINGUA

Questo repository include sedici file di testo principali, ognuno con la propria sezione di traduzioni:

- translations.txt -- queste sono traduzioni generali e vengono caricate ogni volta
- helptext.txt     -- queste sono tutte le sezioni di aiuto e vengono caricate ogni volta
- dashboard.txt    -- queste sono le traduzioni riguardanti la sezione Dashboard
- main.txt         -- queste sono le traduzioni riguardanti la sezione Principale
- shares.txt       -- queste sono le traduzioni riguardanti la sezione Condivisioni
- users.txt        -- queste sono le traduzioni riguardanti la sezione Utenti
- settings.txt     -- queste sono le traduzioni riguardanti la sezione Impostazioni
- plugins.txt      -- queste sono le traduzioni riguardanti la sezione Plugin
- docker.txt       -- queste sono le traduzioni riguardanti la sezione Docker
- vms.txt          -- queste sono le traduzioni riguardanti la sezione Macchine virtuali
- tools.txt        -- queste sono le traduzioni riguardanti la sezione Strumenti
- javascript.txt   -- queste sono le traduzioni riguardanti gli Script javascript
- scripts.txt      -- queste sono le traduzioni riguardanti gli Script locali
- apps.txt         -- queste sono le traduzioni riguardanti la sezione App (Community Applications = CA)
- ca_settings      -- queste sono le traduzioni riguardanti la sezione Impostazioni App (CA)
- javascript.ca.txt-- queste sono le traduzioni riguardanti la sezione App Javascript (CA)

Tutti i nomi dei file sono in minuscolo e devono essere inclusi nel repository per completare le traduzioni.

La rimozione di un particolare file comporta la mancata traduzione di quella sezione e la GUI visualizzerà il testo in inglese originale.

### TRADUZIONI

Ogni file di testo contiene stringhe di testo regolari memorizzate in formato UTF-8 con terminazioni di riga Linux.
Utilizzare un editor di testo che supporti il formato UTF-8 e Linux, come [notepad++](https://notepad-plus-plus.org/downloads)

Il contenuto di ogni file di testo è suddiviso in due parti:

### PARTE 1

Queste sono voci a riga singola visualizzate con il seguente formato:

`testo Inglese originale=testo Straniero tradotto`

Modificare solo il testo dopo il segno di uguale (=) e lasciare il testo inglese originale a sinistra invariato.
La rimozione di una riga o l'omissione di una traduzione dopo il segno di uguale, fa sì che la GUI visualizzi questa riga con il testo Inglese originale.

Il testo tradotto può contenere "caratteri speciali", come barre, parentesi o parentesi quadre che non sono inclusi nel testo chiave,
ma che vengono utilizzati per visualizzare il testo di conseguenza. Esempio:

`Options see Help=Opzioni (vedi Aiuto)`

I caratteri \* e \*\* vengono utilizzati per visualizzare il testo rispettivamente in corsivo e in grassetto. Esempio:

`*Array* must be Stopped to change=*L'array* deve essere **Arrestato** per apportare le modifiche`

Si consiglia di effettuare le traduzioni per sezione, ossia un file alla volta, e di verificarne la correttezza nella GUI
prima di procedere con la sezione successiva.

Tenere presente la lunghezza delle traduzioni e cercare di renderle di lunghezza simile al testo originale ed evitare problemi di spazio nella GUI.

### PARTE 2

Queste sono voci a più righe utilizzate per tradurre più righe contemporaneamente.
Le traduzioni a più righe hanno un tag di apertura e chiusura univoco:

**:unique_tag_name_plug:** - tag di apertura univoco utilizzato per qualsiasi sezione di testo a più righe

**:end**    - tag di chiusura

Non rimuovere o alterare questi tag e tradurre solo il testo tra i tag di apertura e chiusura!

### TESTO DI AIUTO

Tutto il testo di aiuto della GUI è memorizzato in un singolo file helptext.txt.

Questo file ha più sezioni di testo di aiuto. Ogni sezione è racchiusa da un tag di apertura univoco e dal corrispondente tag di chiusura.

**:unique_tag_name_help:** - tag di apertura univoco utilizzato per una sezione di testo di aiuto

**:end**    - tag di chiusura corrispondente

Non rimuovere o alterare questi tag e tradurre solo il testo tra i tag di apertura e chiusura!

Tenere presente che viene utilizzata la sintassi di stile Markdown, che deve essere preservata.

### TEST LOCALI

Una volta completate le traduzioni e si desidera testare localmente i risultati (intermedi), i file di testo devono essere compressi in un singolo file ZIP.
Assegnare al file ZIP il nome della propria lingua, ad esempio Italian.zip.

Nella GUI vai a: Strumenti -> webGUI -> Lingua (passa alla visualizzazione Sviluppatore)

- Per impostazione predefinita è installata solo la lingua inglese (integrata)
- Scegliere il file ZIP creato in precedenza come file di origine
- Se il nome della lingua viene riconosciuto, verrà selezionato automaticamente, altrimenti scegliere dal menu a discesa il nome della lingua da installare
- Cliccando su "Carica" le tue traduzioni verranno aggiunte alla GUI con il nome della lingua selezionato

NOTA: se la tua lingua non è disponibile dal menu a discesa, fai una richiesta sul [Forum Unraid](https://forums.unraid.net/forum/75-multi-language-section/)

Ora la tua lingua è disponibile per i test locali!

Nella GUI vai in: Impostazioni -> Interfaccia grafica -> Lingua

- Selezionare la lingua preferita dal menu a discesa. Notare che qui vengono visualizzate solo le lingue disponibili.

### GITHUB

Un repository linguistico sarà reso disponibile su [Github](https://github.com/unraid), dove i traduttori possono creare delle Pull Request (PR) e inviare il loro lavoro.

Una volta soddisfatti dei risultati, utilizzare Github (è richiesto un account) per eseguire il fork del rispettivo repository linguistico e creare una PR con le modifiche.

Limetech lo esaminerà e unirà il tuo lavoro quando approvato.

### AGGIORNAMENTI

Quando in futuro saranno disponibili file di testo sorgente aggiornati in inglese, questi aggiornamenti saranno resi disponibili tramite Github.

I traduttori possono utilizzare il sistema Github per vedere quali modifiche vengono apportate e aggiornare di conseguenza le loro traduzioni.

### CREDITI

I tuoi sforzi sono molto apprezzati e per mostrare il nostro apprezzamento, il tuo nome e la tua lingua sono accreditati nella pagina dei crediti sotto Strumenti nella GUI.
Facci sapere quali credenziali utilizzare.

Grazie mille!
