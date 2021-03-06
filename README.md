# GymBuddy
A system that tells you how many people have swiped in to the gym, how many are estimated to still be there, and if that amount of people is historically significant. Also contains a workout tracker. 

We came up with this idea due to the seemingly random times that the gym fills up with students. At Pitt, there is so much variance to cause the gym to become busy at different times, such as midterms, summer term, etc. Thus, we decided to create a system that can tell you if the gym is typically busy at this time, and how many people are estimated to be there.

The tracking system is intended to be connected to the Pitt ID swipe system. Every swiped ID counts as a new person attending a gym session. The system estimates how long they stay to be a time between 45-70 minutes, the average time gym-goers spend at the gym. It stores this data and keeps an average of it, plotting out six time intervals for every day of the year, taking the average amount of people in that time interval. This historical data is kept to let the user know that, at the same time interval this year and the year before and so on, whether the gym should be busy. This way, all of the confounding variables that come with school semesters are mostly accounted for.

The model depicted on the website shows a scaled down version for a quick demo. The grid on the left demonstrates the estimated amount of people currently at the gym, and what time they are expected to leave. On the right side is a graph that demonstrates how historically busy the gym is at that exact date and time interval, along with an estimate on whether the gym is very busy, a little busy, or not busy. 

Realistically, this model would move much slower. Instead of refreshing every second, it would be on the scale of minutes, and instead of a day being considered a minute long, it would be 1440 minutes long. Since the test data is randomly generated, the real-world data would give a lot more predictable estimate than that given by the analysis of randomized data. 

## Preview

### Landing Page
![Landing Page](https://github.com/jerols4/GymBuddy/blob/master/Landing.PNG)

### Gym Traffic
![Gym Traffic Page](https://github.com/jerols4/GymBuddy/blob/master/ActivityTracker.PNG)

### Workout Tracker
![Workout Tracker Page](https://github.com/jerols4/GymBuddy/blob/master/WorkoutTracker.PNG)
