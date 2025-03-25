# Venue Management App

## Overview
The Venue Management App is a web application designed to manage clients and offers for a venue. It provides functionalities to display a list of clients, details of specific offers, and the schedule of open and closed days. The application is built using React and connects to a Firebase database for data management.

## Features
- **Client Management**: View and manage a list of clients.
- **Offer Details**: Retrieve and display details of available offers.
- **Venue Schedule**: View the schedule of open and closed days for the venue.

## Technologies Used
- React
- Firebase
- HTML/CSS

## Project Structure
```
venue-management-app
├── public
│   ├── index.html
│   └── style.css
├── src
│   ├── components
│   │   ├── ClientList.js
│   │   ├── OfferDetails.js
│   │   └── VenueSchedule.js
│   ├── firebase
│   │   └── firebaseConfig.js
│   ├── App.js
│   └── index.js
├── package.json
├── README.md
└── .gitignore
```

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd venue-management-app
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm start
   ```

## Usage
- Open your browser and navigate to `http://localhost:3000` to view the application.
- Use the navigation to access different features of the app.

## License
This project is licensed under the MIT License.