## frontend & templating

the frontend is built with **jinja2 templates** and **tailwind css**, focusing on a component-based approach for high performance and a clean, modern ui.

---

### core pages

#### landing page (`home.html`)
modern entry point featuring a dark-themed ui with radial gradients and responsive navigation.

#### auth suite (`login.html` & `register.html`)
custom-validated forms that provide instant visual feedback (success/error states) without page reloads.

#### user dashboard (`dashboard.html`)
a centralized hub displaying application statistics (interview, applied, offer) and a filtered list of job entries.

#### profile management (`profile.html` / `setup.html`)
dynamic forms for managing personal data, professional links (github/linkedin), and cv uploads.

#### application control (`create.html` / `edit.html`)
intuitive interfaces for managing job application details and document attachments.

---

### key ui features

#### responsive architecture
mobile-first design using tailwind’s grid and flexbox utilities.

#### state feedback
smooth transitions and hover effects to improve user interaction.

#### dynamic components
conditional rendering using jinja2 logic for user-specific alerts and navigation states.
