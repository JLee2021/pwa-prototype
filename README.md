# pwa-prototype

> May 2021

<br>

### Project Description:

This project will prototype a mobile-first fullstack progressive web application (PWA) for offline fisheries data collection, including font- and back-end and database. The lessons learned from this effort will inform the DIS Development Team of the pros and cons of PWA development as an alternative to native mobile applications development for offline data collection. This effort does not intend to build a "useful" or "production" application. This effort intends to explore and validate new technologies.

<br>

This application, named _AtlasDataEntry_, will allow the user to sign into the application. create a fishing trip, and record basic catch data (species name, code, and disposition). See requirements and mockups below.

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

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

**Getting Started**

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

**Learn More**

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

**Deploy on Vercel**

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

<br>

### Requirements:

- Assets for the manifest.json file will be provided the Agency
- The serviceworker.js file should serve up all assets, including any support tables
- Species list and disposition codes will be provided by the Agency
- As a user, I can sign into the app using my unique 3-digit ID number, e.g., 999 (for the purposes of this prototype, ID numbers and passwords will be provided by the Agency)
- As a system, I will validate who is signing into the app
- As a user, I can create a new fishing trip
- A unique trip number displayed in the dashboard is the concatenation of the users 3-digit ID number and 3-digit sequential number starting at 001
- As a user, I can create a fishing haul (multiple hauls in a single trip) and collect the time and GPS from the device at the start of that fishing haul
- As a user, I can create catch (species and disposition) (multiple catch for a single haul) via a dropdown menu, typing in the species common name, or typing in the species code

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
