# Timer Stopwatch Pending
Problem
Problem : Google timer


Make a react app with the name timer_stopwatch
<img src ="https://github.com/Satya12325/React-Stopwatch-Timer/blob/master/Screenshot%20(28).png" />

Make sure to include this MarkDown file in your submission with checked boxes for all parts you have completed.

NOTE: Follow the instructions carefully and follow coding discipline

NOTE2: Indent your code correctly and stick to one kind of naming style

NOTE3: All components must be in different files and within a Components folder. CSS can be shared between components if desired. CSS modules must also be in your components folder.

NOTE4: All static files like images must be in the public folder.

NOTE5: All components files must have the same name as their compoenents. Eg: App must be in App.js.

NOTE6: You must only call ReactDOM.render once in your index.js file!

Within the react App, delete all files from the src folder and create your own files!

Learning objectives:
Using listeners in react.
Modifying state using setInterval
Using lifecycle methods. ( you can check in componentDidUpdate if seconds are 0, and initiate a stop, write a cleanup with componentWillUnmount )
if else rendering or using && to render based on condition
Final Goal
The goal of this project should be to create a clone of the Google countdown timer and stopwatch.

You can see this by either searching google for "stopwatch" or visiting this link https://www.google.com/search?q=stopwatch.

Minimum Viable Product
MVP or minimum viable product is the least amount of functionality you must have done by the end of today.

You don't need to focus on styles for the MVP.

 You must have implemented a stopwatch that lets you start, stop and reset.
 The stopwatch must display the number of seconds and milliseconds.
 The timer must allow a user to manually enter the time using an inputbox, in seconds.
 The user should be able to start, stop and reset the timer.
 The user should be able to toggle between the timer and the stopwatch using tabs just like the google timer.
 The timer should not increment twice if its already clicked
Stretch Goals
If you are able to complete the MVP in time, implement this additional functionality. This must be completed by the end of the next day.

 The stopwatch must also display the minutes and hours.
 The timer must also display the minutes and hours.
 The timer must allow the user to input the time in seconds minutes and hours just like the Google timer.
if you want the state of time to be maintained then either lift the state up to the parent component
or use CSS to hide the other component

