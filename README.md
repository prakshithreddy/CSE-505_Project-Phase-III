# CSE-505---Project-Phase-III
Verifying the results of the paper - "Lifted Variable Elimination for probabilistic logic programming" by ELLENA BELLODI, RICARDO ZESE, VITOR SANTOS COSTA, FABRIZIO RIGUZI..

The workshop attributes example described in the paper Milch et al. 2008 is used to compare ProbLog and PFL using GC-FOVE to test the performance of the newly included het and deputy factors.

In this example, we initialize each problem with 50 persons and increasing attributes to plot a graph as mentioned in the paper.

Usage - Install YAP 6.3.3 or above to run PFL programs, problog can be installed by running "pip install problog"(problog is built in python, available in python 2.7 or 3.x).

Predicates from input files are to be copied in to the .pl files before running them and their performance can be tested, input1 contains 2 attributes, and an extra attribute is added in each other input file. This would result in 10 data points, which would be necessary to plot the graph.
