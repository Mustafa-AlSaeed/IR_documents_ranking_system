# IR_documents_ranking_system
Document ranking system


Starting with the main fucntion, it loads all the required
files to run the program, it first calls upon PreProcess 
which normalizes the data and the removes the list of
stopwords. These words are then added to a dictionary
which is then used to build the inverted index. The main
function recieves the already built inverted index. 

then the queries are added into the program and given a topic and an ID
releveancy of the documents is then determined by comparing the words in the query to the inverted index

results are then stored in soted linkedhashmap and saved to results.txt
