# Nxt Watch

Nxt Watch is a video streaming application built with React.js. It allows users to browse and watch videos, save videos to a saved list, and toggle between light and dark themes.

## Features

*   Browse and watch videos
*   Save videos to a saved list
*   Toggle between light and dark themes
*   Login and authentication
*   Trending, Gaming, and Saved Videos routes
*   Video item details page

## Technologies Used

*   React.js
*   Styled Components
*   React Router
*   js-cookie
*   react-loader-spinner
*   react-player
*   date-fns

## Setup Instructions

1.  Clone the repository: `git clone <repository-url>`
2.  Navigate to the project directory: `cd Nxt-Watch`
3.  Install dependencies: `npm install`
4.  Start the development server: `npm start`

## Routes

*   `/login`: Login page
*   `/`: Home page
*   `/trending`: Trending videos page
*   `/gaming`: Gaming videos page
*   `/saved-videos`: Saved videos page
*   `/videos/:id`: Video item details page
*   `/not-found`: Not found page

## API Endpoints

*   `POST https://apis.ccbp.in/login`: Login API
*   `GET https://apis.ccbp.in/videos/all?search=`: Home videos API
*   `GET https://apis.ccbp.in/videos/trending`: Trending videos API
*   `GET https://apis.ccbp.in/videos/gaming`: Gaming videos API
*   `GET https://apis.ccbp.in/videos/:id`: Video details API

## Contributor

- Nenavath Suresh - [GitHub Repo](https://github.com/Nenavath-Suresh)
