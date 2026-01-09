# career management platform – mvp

<img width="240" height="25" alt="image" src="https://github.com/user-attachments/assets/325f60d1-b85d-49cc-98f9-809cece96d5c" />

this repository contains the **minimum viable product (mvp)** for a career and job application management platform. the project focuses on a high-quality **user experience (ux)** and a modern, clean interface, integrating a **python flask backend** with a **responsive tailwind css frontend**.

---

## project overview

the primary objective of this mvp was to build a robust **authentication flow** with **custom client-side validation**, moving away from standard browser behaviors to provide a more integrated and professional user experience.

---

## key technical features

### custom form validation
implementation of a javascript-driven validation system that replaces default html5 *"fill this field"* bubbles. it provides real-time feedback with:

- inline error messages for required fields  
- dynamic visual states (success/error borders)  
- validation icons (svg) injected via css classes  

### modern ui / ux
developed with a **dark-theme-first** approach using **tailwind css**. the interface is fully responsive and adapts seamlessly to both mobile and desktop resolutions.

### flask routing
a structured backend responsible for page navigation and form submissions, implemented using **python flask**.

### theme configuration
custom **tailwind css theme extension** defining a specific color palette (**slate-900 / slate-800**) and typography (**outfit** and **inter** fonts).

---

## project structure

project-mvp/
├── app.py # application entry point and flask routes
├── requirements.txt # project dependencies
├── readme.md # technical documentation
└── templates/ # jinja2 html templates
├── home.html # landing page
├── login.html # authentication page with custom js validation
└── register.html # account creation page with custom js validation

yaml
Copy code

## technologies used

### backend
- python 3.x
- flask

### frontend
- html5
- javascript (vanilla)
- tailwind css

### assets
- fontawesome (icons)
- google fonts (outfit & inter)

---

## installation and setup

to run this project locally, ensure you have python installed on your system.

### 1. clone the repository
git clone https://github.com/vitorpp10/project-mvp.git
cd project-mvp

r
Copy code

### 2. create and activate a virtual environment (optional but recommended)

```python -m venv venv```


- windows
  
```venv\scripts\activate```

- macos / linux

```source venv/bin/activate```

### 3. install dependencies

```pip install flask```

### 4. execute the application

```python app.py```

### 5. access the application

```http://127.0.0.1:5000```
