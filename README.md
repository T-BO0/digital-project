# React Node.js Project

## Overview

This project is a full-stack application with a React front-end and Node.js back-end.

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/T-BO0/digital-project.git
2. **Navigate to the digital-project/final-api and install dependencies**
   ```bash
   # navigate to api project
   cd digital-project/final-api

   # install dedependencies
   npm install
   
3. **Open Docker Desktop and run docker compose file**
   
   open terminal and run:
   ```bash
   docker compose up

4. **Run back-end server**
   
   open new tab in the terminal in final-api directory and run:
   ```bash
   npm run start:dev

5. **Start front-end**
   open new tab interminal and navigate to front-end project and run front-end project
   ```bash
   # navigate to front-end project
   cd ../digit-shop

   # install dependencies
   npm install

   # run front-end project
   npm start
   
   # The app is running locally on the given port
   Local:   http://localhost:5173/
   ➜  Network: use --host to expose
   ➜  press h + enter to show help
