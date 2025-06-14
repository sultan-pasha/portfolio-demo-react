# 🌍 Portfolio Demo – React + Redux (AR/EN Multilingual)

This is a **demo version** of a real-world portfolio website originally built for SASKE Company.  
The site showcases frontend architecture, multilingual support, and clean UI design.

🟢 **Live Preview**: [SASKE Company Portfolio](https://saske.pages.dev)  
📌 **Note**: The original production code is proprietary. This is a public demo version.

---

## 🚀 Overview

This portfolio is a modern, responsive, single-page React app featuring bilingual (Arabic/English) content managed entirely via **Redux Toolkit**. It serves as a base for building highly customizable business portfolios and corporate showcases.

---

## 🌐 Multilingual Support

- Language switching is handled via **Redux global state**
- All static content is dynamically rendered based on selected language
- Right-to-left (RTL) layout for Arabic is fully supported

---

## 🛠️ Tech Stack

| Layer          | Technologies Used                                      |
|----------------|--------------------------------------------------------|
| **Framework**  | React.js (v18), JSX                                    |
| **Routing**    | React Router DOM (v6)                                  |
| **State Mgmt** | Redux Toolkit, React-Redux                             |
| **Languages**  | Arabic (RTL) + English (LTR) with Redux switching      |
| **Styling**    | Bootstrap 5, React-Bootstrap, CSS Modules              |
| **UI**         | jQuery + jQuery Flipster (project slider effect)       |
| **Linting**    | ESLint (Airbnb-style rules)                            |
| **Testing**    | Testing Library (Jest, DOM, User Event)                |
| **Deployment** | Cloudflare Pages (Build via CRA)                       |

---

## 📂 Project Structure

```bash
portfolio-demo/
├── public/
├── src/
│   ├── assets/         # Images and icons
│   ├── components/     # Navbar, Footer, Project Cards, etc.
│   ├── pages/          # Home, About, Contact, Services
│   ├── redux/          # Language slice, store config
│   ├── styles/         # Global SASS files
│   └── App.js
├── package.json
└── README.md
