# Demo

`` my name is vansh ! ``

# how to connect with git repo :

`` - git remote add origin [branch-name] ``

# push :

`` - git push -u origin main ``

#### - Here , `-u` is use to generate a shortcut when we need to push by just typing `git push` basically it become default connection repo

# Branch :

### List branches :

`` - git branch ``

### Create branch & switch inside it :

`` - git checkout -b [branch-name] ``

### only switch branch :

`` - git checkout [branch-name] ``

### compare branch changes :

`` - git diff [branch-you-want-to-compare]``

### Merge branches :

`` - git merge [branch-you-want-to-merge] ``

### delete branch :

`` - git branch -d [branch-name] ``

# Undoing in Git :

### unstage (remove Added files) files :

``- git reset `` (defalut last added , you can also give file name )

### Undo commit :

``- git reset HEAD~1 `` ( by doing this you can unstage and uncommit by one step back means undo you can now make changes , add to stage , finally update your commit also )

### Reset hard :

`` - git reset --hard [id-of-commit] `` ( you should show commit id by loging commits ` git log ` , you should copy where you want to jump into your previous code and apply this command )