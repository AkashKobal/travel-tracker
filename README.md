# Travel Tracker Web App
![Screenshot](https://github.com/AkashKobal/travel-tracker/blob/main/Screenshot%202024-07-10%20005244.png)

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Setup Instructions](#setup-instructions)
5. [Usage](#usage)
6. [Testing](#testing)
7. [Contributions](#contributions)
8. [License](#license)
9. [Contact Information](#contact-information)


## Description
This web application allows users to track the countries they have visited. Users can add country names, and the visited countries will be visualized on a map using Canvas. The app is built using HTML, CSS, JavaScript, EJS for templating, and PostgreSQL for database management.

## Features
- **Dynamic Templating**: Uses EJS to create reusable templates and dynamic content.
- **Interactive Frontend**: Implements JavaScript for enhanced user interactions and a responsive UI.
- **Database Integration**: Connects to a PostgreSQL database for storing and retrieving user data.
- **Canvas Visualization**: Utilizes Canvas for graphical representation of visited countries.
- **Express Framework**: Utilizes the Express.js framework for efficient routing and middleware management.


## Prerequisites
- Node.js
- PostgreSQL
- npm (Node Package Manager)

## Setup Instructions
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/AkashKobal/travel-tracker

2. **Install Dependencies**:
   ```sh
   npm install express body-parser pg ejs

3. **Configure Database**:

   [Download CSV file](https://github.com/AkashKobal/travel-tracker/blob/main/countries.csv) <br>
   Set up your PostgreSQL database and update the connection settings in the .env file.

5. **Run the Application**:
   ```sh
   node index.js

## Usage
+ Development:
  ```sh
  npm run dev

+ Production:
  ```sh
  npm start

## Testing
+ To run tests:
  ```sh
  npm test

## Contributions

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the [MIT License](https://github.com/AkashKobal/guess-the-capital/blob/main/LICENSE).

## Contact Information
For further questions or support, please contact [akashkobal02@gmail.com] or open an issue on this repository.
