# Git-learning
What Are Git and GitHub?
Git: A distributed version control system that tracks changes in files and coordinates work among multiple people. It allows you to manage the history of your source code and collaborate on projects.
GitHub: A web-based platform that hosts Git repositories, allowing you to store your code online, collaborate with others, and use features like pull requests and issues.
Getting Started
Install Git:

Download Git and install it for your operating system (Windows, macOS, or Linux).
Create a GitHub Account:

Sign up at GitHub if you don't already have an account.
Set Up Git Locally:

Configure your Git with your name and email (these will be used for commits):
bash
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Basic Git Workflow
Create a New Repository

Locally:
bash
Copy code
git init my_project
cd my_project
On GitHub:
Click the "+" button in the top-right corner and select "New repository."
Name your repository and click "Create repository."
Connect Local Repository to GitHub

Add the remote URL (replace <username> and <repo> with your GitHub username and repository name):
bash
Copy code
git remote add origin https://github.com/<username>/<repo>.git
Basic Commands

Check the Status:
bash
Copy code
git status
Add Files to Staging Area:
bash
Copy code
git add filename.txt  # Add a specific file
git add .             # Add all files
Commit Changes:
bash
Copy code
git commit -m "Describe your changes here"
Push Changes to GitHub:
bash
Copy code
git push origin main
If pushing for the first time, you might need to set the upstream branch:
bash
Copy code
git push -u origin main
Cloning a Repository

To clone an existing repository from GitHub:
bash
Copy code
git clone https://github.com/<username>/<repo>.git
Branching and Merging

Create a New Branch:
bash
Copy code
git checkout -b new-feature
Switch Between Branches:
bash
Copy code
git checkout main
Merge Changes from Another Branch:
bash
Copy code
git checkout main
git merge new-feature
Handling Pull Requests (PRs)

On GitHub, create a pull request to merge changes from one branch into another (often used for code reviews).
Click "New pull request" in your repository.
Other Useful Commands
Pull Updates from Remote Repository:
bash
Copy code
git pull origin main
View Commit History:
bash
Copy code
git log
Undo Last Commit (without removing changes):
bash
Copy code
git reset --soft HEAD~1
Remove Changes from Staging Area:
bash
Copy code
git reset filename.txt

thanks
