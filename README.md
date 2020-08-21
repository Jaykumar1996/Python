# Python
The Project file uses a CSV file named "states_all.csv". This file contains the information on how each state government spends their money in eduacation in the united states.
It also contain the information of an average score in different subjects grouped under each states of united states.

Achievments:
      
       1. Droped the columns that contained a little data
       2. Droped the columns that were not useful.
       3. Made a new column that contain the average score.
       4. I have made a line graph showing the expenditure of 3 states over time.
       5. Made a scatter plot showing types of expenditure VS the average score.
       6. Made a bar graph showing total expediture of all the states.
       
Training and testing data :
      train_data.drop(["STATE","YEAR"], axis=1)
      test_data.drop(["STATE","YEAR"], axis=1)
      with the above two lines the total squared error = 606.74 and total error = 201.09
      without: total squared error = 504.16 and total error = 172.64
      
Conclusion:
  
      Thus we conclude that dropping the offset values completely is unnecessary here. We are best off including them
      in the linear regression algorithm.
      Also the the Expenditure of state on education does not depends linearly on the average score of the students.
