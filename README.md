# google_books
Command Line Application to access the Google Books API and create a Reading List.

To run the app:

1. fork or clone the repository.
2. from the command line, cd into the directory and enter touch config.js then add the following code to this file: module.exports = { GOOGLE_BOOKS_API_KEY: '' }, you should then insert your Google Books API key as a string (within the empty single quotes).
3. once the config.js file has been added, run npm install books to install dependencies and sudo npm link to run the application from the command line, type books and follow the prompts.
