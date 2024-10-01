# Anonymous Feedback System

## Project Title  
Anonymous Feedback System

## Project Description  
The Anonymous Feedback System is a web application designed to allow users to submit feedback anonymously. It provides a user-friendly interface for individuals to share their thoughts without revealing their identities. Admins can log in to view and analyze the received feedback, fostering an environment of open communication and continuous improvement.

## Inspiration Behind the Project  
The inspiration for this project came from the need to create a platform that encourages open communication while maintaining user anonymity. Anonymous feedback is vital for fostering a safe environment where individuals can voice their concerns or suggestions without fear of repercussions. This project aims to facilitate honest dialogue and promote a healthier workplace culture.

## Tech Stack  
- **Frontend:** React.js (for building the user interface)
- **Backend:** Appwrite (for handling authentication, databases, and functions)
- **Database Structure:**
  - **Feedback Collection:** Stores feedback entries including text and timestamps.
  - **Admins Collection:** Stores admin credentials for accessing feedback data.

## Implementation Plan  
### Project Setup (Days 1-2)
1. Set up the front-end using `create-react-app`.
2. Sign up for Appwrite Cloud and create a new project.
3. Create two collections in Appwrite: **Feedback** and **Admins**.
4. Set up user authentication for admins and implement a function to anonymize feedback.

### User Interface Development
- Develop a feedback form for users to submit feedback anonymously.
- Create a login form for admins to access feedback.

### Database Integration & Admin Panel (Days 3-4)
1. Implement the feedback submission process using Appwrite’s Databases API.
2. Ensure feedback is anonymized before saving.
3. Set up an admin panel where logged-in admins can view feedback submissions in a readable format.

### Polishing and Testing (Days 5-6)
1. Add form validation to prevent empty feedback submissions.
2. Implement error handling for failed submissions or login attempts.
3. Enhance UI/UX with basic styling for a clean layout.
4. Conduct thorough testing of both feedback submission and viewing processes, ensuring no personally identifiable information (PII) is saved.

### Final Adjustments & Submission (Day 7)
1. Deploy the front-end using services like Netlify or Vercel.
2. Ensure proper integration with Appwrite Cloud.
3. Push the code to GitHub and submit the project through the Built With Appwrite portal.

## Usage of Appwrite
- **Appwrite Databases:** Used to store user feedback securely.
- **Appwrite Authentication:** Managed admin access while maintaining user anonymity.
- **Appwrite Functions:** Employed to anonymize feedback submissions before storage.

## Project Repository  
[Anonymous Feedback System GitHub Repo](https://github.com/shuddhi-jain/anonymous-feedback)

## Demo Video  
[Watch the Demo](https://www.youtube.com/watch?v=demo-video-link)

## GitHub Handles of Team Members  
- @shuddhi-jain  


