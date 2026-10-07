# Greta Papetti

M.Sc. Computer Science and Engineering, Politecnico di Milano.

I work on retrieval-augmented LLM systems, and on the data preparation and analysis that sits underneath them — profiling messy data, cleaning it, and measuring whether what I build on top of it actually works.

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
