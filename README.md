# Analisi e Classificazione dei Contenuti di Wikipedia

## Descrizione del progetto e obiettivi
Il progetto, sviluppato durante il master in Data Science di Profession AI, consiste nell'effettuare un'analisi esplorativa dei contenuti di Wikipedia, suddivisi per categoria tematica, e sviluppare un sistema di classificazione automatica per categorizzare i nuovi articoli basandosi sul loro contenuto. 

### Obiettivi

1. **Analisi Descrittiva**:
   - Conteggio degli articoli per categoria.
   - Lunghezza media e massima degli articoli per categoria.
   - Creazione di nuvole di parole per ciascuna categoria.

2. **Classificazione Automatica**:
   - Creazione di modelli di machine learning per classificare gli articoli usando il sommario e il testo completo degli articoli.

3. **Nuovi Insights**:
   - Identificare pattern e tendenze nei contenuti di Wikipedia per migliorare l’organizzazione e l’efficienza.

## Workflow del Progetto

1. **Caricamento dei Dati**: I dati vengono scaricati da un file CSV `wikipedia.csv` ospitato su **S3** e caricati in un **DataFrame Spark** per una gestione efficiente.
   

