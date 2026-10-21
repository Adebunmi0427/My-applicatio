# HIGHERIMMACULATE Education Consult — Frontend

Responsive HTML, CSS and vanilla JavaScript frontend for the HIGHERIMMACULATE EDUCATION CONSULT learning portal.

## Files
- `index.html` — page structure and content
- `style.css` — responsive layout, components, animations and dark mode
- `script.js` — curriculum search/filter, CBT practice engine, timer, score review, local CBT history, WhatsApp enquiry forms

## Run locally
Open `index.html` in a modern browser. No build tools or dependencies are required.

## Publish on GitHub Pages
1. Create a new repository on GitHub.
2. Upload `index.html`, `style.css`, `script.js` and this README to the repository root.
3. Open **Settings → Pages**.
4. Under build/deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site.

You can also deploy this static frontend to Netlify by connecting the repository.

## Before production
- The CBT bank contains sample questions only. Add reviewed, curriculum-aligned questions and verify answer keys.
- CBT history is saved only in the current browser using `localStorage`; it is not a cloud account or database.
- Admission and contact forms open WhatsApp with a pre-filled message. They do not submit data to a server.
- Update contact details and service information if they change.
- This is an independent educational consultancy frontend, not an official WAEC, NECO, JAMB or government portal.
- A real student account system, staff/admin dashboard, cloud history, secure file storage and analytics require a backend and database.
