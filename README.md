# KanMind Frontend Project

![KanMind Logo](assets/icons/logo_icon.svg)

KanMind is a web-based application designed to provide a clean, structured dashboard experience with authenticated access, API-driven data handling, and a modern, lightweight frontend architecture.

This repository contains the **frontend** part of the KanMind project.

---

## ✨ Features

- Responsive dashboard UI
- Authentication-aware navigation (dynamic header & navigation)
- API-based data handling
- Clean separation of shared assets (CSS, JS, components)
- Privacy Policy & Imprint compliant with German regulations (TMG / GDPR)
- Lightweight, framework-free frontend (Vanilla JavaScript)

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
  - Modular CSS structure
  - Shared variables and assets
- **Vanilla JavaScript**
  - No external frameworks
  - Modular helper scripts
- **REST API integration**
  - Backend communication via `api.js`

---

## 📁 Project Structure

```text
KanMind_Frontend/
│
├── assets/ # Icons, images, static assets
├── shared/
│ ├── css/ # Global styles, variables, layout
│ ├── js/ # Shared JS utilities and API helpers
│
├── pages/
│ ├── dashboard/ # Main dashboard
│ ├── imprint/ # Legal Notice (Imprint)
│ └── privacy/ # Privacy Policy
│
└── index.html # Entry point
```

---

## 🔐 Authentication Handling

- Navigation and UI elements are dynamically adjusted based on authentication state.
- If no authenticated user is detected, protected navigation elements are automatically hidden.
- Authentication data is handled client-side and communicated securely with the backend API.

---

## 🔗 Backend Integration

The frontend communicates with a dedicated backend API for:

- Authentication
- Data retrieval
- Application logic

The backend is expected to be available via a configured API endpoint.

> **Note:** This repository does not contain backend logic.

---

## 📜 Legal Compliance

The project includes:

- **Imprint (Legal Notice)** compliant with §5 TMG / §18 MStV
- **Privacy Policy** compliant with GDPR (DSGVO)

These pages are accessible via the footer at all times.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/OgulcanErdag/kanmind_frontend.git
```

### 2. Open locally

You can run the frontend locally by simply opening index.html in your browser.

For API functionality, ensure the backend is running and API endpoints are correctly configured.

🌍 Deployment

The frontend can be deployed using any static hosting solution, such as:

Nginx

Apache

Cloud hosting platforms

VPS-based static hosting

Ensure correct API endpoint configuration for production use.

📌 Status

This project is actively maintained and serves as part of a larger full-stack system.

👤 Author

`Ogulcan Erdag`
Full-Stack Developer (Frontend-focused)
Germany

---
