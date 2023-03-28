
### Background

GoalZone is a fitness club chain in Canada,
GoalZone Offers a range Of fitness classes in two capacities - 25 and 15.

Some classes are always fully booked, Fully booked classes often have a low attendance rate.

GoalZone wants to increase the number of spaces available for classes.

They want to do this by predicting whether the member will attend the class or not.

If they can predict a member will not attend the class, they can make another space
available.


**Overview:**
Our goal in this project was to develop a predictive model for fitness class attendance, using data on class category and attendee booking information. We explored two models for this task: Logistic Regression and Random Forest.

**Results:**
We found that both models performed similarly in terms of accuracy, with the Random Forest model slightly outperforming the Logistic Regression model with an accuracy of 75.7%. However, when considering other metrics such as precision, recall, F1 score, and ROC AUC score, the two models were relatively close.

Further analysis revealed that the most attended category was HIIT, followed by Cycling ,Strength, Aqua, and Yoga. The attendance rates varied across categories, with HIIT having the highest attendance rate of 32.89% and Strength having the lowest attendance rate of 26.6%. The data was  unbalanced across categories, with HIIT having 600+ bookings followed by Cycling with 350+.

**Recommendations:**
Based on our analysis, we recommend that the fitness center focus on promoting Yoga and Strength classes, as these categories have the highest attendance rates and percentages of attendees. Additionally, the center should encourage individual attendees to book classes in advance, as this was found to be the most important predictor of attendance.

**Limitations:**

It's important to note that our analysis was limited by the available data. We did not have information on factors such as instructor of the fitness classes, which could have an impact on attendance. Additionally, our models were not able to capture any individual-level characteristics that may influence attendance, such as age, gender, or fitness level.

**Conclusion:**

In conclusion, our analysis provides insights into the factors that influence attendance in fitness classes. By focusing on promoting HIIT and Cyclying classes and encouraging attendees to book in advance, the fitness center can improve its attendance rates and ultimately its revenue. However, further research may be needed to fully understand the complex factors that impact attendance in fitness classes.
