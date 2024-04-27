# Contact Management App

This is a contact management app with Charts and Maps using ReactJS, TypeScript, TailwindCSS, React Router v6 and React Query aka TanstackQuery.


GITHUB LINK:-[Vaishnavi-3021/Taiyo-FrontEndTask (github.com)](https://github.com/Vaishnavi-3021/Taiyo-FrontEndTask)



### Objectives Met:-

#### Page Contacts:

* The app have a form for adding new contacts
* The app displays a list of all added contacts

* Each contact have a button to view the contacts details
* The app is able to edit and delete contacts

* Made use of Redux to store the contact data

#### Page Charts and Maps:

Built dashboard with:

- A line graph showing the cases fluctuations
- A react leaflet map with markers that indicates the country name, total number
  of active, recovered cases and deaths in that particular country as a popup.


### APIs used to fetch data and create dashboards:-

* World wide data of cases: [https://disease.sh/v3/covid-19/all](https://disease.sh/v3/covid-19/all)
* Country Specific data of cases: [https://disease.sh/v3/covid-19/countries](https://disease.sh/v3/covid-19/countries)
* Graph data for cases with date:[https://disease.sh/v3/covid-19/historical/all?lastdays=all](https://disease.sh/v3/covid-19/historical/all?lastdays=all)

### Prerequisites:-

- Node.js (at least version 12)
- npm or yarn

### Steps:-

Install dependencies:

```bash
   npm install
```

Start the development server:

```bash
   npm start
```

   This will start the app in development mode and open it in your default web browser.

### Technologies Used:-

- ReactJS
- TypeScript
- TailwindCSS
- React Router v6
- React Query
- Chart.js
- React Leaflet

### Folder Structure:-

- `src/components`: Contains individual components.
- `src/pages`: Contains main pages of the app.
- `src/features`: Contains Redux slices.
- `src/api.ts`: Handles API calls using React Query.
- `src/store.ts`: Redux store setup.


**Thank You.**
