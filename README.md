# day-planner

I have Created a simple calendar application that allows the user to save events for each hour of the day. This app runs in the browser and features dynamically updated HTML and CSS powered by jQuery.

The app displays standard business hours (9 a.m. to 5 p.m.). Each time slot represents one hour and contains the following:

* The time

* Input field

* A save button

Clicking on the save button will store the time and user input in `localStorage`.

Near the top of the calendar, the application displays the current day. Additionally, each hour is color coded to reflect whether the time slot is in the past, the present, or the future. This changes depending on the time of day.

I used the [Moment.js](https://momentjs.com/) library to work with date and time.


