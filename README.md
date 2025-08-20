# KnowledgeVault – Secure Note & Task Manager  

KnowledgeVault is a secure, full-featured note and task management platform built with the **MERN stack**. It combines robust security, productivity tools, and AI-powered features to help you manage your notes, tasks, and ideas efficiently.  

---

##  Features  

-  **Secure Authentication**  
  User registration and login with JWT, password hashing, and session management.  

-  **Note & Task Management**  
  Create, edit, delete, and organize notes; support for checklists and task tracking.  

- **File Import & Export**  
  Import notes from TXT files, export notes as PDF or TXT for backup or sharing.  

-  **Clipboard Integration**  
  Copy notes directly to the clipboard with one click.  

-  **Advanced Search & Sorting**  
  Quickly find and organize notes using keyword search and sorting options.  

-  **AI-Powered Summarization**  
  Summarize note content using a Generative AI API for faster understanding.  

-  **Text-to-Speech**  
  Convert summarized notes to speech for accessibility and hands-free review.  

-  **Data Security**  
  Notes stored securely with encryption and user-level access control.  

---

##  Tech Stack  

- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT, bcrypt.js  
- **Other Tools:** Google Gemini API (summarization), Nodemailer (notifications), Multer (file handling)  

---

##  Installation  

1. Clone the repository  
   ```bash
   git clone https://github.com/vishnuboligili/KnowledgeVault.git
   cd knowledgevault
   
###  Backend Setup  

1. Navigate to the backend directory:  
   ```bash
   cd backend
2.Install the required dependencies:
  ```bash
  npm install
3.Create a .env file in the backend directory and add your environment variables:
  ```bash
  MONGO_URI=<your_mongo_db_connection_string>
  JWT_SECRET=<your_jwt_secret_key>
  PORT=5000
  DB_NAME=<your_database_name>
  CORS_ORIGIN=<cors_origin>
4.Start the backend server
  ```bash
  npm run dev

### Frontend Setup

1.Navigate to the frontend directory:
  ```bas
  cd frontend
2.Install the required dependencies:
  ```bash
  npm install
3.Create a .env file in the frontend directory and add your environment variables:
  ```bash
  VITE_APP_CONTACT_URL=<contact form url>
  VITE_APP_API_KEY=http://localhost:5000/api
4.Start the frontend development server:
  ```bash
  npm run dev

###  Running the Application
1.Ensure both the frontend and backend servers are running.

2.Open your browser and navigate to http://localhost:5173.
