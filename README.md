# MD. Hasib Hossain — Personal Portfolio

An original multi-page personal portfolio website for a university assignment.

## Pages
- `index.html` — Home and profile highlights
- `about.html` — Profile, education, languages, and current research experience
- `skills.html` — Programming languages, DSA, tools, and productivity software
- `projects.html` — Projects and ongoing research loaded with jQuery AJAX
- `achievements.html` — Competitive programming achievements
- `contact.html` — Contact details and front-end form validation

## Design and theme
- Light mode uses blush pink (#F6E2E9), warm cream (#FEFAF3), sage green (#B8CFB3), and muted green (#84A282).
- Dark mode uses a deep forest-green base with soft sage and blush highlights.
- Every page includes a Light/Dark theme toggle.
- The selected theme is saved in the browser and remains active while navigating between pages.
- Responsive navigation, cards, timelines, and form styles adapt to mobile screens.

## Technologies
- HTML5
- CSS3 (responsive layouts and blush, cream, and sage-green light theme with a deep forest-green dark mode)
- JavaScript
- jQuery
- AJAX (`$.ajax()` retrieves `data/projects.json`)
- JSON

## Add your profile photo
1. Choose a clear, professional photo of yourself.
2. Copy it into the project's `images` folder.
3. Rename the photo to exactly `hasib-profile.jpg`.
4. Keep the image path as `images/hasib-profile.jpg`.
5. Refresh the Home and About pages. The same photo will appear in both places inside portrait-shaped frames, with the image fitted to avoid circular cropping. If the photo is not present, the site shows the `MH` initials fallback.

If your photo is PNG instead, either convert it to JPG or change the `src` value in `index.html` to `images/hasib-profile.png` and use that exact filename.

## Run locally
1. Extract the project ZIP.
2. Open the `My-Portfolio-Hasib` folder in VS Code.
3. Install the **Live Server** extension if needed.
4. Right-click `index.html` and select **Open with Live Server**.
5. Visit Projects and confirm the project cards load from the JSON file.

Do not open HTML pages by double-clicking them; AJAX needs a local web server.

## Personal content included
- C, C++, Java fundamentals
- STL, recursion, graph algorithms, dynamic programming, greedy algorithms
- GitHub, VS Code, Code::Blocks, Sublime Text
- MS Word, PowerPoint, Excel
- Bangla (Native), English (Fluent), Hindi (Conversational)
- Current research paper on explainable machine learning for predicting self-reported sleep duration

## Before public deployment
- Review the phone number and decide whether you want it visible on a public website.
- Check every page and navigation link.
- Confirm AJAX loads all project records.
- Add your own profile photo.
- Add real public repository links if you have them.
- Capture screenshots for the analytical report.

The contact form performs browser-side validation only. It does not send or store messages; a real message-delivery form needs a backend or a form service.
