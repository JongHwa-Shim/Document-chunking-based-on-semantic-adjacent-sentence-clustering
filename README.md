## Document Chunking with Semantic Adjacent Sentences Clustering
(Neighboring Sentence Clustering with Embedding Cosine Similarity)

- Clustering based on embedding similarity between adjacent sentences → Each cluster is to be chunk.
- Using Sentence Transformer as a vectorization model for similarity calculation **Can be implemented even in closed networks**
- Arbitrary **chunking environment can be set by adjusting similarity threshold or minimum & maximum chunk size.**
- **Advantages:** Consistency of content of each chunk, flexible chunk size, adjustable parameters such as threshold, order preservation
- **Disadvantages:** The method is somewhat complicated, increases processing time, is not effective if uniformity of chunk size is important, if the composition of the text content is very complex (sentences, word fragments, format marks, etc. mixed together) sentence transformer Vectorization performance may decrease

## Data Pipeline
./data/corpus.txt --> Text data that needs to be chunked. Please the file contents with whatever you want.   
./data/chunked_corpus.txt --> Chunking result of "./data/corpus.txt".    

## Installation
1. Python installation - Please install python version 3.10.   
2. Install packages, dependencies - Please execute "installation.bat" in the command prompt (python 3.10 environment).   

## One Click Execution - Execute python file main.py with default setting (Assume text is mainly in korean, use sentence transformer vectorizer).
- Please execute "chunking.bat" in command prompt (python 3.10 environment).   

## User Customized Command
- Please enter command "python main.py --splitter_name [SPLITTER NAME] --vectorizer_name [VECTORIZER NAME] --threshold [THRESHOLD]"



