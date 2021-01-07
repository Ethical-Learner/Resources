# Github Collaboration 

## Worflow management
Below are some important Github CLI commands, which will be helpful to manage collaboration with other developer. Always follow this sequence when you're collaborating in a team over a single repository.

1. Firstly, stage all modified files: **`git add .`**  
1. Then, commit you code:  **`git commit -m 'Commit Message'`**. This will let you have a unique commit key that will/can be used in some other tasks like reverting code to previously staged code.
1. Always pull before pushing your code: **`git pull`** to pull all the changes in different branch or **`git pull origin branch_name`** to pull changes from one branch only.
1. Resolve conflict (if any). Note: if you're using VSCode editor, then install GitLens' (id: eamodio.gitlens) extension to help you to resolve conflicts and see the change wrt to previous commit as well.
1. Now after resolving conflicts, commit your code again.
1. Finally, push your changes on Github website: **`git push origin branch_name`**. Note: never ever run **`git push`** if you've multiple branches. Because this will always push your code into 'master' or 'main' branch which is not a good practice.

### Tips: 
- Always use **`git pull`** before start working.
- Run this while cloning a repo: **`git clone https://username:password@github.com/username/reponame.git`** to avoid inserting ID & password each time you pull or push code into the repo.
- Always push the complete code (don't push code if it persist some error)


Need Help? ping [this](https://github.com/genialkartik) guy!

Detail Guidance: [https://guides.github.com/](https://guides.github.com/)
