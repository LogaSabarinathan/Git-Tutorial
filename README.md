# What is Git?
  Git is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development. Linus Torvalds created Git in 2005 for the development of the Linux kernel.
  ***
  # Major commands
  1. Add
  2. Commit
  3. Push
  4. Branch
  5. Pull
  6. Checkpoint
  7. Log
  8. Merge
  9. Clone
  10. Status
  ***
  # Add command
  Add command is to track the file in local git.
  
  Add command - `git add <filename>`
  # Commit command
  Commit command is used to save changes and craete a checkpoint in local git.
  
  Commit command - `git commit -m "YOUR MESSAGE"`
  # Push command
  Push command is used to push your local repo to remote repository in github.
  
  Push command - `git push origin master`
  
  **Note:** Before using the above command to push local repo to github ensure that you used `git remote add origin <YOUR GITHUB REPO LINK>` to mention that is your origin.
  # Branch command
  Branch command is used to list the available branch for that repository.
 
  Branch command - `git branch`
  # Pull command
  Pull command is used to fetch and merge all the commits with local repository.
  
  Pullcommand - `git pull <REPO URL>`
  # Checkpoint command
  Checkpoint command is used to switch to other branch and it is also used to craete new branch.
  
  Checkpoint command - `git checkpoint -b branch2` *This creates a new branch named **branch2** and switch to it from current branch*
  
  `git checkpoint master` *This command is used to switch to **master** branch*
  
  # Log command
  Log command is used to list all the commits that has been done before with commit messges.
  
  Log command - `git log`
  
  # Merge command
  Merge command is used to merge two branches and it happens if there is a common commit in both branches.
  
  Merge command - `git merge <BRANCH_NAME>`
  # Clone command
  Clone command is used to duplicate the remote repository to local repository.
  
  Clone command - `git clone <REPO URL>`
  # Status command
  Status command is used to know whether all the files in the repository is tracked and committed.
  
  Staus command - `git status`
  
  
  [Reference Link](https://www.youtube.com/watch?v=RGOj5yH7evk)
