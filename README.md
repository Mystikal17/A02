# A02 – Git, GitHub, and WebStorm Tutorial

Part 1: Step-by-Step Tutorial

1. Create a GitHub Account
Go to https://github.com and sign up.
Choose a username, email, and password.
Verify your email to activate the account.

3. Create a Repository
After logging in, click New Repository.
Name it what you want (case-sensitive).
Check the box to Initialize with a README.md.
Click Create Repository.
Your repository link will look like:
https://github.com/yourUSERNAME/RepositoryName

5. Install Git
Download Git from: https://git-scm.com/downloads
Follow the installer prompts (keep defaults if unsure).
Verify installation by opening a terminal/command prompt and typing:
git --version

7. Install WebStorm (Editor)
Download WebStorm from: https://www.jetbrains.com/webstorm/
Install the software and sign in with your JetBrains account.
Open WebStorm → Configure Git path (File → Settings → Version Control → Git).

8. Clone the Repository to Your Computer
Open WebStorm.
Go to Settings → Click your GitHub Account → Click on your respoistory.
Paste your repository URL:
https://github.com/yourUsername/RepositoryName
WebStorm will clone the repository to your local machine.

10. Make Changes and Commit
Open README.md and edit it.
Save your changes.
In WebStorm, go to Git → Commit.
Add a clear commit message:
Task: Create Repository
Feature: added workflow for using GitHub
Fix: updated readme.md for definition of terms
Click Commit (or Commit and Push).

11. Push Changes to GitHub
If you only committed, now click Git → Push.
This will push changes from your local computer to GitHub.
Refresh your repository on GitHub to confirm changes.

12. Pull Changes
If you make changes on GitHub directly, return to WebStorm and select Git → Pull to update your local copy.

-----------------------------------------------------------------------------------------------------------------------------

Glossary

**Branch** – A parallel version of a repository where you can work on changes without affecting the main project.
**Clone** – A copy of a GitHub repository downloaded to your local computer.
**Commit** – A saved change in Git; like a snapshot of your project.
**Fetch** – Downloads commits, branches, and files from a remote repository without merging them.
**GIT** – A distributed version control system that tracks changes in code.
**GitHub** – A platform for hosting Git repositories in the cloud, with collaboration tools.
**Merge** – Combines changes from one branch into another.
**Merge Conflict** – Happens when Git cannot automatically merge changes; requires manual resolution.
**Push** – Sends your local commits to a remote repository (e.g., GitHub).
**Pull** – Fetches and merges changes from a remote repository into your local branch.
**Remote** – A version of the project hosted on GitHub or another server.
**Repository** – A storage space for your project files and version history.


References
Git Documentation: https://git-scm.com/doc
GitHub Guides: https://docs.github.com/en
JetBrains WebStorm Docs: https://www.jetbrains.com/webstorm/documentation/
