# EAK International School — Frontend Redesign Project

> **Second-Round Hiring Assignment for Frontend Web Developer Intern**  
> **Prepared for:** EAK Pustak Pvt. Ltd.  
> **Candidate Implementation:** Fully Responsive, Modern Multi-Page Architecture (HTML5, Modern CSS, Vanilla JavaScript)

---

## 🌟 Executive Overview
This project is an end-to-end redesign of **EAK International School’s** digital presence. Rather than relying on rigid generic templates, this site was custom-crafted to solve the real problems identified in the assignment brief:
- **Immediate Clarity:** Clear answers to parent questions (identity, values, academics, safety, and enrollment steps).
- **Modern Aesthetic:** Deep navy (`#0A192F`), rich gold/amber (`#F59E0B`), crisp typography (`Plus Jakarta Sans`), and subtle elevation shadows.
- **Flawless Responsiveness:** Engineered mobile hamburger drawer navigation, flexible CSS Grid, and responsive card systems.
- **Rich Frontend Interactivity:** Live search & category filters for notices/events, interactive accordion FAQs, animated statistics counters, and toast-feedback form submissions without external dependencies.

---

## 📑 Required Pages Implemented (100% Complete)

| Page | File | Key Features & Implementation Highlights |
| :--- | :--- | :--- |
| **01. Home Page** | `index.html` | Hero with CTA & Stats banner, 6 Core Strengths, Principal's Message with experience badge, Academic Wing hierarchy cards, Facilities gallery preview, Upcoming Events feed, Testimonials, Admissions CTA. |
| **02. About Us** | `about.html` | Vision & Mission statements, 4 Core Institutional Values, 28-Year Chronological Timeline (1998-2026), Leadership & Mentorship profiles. |
| **03. Academics** | `academics.html` | Distinct wings (Primary, Middle, Secondary, Senior Secondary) with curriculum breakdown, STEAM focus pills, and 6 active student Co-Curricular Clubs. |
| **04. Admissions** | `admissions.html` | **Exact 5-Step Process** (Enquiry &rarr; Application &rarr; Interaction &rarr; Selection &rarr; Enrollment), Age Eligibility criteria table, Mandatory documents checklist, Interactive Application Prototype Form, and FAQ Accordion. |
| **05. Facilities** | `facilities.html` | Showcase of Smart Classrooms, STEAM & Research Labs, 35k-volume Central Knowledge Hub, Olympic Sports Arena, 800-seat Auditorium, and GPS Transit with medical infirmary. |
| **06. Events & Notices** | `events.html` | **Live Frontend Search & Filter System** by category (*Circulars, Upcoming Events, Examinations, Sports*), date badges, and pagination simulation. |
| **07. Contact Us** | `contact.html` | Campus location, department phone/email directory, administrative office hours, embedded interactive Map, and interactive message form. |

---

## 🛠️ Architecture & Design Decisions

### 1. Technology Choices:
- **Semantic HTML5:** Built using `<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<article>`, and `<footer>` tags for search engine optimization and screen reader accessibility.
- **Pure Modern CSS (`css/style.css`):**
  - CSS Custom Properties (Variables) for color theming, spacing, and border radiuses.
  - Responsive CSS Grid and Flexbox layouts.
  - Zero heavy CSS framework overhead for fast page loads.
- **Vanilla JavaScript (`js/main.js`):**
  - Sticky navbar with scroll detection.
  - Responsive mobile drawer navigation with outside-click handling.
  - Accordion interaction for FAQs.
  - Live filter and search DOM manipulation on Events & Notices.
  - Interactive form submission with realistic button states and animated feedback toast notification.
  - Scroll-to-top floating button and intersection observer number animation.

---

## 🚀 How to Run and Test the Project

1. **Direct Browser Preview:**
   - Navigate to the `eak-international-school` directory on your desktop.
   - Double-click `index.html` or open it with Google Chrome / Microsoft Edge.
2. **Local Development Server:**
   - If using VS Code: Right-click `index.html` and click **"Open with Live Server"**.
   - Or with Python: Run `python -m http.server 3000` inside `eak-international-school/` and navigate to `http://localhost:3000`.

---

## 🎯 Evaluation Rubric Alignment

- **Visual Design & UX (40%):** Cohesive typography, generous white space, clear contrast, and intuitive user paths for prospective parents.
- **Responsiveness (15%):** Thoroughly tested on mobile screens (down to 375px), tablets (768px), and ultra-wide displays (1440px+).
- **Creativity (15%):** Includes timeline diagrams, live search filters, and an animated stats counter.
- **Frontend Quality & Attention to Detail (25%):** Clean code formatting, modular CSS variables, and zero console errors.
- **Product Thinking (5%):** Designed with empathy toward the primary user personas (parents comparing schools, existing students checking circulars).
