# Job Portal: Full-Stack Platform for Job Seekers & Employers

---

### **Live Demo:** [JobFind](https://jobfind-f6u1.onrender.com/)
### **GitHub Repository:** [05HarshaVardhan/JobFind](https://github.com/05HarshaVardhan/JobFind)

---

### **Project Overview**

JobFind is a modern, full-stack web application designed to streamline the job search and hiring process. Built with the **MERN (MongoDB, Express, React, Node.js)** stack, it provides a comprehensive and scalable platform for both job seekers and employers. The application features a robust and responsive user interface, efficient state management, and secure, role-based authentication to create a seamless and professional experience.

### **Key Features**

* **Role-Based User Experience:** Separate dashboards and functionalities for job seekers and employers, ensuring a tailored and secure user experience.
* **Secure Authentication:** Implemented **JWT (JSON Web Tokens)** for secure, token-based authentication and authorization.
* **Job Posting and Application:** Employers can post new job openings, while job seekers can browse, filter, and apply for positions.
* **Responsive UI/UX:** Developed a mobile-first, responsive design using **Tailwind CSS** to ensure a consistent and optimal experience across all devices.
* **Efficient State Management:** Leveraged **Redux** to manage global application state, resulting in a highly performant and maintainable codebase.

### **Technical Stack**

* **Frontend:**
    * **React:** A powerful JavaScript library for building dynamic user interfaces.
    * **Redux:** For predictable and centralized state management.
    * **Tailwind CSS:** A utility-first CSS framework for rapid and responsive styling.
* **Backend:**
    * **Node.js & Express.js:** Used to build a RESTful API, providing a scalable server-side environment.
    * **MongoDB:** A flexible NoSQL database for efficient data storage.
* **Authentication:**
    * **JWT:** For secure, stateless user authentication.

