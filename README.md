# mern-auth
MERN auth app using tailwind css, redux and jwt

This is a MERN (MongoDB, Express, React, Node.js) stack application with authentication. It allows users to sign up, log in, and log out, and provides access to protected routes only for authenticated users.
      
The front-end of the application is built with React and uses React Router for client-side routing. The back-end is built with Node.js and Express, and uses MongoDB as the database. Authentication is implemented using JSON Web Tokens (JWT). The app has also register and sign-in functionality using Google auth.

This application is intended as a starting point for building full-stack web applications with authentication using the MERN stack. It is mostly my way of exploring React with Redux for frontend and NodeJS, ExpressJS & MongoDB for backend. I am also kind of using it to showcase my skills as a MERN stack developer 😉.
 
List of libraries installed for backend (BTW you only need to type npm i or npm install) : - 

- npm init -y (outside client folder, but inside mern-auth folder)
- create a folder named api or backend inside mern-auth folder
- node i express (inside mern-auth only)
- npm i nodemon (inside mern-auth folder) --> npm run dev
- npm i mongoose (inside mern-auth folder)
- npm i dotenv (inside mern-auth folder)
- npm i bcryptjs (inside mern-auth folder) -- bcryptjs and not bcrypt(problem in production)
- npm i jsonwebtoken (inside mern-auth folder)
- npm i cookie-parser (inside mern-auth folder)
