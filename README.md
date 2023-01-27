# learning-github
Understanding push, pull, merge, fork, clone etc using vs code and github

This is a github repo to understand and recall how to use VS code to work with github simultaneously and how branches, push, pull requests, edits, ets work to make a good github working environment. For example this paragraph was written in VS code rather directly being edited on github and then pushed on a new branch, further merging the new branch with the main branch via a pull request. The following parts of the readme ecplaine exactly how this was done!

This is the first line that has been updated on github using VS code
Steps : 1. Copy the https code from github repo
        2. ctrl+shift+p on VS code to open command pallette and type clone to clone the repo
        3. Paste the copied https url and select the repo to clone
        4. Perform changes(i.e. the last 5 lines including this) and save the file
        5. Add the file to the stage by clicking +, enter commit message, commit and then publish to see the changes in github repo! and then click sync
        6. Once done, open github to see updated push 


This is the second part or way to perform changes to github using VS code
Steps: 1. Create a new branch by clicking on branch name at left bottom and then selecting
        create branch. Name your new branch and click create.
       2. Confirm that you are in new branch by viewing branch name in the left bottom
       3. Repeat steps 5 to 6.
       4. Now one can see that a new branch has been created
       5. Create a pull request which can be then seen by the admin and reviwed so that they can merge the new branch with the main branch!

This is the third part where we will add a new python file to the repo via vs code and commit changes
Steps: 1. Go to the file explorer and create a new .py file and write some code in it and save
       2. Then add the file to stage, enter commit message, commit and then sync
       3. Now again create a pull request to perform changes to main
       
This change is being made on the new branch in which we have been commiting till now. Once saved, create a new pull request to update changes in main branch.

This final block of change is being done directly in the main branch in github, so there wont be any need to create a new pull request to update main branch!
For recalling vscode working with github, visit the YT video : https://www.youtube.com/watch?v=i_23KUAEtUM&ab_channel=VisualStudioCode
