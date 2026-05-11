# Computer Science Student Portfolio

A modern responsive portfolio website built with HTML, CSS and JavaScript. You can host it for free using GitHub Pages, Vercel or Netlify.

## Folder Structure

```text
cs-portfolio-project/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── profile.jpg
│   └── cv.pdf
└── README.md
```

## How to edit your information

Open `index.html` in VS Code and replace these placeholders:

### 1. Your name
Search for:

```html
Abdur Rahaman
```

Replace it with your real name.

### 2. Your photo
Put your photo inside the `assets` folder and rename it exactly:

```text
profile.jpg
```

If your image is PNG, either rename it to `profile.jpg` after converting, or change this line in `index.html`:

```html
<img src="assets/profile.jpg" alt="Profile photo" class="profile-img" />
```

to:

```html
<img src="assets/profile.png" alt="Profile photo" class="profile-img" />
```

### 3. Your CV
Put your CV PDF inside the `assets` folder and rename it exactly:

```text
cv.pdf
```

All Download CV buttons will work automatically.

### 4. GitHub link
Search for:

```text
https://github.com/Abdur-r1
```

Replace `yourusername` with your GitHub username.

Example:

```text
https://github.com/abdurrahaman
```

### 5. Codeforces link
Search for:

```text
https://codeforces.com/profile/abdurrahaman01
```

Replace `yourusername` with your Codeforces handle.

### 6. LeetCode / LinkedIn / Email
Search and replace:

```text
https://leetcode.com/u/rahaman1/
https://www.linkedin.com/in/md-abdur-rahaman-bb76b9263
youremail@example.com
+880 1XXXXXXXXX
```

### 7. Results / CGPA
Find the `Results / Education` section in `index.html` and edit:

```html
<span>GPA: 5.00 | 2020</span>
<span>CGPA: 3.72 | 2022 - Present</span>
```

### 8. Projects
Find the `Projects` section and replace project names, descriptions and links.

## Run locally

Just double-click `index.html`, or use VS Code Live Server extension.

## Upload to GitHub and make live with GitHub Pages

1. Create a GitHub account if you do not have one.
2. Create a new repository. Example name: `portfolio`.
3. Upload all files: `index.html`, `style.css`, `script.js`, `README.md`, and the `assets` folder.
4. Go to repository `Settings`.
5. Click `Pages` from the left menu.
6. Under `Build and deployment`, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
7. Click `Save`.
8. After a few minutes your live link will look like:

```text
https://Abdur-r1.github.io/portfolio/
```

## Deploy with Vercel

1. Go to Vercel and sign in with GitHub.
2. Click `Add New Project`.
3. Select your portfolio repository.
4. Click `Deploy`.
5. Vercel will give you a live link.

## Important notes

- Do not change the file name `index.html`.
- Keep `assets/profile.jpg` and `assets/cv.pdf` paths correct.
- If a link does not work, check whether the URL starts with `https://`.


## Updated Personal Information

- Name: Abdur Rahaman
- SSC: 2016
- HSC: 2020
- B.Sc. in CSE: 2025

To change these later, open `index.html` and edit the `Results / Education` section.
