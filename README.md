
# Backend Development Fundamentals – Lab 01

**Live Deployment URL:** https://backend-development-fundamentals-lab-01-qzre.onrender.com/

**Subject:** Backend Development Fundamentals  
**Year/Term:** Year II, Term II  
**University:** Aurora Deemed to be University  
**Faculty:** Mr. Joel Prashanth D

## Student Details

| Field | Details |
|---|---|
| Name | VIJAY BHASKAR |
| Registration Number | 252U1R9153 |
| Section | S-26 |

## GitHub Repository

**Repository URL:** https://github.com/kannaff519-tech/backend-development-lab-01.git

## Project Objective

This lab demonstrates the fundamentals of creating and running a Node.js backend server using Express.js. It covers project initialization with npm, dependency installation, Express application setup, route handling, JSON responses, date and time generation, HTTP status codes, and handling unknown routes.

The application uses Express.js in `server.js`. The local development server runs on port 3000.

## Technologies Used

- Node.js
- Express.js
- npm
- JavaScript (CommonJS)
- HTTP and JSON response handling

## Project Folder Structure

```text
lab-01/
├── server.js
├── package.json
├── package-lock.json
├── README.md
├── .gitignore
└── screenshots/
    ├── home.png
    ├── about.png
    ├── time.png
    └── 404.png
```

## Installation and Execution

### Prerequisites

- Node.js installed
- npm installed
- A terminal or command prompt

### Install Dependencies

Open the terminal in the project directory and run:

```bash
npm install
```

If creating the project from an empty folder, initialize npm and install Express:

```bash
npm init -y
npm install express
```

### Start the Server

Run the following command:

```bash
node server.js
```

The local server is available at:

`http://localhost:3000`

Stop the server using `Ctrl + C`.

## Endpoints

| HTTP Method | Path | Description | Status Code |
|---|---|---|---|
| GET | `/` | Returns a welcome message | 200 |
| GET | `/about` | Returns JSON containing information about the application | 200 |
| GET | `/time` | Returns the current date and time | 200 |
| Any | Unknown path | Returns a Page Not Found response | 404 |

### Example URLs

- `http://localhost:3000/`
- `http://localhost:3000/about`
- `http://localhost:3000/time`
- `http://localhost:3000/unknown`

SCREENSHOTS 
Home Route
![Screenshot](./Screenshot%202026-10-29%20144340.png)
About Route
![Screenshot](./Screenshot%202026-10-29%20144354.png)
Time Route
![Screenshot](./Screenshot%202026-10-29%20144443.png)
404 Route
![Screenshot](./Screenshot%202026-10-29%20144458.png)


## Live Deployment

The application has a deployment URL on Render:

https://backend-development-fundamentals-lab-01-qzre.onrender.com/

The deployed endpoints can be tested by appending `/about`, `/time`, or `/unknown` to the base URL.

## Problems Faced and Solutions

| Problem | Solution |
|---|---|
| Understanding npm project management | Used `npm init -y` to create the project configuration. |
| Express.js was not available initially | Installed Express using `npm install express`. |
| Different routes require different response formats | Used `res.send()` for text and `res.json()` for JSON responses. |
| Unknown URLs needed appropriate handling | Added middleware to return a 404 response. |
| Preparing the application for deployment | Used a Node.js-compatible hosting service and configured the application to run on the hosting platform. |

## Learning Outcomes

- Learned to initialize a Node.js project using npm.
- Understood the purpose of `package.json` and `package-lock.json`.
- Installed and used Express.js.
- Created a backend server and implemented GET routes.
- Returned text and JSON responses.
- Generated date and time using `new Date()`.
- Understood HTTP status codes and 404 error handling.
- Learned the basic process of deploying a backend application.
- Practiced maintaining project files in a GitHub repository.

## GitHub Repository Management

Repository: https://github.com/kannaff519-tech/backend-development-lab-01.git

The project files should be committed and pushed to the repository so the source code can be reviewed and maintained.

Create a `.gitignore` file in the project root containing:

```text
node_modules/
.env
```

Do not commit passwords, API keys, or other private credentials.

## Conclusion

This lab provided practical experience in backend development using Node.js and Express.js. It helped build an understanding of npm, routing, HTTP responses, JSON data, error handling, and deployment. The project also provided experience in organizing source code and maintaining a backend application using GitHub.

**Student Name:** VIJAY BHASKAR  
**Registration Number:** 252U1R9136  
**Section:** S-26

