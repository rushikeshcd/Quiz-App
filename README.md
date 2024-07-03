
# Quiz App

## Overview
The Quiz App is an interactive web application designed to create, manage, and take quizzes. Built using modern web technologies, this application provides an engaging platform for users to test their knowledge across various topics.

## Features
- **User Registration and Authentication:**
  - Secure user registration and login system.
  - Role-based access for administrators and regular users.

- **Quiz Creation and Management:**
  - Administrators can create, update, and delete quizzes.
  - Options to add multiple-choice questions with configurable answers.

- **Taking Quizzes:**
  - Users can browse available quizzes and attempt them.
  - Timer functionality for each quiz to add a competitive edge.
  - Immediate feedback on quiz completion with scores and correct answers.

- **User Dashboard:**
  - View and manage user profiles.
  - Track quiz history and performance analytics.

## Technology Stack
- **Frontend:** React, Material-UI, HTML5, CSS3, JavaScript
- **Backend:** ASP.NET MVC, C#
- **Database:** SQL Server

## Installation and Setup
### Backend Setup
1. Clone the repository from GitHub:
   ```bash
   git clone https://github.com/rushikeshcd/Quiz-App
   ```
2. Open the project in Visual Studio.
3. Restore the NuGet packages.
4. Update the database connection string in `Web.config`.
5. Run the application to set up the backend server.

### Frontend Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```
2. Install the necessary npm packages:
   ```bash
   npm install
   ```
3. Start the React development server:
   ```bash
   npm start
   ```
4. Navigate to `http://localhost:3000` to view the application in your browser.

## Usage
1. **Register/Login:**
   - Register as a new user or log in with existing credentials.
   
2. **For Administrators:**
   - Access the admin dashboard to create and manage quizzes.
   - View user statistics and quiz performance.

3. **For Users:**
   - Browse available quizzes and select one to attempt.
   - Complete the quiz within the given time and submit your answers.
   - View your score and correct answers upon completion.

## Future Enhancements
- Integration of a question bank for randomized quiz generation.
- Enhanced security features like two-factor authentication.
- Mobile-responsive design for improved usability on smartphones and tablets.
- Multi-language support to cater to a global audience.

