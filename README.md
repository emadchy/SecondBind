# Book Inventory Management System

This is a simple web-based application for managing a book inventory system. It allows users to add new books, search for books, and export book data in CSV or JSON format. The application also includes a theme switcher (light and dark mode) for better user experience.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Database Setup](#database-setup)
5. [Running the Application](#running-the-application)
6. [Usage](#usage)
7. [Theme Switcher](#theme-switcher)
8. [Technologies Used](#technologies-used)
9. [License](#license)

## Project Overview

The Book Inventory Management System is designed to help manage a collection of books, enabling users to:
- Add new books with details like title, author, genre, publication date, and ISBN.
- Search for books based on title, author, and genre.
- Export the list of books as CSV or JSON files.
- Toggle between light and dark modes using a custom theme switcher.

## Features

- **Add New Books:** Users can add new books to the inventory by filling out a simple form.
- **Search Functionality:** Easily search for books based on title, author, and genre.
- **Export Data:** Export book data in both CSV and JSON formats.
- **Dark/Light Mode Switch:** Switch between light and dark themes using the lightbulb icon.

## Installation

### Prerequisites:
- Node.js (v14.x or higher)
- SQLite (comes with the project)
- A web browser (Chrome, Firefox, etc.)

### Clone the Repository:

bash
git clone https://github.com/emadchy/SecondBind.git
cd <repository-folder>
Install Dependencies:
bash
Copy code
npm install
Database Setup
Initialize the SQLite Database:
Run the following command to set up the database and create the required Inventory table:

bash
Copy code
node initializeDatabase.js
This script will create a file called books.db in your project directory and set up the table.

### Running the Application
Start the Server:
bash
Copy code
npm start
The server will be running at: http://localhost:3000

Access the Application:
Open your browser and go to http://localhost:3000.

### Usage
Add a New Book:
Navigate to the Add a New Book section, fill out the form with the required information, and click the "Add Book" button to submit.

Search Books:
Enter search criteria (Title, Author, Genre) in the Search Books form and click "Search" to filter the books in the inventory.

Export Book Inventory:
Navigate to the Export Book Inventory section and choose either CSV or JSON format to download the current book list.

### Theme Switcher
You can toggle between light and dark themes by clicking the lightbulb icon at the top right corner of the page. The lightbulb image changes the theme, switching the interface between Lime Green & Black for dark mode and Lime Green & White for light mode.

### Technologies Used
Frontend: HTML, CSS (with custom theming), JavaScript
Backend: Node.js, Express.js
Database: SQLite
External Libraries: Body-parser (for handling form submissions)


### License
This project is open source and available under the MIT License.

### Future Enhancements
Pagination for large inventories.
Book cover images for each entry.
More advanced filtering options (e.g., filter by date range or ISBN).
User authentication for managing inventory securely.