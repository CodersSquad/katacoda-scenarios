Welcome, this is the first step for every new cloned project. Further
steps will be the common ones for every lab in the future.

If you're running these steps in your personal computer, the following
instructions will be executed ONLY one time, you are not required to
run them on every lab.


# Let's first clone your class project

You will be running **ONLY** one of the 2 following paths, it will
depend in the class you're enrolled.  Follow the section that applies
for your class.


## Advanced Programming

- Clone our Advanced Programing Class project

`git clone https://github.com/CodersSquad/ap-labs.git`{{execute}}

- Move into your new cloned project

`cd ap-labs`{{execute}}

- Run some testing commands

`pwd`{{execute}}
`ls -la`{{execute}}
`git remote -v`{{execute}}


## Distributed Computing

- Clone our Distributed Computing Class project

`git clone https://github.com/CodersSquad/dc-labs.git`{{execute}}

- Move into your new cloned project

`cd dc-labs`{{execute}}

- Run some testing commands

`pwd`{{execute}}
`ls -la`{{execute}}
`git remote -v`{{execute}}


# Fork the project

In order to submit your work to a place where you can have access to
submit changes you will need to create a fork from the original
repository. Below the links to the github projects that Classify API
is currently supporting, click in the one that applies for your
current class.

- [Advanced Programming Labs](https://github.com/CodersSquad/ap-labs/)

- [Distributed Computing Labs](https://github.com/CodersSquad/dc-labs/)


## Fork it

Before proceeding with the fork actions, make sure that you have the
following 2 requirements:

- A Classify API account If you don't have it, please go the the
  [Classify API
  Introduction](https://www.katacoda.com/coderssquad/scenarios/classify-intro)
  Katacoda Scenario.
- A valid github account. If you don't have it, please create it at
  [Github](https://github.com/)

Once you're all set, let's go for it.

## Fork it

There's a little `Fork` button at the top-right of the [class github
project](#let-s-first-clone-your-class-project), **click it**.

![github_fork](./assets/github_fork.png)

It will ask some confirmation, say `yes`, it's safe.


## Create a new remote in your repository

Now that you officially forked your class github repository, we need
to add it as a remote source in your local cloned project.


From the following command replace the enclosed strings
`<github_accout>` to your personal github user account.

`git remote add <your_github_account> https://github.com/<your_github_account>/dc-labs.git`{{execute no-newline}}


Let's verify that the new remote source has been properly created

`git remote -v`{{execute}}

You should have 2 tuples for the remote source:

- `origin` which points to the original code from your class github
  repository
- `<your_github_account>` which points to your personal fork


In case that failed in the url typing, you can remove the remote
resource and create it again. Below the command for removing a wrong
remote source.

`github remote remove <wrongly_created_remote>`{{execute no-newline}}

That's all for this step, let's continue to the next section.
