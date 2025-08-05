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

*(Add high-quality screenshots or a GIF here to showcase the different user interfaces, such as the home page, job listings, and dashboards for both employers and job seekers.)*

---

### **Author**

* **Harsha Vardhan** - [GitHub](https://github.com/05HarshaVardhan)

