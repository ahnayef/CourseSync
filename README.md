# CourseSync

CourseSync is an Android app designed to streamline university life for students and teachers, creating a centralized hub for academic information and communication.


---

## Features

- **General Notice Board**: Managed by the CR, exclusive for each semester.
- **General Discussion Page**: Thread-based discussions for batch members.
- **Dynamic Schedule Screen**: Customized schedules for teachers and students.
- **Course Pages**:
  - **Course Details**
  - **Notice Board**: Managed by teachers.
  - **Course Discussion Page**: Thread-based discussions for enrolled students.
  - **Student List**: Managed by teachers and CR.
- **Special Roles**:
  - **Head of Department (HOD)**: Manages students, courses, and schedules.
  - **Super Admin**: Manages HODs and overall system settings.

---

## Motivation

CourseSync was born out of the challenges faced by students juggling multiple platforms for university communication. The app aims to:
- Centralize educational resources and communication.
- Reduce distractions caused by non-academic interactions on platforms like WhatsApp.
- Simplify access to schedules, notices, and course discussions.

---

## Technologies Used

- **Frontend**: React Native
- **Backend**: Express.js
- **Database**: MySQL

---

## Installation

### Frontend

1. **Clone the Frontend Repository**:
   ```bash
   git clone https://github.com/ahnayef/CourseSync-frontend.git
   cd CourseSync-frontend
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Setup Environment Variables**:
   - Copy `env.example` to `.env` and configure it as needed.

4. **Run the Frontend**:
   ```bash
   npm start
   ```

---

### Backend

1. **Clone the Backend Repository**:
   ```bash
   git clone https://github.com/ahnayef/CourseSync-backend.git
   cd CourseSync-backend
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Setup Environment Variables**:
   - Copy `env.example` to `.env` and configure it with your MySQL credentials.

4. **Start MySQL Server**:
   - Ensure your MySQL server is running.
   - Create a database named `coursesync`.

5. **Reset the Database**:
   ```bash
   npm run reset
   ```

6. **Run the Backend**:
   ```bash
   npm start
   ```

---

## How to Use

1. **Login/Register**:
   - Teachers, students, HODs, and Super Admins can log in using their credentials.
2. **Explore Features**:
   - Access notices, schedules, course discussions, and more based on your role.
3. **Admin Roles**:
   - HODs can manage students, courses, and schedules.
   - Super Admins can oversee the entire system.

---

## Resources

- **[Presentation Slide](https://docs.google.com/presentation/d/1AzJrTQhHst8kZbIWvwccjE4M3x05hW7ZXn2NBkQDr6Q/edit?usp=sharing)**

- **[Project Demo Video](Demo/Video/CourseSync%20-%20Demo.mp4)**

-  Source Code:
 - - [Frontend](https://github.com/ahnayef/CourseSync-frontend.git)
 - - [Backend](https://github.com/ahnayef/CourseSync-backend.git) 


---


## License

This project is licensed under the [MIT License](LICENSE).
