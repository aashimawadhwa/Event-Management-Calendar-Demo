# Event-Management-Calendar-Demo
## For Talawa Calendar

This project is a clone of Google calendar with simplified functionality. Implemented without any third-party libraries, for example, working with date and time (moment.js, day.js) or ready-made UI components


When you enter the site, you get to the week of the current day, you can create an event by clicking on the area in which you are interested, then a window with the selected time will appear

![Screenshot 2023-04-10 at 2 38 06 PM (2)](https://user-images.githubusercontent.com/73706697/230871395-eee2b8bd-b5b9-4d7c-9829-d7ac486f73e6.png)



![Screenshot 2023-04-10 at 2 39 45 PM (2)](https://user-images.githubusercontent.com/73706697/230871679-47e4d2e5-6d7f-4052-a598-f3a9d0c4c82b.png)
![Screenshot 2023-04-10 at 2 39 53 PM (2)](https://user-images.githubusercontent.com/73706697/230871696-b2f57619-cacd-429f-89eb-d718219eca01.png)


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
  
 ![Screenshot 2023-04-10 at 2 36 04 PM (2)](https://user-images.githubusercontent.com/73706697/230870915-25bbc2fa-f287-4316-ae46-7ebe41e9173a.png)

  - **TimePicker** (src/components/common/forms-elements/time-picker)- The timepicker is simple for all languages, the hint shows the time difference between two dates and appears when the dates correspond to each other (that is, the same day is selected) and you can change the state using the keyboard.
  ![Screenshot 2023-04-10 at 2 33 55 PM (2)](https://user-images.githubusercontent.com/73706697/230870637-a45cc9ad-d39b-4410-b401-4db14602c133.png)
![Screenshot 2023-04-10 at 2 33 59 PM (2)](https://user-images.githubusercontent.com/73706697/230870654-36c50721-455c-465e-970d-3d7e6928ff02.png)



Author **Aashima Wadhwa**
