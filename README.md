# DataPizza_Hackaton_Simpliciter_Team
Questa repository contiene il codice usato dal team ElementareWatson per il primo hackaton di Datapizza.  
L'obiettivo della sfida è quello di usare Generative AI per poter rispondere a delle query relative a preparazioni culinarie di un mondo intergalattico fittizio.  
Per poter portare a termine è possibile usare pipeline basate su RAG, e sistemi di Agentic AI.

### Prerequisites
Creare un conda environment dove installare le librerie:
```bash 
conda create --name datapizza_hack python=3.12 --y
conda activate datapizza_hack
```  
Le librerie possono essere installate facilmente tramite i notebooks.  
### How to use this repository  
* In `Notebooks/`, `Prompts/`, è possibile estrarre nuovi dati strutturati dai dati grezzi forniti per iniziare il task. In particolare con questi notebook è possibile estrarre versioni più strutturate e comprensibili per un LLM.    
* I seguenti notebooks: `Batch_Document_Exraction_Pipeline_Official.ipynb`, `Jsons_entities_aggregators_and_validity_checks.ipynb`, `Jsons_Merger.ipynb`, ed i file nella cartella `Prompts` servono per rifinire i documenti contenenti i Menù dei ristoranti.  
* Il Notebook `get_planet_distances.ipynb` serve per convertire la matrice di adiacenza dei pianeti, pesata dalle distanze, in una stringa che può essere tokenizzata ed interpretata dall'LLM.
* I files relativi al Codice Galattico e il Manuale di Cucina, sono stati semplicemente convertiti in markdown.  
* I blog-post non sono stati usati, per via della poca rilevanza con il task.  
* Tutti i dettagli ed il codice su come riprodurre il nostro miglior agente sono disponibili nel Notebook `main_pipeline.ipynb`.

```  
  
Tutti i notebooks si aspettano i dati forniti per la competizione, così come descritto dal codice stesso.



