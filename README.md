# Hotel Reservation and Guest Management System

## Student Information

**Student Name:** Melea G. Dorado

**Student ID:** 61962024

**Selected Module 6 Entity:** Hotel Reservations

## 1. System Description

The Hotel Reservation and Guest Management System is a Vue.js frontend prototype based on the Hotel Reservations entity selected from the Module 6 system architecture.

The system allows users to manage hotel reservation records through a web interface. Users can add, view, edit, delete, and search reservation records.

The application also provides validation and uses browser localStorage to save reservation records.

## 2. Features

- Add hotel reservation records
- View reservation records
- Edit existing reservation records
- Delete reservation records
- Search reservation records
- Validate required fields
- Save reservation records using localStorage
- Restore saved records after refreshing the page
- Responsive user interface

## 3. Technologies Used

- Vue.js
- Vite
- JavaScript
- Tailwind CSS
- Browser localStorage
- Git
- GitHub
- GitHub Actions

## 4. Installation

Clone the repository:

```bash
git clone https://github.com/leighgd/dorado-module7-vue-system.git
```

Enter the project folder:

```bash
cd dorado-module7-vue-system
```

Install the dependencies:

```bash
npm install
```

## 5. How to Run

Start the development server:

```bash
npm run dev
```

Open the local address displayed by Vite in your web browser.

## 6. localStorage

The application uses browser localStorage to save hotel reservation records.

When reservation records are added, edited, or deleted, the updated records are saved to localStorage.

When the page is refreshed, the application retrieves the saved records from localStorage.

This allows the prototype to keep data without using a backend database.

## 7. Connection Between Module 6 and Module 7

Module 6 provided the architectural design for the proposed Hotel Reservation and Guest Management System.

Module 7 implements the Hotel Reservations entity from the Module 6 architecture as a working Vue.js frontend prototype.

The Module 7 prototype uses Vue.js components, Tailwind CSS, JavaScript CRUD logic, validation, search, and browser localStorage.

The backend, API, and database can be implemented as future components.

## 8. Limitations

- The system does not currently have a backend server.
- The system does not use a production database.
- Reservation records are stored in browser localStorage.
- There is no user authentication yet.
- The application is currently a frontend prototype.

## 9. Future Improvements

- Add a backend API
- Add a database
- Add user authentication
- Add guest management
- Add hotel room management
- Add online booking and cancellation
- Add payment processing
- Add email reservation confirmation
- Add an administrator dashboard

## 10. GitHub Repository

https://github.com/leighgd/dorado-module7-vue-system