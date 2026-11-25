# U M Vinay — Developer Portfolio

A responsive personal portfolio built with React + Vite, using a dark navy and blue visual theme.

## Included
- Responsive home, about, skills, experience, projects, education, certifications and contact sections
- Profile photo and downloadable resume in `public/assets/`
- GitHub and LinkedIn links
- Four project cards with the repository URLs supplied by Vinay

## Requirements
- Node.js 18+ (Node.js 20+ recommended)
- npm

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Production build

```bash
npm run build
npm run preview
```

The production site is generated in the `dist/` folder.

## Deploy to Vercel
1. Create a GitHub repository and upload this project folder.
2. Import the repository in Vercel.
3. Framework preset: **Vite**.
4. Build command: `npm run build`.
5. Output directory: `dist`.
6. Deploy.

## Personalization notes
- Edit contact details and content in `src/main.jsx`.
- Edit colors, layout and responsive styles in `src/style.css`.
- Replace `public/assets/vinay-profile.png` or `public/assets/UM-Vinay-Resume.pdf` to update the photo or resume.
- The contact button uses a `mailto:` link. To receive form submissions through a backend service, connect a form provider or API.

## Content accuracy
The portfolio uses the internship dates, education, CGPA, skills and project descriptions supplied by Vinay and his resume. Heartiest Mind internship tasks are described only as Python, HTML, CSS and MySQL learning/practical activities; no specific company project has been assumed.
