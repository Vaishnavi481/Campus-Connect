# Campus-Connect

Campus-Connect is a web-based platform designed to bridge the gap between students and professors in academia. The system centralizes TA, research, and student worker opportunities, enabling professors to post available positions and students to easily browse and apply for them. The platform also offers detailed profiles for both user types and robust search functionality to foster meaningful academic connections.
git
## Features

### For Professors
- **Profile & Dashboard:**  
  - Create and manage a profile using email/password and Google Sign-In.
  - Dashboard with multiple tabs:
    - **Profile:** Basic information, description, and resume/CV upload.
    - **Research & Interests:** Display research areas, publications, and academic interests.
    - **Courses Offered:** List current and past courses taught.
    - **Discussion:** View profiles of students interested in your research.
- **Student Directory:**  
  - Access a directory of all students with search and filtering options (by course, research interests, etc.).
- **Course Management:**  
  - Create and manage course details including:
    - Course name and description
    - Instructor and enrolled students
    - Semester offered, timings, and prerequisites
    - Technologies used and skills learned
    - Student count

### For Students
- **Profile & Dashboard:**  
  - Create and manage a profile using email/password and Google Sign-In.
  - Dashboard with multiple tabs:
    - **Profile:** Basic personal details, description, and resume/CV.
    - **Research & Interests:** Showcase your academic interests and research areas.
    - **Courses Enrolled In:** View and manage your current and past course enrollments.
    - **Posts Interested In:** Track job postings, research opportunities, or TA positions you’ve applied for or bookmarked.
- **Professor Directory:**  
  - Browse a directory of professors with search options by department or research interests.

### Global Features
- **Authentication:**  
  - Secure sign-up and login using Firebase Auth.
- **Search & Filtering:**  
  - Global search across both professor and student directories.
- **Responsive Design:**  
  - Mobile-friendly UI using React.js and Material UI.
- **CI/CD Pipeline:**  
  - Automated build, test, and deployment process via GitHub Actions to Firebase Hosting.

## Tech Stack

- **Frontend:** React.js, MaterialUI
- **Backend:** Node.js, Express
- **Database:** Firebase Firestore
- **Authentication:** Firebase Auth
- **CI/CD:** GitHub Actions
- **Hosting:** Firebase Hosting

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Firebase CLI (for deployment)

### Installation

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd campus-connect
