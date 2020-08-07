<<<<<<< HEAD
# 20200730-GitCollab This is in response from a second client (oh one more change!)
=======
# 20200730-GitCollab - Let this address a request from one customer
>>>>>>> This addresses a request from one customer
This is a scratch pad to help teach/learn Git (modified)

- `git clone <url>` : downloads the repository from the web to your local computer
  - make sure you do not nest this commonand
  - origin is repo where you can do push or pull
  - unlike git init this sets the origin to remote repository (This added)

- Branches
  - 'git branch <branch_name>' creates a new branch where HEAD is
  - 'git switch <branch name>' move to branch_name

- pull/push
  - `push origin <branch>`
  PR (pull request)
  `git fetch --prune` : clean your git history and removes refrences from remote

  `git branch -d <branch>`

  `git log --online --graph --decorate --all`
    - you can look up how to set this as a git alias

git switch -c <branch_name>
# this is a harmless change (does not cause conflict) which
# should be easily handles using git rebase command
