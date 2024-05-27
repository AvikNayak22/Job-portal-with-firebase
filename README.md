# Joboard

Joboard is a React-based web application designed to help users find job openings that best suit their skills and preferences. This project uses Firebase for data storage and retrieval.

## Features

- Browse and search for job listings
- Filter job listings by role, type, location, and experience level
- View detailed job information
- Apply for jobs directly from the listing

## Technologies Used

- React: Frontend library for building the user interface
- Firebase: Backend-as-a-Service for database and hosting
- Day.js: Library for date manipulation
- Tailwind CSS: Utility-first CSS framework for styling

## Getting Started

### Prerequisites

- Node.js and npm installed
- Firebase project set up with Firestore database
  
### Installation

1. Clone the repository:
   
   ```
   git clone https://github.com/AvikNayak22/Job-portal-with-firebase.git
   ```
2. Install dependencies:
   
   ```
   npm install
   ```
3. Set up Firebase configuration:
   - Create a `.env` file in the root directory and add your Firebase configuration details:
     
     ```
     VITE_API_KEY=your_api_key
     VITE_AUTH_DOMAIN=your_auth_domain
     VITE_PROJECT_ID=your_project_id
     VITE_STORAGE_BUCKET=your_storage_bucket
     VITE_MESSAGING_SENDER_ID=your_messaging_sender_id
     VITE_APP_ID=your_app_id
     ```
4. Run the application:
   
   ```
   npm run dev
   ```

## Firebase Setup
Ensure your Firebase project has a Firestore database with a jobs collection. Each job document should have the following fields:

- **title:** Job title (string)
- **company:** Company name (string)
- **type:** Job type (string, e.g., "Full Time")
- **location:** Job location (string, e.g., "Remote")
- **experience:** Experience level required (string, e.g., "Mid Level")
- **skills:** List of required skills (array of strings)
- **postedOn:** Date the job was posted (timestamp)
- **job_link:** URL to the job application page (string)

## Contributors
  - Avik Nayak (@AvikNayak22)
