# Personal Smart Mirror
 
**Team Members:**

*Blaine Sieck – Group Leader*    
·      Came up with idea of the interface design  
·      Duties: Date, time, calendar event, on/off switch for the whole system, drag and drop
 
*Gabriel Costanzo*  
·      Duties: news api, weather forecast api (responsible for all the APIs)

*Eduardo Lozano*    
·      Duties: music controls/display, light controls settings

*Abdus Sami Yakoob*    
·      Duties: Reminders controls/display, health app controls/displays

**Links:**  

[Github Repo](https://github.com/BlaineSieck/P1.14) (e.g. https://github.com/BlaineSieck/P1.14)  
[Presentation Page](https://blainesieck.github.io/P1.14/.) (e.g. https://blainesieck.github.io/P1.14/., contains content of this README)
 
**Sketch Design:**
![](p1.group14.png)
**Main Functions:**

time, date, schedule/calendar, current weather, weekly weather, health app (sleep, steps etc.), reminders/notifications, news feed, music controls, lighting controls, on/off switch

**Implementation:**

We have divided the functions among our group members to develop individually. We meet once a week to go over what we have accomplished, merge our functions, and make changes to the design when necessary. As of now, the mirror will begin in an off state (only displaying the date and time) and then once it is turned on all of the other functions will become visible and active. You will be able to drag and drop items to any of the 4 edges of the mirror as long as they do not overlap with each other.

**Future Plans:**  

We will continue to make adjustments where necessary as we begin merging our functions.

**Final Functionality:**  

Date and time are accurate and updated continuously  
The calendar is hardcoded  
The weather panel uses an API to get accurate and continious weather updates including the current temperature, high, low, and five day forecast  
The news panel uses an API to get accurate and continous news updates and will dipslay a short description of the article when you hover the mouse over the image  
The music is hardcoded with three different songs and allows for pause and play, next and previous song, volume controls, and will dispaly the appropriate album art  
The lighting controls panel includes RGB sliders to adjust the color of the light and the brightness slider allows for dimming the light which appears as a border around the mirror  
The reminders are hardcoded but there are three different reminders which cycle every twenty seconds  
The health data is hardcoded  
The on and off button disables or enables everything but the clock which we believed to be the best "default" screen  
Drag and drop is available for every item except for the news, since it works best with the article descriptions next to the images, and the reminders and the health panels  
We also added a light blue/silver tint over the webcam to simulate the look of a mirror  

**Demo GIF:**  
![](p1.group14.gif)
