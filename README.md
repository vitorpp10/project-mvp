# Career Management Platform – MVP

<img width="240" height="25" alt="image" src="https://github.com/user-attachments/assets/325f60d1-b85d-49cc-98f9-809cece96d5c" />


This repository contains the **Minimum Viable Product (MVP)** for a career and job application management platform. The project focuses on a high-quality **User Experience (UX)** and a modern, clean interface, integrating a **Python Flask backend** with a **responsive Tailwind CSS frontend**.

---

## Project Overview

The primary objective of this MVP was to build a robust **authentication flow** with **custom client-side validation**, moving away from standard browser behaviors to provide a more integrated and professional user experience.

---

## Key Technical Features

### Custom Form Validation
Implementation of a JavaScript-driven validation system that replaces default HTML5 *"fill this field"* bubbles. It provides real-time feedback with:

- Inline error messages for required fields  
- Dynamic visual states (success/error borders)  
- Validation icons (SVG) injected via CSS classes  

### Modern UI / UX
Developed with a **dark-theme-first** approach using **Tailwind CSS**. The interface is fully responsive and adapts seamlessly to both mobile and desktop resolutions.

### Flask Routing
A structured backend responsible for page navigation and form submissions, implemented using **Python Flask**.

### Theme Configuration
Custom **Tailwind CSS theme extension** defining a specific color palette (**Slate-900 / Slate-800**) and typography (**Outfit** and **Inter** fonts).

---

## Project Structure

```
project-mvp/
├── app.py              # Application entry point and Flask routes
├── requirements.txt    # Project dependencies
├── README.md           # Technical documentation
└── templates/          # Jinja2 HTML templates
    ├── home.html       # Landing page
    ├── login.html      # Authentication page with custom JS validation
    └── register.html   # Account creation page with custom JS validation
```

## Technologies Used

### Backend
- Python 3.x
- Flask

### Frontend
- HTML5
- JavaScript (Vanilla)
- Tailwind CSS

### Assets
- FontAwesome (Icons)
- Google Fonts (Outfit & Inter)

---

## Installation and Setup

To run this project locally, ensure you have Python installed on your system.

### 1. Clone the repository
```
git clone https://github.com/vitorpp10/project-mvp.git
cd project-mvp
```

### 2. Create and activate a virtual environment (optional but recommended)

```python -m venv venv```


- Windows
  
```venv\Scripts\activate```

- macOS / Linux

```source venv/bin/activate```

### 3. Install dependencies

```pip install flask```

### 4. Execute the application

```python app.py```

### 5. Access the application

```http://127.0.0.1:5000```
