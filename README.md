 
LIESHAN VALLIADUM
ST10439494
Introduction to mobile application development
Assesment type: Practicum Exam 
 
 
Table of Contents
Purpose and explanation of the app:	2
Pseudocode and flowcharts	3




GitHub - Lieshan29/IMAD5111PracticumExamLieshanValliadum

 
Purpose and explanation of the app:

The main purpose and use of this app is to provide detailed information related to the weather on each day. The app is required to manage the weather conditions and examine the conditions too. The app can be very beneficial to its users because of the following. 
By the users knowing what kind of weather is expected in the day, it allows them to plan ahead and make the necessary arrangements that they need for they day to be successful. People will be able to know what activities they can and cannot take part in and whether they are required to stay indoors or not. 
The app will also be able to ensure safety as citizens will be able to prepare themselves for any natural disasters such as floods or hurricanes. People will know whether they can go out or not or whether they are needed to evacuate the area in order to survive. 
Environmental awareness will also be promoted. By using a weather app, people will become more and more aware of the environment. Weather patterns and change in temperature can all be studied and analysed by the use of a weather app. 
This app was designed to provide a deep, descriptive insight on weather conditions through the week. This app does indeed serve this purpose. 





 
GitHub repository link 
https://github.com/Lieshan29/IMAD5111PracticumExamLieshanValliadum













Pseudocode and flowcharts 

SplashActivity
onCreate
Set the content view to activity_splash.xml
Start a handler to delay for 3 seconds
After 3 seconds, start MainActivity and finish SplashActivity
MainActivity
onCreate
Set the content view to activity_main.xml
Initialize an array of temperatures (min, max) for each day of the week
Calculate the average temperature using a helper function
Display the average temperature in avgTempTextView
Set up a button click listener to navigate to DetailedViewActivity
Set up a button click listener to clear user data
calculateAverageTemperature
Initialize totalMinTemp and totalMaxTemp to 0
Loop through each temperature pair, summing min and max values
Return the average temperature by dividing the total by the number of days
DetailedViewActivity
onCreate
Set the content view to activity_detailed_view.xml
Enable the back button in the action bar
Initialize arrays for days of the week, temperatures, and weather conditions
Create a list of weather details for each day
Set up an adapter to display the weather details in a ListView
onOptionsItemSelected
If the back button in the action bar is clicked, finish the activity to return to the previous screen
XML Layout Files
activity_splash.xml
Define a RelativeLayout with an ImageView for the logo and a TextView for the app name
activity_main.xml
Define a RelativeLayout with a TextView for the average temperature and buttons for viewing details and clearing data
activity_detailed_view.xml
Define a RelativeLayout with a ListView for displaying detailed weather information
AndroidManifest.xml
Declare SplashActivity, MainActivity, and DetailedViewActivity
Set SplashActivity as the launcher activity
Specify MainActivity as the parent activity for DetailedViewActivity for proper back navigation

 
 
Screenshots of each screen

 
Figure 1: Splash screen UI




 
Figure 2: Main activity ui
