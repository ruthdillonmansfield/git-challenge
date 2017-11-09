# Git Training for Northcoders

**What am I looking for in your work?**

1) Your Git Commit history. This is the most important part of this exercise.
2) Your Branch history
3) Your ability to use HTML and style it with CSS

## 1 - Your task: Creating a Site

Create a short website on a topic of your choice.

Your website should include:

- A Navbar
- 2 Pages
- At least 2 images

Your website should be nicely styled, but do not spend too much time doing this.

**You should branch and commit your work using Git at least 6 times.**

## 2 - Workflow

### CLONING
Clone the repo onto your local machine using Git. You can find the URL in the Github repo.

```shell
git clone <https://whatever-the-url-is.git>
```

### BRANCHING

**Never** work on the master branch of this repo. Once you clone, you will be on the master branch by default. 

*You can check what branch you are on at any time using:* 

```shell
git branch
```

Once you have cloned the repo, create ('*check out*' onto) a new branch. Give the branch a sensible name that will tell you exactly what work you plan to do on the branch.

Check out onto a *new* branch by running:

```shell
git checkout -b "my-amazing-navbar"
```

Remember, you can run:

```shell
git branch
```

to see where you are! You should now be on your branch!

Once you have done some work (for example added some images or changed the Navbar), you need to commit your work. You should know how to do this.

After each commit, upload your new work to Github.

### UPLOADING YOUR WORK

**1 - Uploading**

To upload to Github, you need to *push* your work back to the origin (Github).

```
git push origin <name-of-branch>
```

**2 - Merging with Master**

Now, you have pushed your work to your branch on Github. But it isn't yet merged with master. You need to get permission to merge your work with master. You ask for permission by creating a *pull request*

Go to Github repo, and create a pull request. Ask me (Ruth) to approve your pull request.


**3 - Updating your local repo**

*Once this is approved*, you need to update the master branch on your local machine with Github's master.

First, check out to the existing master branch:

```shell
git checkout master
```

Then run:

```shell
git pull
```

to update your local master.

That's it. You're ready to check out on a new branch!


