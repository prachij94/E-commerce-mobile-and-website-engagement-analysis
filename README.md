# E-commerce-mobile-and-website-engagement-analysis

An Ecommerce company based in New York City sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.
The company is trying to decide whether to focus their efforts on their mobile app experience or their website. 
We analyse the artificially generated customer data by creating a linear model using Linear Regression.

The data has Customer info, suchas Email, Address, and their color Avatar. Then it also has numerical value columns:

- Avg. Session Length: Average session of in-store style advice sessions.
- Time on App: Average time spent on App in minutes
- Time on Website: Average time spent on Website in minutes
- Length of Membership: How many years the customer has been a member.

The data is explored using **seaborn** by finding general relationships between **the Time on Website and Yearly Amount Spent**, **the Time Spent on App and Yearly Amount Spent**, **Time on App and Length of Membership**.
Also, plotting all the variables against each other using pairplot to find the most correlated feature. Based on this plot **Length of membership** looks to be the most correlated feature with **Yearly Amount Spent**.

A linear model is created with *'Avg. Session Length', 'Time on App', 'Time on Website', 'Length of Membership'* to predict *'Yearly Amount Spent'* and then predictions are made for the test data.

Then the model performance is evaluated by calculating the Mean Absolute Error, Mean Squared Error, and the Root Mean Squared Error.

The conclusion about the question is made by interpreting the coefficients of the linear model.

**So the company should focus more on their mobile app or on their website?**

There are two ways to think about this: *Develop the Website to catch up to the performance of the mobile app*, or *develop the app more since that is what is working better*. This sort of answer really depends on the other factors going on at the company, you would probably want to explore the relationship between Length of Membership and the App or the Website before coming to a conclusion.


