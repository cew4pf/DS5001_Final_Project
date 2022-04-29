# **DS5001: Exploratory Text Analytics (ETA) Final Project - Spring 2022**

## **Using Text Analytics to Explore the Works of Charles Dickens and Mark Twain**

### **Cecily Wolfe (cew4pf)**


### **Documents**

* **Dickens**: folder containing 50 works of Dickens curated from [Project Gutenberg](https://www.gutenberg.org/ebooks/58157)

* **Twain**: folder containing 45 works of Twain curated from [Project Gutenberg](https://www.gutenberg.org/files/28803/28803-h/28803-h.htm)

* **Notebooks**: Jupyter notebooks for analysis
  * dickens_preprocess.ipynb: preprocessing Dickens works into LIB, CORPUS, VOCAB
  * twain_preprocess.ipynb: preprocessing Twain works into LIB, CORPUS, VOCAB
  * dickens_analysis_M3-7.ipynb: language models, word vector models, clustering, and PCA for Dickens works
  * twain_analysis_M3-7.ipynb: language models, word vector models, clustering, and PCA for Twain works
  * full_analysis_M3-7.ipynb: language models, word vector models, clustering, and PCA for all works (both Dickens and Twain)
  * dickens_tmodel_wordem.ipynb: topic models, word embeddings for Dickens
  * twain_tmodel_wordem.ipynb: topic models, word embeddings for Twain
  * full_tmodel_wordem.ipynb: topic models, word embeddings for all works
  * sentiment_analysis.ipynb: sentiment analysis for Dickens, Twain, and all works

* **ETA_Functions**: python scripts with functions for text analysis
  * bow_tfidf_pca.py: functions to create BOW (Bag Of Words), TFIDF (Term Frequency Inverse Document Frequency) matrix, Principal Component Analysis (PCA) tables (LOADINGS, DCM (Document Count Matrix), COMPINF)
  * hac2.py: function to create HCA (Hierarchical Agglomerative Clustering) plots
  * langmod.py: functions to create a language model
  * textparser.py: functions to parse a list of works and associated regex patterns to process the works into chuncks by work, chapter, paragraph, sentence, token
  * topicmodel.py: function to create a topic model and produce the associated tables (THETA, PHI, TOPIC)

* **HTML_files**: HTML versions of Jupyter notebooks


