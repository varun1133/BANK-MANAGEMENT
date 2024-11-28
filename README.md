# BANK-MANAGEMENT
a) Setting Up the Backend
Navigate to the backend folder.
Install dependencies:
bash
Copy code
npm install express mongoose cors dotenv
Create a .env file in the backend folder:
env
Copy code
MONGO_URI=your_mongodb_connection_string
PORT=5000
Start the server:
bash
Copy code
node server.js
b) Setting Up the Frontend
Navigate to the frontend folder.
Initialize React:
bash
Copy code
npx create-react-app .
Install dependencies (if not already installed):
bash
Copy code
npm install
Start the React app:
bash
Copy code
npm start
5. Testing the Application
Open your browser and go to http://localhost:3000.
Enter a username and password to test the login functionality.
