# A02

# Guidance on connecting GitHub to WebStorm -

Course: IS117
Author: raa223
Repo URL:  https://github.com/Rxchel12/A02


# Overview of this tutorial

1. Install Required Software
2. How to create a **GitHub** account and repository
3. Clone Repository into WebStorm
4. Modify the README.md
5. Pushing changes to GitHub
6. Additional Git Operations
7. Glossary
8. References
------------------------------------------------------

# 1. Install Required Software -

1. Download Git here: https://git-scm.com/downloads
2. Download WebStorm here: https://www.jetbrains.com/webstorm/download/

------------------------------------------------------

# 2. How to create a GitHub account and repository -

1. Create a **GitHub** account following this link: https://github.com/signup
2. Pick a username and password.
3. Once the account is created click the + sign in the top right and  select new **repository**.
4. Call the new repository "A02", check the "Add README file" and click create repository.
5. You will now have the link to your repository which will look like this: "https://github.com/yourUCID/A02".
6. Save the link, we will use it in later steps.

------------------------------------------------------

# 3. Clone Repository into WebStorm -

1. Once everything is installed, open WebStorm.
2. Go to the top left and click New Project Version Control System (VCS). A VCS records changes to files over time.
3.Paste your repo link from step 2. (e.g., https://github.com/yourUCID/A02).
4. Save it to a folder on your computer, then click **Clone**. Now you have your project in WebStorm and GitHub.

------------------------------------------------------

# 4. Modify the README.md -

1. In WebStorm, open the A02 folder and click README.md.
2. Write your information in this file and save it.
3. The file is now changed, but **Git** hasn't saved it yet.
4. Go to the left toolbar and click **Commit**. Check the README file and write a message in the bottom, for example: *Task: Create Repository*.
5. Click **Commit**.

------------------------------------------------------

# 5. Pushing changes to GitHub -

1. After commiting, the changes are still only in your computer.
2. To send changes to GitHub, click in the top left toolbar in WebStorm, then Git, **Push**.
3. Confirm the **branch** (main) and click **push**.
4. Now open your GitHub **repository** (**remote**) and you will see the updated README.md.

------------------------------------------------------

# 6. Additional Git Operations -

1. Before starting new work, it’s a good idea to **Fetch** from the **Remote**. This checks if anything has changed online, without touching the files on your computer.
     - In WebStorm: VCS > Git > Fetch. This downloads information about new commits.    
2. If you want to bring those changes down and update your project, use **Pull**. This adds the new work from GitHub into your local files.
     - In WebStorm: VCS > Git > Pull, choose the branch to update, then click **pull**.   
3. When working on a team, it’s common to create a new **Branch**. This lets you experiment or build a feature separately, and later you can **Merge** it back into the main project.
     - In WebStorm: Click the current branch, select + New Branch, give it a descriptive name (e.g.,feature-login-page), checkout the branch, and click Create.
4. Sometimes Git can’t merge automatically, this is called a **Merge Conflict**. It happens when two people edit the same part of a file. You’ll need to open the file, decide whose changes to keep, and then save and commit again.  

------------------------------------------------------

# 7. Glossary -

- **Branch**: A separate line of development within a project, used to work on features or fixes without affecting the main codebase.  
- **Clone**: Creating a local copy of a GitHub repository on your computer so you can work on it directly.  
- **Commit**: A saved snapshot of changes in Git, representing a point in the project’s history.  
- **Fetch**: Checking for updates from the remote repository and downloading information about new changes. it doesnt apply them to your local files.
- **Git**: A version control system that tracks changes in files and manages project history.  
- **GitHub**: A platform for hosting Git repositories online, often used for collaboration and project sharing.  
- **Merge**: The process of integrating changes from one branch into another.  
- **Merge Conflict**: A situation where Git cannot automatically merge changes, requiring manual resolution.  
- **Push**: Sending your committed changes from your local repository to the remote repository on GitHub.  
- **Pull**: Retrieving updates from the remote repository and applying them to your local branch.  
- **Remote**: The version of your repository stored on GitHub (or another server) that your local repository connects to.  
- **Repository**: A storage location tracked by Git that contains your project files and the complete history of changes.  

------------------------------------------------------

# 8. References -

- Slides from classes.
- Git guides - install git. GitHub. (n.d.). https://github.com/git-guides/install-git 
- GitHub: WebStorm. WebStorm Help. (n.d.). https://www.jetbrains.com/help/webstorm/github.html 


