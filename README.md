#Freelancing Platform for Punjab Gig Workers**

**Overview**
This project is a freelancing platform designed to support gig workers in Punjab by offering them a localized 
and intuitive way to connect with potential clients. It includes features such as profile management, 
a job posting system, real-time messaging, and a tier-based freelancer evaluation system, ensuring a fair and transparent work environment.

**Technology Stack**
Our platform utilizes a robust technology stack to ensure scalability, security, and efficiency:
**Frontend:**
Next.js (React Framework)
Utilized for fast, server-side rendering and efficient routing for an optimal user experience.

**Backend:**
Node.js with Express for handling API requests and server-side logic.
MongoDB (NoSQL Database) for storing user profiles, job listings, and transactions.

**Security:**
OAuth 2.0 for secure user authentication.
Helmet.js for securing HTTP headers.
Real-Time Communication:
Socket.io for enabling real-time, bi-directional communication between freelancers and clients.
Email Notifications:
SendGrid for email notifications about job postings, bids, and system alerts.

**Analytics:**
Google Analytics for tracking user interactions and gathering insights into user behavior.
Deployment:
Vercel for the seamless deployment of our Next.js application.
Key Features

**User Authentication:**
Secure login and registration using OAuth 2.0.

**Tier System:**
A non-bidding system that uses a tier-based evaluation. 
Freelancers are assessed based on performance metrics like reviews, 
successful project completions, and overall contributions to the platform. 
Their tier level impacts the types of jobs they can access.

**Real-Time Messaging:**
Communication between freelancers and clients is facilitated via Socket.io, ensuring fast and reliable messaging.

**Job Posting:**
Clients can create detailed job posts with a defined scope, budget, and timeline.

**Profile Management:**
Freelancers can build their profiles by listing their skills, experience, and past projects.

**Payment Gateway:**
Integration with Stripe for secure and seamless payments between clients and freelancers.
Installation

**Prerequisites:**
Make sure you have the following installed:
Node.js
MongoDB (For local or cloud database setup)

**GitSteps:**
Clone the repository:
git clone https://github.com/your-team-repo/freelancing-platform.git
cd freelancing-platform

Install dependencies:
npm install
Environment Variables: Create a .env.local file and add the following environment variables:

MONGO_URI=your_mongodb_connection_string
SENDGRID_API_KEY=your_sendgrid_key
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_GOOGLE_ANALYTICS=your_google_analytics_id

Running the Application: 
To start the development server, use:
npm run dev

Build for Production:
npm run build
npm start

**Folder Structure**
freelancing-platform/
├── components/        # React components for UI (header, footer, etc.) <br>
├── pages/             # Next.js pages (index.js, jobs.js, profile.js, etc.)
├── models/            # Mongoose models (User.js, Job.js, etc.)
├── api/               # API routes and backend logic
├── public/            # Static files like images, icons
├── styles/            # Tailwind CSS for styling
├── utils/             # Helper functions and middleware
├── .env.local         # Environment variables
└── README.md          # Project documentation

**Contributing**
We welcome contributions to the project. Here’s how you can contribute:

Fork the repository.
Create a new branch for your feature or bug fix:
git checkout -b feature/your-feature-name

Commit your changes:
git commit -m "Add feature"

Push to your branch:
git push origin feature/your-feature-name
Create a pull request to have your code reviewed and merged.

**License**
This project is licensed under the MIT License. See the LICENSE file for more information.
