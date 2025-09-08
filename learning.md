# Reviews

1. Why do we need Git and GitHub?

2. Basic Configuration

3. SSH Key
   - Generate SSH key
   - Add SSH public key to GitHub

4. Git Workflow

5. Merge Conflict  
    - main branch → `index.html` → python  
     - feature/skill12 branch → `index.html` → java

6. How to Resolve Merge Conflict

7. Collaboration and Contribution  
   - fork → clone

8. GitHub Pages

9. git merge vs git rebase

10. github actions (CI/CD)
 
12. Advanch 

 -github action (CI/CD)
 - git flow / github flow, trank basked development
 - rewriting history: git reflog, git filter-branch, git cherry-pick
 - performence and optimizatiom: Shallow clones, partial clones
 - what is github API


 -    #undo changes (working directory - local repo - remote repo)      
         command(git checkout --<fileName>)    (undo from unstaging)
                - git reset HEAD . (staging area undo)
                - git reset --hard HEAD (undo from staging and unstaging)

                                 commit message changes
                - git commit --amend (correcting the commit message and add new fill)

                                 commit delete local
                - git revert HEAD (UNDO a letest commit)


                                     push commit undo from remote repo

                - git revert,id + git push (reverting a push commit) recommended added commit history.
                - git reset --hard, id + git push --force (force pushing to undo a commit) history hide its dangerous.not recommanded but workfull.


