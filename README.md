# Job Portal

**Created by:** Arun.webcode

## 🎉 Welcome to the Job Portal! 🎉

Happy coding! This project is a comprehensive learning experience designed to emulate a real-world job portal, complete with all the functionalities you’d expect from a professional platform. Whether you’re a job seeker or a recruiter, this portal has something for everyone!

## Live Demo

You can access the live hosted version of the Job Portal [here](https://jobportal-live.onrender.com).

## Tech Stack

### Frontend

- **React**: The primary frontend framework.
- **State Management**: 
  - **Redux**: Utilising `@reduxjs/toolkit`, `react-redux`, and `redux-persist` for state management.
- **Routing**: 
  - **React Router**: Handling routing within the application using `react-router-dom`.
- **Styling**: 
  - **Tailwind CSS**: Utilised for styling the application.
- **UI Components**: 
  - **Radix UI**: Providing reusable UI components with various `@radix-ui` packages.
- **Other Dependencies**:
  - **Axios**: For making HTTP requests.
  - **Framer Motion**: For animations.
  - **Lucide React**: For icon components.
  - **Next Themes**: For theme switching.
  - **Class Variance Authority**: For class variance analysis.
  - **Clsx**: For conditionally joining class names.
  - **Embla Carousel React**: For creating carousels.
  - **Sonner**: For generating static assets.
  - **Tailwind Merge**: For merging Tailwind classes.
  - **Tailwindcss Animate**: For Tailwind CSS animations.
- **Build Tool**:
  - **Vite**: As the build tool.
- **Linting**:
  - **ESLint**: For maintaining code quality.

### Backend

- **Express.js**: The primary backend framework.
- **Database**: 
  - **MongoDB**: Utilising `mongoose` for database management.
- **Authentication and Authorization**:
  - **JSON Web Tokens (JWT)**: For secure authentication.
  - **Bcrypt**: For password hashing.
- **Cloud Storage**:
  - **Cloudinary**: For storing images and media.
- **Middleware**:
  - **Cookie-Parser**: For cookie management.
  - **Cors**: For enabling Cross-Origin Resource Sharing.
- **Other Dependencies**:
  - **Datauri**: For converting data to URI strings.
  - **Dotenv**: For loading environment variables.
  - **Multer**: For handling file uploads.
  - **Nodemon**: For automatic server restarts during development.
  
### Environment Variables

Make sure to set up the following environment variables in your `.env` file:

MONGO_URI = ... 
PORT = 8000 
SECRET_KEY = ... 
CLOUD_NAME = ... 
API_KEY = ... 
API_SECRET = ..



These variables are required for MongoDB database connections and Cloudinary configurations.

## Functionality

The Job Portal supports two types of accounts:

1. **Student (Job Seekers)**:
   - Create an account with an ID and password.
   - Apply for jobs.
   - Update profile information, including uploading profile pictures and resumes.
   - View application status.
   - Filter jobs based on various criteria.

2. **Recruiter**:
   - Create an account to post job listings.
   - Create company accounts.
   - View and manage job applications from candidates, accessing their details such as CV, phone number, email, and name.

### Additional Features

- **Theme Switching**: Users can toggle between dark and light themes.
- **Protected Routes**: Ensures secure access to certain functionalities based on user authentication.

## Local Development

For a local version of the Job Portal, please visit the GitHub repository: [Job Portal MERN Stack](https://github.com/Arun-webcode/Job-Potal-MERN-Stack).

---

**Happy Coding!** Enjoy exploring and contributing to the Job Portal project. Let's build something amazing together! 🚀
