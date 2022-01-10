# Socioeconomic Data from Albany, NY - Analysis

These files are the results of a project I was assigned.  An anonymized version of our slides is included. My contributions come from the following analysis.

You'll find an ipynb file for:
- Decision Tree Classification (poor results, sadly),
- KNN Classification (some encouraging results), and
- Plotting the results.
- A much faster algorithm for suggesting accurate classifiers (FastKNNHeur).

The classification was done in an attempt to recover features used in the decision making process for, 'where to place free food fridges in Albany, NY'.  Several pairings and triples of SE data were found to classify potential neighborhoods and some accuracies were found above 84% - about 3% higher than classifying all neighborhoods as 'do not put a fridge here'.  All of this was prior to the faster method for feature selection discovered after the submission of the paper.  

New classifiers were found using the "FastKNNHeur" program with accuracies above 90% and in considerably less time (approximately five orders of magnitude faster than the previous resampling method).  See results in "PlotsAftHeur".   

The features which classify most accurately do affirm that marginalized people groups are the targets for the free food fridges.  This is an encouraging finding.  

There are maps of Albany showing some neighborhoods as well as a map indicating the approximate location of the free food fridges.

I find that this research is a great conversation topic and I welcome those discussions.  Please, let me know if you have questions or comments (tlove (at) albany [dot] edu).
