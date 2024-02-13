<Data Pipeline>
./data/corpus.txt --> Text data that needs to be chunked. Please the file contents with whatever you want.
./data/chunked_corpus.txt --> Chunking result of "./data/corpus.txt". 

<Start - python installation>
Please install python version 3.10.

<Start - install packages, dependencies>
Please execute "installation.bat" in the command prompt (python 3.10 environment).

<One Click Execution - Execute python file main.py with default setting (Assume text is mainly in korean, use sentence transformer vectorizer).>
Please execute "chunking.bat" in command prompt (python 3.10 environment).

<User Customized Command>
Please enter command 
"python main.py --splitter_name [SPLITTER NAME] --vectorizer_name [VECTORIZER NAME] --threshold [THRESHOLD]"



