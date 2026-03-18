# Fatima Asif — Communications Portfolio

A clean, static portfolio site built for GitHub Pages.

## File Structure

```
fatima-portfolio/
├── index.html        ← main page
├── css/
│   └── style.css     ← all styles
├── js/
│   └── main.js       ← scroll animations + nav
├── images/           ← add your graphics here
│   └── (empty — add project1.jpg, project2.jpg, etc.)
└── README.md
```

## How to Deploy on GitHub Pages

1. Create a new GitHub repo (e.g. `fatima-portfolio` or `your-username.github.io`)
2. Upload all files keeping the folder structure intact
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click Save — your site will be live at `https://your-username.github.io/fatima-portfolio`

## How to Add Your Graphics

For each project, find the `<!-- GRAPHIC -->` comment in `index.html` and replace the placeholder `<div>` with a real image:

```html
<!-- Remove this: -->
<div class="graphic-block graphic-feat">...</div>

<!-- Add this: -->
<img src="images/project1.jpg" alt="Description of your graphic" class="feat-img"/>
```

Save your image files into the `/images/` folder with names like:
- `images/project1.jpg` — Social media strategy
- `images/project2.jpg` — Social media storytelling
- `images/project3.jpg` — Impact stories
- `images/project4.jpg` — Brand systems
- `images/project5.jpg` — Live events
- `images/project6.jpg` — Internal comms system

Images can be JPG, PNG, or WebP. Keep file sizes under 500KB for fast load times.

## What to Personalize

In `index.html`, search for and update:
- `your@email.com` → your real email address
- `YOUR-HANDLE` → your LinkedIn username (e.g. `fatima-asif`)
- Commented-out links (`<!-- <a href="YOUR_LINK"...`) → add real URLs when ready
- Impressions data marked as needing update

## To Print as PDF

Open `index.html` in Chrome → File → Print → Save as PDF.
The print stylesheet ensures everything looks clean.
