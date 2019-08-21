# Problem Set 0

** Due via Github classroom **

The purpose of this problem set is to make sure that you understand the submission system, and also get a chance to learn a bit about you.

## Step 1: Create a github account

You should create a github account if you don't already have one. 

Once you created your account, or if you haven't yet, you should create an ssh public/private key. On Linux/Mac, in terminal run `ssh-keygen`. This will create a public/private key in your `.ssh` director in your home directoty. Copy and paste the contents of your `.ssh/id_rsa.pub` into your github settings for public ssh keys. 

## Step 2: Accept the assignment

Go to course [classroom](https://classroom.github.com/classrooms/54329729-csci-3907-6907-usable-security-and-privacy-fall-2019) and accept this assignment for [Problem Set 0](https://classroom.github.com/a/1PPIWtfr) ... or click the link there! 

Once you accept the assignment it will create a new git repo for you with any starter code. You'll get a link to your assignment repo. Go there.

## Step 3: Git Clone

Clone your assignment repo to your local computer by clicking the button **Clone or download**. I would recommend doing this in a directory that is well named for this class. 

For example, for my assignment I would do:

```
git clone git@github.com:usable-security-privacy-fall-2019/problem-set-0-adamaviv.git problem-set-0
```

Which will create a directory called `problem-set-0`. Change into that directory.

## Step 4: Do the assignemtn

Edit the file `README.md` as appropriate for the instructions.

## Step 5: Commit your changes

Now that you've edited the file, you have to commit the changes to your local repository.

```
git commit -a -m "snarky message"
```

The `-a` says to add everything to the commit. The `-m` is for the message. Choose a useful message for you. 

If you've created new files, you need to add them first before comitting.

```
git add new-file.txt
git commit -a -m "Added a new file to the repo"
```

## Step 6: Push your changes to github

Now you're all done, you have to push all your local commits to github

```
git push origin master
```

The `origin` repository in this case is github, and the `master` refers to the master branch, the branch you've been working on. 

## Step 7: Rinse and repeat until the deadline

This problem set probably only requires you to do one push to complete, but in others, you might want to push multiple times. You can continue to push up until the deadline for the assignment. Your last push will be graded.



