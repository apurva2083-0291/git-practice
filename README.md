# git-practice

This repo is used for **Assignment 24: Git and Github**: 

Question:
Demonstrate your ability to track file changes locally and collaborate using a remote repository. You will initialize a project, create branches, merge changes, and complete a Pull Request on GitHub.

Prerequisites:
Git must be installed on your computer.
You need an active GitHub account.
Use the command line or terminal for all local steps.
Part 1: Local Setup and Commits
Your first task is to set up a new project on your computer and make your first recorded change.
Create a new folder on your computer named git-practice-yourlastname.
Open your terminal and navigate inside this new folder.
Run git init to initialize a new repository.
Create a new file named project.txt. 
Inside this file, write a short sentence about what you want to learn in this class.
Use git add project.txt to stage the file.
Use git commit -m "Initial commit with project goals" to save this version to your history.

Part 2: Branching and Merging Locally
Working directly on the main branch is not a good habit. You will now create a separate branch to safely test out new changes.
Create a new branch named draft-ideas and switch to it immediately.
Open project.txt and add a second sentence describing a potential project idea.
Stage the file and commit the change with a descriptive message.
Switch back to your main branch. 
If you open the text file now, you will notice your second sentence is missing.
Run git merge draft-ideas to bring your new changes into the main branch.

Part 3: Remote Repositories and Pushing
Now you will back up your local repository to GitHub.
Log into GitHub in your web browser.
Create a new repository named git-practice. 
Leave it empty (do not check the boxes to add a README or .gitignore file).
Copy the URL of your new repository.In your local terminal, link your local folder to GitHub by running git remote add origin [your-repository-URL].
Run git push -u origin main to upload your code to GitHub.

Part 4: Pull Requests and Pulling
The standard way to propose changes in a team is through a Pull Request. You will simulate this process.In your local terminal, 
create and switch to a new branch called final-edits.
Open project.txt and add a third sentence stating your favorite programming language.
Stage and commit this change.
Push this specific branch to GitHub by running git push origin final-edits.
Go to your repository page on GitHub in your browser. 
You will see a banner suggesting you create a Pull Request for final-edits.
Click the button to open the Pull Request. 
Add a short title and click "Create Pull Request".
Review the changes on the screen, then click "Merge pull request" to combine it with the main branch on GitHub.
Go back to your local terminal and switch to your main branch.
Run git pull to download the final merged version from GitHub to your computer.

Submission Guidelines
To submit this assignment,  create a docx or pdf showing outputs after each part of the assignment. Similarly copy the URL of your GitHub repository and paste it at the end of the submission docs.
