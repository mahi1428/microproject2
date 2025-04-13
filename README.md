📦 Microproject 2

A Node.js backend application that connects to MongoDB and follows the MVC (Model-View-Controller) architecture.

🛠 Tech Stack

Node.js

Express.js

MongoDB

Mongoose

dotenv


📁 Project Structure
microproject2/
├── config/ → db.js (MongoDB connection setup)
├── controllers/ → controller.js (Business logic)
├── models/ → model.js (Mongoose schema)
├── .env (Environment variables)
├── package.json (Dependencies & scripts)

🚀 Getting Started
1. Clone the repository
git clone <your-repo-url>  
cd microproject2  

2. Install dependencies
npm install  

3. Create .env file
PORT=5000  
MONGO_URI=your_mongodb_connection_string  

4. Run the server
npm start  
# or for development  
npm run dev  

📌 Features
Connects to MongoDB with Mongoose

Clean MVC structure

Easy to scale & maintain