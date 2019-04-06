# My GitHub Workflow

## How I create changes
1. Create issue in Github website
2. Pull remote repo to local computer ``` git pull remote branchname ```
3. Create new branch in local repo ``` git checkout -b new-branch-name ```
4. Make necessary changes to code
5. Commit changes to ```new-branch-name ```
6. Push commit to remote ```git push origin new-branch-name```
7. Create a pull request and give a good description of what was done. Reference to Issue you made in Step 1 ```#issue_number```
8. Merge to master branch
9. Delete branch
10. Close Issue
11. Manually delete local branch ```git branch -D branch-name```
