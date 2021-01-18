Now that you have cloned the git-based project, it's time to create your Classify User

# Configure your local variables

Before the user creation you need to define some variables in the git local storage

**Note:** Make sure that you replace the `<>` enclosed strings.

``git config --local classify.fullname "<Your Full Name>"``{{execute no-newline}}

``git config --local classify.github-user <you_github_user>``{{execute no-newline}}

``git config --local classify.school-id <your_school_id>``{{execute no-newline}}


# Create the user
Let's do it, let's create a new Classify user

``make user``{{execute}}

# That's it, you created your user in Classify, but ...

**Don't forget to save your Classify token in an external secured location**

For now, we'll save it in your local git storage, you will do this same line when you clone the class repo in your personal computer.
``git config --local classify.token <your_assigned_very_long_token>``{{execute no-newline}}

Done, now you are safe.