# pwa-prototype

> May 12, 2021

<br>

### Project Description:

This project will prototype a mobile-first fullstack progressive web application (PWA) for offline fisheries data collection, including font- and back-end and database. The lessons learned from this effort will inform the DIS Development Team of the pros and cons of PWA development as an alternative to native mobile applications development for offline data collection. This effort does not intend to build a "useful" or "production" application. This effort intends to explore and validate new technologies.

<br>

This application, named _AtlasDataEntry_, will allow the user to sign into the application. create or modify a fishing trip, and record basic catch data (species name, code, and disposition). See requirements and mockups below.

### Type: Progressive Web Application

### URL: [Link](link)

<br>

### Network Location(s):

| Environment | Location         |
| ----------- | ---------------- |
| Development | [Location](link) |
| Test        | [Location](link) |
| Production  | [Location](link) |

<br>

### Contacts:

| Role                  | email                          |
| --------------------- | ------------------------------ |
| Project Manager       | joshua.lee@noaa.gov            |
| Lead Developers(s)    | michael.cranston.ryan@noaa.gov |
| Other Contributors(s) | email                          |

<br>

### Technology Stack:

Any technologies can be used. The following are recommended for this project.

<br>

Front-end

- React.JS/[Next.JS](https://nextjs.org/) or create-react-app (note: Next.JS is a React framework)
- Material UI or Styled Components
- [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)

Back-end

- Google Cloud or AWS
- Node.JS, Python Flask
- PostgreSQL

<br>

### Requirements:

- Assets for the manifest.json file will be provided the Agency
- Species list and disposition codes will be provided by the Agency
- As a user, I can sign into the app using my unique 3-digit ID number, e.g., 999
- As a user, I can create, read, update, and delete a fishing trip
- A unique trip number displayed in the dashboard is the concatenation of the users ID number and 3-digit sequential number starting at 001
- As a user, I can create, read, update, and delete a fishing haul in a fishing trip (multiple hauls in a single trip) and collect the time and GPS from the device at the start of that fishing haul
- As a user, I can create, read, update, and delete catch for a fishing haul (multiple catch for a single haul)
- As a user, I can add catch via a dropdown menu, typing in the species common name, or typing in the species code
- As a user, I can add a disposition code via a dropdown, typing in the name, or typing in the code
- As a system, I will validate who is signing into the app

<br>

### Mockups:

Login Page
<br>
<img src="https://github.com/JLee2021/pwa-prototype/blob/main/readme-images/login.png?raw=true" width="300">

<br>

User Dashboard
<br>
<img src="https://github.com/JLee2021/pwa-prototype/blob/main/readme-images/userdashboard.png?raw=true" width="300">

<br>

New Trip
<br>
<img src="https://github.com/JLee2021/pwa-prototype/blob/main/readme-images/newtrip.png?raw=true" width="300">

<br>

Trip Dashboard
<br>
<img src="https://github.com/JLee2021/pwa-prototype/blob/main/readme-images/tripdashboard.png?raw=true" width="300">

<br>

Start New Haul
<br>
<img src="https://github.com/JLee2021/pwa-prototype/blob/main/readme-images/starthaul.png?raw=true" width="300">

<br>

Catch Log
<br>
<img src="https://github.com/JLee2021/pwa-prototype/blob/main/readme-images/catchlog.png?raw=true" width="300">

<br>

Record New Catch
<br>
<img src="https://github.com/JLee2021/pwa-prototype/blob/main/readme-images/newcatch.png?raw=true" width="300">

<br>

End Haul
<br>
<img src="https://github.com/JLee2021/pwa-prototype/blob/main/readme-images/endhaul.png?raw=true" width="300">

<br>

---

#### This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.
