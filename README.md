🧩 Step 1. Create a GitHub Repository

Go to https://github.com/new

Repository name → example: git_repo

Leave everything else as default
(✅ Keep “Initialize this repository with a README” unchecked)

Click Create repository

You’ll now see instructions like:

git remote add origin https://github.com/your-username/git_repo.git
git branch -M main
git push -u origin main


Keep this page open — you’ll use that URL.

🧩 Step 2. Create a Local Folder

Open Git Bash (or VS Code terminal) and run:

cd ~/Desktop
mkdir git_repo
cd git_repo

🧩 Step 3. Initialize Git in the Folder
git init


This makes your folder a Git repository.
You’ll see:
Initialized empty Git repository in .../git_repo/.git/

🧩 Step 4. Add Some Files

Create a sample file:

echo "# My first Git project" > README.md

🧩 Step 5. Configure Your Identity (only once)

Git needs your name and email:

git config --global user.name "Ashton A"
git config --global user.email "your_github_email@example.com"


(Use your real GitHub email)

🧩 Step 6. Stage and Commit
git add .
git commit -m "Initial commit"

🧩 Step 7. Link Your Local Repo to GitHub

Use the same URL shown on your GitHub page, for example:

git remote add origin https://github.com/2303006-ashton/git_repo.git


Then rename your branch to main (to match GitHub):

git branch -M main

🧩 Step 8. Push to GitHub

Now push everything to your GitHub repo:

git push -u origin main


You’ll be asked to log in to GitHub (once) — use your credentials or token.
