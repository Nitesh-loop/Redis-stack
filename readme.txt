# Redis on git:

https://github.com/Nitesh-loop/Redis-stack.git

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Nitesh-loop/Redis-stack.git
git push -u origin main

notepad .gitignore

# Ignore Notepad++ backup files
*.txt.bak

# Ignore all .bak files (optional)
*.bak

# Ignore temporary files
*.log
*.tmp




git add .gitignore

# Remove Already Tracked .txt.bak Files (If Any):
git rm --cached "*.txt.bak"
git commit -m "Removed .txt.bak files from repo"
git push origin main
