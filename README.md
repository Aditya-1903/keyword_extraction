# Keyword Extraction from Academic Papers

This project aims to compare the performance of different techniques/ models for keyword extraction from titles and abstract of academic papers from PubMed.  

Models/ Techniques compared:  
Term Frequency - Inverse Document Frequency (TF-IDF)  
Rapid Automatic Keyword Extraction (RAKE)  
Yet Another Keyword Extractor (YAKE)  
KeyBERT  
TextRank  

The titles, abstracts and keywords provided by the authors were extracted via the Biopython library using their PubMed ID. The above mentioned techniques were used to extract keywords and their performance was compared by using the gold label keywords proposed by the authors of the papers.
