# Pull Request Practice
This repository is for practicing and learning how to make pull requests in GitHub.

## Why make a pull request?

Pull requests allow us to segment our changes and bring them into a known working branch in increments. They also allow for helpful peer-reviews of code before bringing them into main branch.

Here are the steps to make a branch for a pull request in GitHub:

## First we must make a branch and edit it.

1. Clone this repository (or any other repository, using their link) by typing `git clone https://github.com/Tannerpalin/pullRequestPractice.git`

2. `cd` into the folder of the repository.

3. Type `git branch branchName` where `branchName` is the name of the branch you would like to make. Sometimes a semi-descriptive name is helpful.
  
    - This new branch will be "connected" to the branch that you were on when typing this command.

4. Next, type `git checkout branchName`. This will allow your editor (VSCode) to jump over and edit only your local branch.

5. Now you can make all your edits, fixes, updates to your local branch. If you'd like to, feel free to add your username to the practiceList.txt

## Now we must save these changes to our local branch and push to the remote repository.

1. Type `git status` to see a list of all the files you've changed with your edits.

2. Add the files you would like to include in this update by typing `git add fileName`. Where `fileName` is your changed file.

  - If you have many files changed, sometimes you can use the name of the folder or use * followed by the file type extension.
  
  - You can use `git status` as you add files to see if any still need to be added or removed. `git reset fileName` will remove a file.
  
3. After you are done adding files, type `git commit -m "insert helpful message here."` to save these updates as a commit.

4. Now we may push to the remote repository through: `git push -u origin branchName`

5. Now you may check the in-browser repository for your branch to create a pull request from.
