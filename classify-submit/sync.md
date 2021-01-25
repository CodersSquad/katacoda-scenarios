This section will be really important for every lab that you're going
to develop. Every time that you're going to start a new lab, make sure
that you sync first your local cloned repository in order to get the
latest changes from the class github repository.

First, make sure you are located in the root path of the
repository. You can run the following command to verify it.

`pwd`{{execute}}


## Checkout into the master branch

`git checkout master`{{execute}}


## Pull latest original ap-labs content.

This will synchronize with the original class repository.

`git pull --rebase origin master`{{execute}}

That's all, after some seconds your `master` branch should be
up-to-date and ready for the next step.
