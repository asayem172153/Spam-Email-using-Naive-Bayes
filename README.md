# Spam Email using Naive Bayes
- **Model Used:** - MultinomialNB  
                  - BernoulliNB
- **STEP**:  
           i. Firsly, We removed the **Punctuations** (period, comma, apostrophe, quotation, question, exclamation, brackets, braces, parenthesis, dash, hyphen, ellipsis, colon, semicolon, etc) and **Stopwords** (a, the, is, are, and, etc).  
           ii. Secondly, **Lemmatization**. It's a technique used to reduce words to their basic form or root form. For example, in lemmatization:  
          "running" becomes "run."  
          "better" becomes "good."  
          "wolves" becomes "wolf."
           iii. Then, **TF-IDF Vectorizer**
                      - **TF** (Term Frequency): It measures the frequency of a word in a document, indicating how often a word appears in a specific document.  
                      - **IDF** (Inverse Document Frequency): It measures the importance of a word across a collection of documents, highlighting the uniqueness of a word in the entire corpus.  
                      - **TF-IDF Score**: It combines TF and IDF to represent the importance of a word in a document and across the corpus.            iv. Finally, we fit the model and **Evaluate** the performance.
