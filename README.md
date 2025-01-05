# Expense-Tracker-
 
1) Project Overview: "A full-stack Expense Tracker application to manage income sources and monthly expenses with graphical insights."

Key Features:

3) Add, edit, and delete income sources and expenses.
Visualize income and expenses through dynamic graphs using libraries like Chart.js or D3.js.
User-friendly and responsive design for enhanced accessibility.

4) Tech Stack:
Frontend: React.js, CSS
Backend: Node.js, Express.js
Database: MongoDB (or any database used)
Setup Instructions:

## Configuration and Setup

In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

- Open the project in your prefered code editor.
- Go to terminal -> New terminal (If you are using VS code)
- Split your terminal into two (run the Frontend on one terminal and the Backend on the other terminal)

In the first terminal

```
$ cd Frontend
$ npm install (to install frontend-side dependencies)
$ npm run  start (to start the frontend)
```

In the second terminal

- cd Backend and Set environment variables in config.env under ./config
- Create your mongoDB connection url, which you'll use as your MONGO_URI
- Supply the following credentials

```
#  ---  Config.env  ---

PORT =5000
MONGO_URI =

```
