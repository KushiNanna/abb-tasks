Repo Setup-  
Created a GitHub repository: `abb-tasks`.  
Initialized with a `main` branch.
Branching Strategy- 
Followed 'feature-based branching model' :  
-main: Stable production code  
-develop:Integration branch  
-feature/task-1: New feature development    
-hotfix/<hotfix-name>: Urgent fixes for production  

Workflow:  
Step 1: Clone Repository  

git clone https://github.com/KushiNanna/abb-tasks.git
 step-2: create feature branch
 git checkout -b feature-branch
step-3:Create a file,edit and commit
step-4: Push to remote and create PR from feature to develop.
step-5: Merge develop into main
