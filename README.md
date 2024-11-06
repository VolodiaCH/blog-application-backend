# Blog Application Backend

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)


## Prerequisites

Before setting up the project, ensure that you have the following installed:

- **Node.js** (Recommended version: 16.x or higher)  
  You can download Node.js from [here](https://nodejs.org/).

- **Git**  
  To clone the repository, ensure you have Git installed. Download it from [here](https://git-scm.com/).

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/VolodiaCH/blog-application-backend.git
2. Navigate to the project directory:
   ```bash
   cd blog-application-backend
3. Install project dependencies:
   ```bash
   npm install
4. Create local varialbes in .env:
   ```bash
   MONGODB_URI=mongodb://localhost:27017/blog

This will install all the necessary dependencies as specified in package.json.

## Running the Application
To run the application in development mode:

Start the development server:
   ```bash
   npm run start
   ```
This will start the app on http://localhost:3000 by default.
