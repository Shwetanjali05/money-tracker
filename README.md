# Money Tracker App 

## Overview
The Money Tracker App is a simple and user-friendly web application that allows users to track their expenses and incomes. Users can add new transactions, view a list of all transactions, and see the total amount. The application uses Express.js for the backend, MongoDB for the database, and a modern frontend design with HTML, CSS, and JavaScript.

Features
Add transactions with details such as category, amount, info, and date.
View a list of all transactions.
Delete transactions.
Calculate and display the total amount of transactions.
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB
Getting Started
Prerequisites
Node.js
MongoDB
Installation
Clone the repository

sh
Copy code
git clone https://github.com/yourusername/money-tracker-app.git
cd money-tracker-app
Install dependencies

sh
Copy code
npm install
Run MongoDB (Make sure MongoDB is running on your system)

sh
Copy code
mongod
Start the server

sh
Copy code
node index.js
Open the application

Navigate to http://localhost:5000 in your web browser.
Project Structure
plaintext
Copy code
money-tracker-app/
├── public/
│   ├── background.jpg
│   ├── index.html
│   ├── script.js
│   └── style.css
├── node_modules/
├── index.js
├── package.json
└── README.md
public/: Contains all the frontend files including HTML, CSS, and JavaScript.
index.js: Main server file where the Express app is defined.
package.json: Contains metadata about the project and its dependencies.
README.md: The file you are reading now.
Usage
Adding a Transaction
Select the category (Expense or Income).
Enter the amount.
Provide any additional info.
Select the date of the transaction.
Click the "Add" button to save the transaction.
Viewing Transactions
The list of transactions will be displayed under the "Expenses and Incomes List" section.
Deleting a Transaction
Click the "Delete" button next to the transaction you wish to remove.
Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For any inquiries or feedback, please contact [your-email@example.com].
