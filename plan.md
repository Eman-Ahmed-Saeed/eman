Professional Bilingual Portfolio Implementation Plan
This document outlines the implementation plan for creating a professional, bilingual (English and Arabic) portfolio website for Eman A. Saeed based on the provided CV.

User Review Required
IMPORTANT

Please review the proposed design and structure below. Let me know if you approve this approach or if you'd like any changes before I begin building the website.

Proposed Technologies & Aesthetics
Core Technologies: HTML5, Vanilla CSS3, Vanilla JavaScript.
Bilingual Support: JavaScript-based language toggling (English LTR and Arabic RTL). The content will switch instantly without reloading the page.
Design Aesthetics:
Premium & Modern: Sleek dark mode by default (with an option to toggle light mode), vibrant gradients, and glassmorphism effects.
Typography: Google Fonts 'Inter' for English and 'Cairo' (or 'Tajawal') for Arabic to ensure readability and a modern look.
Interactivity: Smooth micro-animations on hover, scroll-based animations (fade-ins), and a responsive design that looks stunning on mobile and desktop.
Website Structure
The single-page portfolio will include the following sections:

Navigation Bar: Language switcher (EN/AR), Theme toggle (Light/Dark), and links to sections.
Hero Section: Eman's name, titles (Human Resources Assistant | Public Relations Specialist), a professional greeting, and contact links (LinkedIn, Email, Phone).
About / Professional Summary: A brief, engaging summary of Eman's experience and skills.
Experience: An elegant timeline or card-based layout showcasing Eman's roles at Modaway Company, Meras Medical, Derma Medical, and Saudi British Hospital.
Education & Courses: Cards displaying the Digital Media degree and various professional courses.
Skills & Languages: Visual representation of skills (e.g., tags or progress bars) and language proficiency.
Footer: Final call to action and copyright info.
Proposed Changes
Portfolio Foundation
[NEW]
index.html
The main structure of the single-page application containing data-i18n attributes for seamless language switching.

[NEW]
style.css
The comprehensive styling system including CSS variables for theme colors, typography, layout (Grid/Flexbox), and animations. It will include RTL specific styles for the Arabic layout.

[NEW]
script.js
The logic for toggling the language, managing the dark/light mode state, and triggering scroll animations. It will contain the translation dictionary for English and Arabic text.

Verification Plan
Manual Verification
I will serve the website locally.
We will verify that the layout looks professional and matches the aesthetic requirements.
We will toggle the language to ensure all text translates correctly and the layout switches seamlessly between LTR and RTL.
We will test the responsiveness of the site on different viewport sizes.
