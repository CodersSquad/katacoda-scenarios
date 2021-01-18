# Let's verify the new Classify User

We are almost done, before we leave, let's verify the new user.

``make test``{{execute}}

Did it work?

- **No?**, let's verify that pre-required variables are properly set.

``git config --local --list | grep classify`` {{execute}}

*In case that you see missing or not desired values, please go the previous step and re-run the commands.*

- *Yes?* cool, that's all, now you are a **Classifier**. You're free to go!
