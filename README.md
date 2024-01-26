# Daily-Scheduler

Description of the Project:

This project is required to have a Daily work scheduler wherein I have firstly created Timeblocks in HTML file defining separate <div> for every hour with their save button (button element) to save the content in the planner accordingly.

In Javascript file I declared current day, date and time using Dayjs - by using the syntax -  dayjs().format('DD MMM YYYY dddd [at] hh:mm:ss a');

 - Declared saveBtn click listener function.
 - Saving content in local storage.
 - Declaring function timeTracker() to see current number of hours.
 - Using if and else statement for background indicators - Past, Present & Future.
 - Get item from the local storage.
 - Calling the function timeTracker();

 Links Used :

 https://day.js.org/docs/en/display/format

 https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage