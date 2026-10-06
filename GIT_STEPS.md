# Experiment 1 - Git and GitHub steps
Replace YOUR-USERNAME with your GitHub username.

## 1. Create the repository and push
```bash
git init
git add .
git commit -m "Initial commit: add index.html and README"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/Web-Design-Experiment-1.git
git push -u origin main
```
(Or create the repo on github.com / GitHub Desktop and publish it from there.)

## 2. Create a branch and change something
```bash
git checkout -b feature-update-contact
# edit index.html (e.g. change the email in the Contact section)
git add index.html
git commit -m "Update contact email"
git push -u origin feature-update-contact
```

## 3. Merge the branch
```bash
git checkout main
git merge feature-update-contact
git push origin main
```
(Or open a Pull Request on GitHub and click "Merge pull request".)

## 4. Enable GitHub Pages
Repository -> Settings -> Pages -> Source: "Deploy from a branch" -> Branch: main, folder: / (root) -> Save.
Live URL: https://YOUR-USERNAME.github.io/Web-Design-Experiment-1/

## 5. Take screenshots for the report
Live website, and the GitHub repo page showing the files, branches and the Pages deployment.
