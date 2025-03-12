# Scalable E-Learning Platform 🚀  

## Overview  
This project is a **Scalable E-Learning Platform** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)** and hosted on **AWS Cloud**. The platform enables students and instructors to interact in a seamless online learning environment. It provides features such as **course creation, student enrollment, progress tracking, and real-time doubt resolution**.  

## Features 🏆  
- 📚 **Course Creation** – Instructors can add and manage courses with video lectures and study materials.  
- 👩‍🎓 **Student Enrollment** – Students can browse and enroll in courses.  
- 📊 **Progress Tracking** – Users can track their learning progress and completed courses.  
- 💬 **Doubt Resolution** – Chat functionality for students to ask questions to instructors.  
- 🔐 **Authentication & Authorization** – Secure login and signup using JWT.  
- 🌐 **Cloud Storage** – Course videos and materials are stored on AWS S3 for scalability.  
- 🚀 **Deployment on AWS** – Hosted on AWS EC2, with backend services using AWS Lambda.  

## Tech Stack 💻  
- **Frontend**: React.js, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Atlas)  
- **Cloud Services**: AWS (S3, EC2, Lambda, CloudFront)  
- **Authentication**: JWT (JSON Web Token)  

## Installation & Setup ⚙️  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/scalable-e-learning-platform.git
   cd scalable-e-learning-platform
   ```

2. **Backend Setup**  
   ```bash
   cd backend
   npm install
   npm start
   ```

3. **Frontend Setup**  
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. **Environment Variables**  
   Create a `.env` file in the backend directory and add:  
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   AWS_ACCESS_KEY=your_aws_access_key
   AWS_SECRET_KEY=your_aws_secret_key
   ```
## Copied idea

## Deployment on AWS 🚀  
- Frontend hosted using **AWS Amplify / S3 + CloudFront**  
- Backend deployed on **AWS EC2 / Lambda**  
- Database hosted on **MongoDB Atlas**  

## Screenshots 📸  
(Add relevant screenshots here)  

## Future Enhancements 🔥  
- AI-based personalized course recommendations  
- Live video lectures integration  
- Gamification (badges, leaderboards)  

