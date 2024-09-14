# GraphBooksExplore

# GraphBooksExplore

GraphBooksExplore is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that allows users to search for books via the Google Books API and save their favorite books to a personal list. The app uses GraphQL with Apollo Client for API queries and mutations, allowing users to manage their saved books efficiently.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Description

GraphBooksExplore allows users to search for books using the Google Books API, save selected books to their profile, and manage their personal book collection. The application is built using the MERN stack and leverages GraphQL and Apollo Client for efficient data management.

## Features

- **Search for Books**: Search for books using the Google Books API.
- **Save Books**: Save books to your personal collection after logging in.
- **View Saved Books**: View books saved in your personal collection.
- **Delete Saved Books**: Remove books from your collection with ease.
- **User Authentication**: Secure login and signup functionality with JWT authentication.

## Technologies

- **MongoDB**: Database for storing user and book data.
- **Express.js**: Back-end framework for server logic.
- **React.js**: Front-end library for building interactive UIs.
- **Node.js**: JavaScript runtime for the server-side application.
- **GraphQL & Apollo Client**: For querying and mutating data via GraphQL.
- **JWT**: Authentication using JSON Web Tokens.
- **Google Books API**: External API to search for books.

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/en/) installed
- MongoDB Atlas account or MongoDB installed locally

### Steps

1. Clone the repository:
 
   git clone https://github.com/ktcv31/GraphBooksExplore.git


2.Intall server dependencies:

    npm install

3. Instqll client dependencies:

    cd client
    npm install

4. Set up environment variables: Create a .env file in the root of the project and add your MongoDB connection string and JWT secret:


        MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/myDatabase?retryWrites=true&w=majority
JWT_SECRET=yourSecret


5. Start the server:

    npm run start 


   






-  Screenshots:
### Home Page
![Home Page](./Screenshot%202024-09-14%20at%206.16.44 AM.png)

### Search Results
![Search Results](./Screenshot%202024-09-14%20at%206.16.59 AM.png)

### Saved Books
![Saved Books](./Screenshot%202024-09-14%20at%206.17.56 AM.png)


Github URL : https://github.com/ktcv31/GraphBooksExploreLinks to an external site.

 

Deployed URL : https://graphbooksexplore.onrender.com/Links to an external site.

