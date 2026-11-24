# Personal Portfolio Website — Analytical Assignment Report

**Prepared by:** MD. Hasib Hossain  
**Programme:** B.Sc. in Computer Science & Engineering  
**Institution:** Daffodil International University

## 1. Introduction
This is an original six-page personal portfolio website presenting my academic background, technical skills, projects, competitive programming achievements, current research experience, and contact information. The visual identity uses a navy-and-ivory palette with cobalt and warm-gold accents and a responsive layout.

## 2. Objectives
- Build an original multi-page portfolio.
- Present my education, programming skills, projects, achievements, and current research work.
- Apply HTML, CSS, JavaScript, jQuery, AJAX, and JSON.
- Demonstrate asynchronous project-data retrieval.
- Prepare the website for public hosting.

## 3. Technologies Used
- **HTML5:** page structure and content.
- **CSS3:** navy/ivory design, responsive layouts, and visual styling.
- **JavaScript:** interactive behaviour, image fallback, and form validation.
- **jQuery:** navigation and DOM/event handling.
- **AJAX:** `$.ajax()` retrieves project records from `data/projects.json`.
- **JSON:** stores project details separately from page markup.

## 4. Website Structure and Features
- **Home:** profile introduction, programming highlights, research summary, and optional profile photo.
- **About:** education, profile, languages, and current research experience.
- **Skills:** C, C++, Java fundamentals, DSA, OOP, development tools, and MS Office tools.
- **Projects:** academic projects and ongoing research loaded dynamically using AJAX.
- **Achievements:** CodeChef 2-Star, peak rating 1438, 350+ solved problems, 28th place in Take-Off Programming Contest, 4th place in Unlock the Algorithm Preliminary, and 15th place in its Final.
- **Contact:** email, phone, GitHub, location, and client-side form validation.

## 5. Current Research Experience
I am currently working on a research paper titled: “Explainable Machine Learning for Predicting Self-Reported Sleep Duration Using Timing-Specific Smartphone Behaviours and Academic-Lifestyle Factors Among University Students in Bangladesh.” This work is described as ongoing.

## 6. Implementation Analysis
The six pages share a stylesheet and JavaScript file. CSS media queries adapt the layout for smaller screens. jQuery handles navigation and form interactions. On the Projects page, `$.ajax()` sends an asynchronous GET request for `data/projects.json`; JavaScript creates project cards from the returned data, or displays an error if the request fails. The Home page can display `images/hasib-profile.jpg`; otherwise, the initials “MH” are shown.

## 7. Testing and Analysis
Run the website using VS Code Live Server. Check all six pages and navigation links, test desktop and mobile layouts, verify that project cards load from JSON, add a profile photo, and test empty or invalid contact-form input. Add actual test outcomes and screenshots after completing these checks.

## 8. Limitations
The contact form validates input but does not send or store messages. Project data is stored in a JSON file, with no database or server-side application. The site uses externally hosted jQuery and Google Fonts. The research paper is ongoing.

## 9. Conclusion
The website demonstrates an original, responsive, multi-page portfolio using HTML, CSS, JavaScript, jQuery, AJAX, and JSON. After browser testing and deployment through a static host such as GitHub Pages, it can be shared using a public URL.

*Before submission, add screenshots of the final website and record the actual testing results.*


## Theme switching
The website offers two coordinated themes. Light mode is based on the selected pastel palette: blush pink (#F6E2E9), warm cream (#FEFAF3), pale sage (#B8CFB3), and muted sage green (#84A282). Dark mode uses a deep forest-green background with soft sage and blush highlights for comfortable contrast. A theme toggle appears on every page. JavaScript stores the visitor's choice in browser local storage, so the preference remains active while navigating between pages.
