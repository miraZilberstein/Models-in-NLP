# Models-in-NLP
# TF-IDF (Term Frequency-Inverse Document Frequency)- 
a statistical measure used to evaluate the importance of a word within a document in relation to a collection (corpus) of documents. This measure helps in identifying the relevance of words by balancing their frequency in documents against their occurrence across the entire corpus, effectively highlighting words that are unique and informative to specific documents.

parts in the implementation:
1. Term Frequency (TF): This part of the code calculates how frequently a term appears within a document.
2. Document Frequency (DF): This measures the prevalence of a term across all documents in the corpus.
3. Inverse Document Frequency (IDF): This component is designed to diminish the weight of terms that appear too frequently across the corpus, as these are less informative or distinctive for any particular document.
4. TF-IDF Calculation: The final step combines TF and IDF to produce a single score that represents the importance of a term within a document relative to the corpus. This score is higher for terms that are more unique to a particular document, thus helping in identifying which documents are most relevant to a given query or term.
5.Application on real example from wikipedia
