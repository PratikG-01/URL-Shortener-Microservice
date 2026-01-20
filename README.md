# URL Shortener Microservice

## Overview
This project is a simple microservice built with Node.js and Express 
that allows users to shorten URLs. It accepts a valid URL via POST 
and returns a shortened version.

Users can then visit the shortened URL to be redirected to the original link.

---

## Features

- Accepts valid URLs and returns a shortened version
- Stores and maps short URLs to original URLs
- Redirects users from short URLs to the original addresses
- Validates input to ensure it's a proper URL

---

## Prerequisites
- Node.js and npm installed

---

## Installation
- Clone the repository
- Navigate into the project directory
- Run npm install to install dependencies
- Start the server using npm start or node index.js

---

## Project Structure
- index.js – Main application file

    •    package.json – Dependencies and scripts
