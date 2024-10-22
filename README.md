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
   git clone https://github.com/JackFadlovich/mern-book-search.git
