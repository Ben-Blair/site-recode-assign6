# Push this project to GitHub

Git isn’t available in your current environment. Follow these steps to create a repo and push.

## 1. Install Git (if needed)

- Download: https://git-scm.com/download/win  
- Run the installer; keep defaults and choose **“Git from the command line and also from 3rd-party software”**.  
- Close and reopen PowerShell/terminal after installing.

## 2. Create a new repo on GitHub

1. Go to https://github.com/new  
2. **Repository name:** e.g. `site-recode-assign6` (or any name you like)  
3. Choose **Public**, leave “Add a README” **unchecked**  
4. Click **Create repository**

## 3. Push this folder from your PC

In **PowerShell** (or Git Bash), run:

```powershell
cd "c:\Users\ben0r\Desktop\website\site-recode-assign6"

git init
git add .
git commit -m "Initial commit: AHG accessibility recode assignment"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

Replace **YOUR_USERNAME** with your GitHub username and **YOUR_REPO_NAME** with the repo name you chose (e.g. `site-recode-assign6`).

If GitHub asks for login, use your GitHub username and a **Personal Access Token** as the password (Settings → Developer settings → Personal access tokens).

Your site will be at:  
`https://github.com/YOUR_USERNAME/YOUR_REPO_NAME`  
and (if you enable GitHub Pages) at:  
`https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`
