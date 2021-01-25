Ok, you're ready to commit, push and submit your code. The following
steps are really important to make sure that you're complete done with
the lab.

## Prepare

This extra step is executed ONLY on new cloned projects. If you're in your
personal computer and you already did it, you don't need to run it
again. If you don't have a token, maybe you have not created your
Classify API token, if so, go to the [Classify API
Introduction](https://www.katacoda.com/coderssquad/scenarios/classify-intro)
katacoda scenario.

- Add your personal data into the local git config

``git config --local classify.fullname "<Your Full Name>"``{{execute no-newline}}

``git config --local classify.github-user <you_github_user>``{{execute no-newline}}

``git config --local classify.school-id <your_school_id>``{{execute no-newline}}


- Add your Classify API token and your github account

``git config --local classify.school-id <your_classify_token>``{{execute no-newline}}


## Commit

Commit your solution change to the git history.

It's highly recommended to add only the changed the files instead of
adding everything at once.


- Add the changed files (repeat this action for each changed file)

``git add test-lab.go``


- Commit it

``git commit -s -m "Solve test-lab"``{{execute}}

For good commit messages guidelines go to [How to crite a git commit
message](https://chris.beams.io/posts/git-commit/)


It may ask you to configure your user's name and email. if so, run the
following commands and the try the commit command again.

``git config --global user.name "<Full Name>"{{execute no-newline}}

``git config --global user.email "<your-email>"``{{execute no-newline}}


- Verify that it was added to the branch's history. Type `q` to quit.

``git log``{{execute}}


## Push

Once your change is commited to the local repository history, it's
time to push it to your fork's remote source. If skip this step,
Classify API will be able to download your code and it will not be
able to grade it.

``git push <your_github_account> <branch_name>``


## Submit
This is super easy.

``make submit``{{execute}}


**Important**
If you did all previous steps and then you need to do
another change, don't worry, you can do the `commit`, `push` and
`submit` as many times as needed before the lab's due date.

Ok, that's all, you have submitted your work to the Classify API.
