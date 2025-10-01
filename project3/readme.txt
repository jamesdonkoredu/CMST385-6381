PROJECT 3 STARTER — Music Artist Website
Generated: 2025-09-27T16:20:29

FILES
- index.html (Home)
- music.html (Music/Discography)
- news.html (News)
- style.css (External stylesheet)
- images/ (Put your optimized images here; keep each ≤100 KB)

CHECKLIST (map to rubric)
[ ] Three HTML5 pages created (index, music, news) and linked via navigation.
[ ] External style.css referenced on ALL pages.
[ ] Home page: artist name + image + background info (+ image credit caption).
[ ] Music page: ≥3 albums, each with cover, album name, track list, and publish date; cite sources.
[ ] News page: REAL latest news with dates + links to reputable sources; summarized in your words.
[ ] CSS includes: H1/H2/paragraph styles; at least one #id and .class; body bg + readable text color + Verdana/Arial/sans-serif stack; centered nav; header/footer styles; wrapper/container; float example (.float-img) with padding + cleared.
[ ] One hyperlinked image on the site (index hero image is set up as a link by default).
[ ] Images optimized (≤100 KB each).
[ ] HTML & CSS validate with W3C; include validation info/links in Project Reflection.

VALIDATION
1) Upload to ALOFT. Then validate:
   - HTML: http://validator.w3.org (paste your page URL)
   - CSS:  http://jigsaw.w3.org/css-validator/ (paste style.css URL)
2) If no errors, copy validator result URLs or embed code into your Reflection (per assignment).

DEPLOY (GitHub → ALOFT quick flow)
- Locally place these files in: www/project3/
- Git initialize (if needed):
    git init
    git add .
    git commit -m "Project 3: initial site"
    git branch -M main
    git remote add origin https://github.com/<you>/<repo>.git
    git push -u origin main
- Upload to ALOFT (via GitHub Actions you configured, or via FTP/SFTP if provided).
  Final public URL should resemble:
    https://<your-aloft-site>.azurewebsites.net/project3/index.html

REFLECTION TEMPLATE (copy into LEO submission)
a) URL: https://<your-aloft-site>.azurewebsites.net/project3/index.html
b) Issues/Challenges:
   - Choosing an artist and verifying REAL news
   - Optimizing images to ≤100 KB while keeping quality
   - Passing W3C validation without errors
   Resolutions: sourced images from official sites/press kits, batch-compressed images with Squoosh, fixed semantic tags/alt text until validators passed.
c) Software used: VS Code, Git/GitHub, image optimizer (Squoosh/TinyPNG), W3C validators; optional: Figma for layout.
d) Image sources: List URLs and credit lines for each image used (placed under each figure).
e) Validation info: Paste the validator result links and/or embed codes for HTML/CSS.

Good luck!
