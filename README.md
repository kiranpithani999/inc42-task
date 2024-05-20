Create a GitHub Repository
Create a new public repository on GitHub:

Name it something like project inc42-task
Initialize it with a README.md file.
Create directories for Go, Next.js, and WordPress:


Copy code
mkdir -p project/go-app project/nextjs-app project/wordpress-site


git init
git add README.md
git commit -m "first commit"
git branch -M main


Copy code
git branch -M main
git remote add origin https://github.com/kiranpithani999/inc42-task.git
git push -u origin main