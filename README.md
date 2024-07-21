# Melodywood

Melodywood è un applicazione che è stata sviluppata da G. Margarella e N.P. Santorsa come progetto di corso di "Musica Algoritmica e Sound Computing" durante l'anno accademico 2023/2024.

## Funzionamento dell'applicativo

L'applicazione sviluppata analizza le sceneggiature cinematografiche di diversi film e, a partire da esse, genera musica di sottofondo.
Le sceneggiature sono state ottenute utilizzando il [seguente codice github](https://github.com/AdeboyeML/Film_Script_Analysis/tree/master) per effettuare web scraping sul sito [IMSDB](https://imsdb.com/) e successivamente segmentare lo stesso in scene.
A partire dal dataset costruito, si sono poi estratte caratteristiche, come il genere musicale consigliato per la scena e le emozioni che essa suscita, tramite la descrizione testuale utilizzando il modello Gemma 2.
Queste caratteristiche sono state poi date in input ad un modello MusicGen per generare la melodia finale.

Il prototipo dell'interfaccia è stato sviluppato utilizzando la libreria Gradio ed è eseguibile tramite il corrispondente notebook presente nella repository.

## Documentazione

Per ulteriori dettagli implementativi si rimanda alla cartella deliverables presente nella repository, in cui sono contenute la presentazione e il report del progetto.
