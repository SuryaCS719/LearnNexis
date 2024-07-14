# LearnNexis - Ed-Tech Platform

**Description:**

LearnNexis is a comprehensive online learning platform designed to empower both instructors and students. Instructors can easily create and share their courses, while students can discover and enroll in a wide range of educational content.

**Key Features:**

- **Course Creation and Management:** Instructors can effortlessly create, manage, and update their courses, incorporating multimedia content like videos, quizzes, and interactive exercises.
- **Personalized Learning Experience:** Students can explore a diverse catalog of courses, enroll in their preferred subjects, track their progress, and interact with instructors and peers through discussion forums.
- **Secure User Authentication:** Robust authentication and authorization mechanisms using JWT and Bcrypt ensure the security of user data and protect against unauthorized access.
- **Seamless Payment Integration:** Integrated Razorpay, a popular payment gateway, to facilitate secure and convenient transactions for course purchases.
- **Enhanced User Experience:** Implemented OTP verification and password reset functionality to provide a smooth and user-friendly experience.
- **Scalable and Responsive Design:** Designed and deployed RESTful APIs for efficient data management and communication between front-end and back-end, ensuring a responsive and scalable platform.
- **Reliable Deployment:** Deployed on Vercel (front-end) and Render (back-end) to ensure high availability and performance, capable of supporting up to 1,000 concurrent users.

**Tech Stack:**

- **Database:** MongoDB
- **Back-end:** Node.js, Express.js
- **Front-end:** React.js, Redux
- **Authentication:** JWT, Bcrypt
- **Payment Gateway:** Razorpay
- **Deployment:** Vercel, Render

**Installation:**

1. Clone the repository: `git clone https://github.com/SuryaCS719/LearnNexis.git`
2. Install dependencies: `npm install` (for both front-end and back-end)
3. Set up environment variables: Create a `.env` file in both the root and client directories and add your MongoDB connection string, Razorpay API keys, and other necessary credentials.
4. Start the server: `npm start` (in the root directory)
5. Start the client: `npm start` (in the client directory)

**Usage:**

1. Visit the deployed website: [LearnNexis](https://learn-nexis-surya-gitam.vercel.app/)
2. Sign up or log in as an instructor or student.
3. Instructors can create and manage courses.
4. Students can browse courses, enroll, and start learning.
