Authentication and Secrets App
This project is a Node.js web application that allows users to register, log in, and submit secrets. It features local and Google authentication using Passport.js and stores user data securely with PostgreSQL.

Features
Local Authentication with email and password
Google OAuth2 Authentication
Session Management with express-session
Data Storage with PostgreSQL
Password Encryption with bcrypt
Secrets Submission for authenticated users
Technologies Used
Node.js and Express
Passport.js (Local and Google OAuth2 strategies)
PostgreSQL (pg library)
bcrypt for password hashing
dotenv for environment variables
Setup
Clone the repository:

bash
Copy code
git clone <repository-url>
cd <repository-directory>
Install dependencies:

bash
Copy code
npm install
Set up environment variables in a .env file:

plaintext
Copy code
SESSION_SECRET=<your_session_secret>
PG_USER=<your_db_user>
PG_HOST=<your_db_host>
PG_DATABASE=<your_db_name>
PG_PASSWORD=<your_db_password>
PG_PORT=<your_db_port>
GOOGLE_CLIENT_ID=<your_google_client_id>
GOOGLE_CLIENT_SECRET=<your_google_client_secret>
Run the application:

bash
Copy code
npm start
Access the app at http://localhost:3000.

Folder Structure
public/: Static files
views/: EJS templates
Note
Ensure PostgreSQL is running and configured properly with the necessary tables.