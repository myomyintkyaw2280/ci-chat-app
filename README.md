# create a new repository on the command line
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M branch-name
- git remote add origin https://github.com/myomyintkyaw2280/ci-chat-app.git
- git push -u origin branch-name

# push an existing repository from the command line
- git remote add origin https://github.com/myomyintkyaw2280/ci-chat-app.git
- git branch -M branch-name
- git push -u origin branch-name



# When you are facing conflict file to fix below command

Step 1: Clone the repository or update your local repository with the latest changes.

git pull origin branch-name
Step 2: Switch to the head branch of the pull request.

git checkout branch-name
Step 3: Merge the base branch into the head branch.

git merge branch-name
Step 4: Fix the conflicts and commit the result.

See Resolving a merge conflict using the command line for step-by-step instructions on resolving merge conflicts.
Step 5: Push the changes.

