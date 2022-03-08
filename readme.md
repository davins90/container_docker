# Info

Repo contenente i file utili a lanciare una immagine docker all'interno di due container. Sono presenti:
- container 1: jupyter lab basato sull'iummagine data science e python 3.9.2 --> porta:8080
- container 2: demo streamlit --> porta:8501

# Comandi
- docker-compose up -d --build = costruisce l'immagine per la prima volta installando le librerie. Da usare al primo lancio e ogni volta che viene cambiato il file dei requirements.
- docker-compose up = caricare l'immagine (se non ci sono state modifiche agli altri file).
- docker-compose down = spegnere l'immagine

## NOTA
Appena scaricata l'immagine creare manualmente una cartella all'interno della cartella "container" dal nome "src".

Aggiornamento: 8/3/22