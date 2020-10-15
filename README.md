# BaseballML--Predicted-Slug
This machine learning project was conducted with the goal of predicting 2020 slugging percentage based on 2019 Statcast quality of contact data. The 3 quality of contact statistics selected were: average exit velocity, average launch angle, and barrels. These three metrics were selected based on a previous study conducted by Al Melchoir, in which he found average exit velocity, average launch angle had the highest correlation with Isolated SLG. 

After visualizing the data, I found the correlation between the metrics and then between slugging percentage and each individual metric, respectively. 
The next step was utilizing Sci-Kit to process and clean the data. I then applied the linear regression function, with the processed metrics and 2019 slugging percentage as the two inputs. After calculating the root mean square error and the mean error, I was satisfied that the model was accurate. 
Finally, I ran the 2019 exit velocity, average launch angle, and barrel metrics for the qualified Mets hitters through my regression model to calculate their predicted slugging percentage for 2020. 

Disclaimer: This project was a way for me to explore data and apply my python skills to baseball. I understand that Statcast data is not predictive year to year and the sample size I used was small. 
