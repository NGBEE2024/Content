
create a single Git repository which you can use to add, commit and push your files to Git and Github

Need "" if there is space in between the words
Create a new folder in cdrive(named Local_Git_Repository):
-> inside folder create lab1: mkdir lab1
cd "C:\Local_Git_Repository\lab1"
git init (creates a .git subdirectory)


git status : to see what file needs to be commit

git add file_name.file_type (move to staging area)
git commit -m ("msg_what I have change/history/a record")
Save and Perform the two lines above when I want to save and add msg to the files


git diff: to view the file differences before
deciding to either commit the file again to the Git repository, or continue modifying
the file and commit the changes to the Git repository later

git branch: view all the branches created in the current Git repository 
*branch_name means this is the current branch u are in 

git branch hidden (create new git branch named hidden)
Use git  branch to see if the creation of branch is successful

git checkout hidden (go to hidden branch)

git merge hidden (merge the file in the branch that u are in right now with file from hidden)


Before pushing your Local Git Repository to GitHub, you need to first specify the URL of the remote GitHub repository

To check if the currently local Git repository has the remote repository server correctly configured, run the following Git command below: git remote -v
git push --set-upstream origin master (use "--set-upstream origin " for the first time. Just git push or pull the next time.)

Readme.md !!
Add a header using # (has tag + space)
Future syntax: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax



Tags are used in Git usually to create Software Releases

git tag -a v1.0 -m "Initial release v1.0"

Click 1tag , click releases, create new releases



Click publish release

Submodules:
s the Mini-Project it’s sometimes necessary to reference external shared Git/Github repositories that are maintained centrally by another team but used in the repositories of other teams


add a Git Submodule from your friend repository:
git submodule add 

git submodule add https://github.com/ET0735-DevOps-AIoT/Lab1_submodule.git

![image](https://github.com/user-attachments/assets/e98e4424-f895-4224-a046-9bfcba591530)

