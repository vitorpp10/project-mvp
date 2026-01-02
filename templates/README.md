## Frontend & Templating

The frontend is built with **Jinja2 templates** and **Tailwind CSS**, focusing on a component-based approach for high performance and a clean, modern UI.

---

### Core Pages

#### Landing Page (`home.html`)
Modern entry point featuring a dark-themed UI with radial gradients and responsive navigation.

#### Auth Suite (`login.html` & `register.html`)
Custom-validated forms that provide instant visual feedback (success/error states) without page reloads.

#### User Dashboard (`dashboard.html`)
A centralized hub displaying application statistics (Interview, Applied, Offer) and a filtered list of job entries.

#### Profile Management (`profile.html` / `setup.html`)
Dynamic forms for managing personal data, professional links (GitHub/LinkedIn), and CV uploads.

#### Application Control (`create.html` / `edit.html`)
Intuitive interfaces for managing job application details and document attachments.

---

### Key UI Features

#### Responsive Architecture
Mobile-first design using Tailwind’s grid and flexbox utilities.

#### State Feedback
Smooth transitions and hover effects to improve user interaction.

#### Dynamic Components
Conditional rendering using Jinja2 logic for user-specific alerts and navigation states.
