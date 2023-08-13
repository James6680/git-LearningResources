<h1>Git and Github Learning Resources 👽</h1>
<h3>Here's a step-by-step process to get started:</h3>

1. Setting Up Your Local Environment:
   - Install Git: If you haven't already, download and install Git from the official website: https://git-scm.com/downloads

2. Creating a GitHub Repository:
   - One of your group members can create a new repository on GitHub:
     - Log in to GitHub and click the "+" icon in the upper right corner, then select "New Repository."
     - Give your repository a name, description, and choose other settings as needed.

3. Cloning the Repository:
   - On your local machine, navigate to the directory where you want to store your project.
   - Clone the repository using the URL from the GitHub repository:<br>
     - <code>git clone <repository_url></code>

4. Setting Up Remote:
   - Change into the cloned directory:
       - <code>cd <repository_name></code>
   - Connect your local repository to the remote on GitHub:
       - <code>git remote add origin <repository_url></code>

5. Branching:
   - Create a branch for the feature you're working on:
       - <code>git checkout -b <branch_name></code>

6. Developing and Committing:
   - Make changes to your code.
   - Stage the changes for commit:
       - <code>git add .</code>
   - Commit the changes with a descriptive message:
       - <code>git commit -m "Add feature X"</code>

7. Pushing Changes:
   - Push your changes to the remote repository:
       - <code>git push origin <branch_name></code>

8. Pull Requests:
   - On GitHub, navigate to your repository and the branch you pushed to.
   - Click on "Compare & pull request."
   - Review the changes and click "Create pull request."
   - Your team can discuss the changes, make additional commits, and comment on the pull request.
   - Once approved, merge the pull request into the main branch.
  
9. Pulling Updates:
   - Regularly pull updates from the main branch to your working branch to stay up-to-date:
     <code>
       git checkout main
       git pull origin main
       git checkout <your_branch>
       git merge main
     </code>

10. Resolving Conflicts:
    - If conflicts arise during merging, resolve them in your local environment, then commit and push the   changes.

11. Continuous Collaboration:
    - Repeat steps 5-10 for each feature or task.
    - Communicate with your team members about your work and any issues.

<h4>Check out these videos related to Github:<h4>

[Click here to watch the tutorial video on YouTube....](https://youtu.be/0M51U-pEJD4)
<br>
[Click here to watch the tutorial video on YouTube....](https://youtu.be/k5D37W6h56o)
<br>
[Video to customize your Github profile....](https://youtu.be/G-EGDH50hGE)
