Git Commit States

1. Untracked:  
   - The file is not being tracked by Git.  
   - Use `git add <file>` to start tracking it.  

2. Staged:  
   - The file is added to the staging area and ready for commit.  
   - Use `git commit -m "Message"` to commit the changes.  

3. Committed:  
   - The file is stored in the repository's history.  
   - It is now a part of the project's version control.  

Importance of Git History in Version Control & Debugging

1. Tracking Changes:  
   - Git history helps keep track of all modifications in a project.  
   - Use `git log` to view past commits.  

2. Restoring Previous Versions:  
   - If a mistake is made, you can revert to an earlier version.  
   - Use `git checkout <commit-id>` or `git revert <commit-id>`.  

3. Debugging Issues:  
   - Helps identify when and where a bug was introduced.  
   - Use `git blame <file>` to check changes made by different contributors.  
