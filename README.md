# Greta Papetti

M.Sc. Computer Science and Engineering, Politecnico di Milano.

I work on retrieval-augmented LLM systems, and on the data preparation and analysis that sits underneath them — profiling messy data, cleaning it, and measuring whether what I build on top of it actually works.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗%20Transformers-FFD21E)
![FAISS](https://img.shields.io/badge/FAISS-0467DF)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?logo=neo4j&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?logo=apachespark&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)

---

## Selected work

#### [Retrieval-Augmented Quiz Agent](https://github.com/grepapetti/retrieval-augmented-quiz-agent)

An LLM that answers multiple-choice questions by retrieving evidence, searching the web and writing Python — under a 30-second budget on a single free GPU. Hybrid dense + sparse **RAG** with reciprocal rank fusion and cross-encoder reranking, self-consistency decoding, and a Whisper front-end for spoken questions. Evaluated on 5,441 questions.

`Qwen2.5` · `FAISS` · `Transformers` · `Whisper` · `spaCy`

#### [Reproducing a CVPR Paper: Continual Self-Supervised Learning](https://github.com/grepapetti/continual-self-supervised-learning-pfr)

Revived a four-year-old research codebase and reproduced *Projected Functional Regularization* (Gomez-Villa et al., CVPRW 2022) end to end: patched the breaking changes that accumulated since 2022, trained four continual-learning variants on CIFAR-100 split into four tasks, and measured average accuracy, forgetting and forward transfer against the paper. An anomaly in the feature-distillation baseline led to an ablation of its regularization strength.

`PyTorch` · `PyTorch Lightning` · `Barlow Twins` · `Weights & Biases` · `reproducibility`

#### [Milan Services Data Cleaning](https://github.com/grepapetti/data-cleaning-and-preparation-milan-services)

End-to-end data quality work on a municipal dataset: profiling for uniqueness, constancy and correlation, KNN imputation for missing values, outlier detection and removal, producing a cleaned dataset ready for analysis.

`pandas` · `scikit-learn` · `data profiling` · `imputation`

#### [DBLP Dataset Paper Mining](https://github.com/grepapetti/dblp-dataset-paper-mining)

An ETL pipeline that mines dataset-papers from DBLP: web scraping, NLP validation of candidates, and citation-network analysis.

`scraping` · `NLP` · `ETL` · `network analysis`

---

## Toolbox

- **Data analysis** — pandas · NumPy · SciPy · scikit-learn · Jupyter · Matplotlib
- **Databases & big data** — SQL · MongoDB · Neo4j · Elasticsearch · Cassandra · Redis · Spark · Hadoop
- **NLP & LLM** — Transformers · PyTorch · PyTorch Lightning · FAISS · spaCy · RAG pipelines · Whisper
- **Engineering** — Python · Git · LaTeX · C/C++ · JavaScript
