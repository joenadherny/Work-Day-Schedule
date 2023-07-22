# Work-Day-Schedule
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with time blocks for standard business hours of 9am to 5pm
WHEN I view the time blocks for that day
THEN each time block is color-coded to indicate whether it is in the past, present, or future
WHEN I click into a time block
THEN I can enter an event
WHEN I click the save button for that time block
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
I first made a function for the save btn that would save the input of the user depedning on the id. I also copied the divs that were provided and made them up to 5pm. 
After doing that I made a for loop concerning the way of making sure the data was saved on local storage. 
Then i created an if else statement that focused on adding or removing classes deping on the time of the day that lined up with the class. This resulted in using day js along with jquery to implement this function. 
Finally I made a function that would display the current date of the day in the header.
I had a tutoring session provided by class that helped me set up the for loop and then did some research on my own in google to figure out where to go next. I also utilized ask BCS for times when I was stuck.