#### created a local copy in your current dir
git clone <GIT_URL>
#### stages all files/dirs
#### files can be skipped with a .gitignore file...more on this later
git add .
#### commit it locally, general convention is to have your message be present tense eg "Update index.html" not "Updated index.html"
git commit -m "some message"
#### create a copy and switch the the copy....you'll be in the same directory, but any new changes will be tracked in this branch
git checkout -b <BRANCH_NAME>
#### switch to an existing branch... note you need to either commit or lose changes in your current branch before you can switch
git branch <OTHER_BRANCH_NAME>
#### delete branches
git branch -d <BRANCH_NAME>
#### list local branches
git branch
#### list all branches, local and remote
git branch -a
#### See logs and what changed
git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative
#### Go back to a specific commit
Git --reset HARD head~2
#### See configuration
git config --list
#### Change git config
vi ~/.gitconfig
#### 
Git remote -v 
