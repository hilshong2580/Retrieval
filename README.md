# Retrieval

In the project, I add 6 queries to a string array. Then put it into the retrieveQuery() function with variable K as the number of results for each query. Using a for loop to find each query
by documentAtATime() function with second parameter string BM25 or QL. The documentAtATime() contains BM25() and QueryLikelihood() to calculate the score by
different values. Finally, using the PrintWriter function to write the result.

In this project, The first version is incorrect because the Q6 to be or not to be contains terms reply. I use a list to store the terms that cannot make it distinct. Therefore, the “qtf” is always equal to one and does not match the result. Therefore, use a function to add a term to the list if the term does not exist in the list before.
