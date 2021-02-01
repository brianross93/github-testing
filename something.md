Here is some text that I will use to test Github branching and merging.
 

 Here is the command line github flow for reference. 

$ cd ~/dev/repos/
$ git clone git@github.com:YOUR_USERNAME/git-branchy.git
$ cd git-branchy
$ git pull origin main
$ git checkout -b develop
$ git add .
$ git commit -m "[add] code from step 5 of sweet git tutorial"
$ git pull origin main
$ git push origin develop
$ git checkout main
$ git pull origin main
$ git merge develop
$ git add .
$ git commit -m "[add] merge the develop branch"
$ git push origin main