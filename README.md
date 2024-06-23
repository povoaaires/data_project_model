# Structure Data Pipeline 


## Enviroment

Requirements to start your Data Pipeline

```
python -m venv .venv
.venv/Scripts/activate
pip freeze > requirements.txt
```

## Map

```
├── data
│   ├── in             <- Original data obtained directly from the source organized by date hierarchy.
│   └── out            <- Output data after transformation.
│
├── extract            <- Folder with files for data extraction.
|
├── load               <- folder with files for data upload.
│
├── transform          <- Folder with files for data wrangling.
│
├── pipeline.py        <- Consolidated pipeline to run all stages.
│
│        
├── requirements.txt   <- The requirements for the project execution.
│
│
│
└── README.md          <- The top-level README for developers using this project.


```  
