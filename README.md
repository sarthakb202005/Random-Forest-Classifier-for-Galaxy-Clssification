# Random-Forest-Classifier-for-Galaxy-Clssification
This script is fundamentally dervied from the galaxy zoo classification activity.
The repository contains an implementation of Random Forest classifier to classify the galaxies as spirals,ellipticals, or mergers. The features that form the basis of classification primarily consists of
the color indices, eccentricities, 4th absolute moment, and petrosian fluxes. 

Initially , the classiifcation is done with using the Decision Tree Classifier and a Confusion Matrix is plotted which showcases the number of TRUE POSITIVES , FALSE NEGATIVES AND FALSE POSITIVES. The model accuracy
using the 10-fold cross validation.

The dataset is then further trained with the Random Forest Classifier with the accurcay scores and Confusion Matrixes being measured, which present a better upgrade than the previous model used simply due to the 
working mechanisms explained. This method can also be termed as ENSEMBLE LEARNING , since the RFC is a colection of various trees that are independently trained, where the output with most occurences/probability among those trees is taken into account. 
