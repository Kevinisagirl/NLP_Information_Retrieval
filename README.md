# NLP_Information_Retrieval
HW for NLP class

Please write an iPython notebook that implements Boolean and ranked retrieval for the Reuters corpus. Please use the nltk.corpus.reuters "training" documents (as shown in reuters.fileids()) in all categories. 

Part I. Boolean retrieval

Create an inverted index. You may use nltk normalization and stemming and remove stop words. 
Implement the merge algorithm for AND on slides 31-32 of the Boolean Retrieval slides. Test on a robust set of cases.
Adapt the merge algorithm for OR and NOT as shown in the Exercise, slide 39. Test on a robust set of cases.
Do the Exercise on slide 44 and the first Exercise on slide 45.
Implement the query optimization on slides 41-42. Test on a robust set of cases.
Part II. Ranked retrieval. You don't know what terms the user will search for, so you can't afford to pick the 500 "most informative" words.

Compute the length-normalized tf-idf vector (on the whole vocabulary) for each Reuters document. 
Write a search function that computes the length-normalized tf-idf score of a query and returns the top N ranked documents for the query. Test on a robust set of cases.
Evaluate your search engine. Details to follow.