### **Installation and Setup**

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/05HarshaVardhan/JobFind.git](https://github.com/05HarshaVardhan/JobFind.git)
    cd JobFind
    ```

2.  **Install dependencies:**
    * Navigate to the `backend` directory and install dependencies:
        ```bash
        cd backend
        npm install
        ```
    * Navigate to the `frontend` directory and install dependencies:
        ```bash
        cd ../frontend
        npm install
        ```

3.  **Configure environment variables:**
    * Create a `.env` file in the **`backend`** directory.
    * Add your MongoDB connection string and a secret key for JWT:
        ```env
        MONGO_URI=<Your MongoDB Connection String>
        JWT_SECRET=<Your Secret Key>
        ```

4.  **Run the application:**
    * Start the backend server:
        ```bash
        cd backend
        npm run server
        ```
    * In a new terminal, start the frontend development server:
        ```bash
        cd frontend
        npm start
        ```

### **Screenshots**



---<img width="1755" height="669" alt="login" src="https://github.com/user-attachments/assets/6e29042a-8167-4627-b8f6-e7687461973b" />
### Key elements of the screen include:

* **Header:** A navigation bar at the top with the "JobPortal" logo, and links to "Home," "Jobs," "Browse," "Login," and "Signup."
* **Login Form:** A central, card-like container with a "Login" heading. It contains two input fields:
    * **Email:** A text field for the user's email address.
    * **Password:** A text field for the user's password.
* **User Role Selection:** Two radio buttons below the input fields allow the user to specify their role, "Student" or "Recruiter," before logging in.
* **Login Button:** A prominent, full-width button to submit the form.
* **Sign-up Link:** A small text link at the bottom of the form for users who do not yet have an account, directing them to the signup page.


<img width="1715" height="858" alt="signup" src="https://github.com/user-attachments/assets/8eaccb89-c915-47f9-a275-5ea50b8f07de" />



### Key elements of the screen include:

* **Header:** A consistent navigation bar at the top with the "JobPortal" logo and links to "Home," "Jobs," "Browse," "Login," and "Signup."
* **Signup Form:** A central, card-like container with a "Sign Up" heading. It includes several input fields for new users:
    * **Full Name:** A text field for the user's full name.
    * **Email:** A text field for the user's email address.
    * **Phone Number:** A text field for the user's phone number.
    * **Password:** A text field for the user to create a password.
* **User Role and Profile Picture:**
    * **User Role:** Radio buttons for selecting a user role as "Student" or "Recruiter."
    * **Profile Picture Upload:** An option to "Choose File" for uploading a profile picture, indicating the ability to personalize user profiles.
* **Signup Button:** A prominent, full-width button to submit the registration form.
* **Login Link:** A small text link at the bottom of the form that directs users who already have an account back to the login page.

<img width="1901" height="967" alt="home" src="https://github.com/user-attachments/assets/19c36e80-8431-4dc9-97ac-4dfcbac9e8ab" />


* **Hero Section:**
    * A tagline, "No. 1 Job Hunt Website," establishes the platform's purpose.
    * A large, prominent headline, "Search, Apply & Get Your Dream Jobs," clearly states the value proposition.
    * A sub-headline provides additional descriptive text.
    * A central search bar with a placeholder "Find your dream jobs" and a purple search button, inviting users to begin their job search immediately.
* **Job Categories/Suggestions:**
    * A horizontal carousel of popular job titles, such as "Frontend Developer" and "Backend Developer," allows users to quickly explore specific career paths.
* **Latest & Top Job Openings Section:**
    * A clear heading, "Latest & Top Job Openings," introduces the main content.
    * Three identical job listing cards are displayed, each featuring:
        * **Company Name:** "Microsoft"
        * **Location:** "India"
        * **Job Title:** "Frontend Developer" or "Backend Developer"
        * **Job Description Snippet:** A brief summary of the role's responsibilities, providing quick context for the user.

<img width="1896" height="971" alt="user-profile" src="https://github.com/user-attachments/assets/099455cd-3990-4028-ae91-54308e9f8f48" />

* **User Profile Card:** A central card-like container showcasing the user's information:
    * **Name and Title:** "Sriram Munaga" is prominently displayed, along with the professional title "Aspiring Software Developer."
    * **Edit Profile:** An edit icon is present, indicating that the user can modify their profile details.
    * **Contact Information:** The user's email (`sriram@gmail.com`) and phone number (`9182928077`) are listed.
    * **Skills:** A labeled section for skills, with a skill badge for "MERN stack Development," demonstrating the user's expertise.
    * **Resume:** A link to the user's uploaded resume, "RAKESH.pdf," allowing for easy access and potential downloads by recruiters.
* **Applied Jobs Section:** Below the profile card, a table-like section titled "Applied Jobs" lists the user's application history.
    * **Table Columns:** The table is organized into four columns: "Date," "Job Role," "Company," and "Status."
    * **Application Entries:** Three sample entries show the date of application, the job role (`Backend Developer` and `Frontend Developer`), the company (`Microsoft`), and the current application status, which is "PENDING" for all of them.


<img width="1919" height="970" alt="job-browse" src="https://github.com/user-attachments/assets/a3daacb6-094e-46e6-a7a2-09e02f15c01e" />

* **Filter Jobs Section:** A dedicated sidebar on the left provides filtering options to narrow down job searches:
    * **Location:** Radio buttons for filtering by city, including "Delhi NCR," "Bangalore," "Hyderabad," "Pune," and "Mumbai."
    * **Industry:** Radio buttons to filter by job role or industry, such as "Frontend Developer," "Backend Developer," and "FullStack Developer."
    * **Salary:** Radio buttons for filtering based on salary range, including "0-40k," "42-1lakh," and "1lakh to 5lakh."
* **Job Listings Section:** The main area on the right displays a list of job cards, with three visible in this screenshot:
    * **Job Cards:** Each card contains detailed information about a job opening, including:
        * **Company:** "Microsoft" and "Vidvadeep" are shown.
        * **Job Title:** "Frontend Developer" and "Backend Developer."
        * **Job Description:** A detailed description of the role's responsibilities.
        * **Job Metadata:** Information such as the number of positions available, job type ("Full-Time"), and salary is displayed.
        * **Action Buttons:** "Details" and "Save For Later" buttons allow users to learn more or bookmark the job.
* **UI Elements:**
    * A small bookmark icon is present on each job card, allowing for quick saving.
    * Each card has a timestamp, such as "Today" or "45 days ago," indicating when the job was posted.

<img width="1799" height="736" alt="company0setup" src="https://github.com/user-attachments/assets/97b7a03c-5bad-4fc4-bfc8-355c5dae82bd" />

* **Form Header:** A clear heading, "Company Setup," with a "Back" button, allowing the user to navigate away from the page.
* **Company Information Form:** The form is divided into several input fields to capture company details:
    * **Company Name:** A text field with the value "Microsoft" pre-filled.
    * **Description:** A text area for a detailed description of the company, with a snippet visible.
    * **Website:** A text field for the company's website URL, pre-filled with a sample link.
    * **Location:** A text field for the company's location, with "USA" pre-filled.
    * **Logo:** A file input field labeled "Logo" with a "Choose File" button, allowing the recruiter to upload their company's logo.
* **Call to Action:** A prominent "Update" button at the bottom of the form to save the changes.

<img width="1747" height="783" alt="job-setup" src="https://github.com/user-attachments/assets/efa146ce-63c5-4f75-8bb1-dbe2cdd261e2" />

* **Job Post Form:** A central, card-like container with a two-column layout for the job details:
    * **Title:** A text input field for the job title, with "Software Developer" as a sample value.
    * **Description:** A text area for a detailed job description, with a placeholder snippet.
    * **Requirements:** A text area for outlining the skills and qualifications required for the role.
    * **Salary:** An input field for the salary, with "8LPA" (8 Lakhs Per Annum) as a sample value.
    * **Location:** A text field for the job's location, with "Banglore" as a sample.
    * **Job Type:** A text field for the employment type, with "Full-Time" as a sample.
    * **Experience Level:** An input field for the required years of experience, with "1" as a sample.
    * **No of Position:** An input field for the number of available positions, with "15" as a sample.
* **Company Selection:** A dropdown menu below the form fields, allowing the recruiter to select which company the job belongs to, with "Microsoft" selected.
* **Call to Action:** A prominent "Post New Job" button to submit the form and publish the job opening.

### **Author**

* **Harsha Vardhan** - [GitHub](https://github.com/05HarshaVardhan)

