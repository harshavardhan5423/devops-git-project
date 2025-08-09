 Build a Version-Controlled DevOps Project with Git

## Objective
Manage a DevOps project using Git best practices.

## Tools
- Git
- GitHub

## Deliverables
- Project repo with proper commits, branching, tags, and documentation.

---

## Steps Executed

### 1️⃣ Initialize Repo & Push to GitHub
''' bash 
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/harshavardhan5423/devops-git-project.git
git push -u origin main
2️⃣ Create Development Branches
git checkout -b dev
git push origin dev

git checkout -b feature-ci-cd
git push origin feature-ci-cd
3️⃣ Commit Changes & Merge
Made changes in feature-ci-cd branch.
Committed with proper messages:
git add .
git commit -m "Added CI/CD pipeline config"
Merged into dev and then main (via pull request or local merge).
4️⃣ Add .gitignore
Created .gitignore to exclude:
node_modules/
.env
*.log
5️⃣ Create Tags
git tag v1.0.0
git push origin v1.0.0
6️⃣ Documentation
Created README.md for overview.
Created TASKS.md for detailed execution.
✅ Status
Completed — All deliverables are met 

---

If you add these two files, your repo will be **100% complete and polished**.  
I can also give you the **exact Git commands** to add & push them to GitHub right now.  

Do you want me to give you those push commands?
