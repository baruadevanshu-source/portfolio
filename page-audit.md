# Portfolio page audit

Checked on 28 October 2026 against files in `Documents/some codeing files/devanshu-barua-portfolio`. Vishwas Saini’s existing folder at `Documents/some codeing files/portfolio` was left unchanged. A new folder was used so that site was not overwritten.

Desktop preview was opened once at `http://127.0.0.1:8765/`. That request loaded `index.html`, `style.css`, and `script.js`. Later local-server and mobile-menu checks were interrupted when the preview tab could not reconnect, so those remaining checks are not marked Verified.

| Requirement | Status | Notes |
| --- | --- | --- |
| Name accuracy | Verified | Brand, hero, about, footer, title, and copyright use Devanshu Barua. |
| Education accuracy | Verified | JECRC University, B.Tech CSE, AI & Data Science, Jaipur; Class 12 Green Field Secondary Public School; Class 10 KVM Gwalior. No years, grades, or marks were added. |
| Contact information | Verified | Email, LinkedIn, and GitHub are clearly marked placeholders. Phone is not shown. Location is Phulera, Rajasthan, India. No fake `mailto:` or profile links. |
| About section accuracy | Verified | Describes current B.Tech CSE study at JECRC University and technical interests. No employment, internships, or years of experience. |
| Skills accuracy | Pending | Skills match the supplied list (C, C++, Python, HTML, CSS, JavaScript, DSA, OOP, problem solving, AI, ML, data science, Git, GitHub, VS Code). No resume or project files were found to independently confirm each skill. No percentages are shown. |
| Project descriptions | Verified | MediAssist and Weather Forecasting are named from the supplied brief only. Implemented features are not claimed. An additional project card is a placeholder. |
| GitHub and live demo URLs | No | No real repository or live URLs were found. Cards show `PLACEHOLDER: Add GitHub URL` and `PLACEHOLDER: Add Live Demo URL`. |
| Achievement and certificate accuracy | Verified | Placeholder only: `PLACEHOLDER: Add verified achievements or certificates`. No invented awards. |
| LinkedIn URL verification | No | Displayed as `PLACEHOLDER: Add LinkedIn URL`. No fabricated profile link. |
| Responsive design | Pending | Desktop layout was reviewed in the in-editor browser. CSS includes tablet (960px) and mobile (1100px hamburger) rules. Tablet and mobile visual passes were not completed after the preview disconnected. |
| Mobile navigation | Pending | `script.js` toggles the menu, closes it after a section link, and handles Escape. The hamburger was not exercised in a live mobile viewport in this session. |
| Accessibility and keyboard navigation | Pending | Skip link, landmarks, section labels, `:focus-visible`, and `aria-expanded` are in the markup. A full keyboard-only pass was not completed. |
| HTML validation | Pending | Not submitted to https://validator.w3.org/nu/ because the site is local only. |
| CSS and JavaScript file links | Verified | `index.html` links `style.css` and `script.js`. The 8765 preview requested both files (CSS `200`, JS `304`). Footer year rendered as 2026. |
| Navigation section IDs | Verified | Home, About, Skills, Projects, Education, Achievements, and Contact match `id` values on the corresponding sections. |
| Missing assets | Verified | No local image or video files are referenced. Hero uses a CSS monogram, not a photo. |
| Remaining PLACEHOLDER values | Verified | Email, LinkedIn, GitHub, project stacks/features/links, additional project, and achievements remain clearly marked. |

## Additional notes

- No Devanshu resume, MediAssist source, weather project files, email, GitHub, or LinkedIn URL were found in the previous Vishwas portfolio folder or in Downloads search results used for this build.
- A contact form was not added (none existed in this new project).
- Google Fonts (DM Sans, Fraunces) load from Google; the rest of the site is plain HTML, CSS, and JavaScript.
- Git was not available on PATH in this environment, so the folder was created without `git init`.
