# July 2020 ReFactoring Goals
1. More cleaner and minimalistic UIs
2. Better State Management
3. More Functionality - in areas of job application, job searching on Google Maps, etc.

<hr>

# 1. Technology Overview
1. MongoDB
2. Express.js
3. React.js
4. Node.js
5. Google APIs

# 2. Architecture
### 1) Front-end (React.js - component tree)
<img src="/front-end-architecture.PNG" width="60%"/>


### 2) Back-end (Express.js + Node.js + MongoDB)
<img src="/back-end-architecture.PNG" width="60%"/>

# 3. To run the application
### You need to install depenencie & packages first, run "npm i" in frontend and backend folders
1. Go to /frontend/my-app and run "npm start"
2. Go to /backend and run "node server.js" or "nodemon server start"
3. Go to your browser and the app is running at http://localhost:3000/

### 1) User Credentials
1. To login as a student, use ID = student1 and PASSWORD = student1
2. To login as a recruiter, use ID = recruiter2 and PASSWORD = recruiter2

### 2) Features
#### A. Students
  - Create and update profile
  - Upload a pdf resume to a job
  - Write a review of a company
  - View jobs, sort jobs by deadline date, etc.
  - View applications
  - View jobs on Google Maps
#### B. Recruiters
  - Create and update profile
  - Post and delete a job
  - View applicants with their resumes
  - View jobs, sort jobs by deadline date, etc.
### 3) Functionalities
  - Form Validation
  - Responsive Design
  - Navigation State Update
  - Google Maps Search
  - Application Deadline & Document Validation
# 4. Demo
### 1) Student
<img src="/student-demo.gif" width="100%">

### 2) Recruiter
<img src="/recruiter-demo.gif" width="100%">
