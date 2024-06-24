# Football Data-Analysis

### Autori

- Luisa Giusto (MATR 985710)
- Riccardo Pili (MATR 993308)
- Patrick Salazar (MATR 954941)


### Descrizione del progetto

Analisi e visualizzazione dei dati relativi alle statistiche sul calcio. I dati fanno riferimento al sito [Transfermarkt.com](https://www.transfermarkt.com/) e riguardano le statistiche sulle principali competizioni calcistiche europee.


Il progetto fa ampio uso delle seguenti linguaggi, librerie e strumenti:
- python
- jupyter notebooks
- pandas
- geopandas
- matplotlib
- seaborn


### Fasi dell'analisi dei dati
Nell'analisi dei dati sono state effettuate le seguenti fasi:

- **Data Preparation:** Ogni file di dati csv è stato analizzato singolarmente, includendo le fasi di pulizia e preparazione dei dati. Al termine di ciascun file di data preparation il dataframe viene salvato in formato feather nella cartella cleaned_data.

- **Data Analysis & Visualization:** Sono state create visualizzazioni rilevanti che riguardano più file di dati contemporaneamente in Jupyter notebook diversi, suddivisi in base all'argomento:

  - `players_stats.ipynb`: visualizzazioni e statistiche relative ai giocatori
  - `games_stats.ipynb`: visualizzazioni e statistiche relative alle partite e agli eventi delle partite
  - `teams_stats.ipynb`: visualizzazioni e statistiche relative alle nazionali e alle squadre di club
  - `competitions_stats.ipynb`: visualizzazioni e statistiche relative ai campionati



---

_Non è stato possibile caricare i file di dati csv nella repository GitHub in quanto superavano il limite di dimensione massima consentito._

_Per eseguire i Jupyter Notebooks, è necessario modificare il percorso folder_path nel file `config.py` inserendo la posizione locale della cartella contenente i file di dati csv._
