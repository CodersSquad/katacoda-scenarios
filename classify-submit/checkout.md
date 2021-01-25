Now that your personal cloned repository is synced and up-to-date with
the class github repository, we are ready to create our new lab's
branch.

For this exercise, we're going to use the `test-lab` branch name. It's
highly recommended to name the branch as the lab's name.

`git checkout -b test-lab`{{execute}}

**Note:** *This action will be executed one time per lab*


Let's verify our new created branch:

`git branch`{{execute}}

you should see a list of branches and the one you just created should
have little star symbol `*` at the beginning. In case that you cannot
type more commands, type `q` and you will be out of that list.

**Important**
All laboratories must be implemented in different branches than the
master one. The master branch is ONLY for syncing purpuses.

That's all, now you have a new branch that will be dedicated for your
lab's solution.
