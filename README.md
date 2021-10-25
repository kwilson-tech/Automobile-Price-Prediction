# Automobile-Price-Prediction

![This is an image](https://www.admiral.com/sites/default/files/styles/magazine_article_1280/public/2019-01/Ford%20Cortina.jpg?itok=Qv3Rzw0c)

Price Prediction Regression of Vehicles in 1985. The 'normalized-losses' column had about 20% of the values missing.

I implemented 4 different methods only manipulating the normalized-losses column to see what would the best results:
* Used the mean column to fill the missing values
* Used linear regression to fill the missing values. The predictor used was 'symboling'. Saw the correlation coefficient between 'symboling' and 'normalized-losses' was +0.53
* Used median value of the normalized-losses column to fill the missing values
* Removed the entire 'normalized-losses' column

Results:
I saw using the linear regression method performed the best for the models used.

Models Used:
* Linear Regression
* KNN
* SVR
* Decision Tree Regressor

Folders:
* CSV Files
* Notebook Files

The libraries used are listed below:
 * Pandas
 * Matplotlib
 * Seaborn
 * Numpy
 * Sklearn

References:
* https://www.1aauto.com/content/articles/types-of-fuel-injection
* https://www.usautosales.info/blog/front-wheel-drive-vs-rear-wheel-drive/



