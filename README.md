# MERN: Book Search Engine

## Overview:

The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. It's already set up to allow users to save book searches to the back end.

- Set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.

- Modify the existing authentication middleware so that it works in the context of a GraphQL API.

- Create an Apollo Provider so that requests can communicate with an Apollo Server.


### General Functionality

```
GIVEN a book search engine

WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button

WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button

WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site

WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
# MERN Book Search Engine

## Table of Contents

- [Description](#description)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description

This project is a full-stack **Google Books API search engine** that allows users to search for books and save them to their own library. Originally built using the **MERN stack** with a RESTful API, it has been refactored to use **GraphQL** and **Apollo Server** for better performance and flexibility.

The application allows users to:
- Search for books using the Google Books API
- Save and manage their favorite books in a personal collection
- Sign up and log in with authentication

## Demo

You can view the deployed application here:  
[Live Demo](https://66e332b6c19b060f2778a9df--mernbookssearch.netlify.app/)

## Technologies Used

- **Frontend:**
  - React
  - Apollo Client (GraphQL)
  - HTML / CSS / JavaScript
  - Bootstrap (for styling)
  
- **Backend:**
  - Node.js
  - Express.js
  - Apollo Server (GraphQL)
  - MongoDB with Mongoose for data persistence

- **Authentication:**
  - JWT (JSON Web Tokens) for user authentication

- **Deployment:**
  - Frontend deployed on Netlify
  - Backend deployed on Heroku
  - MongoDB Atlas for cloud database storage

## Features

- **User Authentication**: Users can sign up and log in to save their favorite books.
- **Google Books API Integration**: Fetches book information, including title, author, and cover image, based on search queries.
- **Book Saving**: Users can save books to their personal collection and view them later.
- **GraphQL Refactor**: The original RESTful API was refactored to use GraphQL and Apollo Server for more efficient querying.

## Installation

To set up the project locally, follow these steps.

### Prerequisites

Ensure you have **Node.js** and **npm** installed on your machine. You'll also need a **MongoDB** instance (local or cloud, like MongoDB Atlas) and a **Google Books API key**.

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/mern-book-search.git
# MERN Book Search Engine

## Table of Contents

- [Description](#description)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description

This project is a full-stack **Google Books API search engine** that allows users to search for books and save them to their own library. Originally built using the **MERN stack** with a RESTful API, it has been refactored to use **GraphQL** and **Apollo Server** for better performance and flexibility.

The application allows users to:
- Search for books using the Google Books API
- Save and manage their favorite books in a personal collection
- Sign up and log in with authentication

## Demo

You can view the deployed application here:  
[Live Demo](https://66e332b6c19b060f2778a9df--mernbookssearch.netlify.app/)

## Technologies Used

- **Frontend:**
  - React
  - Apollo Client (GraphQL)
  - HTML / CSS / JavaScript
  - Bootstrap (for styling)
  
- **Backend:**
  - Node.js
  - Express.js
  - Apollo Server (GraphQL)
  - MongoDB with Mongoose for data persistence

- **Authentication:**
  - JWT (JSON Web Tokens) for user authentication

- **Deployment:**
  - Frontend deployed on Netlify
  - Backend deployed on Heroku
  - MongoDB Atlas for cloud database storage

## Features

- **User Authentication**: Users can sign up and log in to save their favorite books.
- **Google Books API Integration**: Fetches book information, including title, author, and cover image, based on search queries.
- **Book Saving**: Users can save books to their personal collection and view them later.
- **GraphQL Refactor**: The original RESTful API was refactored to use GraphQL and Apollo Server for more efficient querying.

## Installation

To set up the project locally, follow these steps.

### Prerequisites

Ensure you have **Node.js** and **npm** installed on your machine. You'll also need a **MongoDB** instance (local or cloud, like MongoDB Atlas) and a **Google Books API key**.

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/mern-book-search.git
# MERN Book Search Engine

## Table of Contents

- [Description](#description)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description

This project is a full-stack **Google Books API search engine** that allows users to search for books and save them to their own library. Originally built using the **MERN stack** with a RESTful API, it has been refactored to use **GraphQL** and **Apollo Server** for better performance and flexibility.

The application allows users to:
- Search for books using the Google Books API
- Save and manage their favorite books in a personal collection
- Sign up and log in with authentication

## Demo

You can view the deployed application here:  
[Live Demo](https://66e332b6c19b060f2778a9df--mernbookssearch.netlify.app/)

## Technologies Used

- **Frontend:**
  - React
  - Apollo Client (GraphQL)
  - HTML / CSS / JavaScript
  - Bootstrap (for styling)
  
- **Backend:**
  - Node.js
  - Express.js
  - Apollo Server (GraphQL)
  - MongoDB with Mongoose for data persistence

- **Authentication:**
  - JWT (JSON Web Tokens) for user authentication

- **Deployment:**
  - Frontend deployed on Netlify
  - Backend deployed on Heroku
  - MongoDB Atlas for cloud database storage

## Features

- **User Authentication**: Users can sign up and log in to save their favorite books.
- **Google Books API Integration**: Fetches book information, including title, author, and cover image, based on search queries.
- **Book Saving**: Users can save books to their personal collection and view them later.
- **GraphQL Refactor**: The original RESTful API was refactored to use GraphQL and Apollo Server for more efficient querying.

## Installation

To set up the project locally, follow these steps.

### Prerequisites

Ensure you have **Node.js** and **npm** installed on your machine. You'll also need a **MongoDB** instance (local or cloud, like MongoDB Atlas) and a **Google Books API key**.

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/mern-book-search.git
# MERN Book Search Engine

## Table of Contents

- [Description](#description)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description

This project is a full-stack **Google Books API search engine** that allows users to search for books and save them to their own library. Originally built using the **MERN stack** with a RESTful API, it has been refactored to use **GraphQL** and **Apollo Server** for better performance and flexibility.

The application allows users to:
- Search for books using the Google Books API
- Save and manage their favorite books in a personal collection
- Sign up and log in with authentication

## Demo

You can view the deployed application here:  
[Live Demo](https://mern-book-search-nqrw.onrender.com/)

## Technologies Used

- **Frontend:**
  - React
  - Apollo Client (GraphQL)
  - HTML / CSS / JavaScript
  - Bootstrap (for styling)
  
- **Backend:**
  - Node.js
  - Express.js
  - Apollo Server (GraphQL)
  - MongoDB with Mongoose for data persistence

- **Authentication:**
  - JWT (JSON Web Tokens) for user authentication

- **Deployment:**
  - Frontend deployed on Netlify
  - Backend deployed on Heroku
  - MongoDB Atlas for cloud database storage

## Features

- **User Authentication**: Users can sign up and log in to save their favorite books.
- **Google Books API Integration**: Fetches book information, including title, author, and cover image, based on search queries.
- **Book Saving**: Users can save books to their personal collection and view them later.
- **GraphQL Refactor**: The original RESTful API was refactored to use GraphQL and Apollo Server for more efficient querying.

## Installation

To set up the project locally, follow these steps.

### Prerequisites

Ensure you have **Node.js** and **npm** installed on your machine. You'll also need a **MongoDB** instance (local or cloud, like MongoDB Atlas) and a **Google Books API key**.

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/mern-book-search.git

WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button

WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button

WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site

WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site

WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout

WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account

WHEN I click on the Save button on a book
THEN that book’s information is saved to my account

WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account

WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list

WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button



```
### Installation

1.  Install Node.js version 20.x or newer
2.  Clone the repo
3.  `cd` into the `BookSearch-MERN` directory
4.  Build the project: Run `npm run render-build` to load all the project dependencies and build
5.  Install or have running an instance of mongo db (latest)
7.  Run `npm run start --omit=dev` to start the application
8.  Access the app http://localhost:3001


Follow the instructions above to run the program locally. Then go to http://localhost:3001 to use the app.

Link to deployed applicaation https://mern-book-search-nqrw.onrender.com/