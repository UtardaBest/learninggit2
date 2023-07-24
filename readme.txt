Hello World

// to create new branch 
git branch <name>

//to switch from one branch to another
git checkout <branch name>

//to create file 
vim <filename>.<extension>   // goes into the file after creation
touch <filename>.<extension> //empty file witout going in

//to edit the file 
press i to chg to insert mode 
edit the file

//to save and exit 
press esc then ": wq"

//to commit
git add .
git commit -a -m "ui feature is added"

//to merge
git merge <branch name> //pull other parallel branch to current
git rebase <branch name> //pull other branches to update current

//to add repo to github
git remote add origin https://github.com/UtardaBest/learninggit2.git //for new repo
git push origin --all //to push all branches to github

//to create a new release 
git log //to view past changes
copy the first 6 characters //use right click
git tag <version> <6 characters> //create a new tag
git push --tag // upload to github

