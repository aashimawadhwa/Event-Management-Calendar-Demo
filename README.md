# Event-Management-Calendar-Demo
## For Talawa Calendar

This project is a clone of Google calendar with simplified functionality. Implemented without any third-party libraries, for example, working with date and time (moment.js, day.js) or ready-made UI components


When you enter the site, you get to the week of the current day, you can create an event by clicking on the area in which you are interested, then a window with the selected time will appear





In the month mode, you can change the month when scrolling the wheel


# How to start

1. Run `npm install` at the root folder
2. Start: `npm run start`
3. Build: `npm run build`


# Tech stack

1. HTML5
2. CSS3
3. Typescript
4. mockApi
5. fetch
6. SCSS-modules 
7. BEM methodology
8. React, hooks
9. js Date api

#
Custom implementations can be found in this repository:


- **Fetch Api Class** (src/gateway/api) - class for working with rest api, uses fetch
- **Hooks**
  - **useForm** (src/hooks/useForm) - a hook for convenient work with the state of the form
  - **useValidator** (sdk/hooks/useValidator) - a hook for convenient work with field validation
  - **useCalendar** (src/hooks/useCalendar.ts) - hooks for convenient work with date and time using the js date api
- **SCSS MODULES + Adaptive** - css modules were used + fully adaptive was made
- **Components/UI kit**
 - **TextField** (src/components/common/forms-elements/text-field) - a simple implementation of the field as in google calendar
  - **DatePicker** (src/components/common/forms-elements/date-picker) - custom implementation of datepicker with simple support for all languages (this means that the date formatting does not fully match to how it should be written in the selected language) and you can change the state using the keyboard

  - **TimePicker** (src/components/common/forms-elements/time-picker)- The timepicker is simple for all languages, the hint shows the time difference between two dates and appears when the dates correspond to each other (that is, the same day is selected) and you can change the state using the keyboard


Author **Aashima Wadhwa**
