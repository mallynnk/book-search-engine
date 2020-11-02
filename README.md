# Book Search Engine

## Description
A fully functioning Google Books API search engine built with a RESTful API. Refactored to be a GraphQL API built with Apollo Server.

## Table of Contents
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Deployed Site](#deployed-site)
  - [Screenshot](#screenshot)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Testing](#testing)
  - [Contribution](#contribution)

# Deployed Site

# Screenshot

# Description
- User Story
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

When the user loads the book search engine, they are presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button. When the user clicks on the 'Search for Books' menu option, they are presented with an input field to search for books and a submit button. When the user is not logged in and enters a search term in the input field and clicks the submit button, they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site. When the user clicks on the Login/Signup menu option, a modal appears on the screen with a toggle between the option to log in or sign up. When the toggle is set to Signup, the user is presented with three inputs for a username, an email address, and a password, and a signup button. When the toggle is set to Login, then the user is presented with two inputs for an email address and a password and login button. When the user enters a valid email address and creates a password and clicks on the signup button, their user account is created and they are logged in to the site. When the user enters their account's email address and password and clicks on the login button, the modal closes and they are logged into the site. When the user is logged in to the site, the menu options change to 'Search for Books,' an option to see the user's saved books, and a 'Logout' option. When the user is logged in and enters a search term in the input field and clicks the submit button, they are presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to their account. When the users clicks on the 'Save' button on a book that book’s information is saved to their account. When the user clicks on the option to see their saved books, they are presented with all of the books they have saved to their account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from their account. When the user clicks on the 'Remove' button on a book, that book is deleted from their saved books list. When the user clicks on the 'Logout' button, they are logged out of the site and presented with a menu with the options 'Search for Books' and 'Login/Signup' and an input field to search for books and a submit button.  

## Installation

- In the server directory run the following command to install the required modules `npm init` and
`npm i bcrypt express moment mongoose nodemon apollo-server-express jsonwebtoken`

- In the client directory run the following command to install the required modules `npm init` and
` npm i apollo-boost graphql graphql-tag @apollo/react-hooks react-router-dom jwt-decode `

- In the root directory run the following command to install the required modules ` npm init ` and ` npm i if-env -D concurrently `

## Usage
Sign up to create an account. Search for books & they will be saved to your account.


## Contribution
- Mallory Korpics(github.com/mallynnk)