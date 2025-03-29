# Venue Management App

## Overview
The Venue Management App is designed to facilitate the management of clients for a venue. It provides functionalities for adding clients, viewing client lists, managing payments, and allowing clients to access their payment history.

## Project Structure
```
venue-management-app
├── public
│   ├── index.html         # Main interface for managing clients
│   └── client.html        # Client-specific interface for logging in and viewing payment history
└── README.md              # Documentation for the project
```

## Features
- **Client Management**: Admins can add, edit, and delete client profiles.
- **Payment Management**: Admins can manage client payments and view payment history.
- **Client Access**: Clients can log in using their phone number and CIN to view their payment dates and history.

## Setup Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd venue-management-app
   ```
3. Open the `public/index.html` file in a web browser to access the admin interface.

## Usage Guidelines
- **Admin Interface**: Use the admin panel to manage clients and payments.
- **Client Interface**: Clients can access their payment information through the `client.html` page by entering their phone number and CIN.

## Technologies Used
- HTML
- JavaScript
- Firebase (for database management)

## License
This project is licensed under the MIT License.
