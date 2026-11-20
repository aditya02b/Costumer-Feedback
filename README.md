[README.md](https://github.com/user-attachments/files/35130835/README.md)
# Customer Feedback App

A simple web app where users can register, log in, and submit or edit their feedback. An admin can manage all feedback from a dashboard.

**Live demo:** https://YOUR-USERNAME.github.io/customer-feedback/

## Features

**User**
- Register with username, email and password (with validation)
- Log in and log out
- Add new feedback
- View and edit previously submitted feedback

**Admin**
- Admin Feedback Dashboard showing ID, feedback, date and actions
- Create: add new feedback
- Read: view full details of any feedback
- Update: edit any feedback
- Delete: remove any feedback

## Demo Login

| Role  | Username | Password   |
|-------|----------|------------|
| Admin | admin    | admin123   |
| User  | Register a new account on the Sign Up page |

## How to Run

1. Download or clone this repository.
2. Open `index.html` in any browser (Chrome, Edge or Firefox).

No installation is needed.

## Technologies Used

- HTML
- CSS
- JavaScript

## Notes

- Data is stored in the browser using `localStorage`, so it stays on the same device and browser.
- Passwords are stored as SHA-256 hashes. This is a demo project, not a production system.
- Use the same browser for the user and admin to see the same data.

## Project Structure

```
customer-feedback/
├── index.html
└── README.md
```
