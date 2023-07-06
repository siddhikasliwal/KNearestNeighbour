# KNearestNeighbour
The k-nearest neighbors (KNN) algorithm is a simple, easy-to-implement supervised machine learning algorithm that can be used to solve both classification and regression problems. 
The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.

##KNN Algorithm
Load the data
Initialize K to your chosen number of neighbors

3. For each data example,

3.1 Determine from the data the distance between the query example and the current example.

3.2 To an ordered collection, add the example's distance and index.

4. Arrange the distances in ascending order from smallest to largest in the ordered collection of indices and distances.

5. Choose the first K items from the collection that has been sorted.

6. Obtain the labels of the K entries that you chose.

7. If regression, return the mean of the K labels

8. If classification, return the mode of the K labels
9. (Took the dataset from the kaggle)
