
  git clone https://github.com/vinita2000/Team12-DevOps.git
  touch PRG1, PRG2
  git add .
  git commit -m"message"
  git push origin master

  git checkout -b BRANCH1 (programmer A)
  git checkout -b BRANCH2 (programmer B)
  git add .
  git commit -m"message"
  git push origin BRANCH1
  git push origin BRANCH2

  git checkout master
  git merge BRANCH1
  git merge BRANCH2
  git branch -d BRANCH1
  git branch -d BRANCH2
  git log

  git mv new_file old_file
  git revert HEAD~

