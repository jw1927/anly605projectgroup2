# Heroku Application

We used Heroku's deployment feature to deploy the model. Users can go to https://anly605projectgroup2.herokuapp.com/ to build the model. They can utilize the following five feature vectors to test the model. A table showing the variables and example values for each variable is included below the input field. Users may also choose to create any feature vectors to fit and test the model.

Here are five feature vectors that users can use for testing:
1. 75, 0, 582, 0, 20, 1, 265000, 1.9, 130, 1, 0, 4
2. 65, 1, 52, 0, 25, 1, 276000, 1.3, 137, 0, 0, 16
3. 65, 0, 146, 0, 20, 0, 162000, 1.3, 129, 1, 1, 7
4. 53, 0, 63, 1, 60, 0, 368000, 0.8, 135, 1, 0, 22
5. 65, 1, 160, 1, 20, 0, 327000, 2.7, 116, 0, 0, 8

![image](https://github.com/jw1927/anly605projectgroup2/blob/main/figure1-1.png)

![image](https://github.com/jw1927/anly605projectgroup2/blob/main/figure1-2.png)

Figure 1  Screenshot of the Heroku application

The above graph displays the scatter plot of four most important features of the dataset, that is, age, ejection fraction, time and serum sodium. The color of the points represents the category of the target variable, that is, Death_Event. Users can provide input to the text box below the graph. After inputting the feature vector, the website will display the updated graph with predictions from the feature vector given from the user’s input.

![image](https://github.com/jw1927/anly605projectgroup2/blob/main/figure2.png)

Figure 2  Predicted vector using 75, 0, 582, 0, 20, 1, 265000, 1.9, 130, 1, 0, 4

![image](https://github.com/jw1927/anly605projectgroup2/blob/main/figure3.png)

Figure 3  Predicted vector using 53, 0, 63, 1, 60, 0, 368000, 0.8, 135, 1, 0, 22

Figure 2 and Figure 3 show the updated graphs with the predicted Death_Event in yellow or darkblue on the plots.
