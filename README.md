Progetto finale – Modulo 5: Power BI

Obiettivo del progetto

Per il progetto finale del modulo, ci è stato chiesto di lavorare su diversi file CSV del database Olist e di realizzare un report interattivo con Power BI.
Ho deciso di concentrarmi sulla creazione di una dashboard che offra una panoramica completa delle performance di vendita e della gestione degli ordini.
L’obiettivo era quello di costruire uno strumento chiaro e interattivo, in grado di mostrare l’andamento degli ordini, dei ricavi e la soddisfazione dei clienti in modo semplice ma efficace.

Pulizia e preparazione dei dati

La prima fase è stata dedicata alla pulizia e preparazione dei dati. Ho importato in Power BI le tabelle principali e ho iniziato a lavorare in Power Query per sistemare e uniformare i dataset.

In particolare, ho:

Controllato e gestito i valori nulli e duplicati;

Applicato la funzione Trim e la capitalizzazione per rendere i testi coerenti;

Corretto i formati di data, numeri e codici postali;

Modificato il file di geolocalizzazione direttamente in Excel, usando XLOOKUP per associare i nomi completi agli stati;

Caricato poi il file aggiornato su Power Query e unito (merge) la tabella con le sigle degli stati;

Scelto solo le colonne realmente utili per l’analisi;

Sostituito i valori nulli nella categoria dei prodotti con “Unknown”, in modo da non perdere informazioni sugli ordini senza categoria.

Analisi e creazione della dashboard

Una volta pronti i dati, ho creato le principali misure DAX per analizzare le performance (ricavi totali, numero ordini, soddisfazione, ecc.).
Ho poi costruito la dashboard dividendo il report in pagine tematiche, ognuna dedicata a un aspetto specifico come vendite, clienti, prodotti e andamento temporale.

Le visualizzazioni includono:

Grafici interattivi e KPI principali;

Slicer per filtrare i dati in tempo reale;

Bookmarks per rendere la navigazione più intuitiva;

Una grafica coerente e curata nei dettagli, per rendere l’esperienza utente più piacevole e professionale.
