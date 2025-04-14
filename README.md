# 🪖 Simulatore di Comando Militare

Questo progetto Python simula una gestione di unità militari con varie specializzazioni come fanteria, artiglieria, cavalleria, supporto logistico e ricognizione. È pensato per scopi educativi e dimostrativi, con un'architettura modulare e orientata agli oggetti.

## 📁 Struttura del Progetto
L'approccio adottato in questo progetto è stato pensato fin dall'inizio per essere scalabile ed estendibile. L'intera architettura è basata su principi di programmazione orientata agli oggetti, il che rende estremamente semplice sia l'aggiunta di nuove funzionalità, sia la modifica o l'espansione di quelle esistenti.

1. army_unit.py definisce la classe base che rappresenta un'unità militare generica. Fornisce le funzionalità fondamentali come il movimento, l'attacco, la ritirata e la visualizzazione dello stato attuale. È pensata per essere estesa da classi più specifiche.
2. army_utilities.py espande la struttura di base introducendo classi specializzate per diversi ruoli militari, come fanteria, artiglieria, cavalleria, supporto logistico e ricognizione. Ogni classe aggiunge comportamenti specifici che riflettono le operazioni tipiche del ruolo che rappresenta.
3. army_controll.py gestisce il coordinamento e la registrazione delle varie unità militari create. Consente di visualizzare l'elenco delle unità registrate e di ottenere dettagli approfonditi su ciascuna di esse, fungendo da centro di comando virtuale.
4. main.py  è il punto d'ingresso del programma. All'interno di questo script vengono create le unità militari, registrate nel sistema di controllo e viene simulata una serie di azioni per mostrare il funzionamento dell'intero sistema. Serve come dimostrazione pratica delle funzionalità offerte dal progetto.

Questa organizzazione permette al progetto di crescere nel tempo, adattandosi a nuove esigenze e scenari. Che si tratti di simulazioni più complesse, interazioni tra unità o persino l’integrazione con un’interfaccia grafica o una rete multiplayer, la struttura modulare rende ogni sviluppo successivo più semplice e naturale.

## 🛡️ Funzionalità principali
* Registrazione delle unità: Tutte le unità vengono registrate centralmente nel ControlloMilitare.

* Azioni specifiche per unità:

    - Fanteria: può costruire trincee in base alla salute.

    - Artiglieria: calibra il fuoco se ci sono abbastanza soldati.

    - Cavalleria: esplora il territorio considerando la resistenza.

    - Supporto logistico: rifornisce altre unità con munizioni e cibo.

    - Ricognizione: esplora aree ed è soggetta a rischi di intercettazione.

    - Visualizzazione dettagliata: È possibile vedere lo stato e i dettagli di ogni unità registrata.
 
## ✅ Conclusioni
Il progetto è una simulazione didattica per la gestione di unità militari, pensata con un'architettura modulare e facilmente espandibile. È ideale per esercitazioni di programmazione a oggetti e come base per sviluppi futuri. La struttura consente l'aggiunta di nuove unità e funzionalità senza modificare il nucleo del sistema. Può essere adattato a giochi, simulatori o ambienti educativi. Contributi e collaborazioni sono benvenuti!

Grazie per aver esplorato questo progetto! 🚀

## 📌 Autore
Creato da Nunzio De Cicco, Liliana Gilca


