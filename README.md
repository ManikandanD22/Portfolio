# Manikandan | Data Analyst Notebook Portfolio

An interactive "digital data notebook" portfolio. Visitors turn through 7 pages, each with its own page transition.

## Features
- 7 notebook pages: Intro, Journey, Skills, Projects, Thinking, Resume, Contact
- Side index, Previous/Next buttons, arrow-key and swipe navigation
- Different transition per page (fade, slide, flip, expand, turn)
- Project cards open as a zoom-in notebook page with a 7-step story (Problem to Action)
- Zoomable dashboard screenshot, skill hover examples, clickable "How I think" steps
- Responsive (bottom index on mobile), keyboard accessible, respects reduced motion

## Tech stack
HTML, CSS, JavaScript. No frameworks.

## Structure
```
index.html  css/style.css  js/script.js
assets/images/   assets/resume/
```

## Run locally
Open `index.html`, or run `python -m http.server` in this folder and visit http://localhost:8000.

## Customize
| What | Where |
|---|---|
| Email, LinkedIn, GitHub | Contact page in `index.html` (search `mailto:` and `linkedin`) and `gh:` values in `js/script.js` |
| Resume | Replace `assets/resume/Manikandan_Data_Analyst_Resume.pdf` |
| Project screenshots | Put images in `assets/images/`, then edit `IMG` and the project objects in `js/script.js` |
| Project text | Replace every `[ADD ...]` in the `PR` list in `js/script.js` |
| Profile image | Not included. Add an `<img>` in the Intro page of `index.html` |

## Deploy on GitHub Pages
1. Create a new repository on GitHub (for example `portfolio`).
2. Add these files to the repository folder.
3. `git init`, then `git add .`, then `git commit -m "Add portfolio"`.
4. `git branch -M main`, `git remote add origin <your-repo-url>`, `git push -u origin main`.
5. On GitHub open **Settings**, then **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/ (root)**, then Save.
8. Wait a minute. Your site appears at `https://<username>.github.io/<repo>/`.
