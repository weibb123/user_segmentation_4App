# user_segmentation_4App

<b><h2>Background:</h2></b>

For this data analysis, I will perform user segmentation to identify types of customers and suggest ideas to keep customers.
Sample data with the following columns

user_id -> each unique id represents a user in the app

Average_Screen Time -> screen time of each users

Average Spent on App -> average of how much an user spend on this app

Left Review -> record of whether an user left a review

Rating -> The rating that an user give

New Password Request -> number of times user request a new password

Last visited minutes -> Last visited minutes of users

Status -> Status of users (installed, uninstalled)

<b><h2>Report:</h2></b>

![image](https://user-images.githubusercontent.com/84426364/230226667-f2edf97b-32a7-4c88-8f89-69cfe7baadef.png)

Those people who installed the app, have a high average on screen time and average spend on App. In other words, user stick to the App after using it.

Those who uninstalled the app leave the app at an early on before actually trying it out.

Customers who spend more money on the app might choose to stay due to sunk - cost fallacy. not wanting give up the cost already made.

![image](https://user-images.githubusercontent.com/84426364/230229788-654cb7ba-3187-4017-b854-c75368d8df05.png)

User who does not spend a lot of time on the app uninstall and give a low rating.

<b><h2>Customer Segmentation</h2></b>

Pipeline: gather data/columns that describe the segment well -> preprocessing/scale each column -> use it on K-nearest-neighbor.

integer label

0: customers that retained

1: customers who churn

2: customers who need attention

![image](https://user-images.githubusercontent.com/84426364/230230423-bbbe2865-a53e-4551-9458-96f805ce006a.png)

The blue segment shows the segment of users who stayed using the app. The red segment shows the segment of users who uninstalled the app or wanting to uninstall. The green segment shows the segment of users that no longer use the applications.

<b><h2>Summary:</h2></b>
 In conclusion, app user segmentation is a good approach to understand the user activities, identify types of users, and how users engaged with the app/product. It helps companies better understand how to retain their users, find the user segment for a marketing compaign, solve problem where it requires to find user with similar characteristic.


