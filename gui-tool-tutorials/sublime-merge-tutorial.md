# First Contributions

| <img alt="Sublime Merge" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/sublime-merge.png" width="200"> | Sublime Merge Git Client |
|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|

It's hard. It's always hard, when you do something for the first time. Especially when you are collaborating, making mistakes isn't a comfortable thing. But open source is all about collaboration & working together. We wanted to simplify the way new open-source contributors learn & contribute for the first time.

Reading articles & watching tutorials can help, but what comes better than actually doing the stuff without messing up anything. This project aims at providing guidance & simplifying the way rookies make their first contribution. Remember the more relaxed you are, the better you learn. If you are looking for making your first contribution just follow the simple steps below. We promise you, it will be fun.


## Sublime Merge

Download [Sublime Merge](https://www.sublimemerge.com/), Install and open it.

## Fork this repository

Fork this repo by clicking on the fork button on the top of this page.
<img align="right" width="300" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/fork.png" alt="fork this repository" />
This will create of copy of this repository in your account.


## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/clone.png" alt="clone this repository" />

In Sublime Merge, go to File -> Clone Repository.


<img style="float: right;" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/sm-clone.png" alt="clone this repository" />

The next step is to clone your repo down to your machine, so you can begin making changes. Sublime Merge needs the URL of your repo, so click the "clone" button and then click the "copy to clipboard" icon.

**CAREFUL:** One mistake that new contributors often make is to clone the repo you forked _from_ rather than cloning your repo. Check your browser's address bar and make sure you are cloning your repo.


Enter the URL of the repo in Sublime Merge, give it a repository name (or leave it blank) and set your directory where to save the repository.

Once you're satisfied with the path, click "Clone".


## Create a branch

Right click Branches -> Create Branch 
or 
Navigate to Repository -> Create Branch

Name your branch "add-your-name", for example: "add-william-sutton"

<img style="float: right;" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/sm-branch.png" alt="name your branch" />


## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor and add your name to it, then save the file.

If you have the repo open in Sublime Merge you'll see there are changes. 
Select the newest commit at the top, named "x unstaged files"
Review the files that have been changed and decide what you would like to stage. 
Give the commit a commit message ("Add <your-name> to Contributors list" sounds nice and descriptive).
When you are happy with your changes stage those changes by staging them file by file or selecting "stage all". Staging is important to tell git exactly what file changes you want associated with this commit.

<img style="float: right;" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/sm-stage.png" alt="stage your changes" />

If you change your mind, you can unstage those changes, or you can discard them all together.
WARNING: As the word discard implies, this is a destructive operation. Do this only if you don't want any change(s) from whatever repository you're in.

Hit commit and enter your username and email address and press Update.

Hit commit again.

Congratulations, you've committed all the changes to your local copy of your branch of your fork of first-contributions.  Onward!


## Push changes to GitHub

Navigate to Repository -> Push
or hit the small arrow in upward direction in the right-hand corner.

<img style="float: right;" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/sm-login.png" alt="login" />

Login to your GitHub Account with your username and password

Submit changes on the origin branch if you want the changes to reflect in the master branch directly, else select the appropriate branch you want to push.


## Submit your changes for review

If you go to your repository on GitHub, you'll see  `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/sublime-merge-tutorial/submit-pull-request.png" alt="submit pull request" />

Every so often, someone in charge of the repo will merge your changes into the main branch of this project.
If you setup to be notified, you will receive a notification email once the changes have been merged.

Congrats! You just completed the standard *fork -> clone -> edit -> pull request* workflow that you'll encounter often as a contributor!

## Where to go from here?

Check out advanced git topics found in this git repo:
#### [Git Workflow Scenarios](../git_workflow_scenarios/README.md)

#### [Additional Material](../git_workflow_scenarios/README.md)

## Tutorials Using Other Tools
[Back to main page](README.md)