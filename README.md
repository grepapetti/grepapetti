# Greta Papetti

M.Sc. Computer Science and Engineering, Politecnico di Milano.

I work on retrieval-augmented LLM systems, and on the data preparation and analysis that sits underneath them — profiling messy data, cleaning it, and measuring whether what I build on top of it actually works.

---

## Selected work

#### [Retrieval-Augmented Quiz Agent](https://github.com/grepapetti/retrieval-augmented-quiz-agent)

An LLM that answers multiple-choice questions by retrieving evidence, searching the web and writing Python — under a 30-second budget on a single free GPU. Hybrid dense + sparse **RAG** with reciprocal rank fusion and cross-encoder reranking, self-consistency decoding, and a Whisper front-end for spoken questions. Evaluated on 5,441 questions.

`Qwen2.5` · `FAISS` · `Transformers` · `Whisper` · `spaCy`

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
- **NLP & LLM** — Transformers · PyTorch · FAISS · spaCy · RAG pipelines · Whisper
- **Engineering** — Python · Git · LaTeX · C/C++ · JavaScript
