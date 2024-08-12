# Use of Control Flow Graphs for Fault Localization

# code
## Functional code: 
### Ranking inside of each mutation
’#DetermineLikelihoods.java’ and ‘#DetermineLikelihoodsIfElse.java’ returns the ranking of each code line by there score of suspiciousness for all mutations for a source code testing. To run this, you need to first adjust the direction of file that you want to work on _(line 8 and line 20)_. The folders’ directions are usually named as **nameOfSourceCode_test_results/**. 

‘#DetermineLikelihoodsIfElse.java’ only generates those mutations that the bug is inside of conditional statement, which the result is often stored in the txt file in ‘#data_output/ranking.txt/nameOfSourceCode_test_totalResultsWithIfElseConsider.txt’. ‘#DetermineLikelihoods.java’ generates all mutation as long as there is at least one passed case and at least one failed case.

# data_output
