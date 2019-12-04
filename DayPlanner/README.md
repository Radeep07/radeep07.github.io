# Third-Party APIs: Day Planner

This is a simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.

The app displays standard business hours (9 a.m. to 5 p.m.). Each time slot represents one hour and contains the following:

* The time.

* A field to hold user input.

* A save button allowing the text to persist when the application is refreshed.

* Each timeblock is color coded to indicate whether it is in a past, present, or future hour.

Clicking on the save button will store the time and user input in `localStorage`.

Near the top of the calendar, the application displays the current day. Additionally, each hour is color coded to reflect whether the time slot is in the past, the present, or the future. This will change depending on the time of day.

I have used the [Moment.js](https://momentjs.com/) library to work with date and time. 

![day planner demo](./Assets/Third-Party-APIs-demo.gif)

## User Story

AS AN employee with a busy schedule

I WANT to add important events to a daily planner

SO THAT I can manage my time effectively 

## Business Context

Poor time management can result in missed meetings and deadlines or create the appearance of unprofessionalism. A daily planner allows employees to see their day at a glance, schedule time effectively, and improve productivity. 