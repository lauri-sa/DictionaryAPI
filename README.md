# Express.js Sample Project

This is a simple Express.js project that implements a Finnish-to-English dictionary API. The API allows users to search for Finnish words and their English translations, and also add new word pairs to the dictionary.

## Project Overview

The application provides the following functionality:
- **GET /:word**: Search for a Finnish word and return its English translation.
- **POST /:word1/:word2**: Add a new Finnish-to-English word pair using URL parameters.
- **POST /add**: Add a new Finnish-to-English word pair using JSON in the request body.

The project demonstrates basic Express.js server functionality, file handling, and input validation.

## Installation

**Clone the repository:** `git clone https://github.com/yourusername/DictionaryAPI.git`

**Navigate to the project directory:** `cd DictionaryAPI`

**install dependencies:** `npm install`

**Start the server:** `node index.js`

The server will start on `http://localhost:3000`. You can test the routes using a tool like Postman or directly from your browser.
