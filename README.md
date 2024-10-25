# QUANT-INO

## Trailer - Watch the video
[![Watch the video](https://img.youtube.com/vi/Q6rhuSUnB9Q/maxresdefault.jpg)](https://www.youtube.com/watch?v=Q6rhuSUnB9Q)
[Download Simulation 3D](https://www.dropbox.com/scl/fi/xunaqy7874sly7zq8k4sv/Build-Simulazione.zip?rlkey=p1wo1el3pxbhhr2amjvjkc2v5&st=3mjlmbad&dl=0)
Quantum K-Means Traffic Clustering
Questo progetto implementa un sistema di clustering quantistico basato sull'algoritmo Quantum K-means, utilizzato per analizzare e monitorare dati di traffico in tempo reale, identificando situazioni critiche di congestione.

Descrizione
L'algoritmo applica il Quantum K-means a un dataset di traffico con misurazioni come value, rain_1h, e wind_speed per classificare i dati in cluster NORMALE e ALLERTA. I dati vengono poi utilizzati per visualizzare i livelli di allerta e la distribuzione dei cluster, consentendo l'identificazione tempestiva di situazioni di traffico critiche.

Funzionalità principali
Clustering Quantistico: Implementa il Quantum K-means per clusterizzare i dati.
Analisi di correlazione e ANOVA: Analizza la correlazione tra le variabili e il livello di allerta.
Visualizzazione e salvataggio dei risultati: Genera grafici per il monitoraggio visivo e salva i risultati in un file CSV.
Requisiti
Python 3.8+
Pennylane per il Quantum K-means
Scikit-learn per la pre-elaborazione dei dati
Pandas e Matplotlib per l'analisi e la visualizzazione dei dati
Installazione
Clona questo repository e installa i pacchetti richiesti:

bash
Copy code
git clone <url-repository>
cd <nome-cartella>
pip install -r requirements.txt
Utilizzo
1. Caricamento dei Dati
Il codice carica un dataset di traffico (dataset_output/df1.csv) e rimuove i valori mancanti.

2. Training del Sistema Quantistico
Addestra il sistema con Quantum K-means e identifica i cluster critici.

3. Visualizzazione dei Risultati
Genera visualizzazioni per:

Livelli di Allerta del Traffico: Un grafico a dispersione con le situazioni di allerta e non.
Distribuzione dei Cluster: Mostra il numero di occorrenze in ogni cluster.
4. Analisi Statistica
Effettua un'analisi di correlazione (Pearson) e ANOVA per verificare se le variabili differiscono tra i cluster.

Esecuzione
Esegui il file .ipynb per addestrare il sistema e visualizzare i risultati. Il riepilogo e i dati dettagliati delle situazioni di allerta vengono salvati in risultati_quantum_cluster.csv.

[Quantum K-means clustering method for detecting heart disease using quantum circuit approach](https://doi.org/10.1007/s00500-022-07200-x)

Unity Assets used:
[CityGen 3d](https://assetstore.unity.com/auth/login?redirect_to=%2Fpackages%2Ftools%2Fterrain%2Fcitygen3d-162468)
[ICONIC: Low Poly Sports Car](https://assetstore.unity.com/packages/3d/vehicles/land/iconic-low-poly-sports-car-free-vol-02-281765)
[Rain Maker](https://assetstore.unity.com/packages/vfx/particles/environment/rain-maker-2d-and-3d-rain-particle-system-for-unity-34938)
