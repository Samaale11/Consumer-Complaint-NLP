# Consumer-Complaint-NLP
**Installation:** Clone the git repo  (https://github.com/Samaale11/Consumer-Complaint-NLP.git). 
**Dependency installation:** Use pip install command to to install dependencies in the environment.yml file.
**Data:**  download consumercomplaints.csv from Kaggle (https://www.kaggle.com/datasets/selener/consumer-complaint-database) and store it in the repository root.
**Instructions:** Open the NLP.ipynb in Jupyter Notebook. Cells have be run used consecutively to load data, preprocess (lowercase, remove punctuation/stopwords, lemmatize), vectorize (CountVectorizer/Tfidfvectorizer), model topics (LDA/NMF) and assess the coherency index (Gensim Cv). 
**Outputs:** The outputs include processeddata.csv (complaints processed) and topics ouput based on coherence scores.
**System requiremets:** 8GB of RAM and around 30 minutes per 10k samples, Python 3.8.
**Interpretation:** View topic words and the coherence scores
