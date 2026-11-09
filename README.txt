ANAMUL HASAN — VIDEO EDITOR & MOTION DESIGNER PORTFOLIO
Updated version: theme customization, four portfolio categories, and your contact details.

FILES
- index.html: complete responsive website. CSS and JavaScript are included in this one file.
- README.txt: setup and editing instructions.

NEW FEATURES
1. Theme settings button in the top navigation.
2. Six preset accent colors and a custom HEX color picker.
3. Save theme in this browser using Local Storage; reset to default.
4. Light/dark mode toggle.
5. Four video categories with working category filters: Short Reels, Promotional Ads, Talking Head & Long-form, Travel & Cinematic.
6. Project preview modal for YouTube/Vimeo embeds.
7. Responsive layout for mobile, tablet and desktop.

CONTACT DETAILS ALREADY ADDED
- Email: anamulhasan12@gmail.com
- WhatsApp: +8801581493802 (opens a WhatsApp chat)
- LinkedIn: https://www.linkedin.com/in/anamulhasan228
- Facebook: https://www.facebook.com/profile.php?id=61588774130566
- YouTube: not added yet (no link supplied)
- Behance: not added yet (no link supplied)

SAMPLE PROJECTS
The four project cards are sample placeholders, not your actual portfolio videos. Replace project titles/descriptions and add your own links before publishing.

HOW TO ADD A VIDEO
1. Open index.html.
2. Find the relevant project button, for example:
   <button class="watch-btn" data-title="Social Media Reels" data-video="">...
3. Paste a YouTube embed URL inside data-video, e.g.:
   data-video="https://www.youtube.com/embed/VIDEO_ID"
   For Vimeo, use its player embed URL, e.g.:
   data-video="https://player.vimeo.com/video/VIDEO_ID"
4. Save and upload the updated index.html to GitHub.

HOW TO ADD MORE PROJECTS
Copy one complete <article class="project" ...> card inside the #projectGrid container.
Set data-category to one of: reels, ads, talking, travel. Update the title, description, category tag and data-video URL.

GITHUB PAGES — FREE HOSTING
1. Open your GitHub repository.
2. Upload/replace index.html in the repository root.
3. Commit the changes.
4. Go to Settings > Pages.
5. Select Deploy from a branch, branch main, folder /(root), then Save.
6. Wait for GitHub Pages to publish.

NOTES
- This is a static website and works with GitHub Pages. No paid hosting or backend is required.
- Theme choice is saved only in each visitor's own browser.
- Editing or adding projects requires changing index.html and uploading it to GitHub.
- A login-based admin dashboard for uploading videos directly is not included.
- Use YouTube/Vimeo embeds rather than uploading large video files to the GitHub repository.
