# Wine Quality Prediction
___
## Content
1. Introduction
2. Data Comprehension and Processing
4. Result
5. Conclusion
6. Reference
___
<p align = 'center'> <strong>Abstract</strong> </p>



The budget-efficiency and time is the important things for wine-maker to create a high-quality wine. The given dataset have several variables of wine and quality become the output. In this analysis, we will use 2 simple model, linear regression, and logistic regression, and utilize hyperparameter to find out the best parameter in terms of accuracy. (`Result and conclusion`) 


<p align = 'center'><strong> 1. Introduction </strong></p>

Wine is the fermented juics of the grape and become the luxury symbol for mid-to-high class. Wine is not only drinkable, but also became one of many ingredients for cook. However, there are certain kind of grape that can be fermented. The grape genus Vitis (e.g. *Vitis vinifera* or called European grape) is one of them. This grape have been developed and recently reported that about 5000 wines is made from this grape. 

According to [Forbes](https://www.forbes.com/sites/lizthach/2023/04/20/wine-exports-break-world-record-in-2022/?sh=258b7709451f), Italy be the most wine exporting countries and U.S. is the most in terms of wine consumers in 2022. Althought still in covid pandemic era, Italy shiped about 20 million hectolitre of wine of the beverage, followed by Spain and France. The overall production this year is nearly 260 milllion hectoliters. From this data, we can conclude that there is a lot of big fan of wine around the world and this post-fermented product is one of the daily needs either for cook or drink.

Winemaking is a series of the process to transform something into wine (e.g. grape). This process involves wide range of indicators (such as bacteria) which had significant influence and may cause negative attributes of some wines [2]. Some indicators such as pH and alcohol, volatile acidity, and etc could make wine  the best or the worst. So, as a data scientist, we are requested to analyze *what variable that can be significant influience of high or low of  wine quality*.

<p align = 'center'><strong> 2. Data Comprehension </strong></p>

The Wine Quality dataset is originally from [UC machine learning dataset](https://archive.ics.uci.edu/dataset/186/wine+quality). THis dataset is uploaded by Cortez from University of California Davis  and contain several variables of physicochemical of wine:

| No | Variables |
| :-: | :-: |
| 1 | `fixed acidity` |
| 2 | `volatile acidity` |
| 3 | `citric acid` |
| 4 | `residual sugar` |
| 5 | `chlorides` |
| 6 | `free sulfur dioxide` |
| 7 | `density` |
| 8 | `pH` |
| 9 | `sulphates` |
| 10 | `alcohol` |

We will give a brief explanation of these variables. The steps after get the data, we check:

* Data duplication
* Null data
* 3M (mean, median, mode)
* Minimum and maximum value each feature
* Interval value between feature and label

These information are important to data scientist to determine what step should they take. After that, we explore this data  by showing some graph and some statistical method like p-value to test the null hypotesis. In this project, we use linear regression and logistic regression as a regression and classification

<p align = 'center'> <strong>3. Result</strong> </p>

<p align = 'center'> <strong>4. Conclusion</strong> </p>

<p align = 'center'> <strong>5. Reference</strong> </p>
1. [Forbes - Wine exports Break World Record](https://www.forbes.com/sites/lizthach/2023/04/20/wine-exports-break-world-record-in-2022/?sh=258b7709451f) 

2. [Bohme, K. Barros-Velázquez, J. Calo-Mata, P. Red Wine Technology. Academic Press, 2019](https://www.sciencedirect.com/science/article/abs/pii/B9780128143995000086).

__
Fikri Abdillah @

___

Check my another project 
