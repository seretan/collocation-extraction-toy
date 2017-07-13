# collocation-extraction-toy
Implementation of collocation extraction (statistical computation: contingency table, lexical association measures) using SQL and MS Access. The implementation comes with preexisting data and is made available for pedagogical purposes.

Lexical Association Measures: log-likelihood ratio, pointwise mutual information, chi-square, t-score, z-score

(to add more, see pages 221-222 of my PhD thesis, http://www.issco.unige.ch/en/staff/seretan/publ/PhDThesis-VioletaSeretan.pdf)

Using the toy:

1.	Open the table en_cooc. It contains some data (candidate pairs). This data is to be replaced with your own data, but for the moment you can use it for the next step.

2.	Run queries 1 to 4 in order. These queries will compute the contingency values (a, b, c, d). Open the table contingency_table if you want to check the values.

3.	Run one of the queries starting with AM, e.g., AM_LRR. These queries apply association measure formulae and display the candidate pairs in the decreasing order of AM score. 
