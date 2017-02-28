# KTH Master Thesis

Repository where source files for my Master Thesis at KTH are stored.

## Template

This project uses the template & classes from KTH CSC. 
They can be downloaded here: http://system.csc.kth.se/misc/tex/

## Outline

### Methodology

**Two solutions** to assess the goodness of an explanation algorithm: 
- train a classifier, print explanations, remove most important explanations and observe the score reducing
- Better: create a bad classifier, print explanations, remove wrong data, retrain and see if score increases -- On 20 news groups

#### Algorithms 

Test it for Lime, treeinterpreter, linear models, Game theory (?), Parzen (?).
For Lime: test with various discretization methods.

#### Datasets
- 20 newsgroup
- kaggle Ames housing market
- Boston Housing
- German credits

Comparison between treeinterpreter & lime ?

