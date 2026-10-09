Complete Step-by-Step Guide for Static Website Deployment & Updates
Phase 1: Initial Setup & Creating the Website
Create Project Folder & Files:
Open your terminal and create a new project folder, then navigate into it:

Bash
mkdir static-website
cd static-website
Create index.html:
Create and open an index.html file and add your website code:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Static Website</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>Welcome to my GitHub Pages website.</p>
</body>
</html>
Phase 2: Documenting in README.md
Create a README.md file to explain your project and document the steps/updates clearly for anyone visiting your repository:

Markdown
# Static Website Hosting with GitHub Pages

This project hosts a simple static HTML website using GitHub Pages.

## Steps Followed:
1. Created a basic `index.html` file.
2. Initialized Git repository and committed the files.
3. Pushed the code to GitHub.
4. Enabled GitHub Pages via repository settings.

## How to Update the Website:
1. Make changes to `index.html`.
2. Run `git add index.html`
3. Run `git commit -m "Update website content"`
4. Run `git push origin main`
Phase 3: Initial Git Setup & Push
Initialize Git:

Bash
git init
Add and Commit Files:

Bash
git add index.html README.md
git commit -m "Initial commit with index.html and README"
Connect to GitHub & Push:

Bash
git branch -M main
git remote add origin https://github.com/AfaqAhmad30/Your-Repo-Name.git
git push -u origin main
Phase 4: Enable GitHub Pages
Go to your repository on GitHub.

Click on the Settings tab at the top.

On the left sidebar, click on Pages.

Under Build and deployment, select the main branch and root folder (/), then click Save.

After a minute or two, your live website link will appear right there!

Phase 5: How to Update the Website Later (and Update README)
Whenever you want to change your website content or document new updates:

Update index.html: Modify your HTML file and save it.

Update README.md: Open README.md and add a small note under a changelog section about what you updated:

Markdown
## Changelog / Updates
- Updated the header text on [Current Date].
Push Changes to GitHub:
Run these commands in your terminal:

Bash
git add index.html README.md
git commit -m "Update website content and README documentation"
git push origin main
View Live Updates: Wait 1–2 minutes, open your live link, and use Ctrl + F5 (or an Incognito window) to view your fresh updates!
