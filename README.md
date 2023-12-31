# Login & Register Form

Login page (the form includes username, password, remember checkbox & a link forgot password)

Link Login page: https://quyenngthmy.github.io/login_form/build/

To login:
- Fill in the correct information of the existing username: username is not case sensitive.
- Fill in any password with at least 6 required characters, containing at least one uppercase letter, lowercase letter, number and special symbol.
- Because it is an emulator, you only need the correct username and enter any password.
  
Register page (The form includes username, password, first name, last name, email, phone, address )

Link Register page: https://quyenngthmy.github.io/login_form/build/register.html

To register:
- Fill in the required information including username, password, full name, email, phone.
- Address is not required.

User page: Displays recently logged in user information.

Link User page: https://quyenngthmy.github.io/login_form/build/user.html


Link dummy user API: https://jsonplaceholder.typicode.com/users

User list to test:
1. Bret
2. Antonette
3. Samantha
4. Karianne
5. Kamren
6. Leopoldo_Corkery
7. Elwyn.Skiles
8. Maxime_Nienow
9. Delphine
10. Moriah.Stanton

# Programing
- Languages: JavaScript
- Web client: HTML (HTML5), CSS (CSS3, BEM, SCSS, Responsive, Flexbox, Grid, Animation), DOM (Document Object Model)
- Framework/Library: Webpack, React, NodeJS, Axios, SCSS, Tailwind
- SCM: GitHub
- Other: RESTful API, React Hooks, npm, babel

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Scripts](#scripts)
- [Folder Structure](#folder-structure)

## Getting Started

### Prerequisites

Make sure you have the following software installed before proceeding:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. Clone the repository:
```
git clone https://github.com/quyenngthmy/exam_form.git
```
2. Navigate to the project directory:
```
cd source
```
3. Install dependencies:
```
npm install
```

### Scripts
List and explain the available npm scripts:

Start the development server:
```
npm start
```
Build the project for production:
```
npm run build
```
Run tests:
```
npm test
```
### Folder Structure
Explain the purpose of each important folder in your project.
```
├── /build/                  # Compiled files (not included in the repository)
├── /src/                   # Source code
│   ├── /assets/            # Static assets
│   ├── /components/        # React components
│   ├── index.scss          # Stylesheets
│   ├── index.html          # HTML template
│   ├── index.js            # Entry point
├── .babelrc                # Babel configuration
├── webpack.config.js       # Webpack configuration
└── package.json            # NPM package configuration
```
