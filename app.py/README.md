## backend logic & routes

the application is powered by **flask**, handling user sessions, database persistence with **sqlite**, and file uploads.

---

### core functionalities

#### authentication & security
managed via **flask-login** with password hashing using **werkzeug**.

#### user onboarding
a multi-step process ensuring profile completion (`setup_profile`) before dashboard access.

#### job tracking (crud)
full **create, read, update, and delete** capabilities for job applications.

#### data export
generates dynamic **csv** reports of the user's application history.

#### statistics
real-time calculation of application metrics:
- applied  
- interview  
- offer  
- rejected  

---

### main endpoints

| route        | description                                             | access  |
|-------------|----------------------------------------------------------|---------|
| `/`         | landing page with platform overview                      | public  |
| `/register` | user account creation with email check                   | public  |
| `/login`    | secure session management                                | public  |
| `/dashboard`| main interface with job filters and statistics            | private |
| `/profile`  | profile management and document upload                   | private |
| `/create`   | manual entry of new job applications                     | private |
| `/export`   | download application data in `.csv` format               | private |
