## Backend Logic & Routes

The application is powered by **Flask**, handling user sessions, database persistence with **SQLite**, and file uploads.

---

### Core Functionalities

#### Authentication & Security
Managed via **Flask-Login** with password hashing using **Werkzeug**.

#### User Onboarding
A multi-step process ensuring profile completion (`setup_profile`) before dashboard access.

#### Job Tracking (CRUD)
Full **Create, Read, Update, and Delete** capabilities for job applications.

#### Data Export
Generates dynamic **CSV** reports of the user's application history.

#### Statistics
Real-time calculation of application metrics:
- Applied  
- Interview  
- Offer  
- Rejected  

---

### Main Endpoints

| Route        | Description                                             | Access  |
|-------------|----------------------------------------------------------|---------|
| `/`         | Landing page with platform overview                      | Public  |
| `/register` | User account creation with email check                   | Public  |
| `/login`    | Secure session management                                | Public  |
| `/dashboard`| Main interface with job filters and statistics            | Private |
| `/profile`  | Profile management and document upload                   | Private |
| `/create`   | Manual entry of new job applications                     | Private |
| `/export`   | Download application data in `.csv` format               | Private |
