# IRIS-Notebook-by-using-Advanced-EDA-Logi.Regr
I have performed both advanced and manual exploratory data analysis (EDA) on the dataset. You are welcome to choose the approach that best suits your needs. Additionally, I have built models using logistic regression and various other machine learning algorithms.

# Aim of the Dataset
The aim of the IRIS dataset is to explore and analyze how the sepal width, sepal length, petal width, and petal length are distributed across the three different Iris flower species (Iris setosa, Iris versicolor, and Iris virginica). This dataset is often used to illustrate various data visualization techniques and machine learning algorithms, particularly classification methods.

| **Feature**    | **Description**                                                                                 | **Unit**        | **Typical Range**         | **Importance**                                                                                         |
|----------------|-------------------------------------------------------------------------------------------------|-----------------|---------------------------|--------------------------------------------------------------------------------------------------------|
| Sepal Length   | Length of the sepal, the protective part of the flower.                                          | cm              | 4.3 cm to 7.9 cm           | Helps distinguish species, especially when combined with other features.                               |
| Sepal Width    | Width of the sepal.                                                                              | cm              | 2.0 cm to 4.4 cm           | Useful in combination with sepal length; less distinctive on its own.                                  |
| Petal Length   | Length of the petal, the colorful part that attracts pollinators.                                | cm              | 1.0 cm to 6.9 cm           | Highly discriminative feature, crucial for distinguishing Iris setosa from others.                     |
| Petal Width    | Width of the petal.                                                                              | cm              | 0.1 cm to 2.5 cm           | Critical for distinguishing Iris species, especially Iris virginica and Iris versicolor.               |
| Target Species | The species of Iris (setosa, versicolor, virginica).                                             | -               | -                         | The label the model predicts, based on the features. Understanding species differences is key.          |

# Conclusion¶
Using Petals over Sepal for training the data gives a much better accuracy. This was expected as we saw in the heatmap above that the correlation between the Sepal Width and Length was very low whereas the correlation between Petal Width and Length was very high.

# --------------------------------------------------Suggestions for further improvements or alternative approaches.---------------------------------------------
