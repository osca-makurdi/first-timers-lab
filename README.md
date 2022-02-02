# Make your first Open Source Contribution 📢
The `first-timers-lab` repository is created to serve as starting point for newbies to easily make their very first contribution to open source.
## Prerequisite 
Should be familiar with git or just a basic understanding else check here [Everyday Git](https://git-scm.com/docs/giteveryday)
## What you will learn.
- How to contribute to open source using a git workflow 
- How to collaborate we teams 

**_Without Further Ado, Let's get started_** 🚀
# STEP 1 - FORK THIS REPOSITORY
![fork](https://user-images.githubusercontent.com/37655600/152088898-f424b02b-646c-4155-8ce1-8916e05e914c.PNG)

Fork this repository by clicking on the `fork` button at the top right corner of this page.

Forking the repository, simply means copying the repository or project to your own github account.
# STEP 2 - CLONE THE REPOSITORY 
Cloning the repository means downloading the project from github to your local system, so you can make changes.

- To do this, go into the forked repository on your personal Github account and click on the `code` button 
- Copy the HTTP link, SSH and GITHUB CLI are also available options but we are using HTTP for this example
- Then open your terminal and enter the following code 

```
git clone THE-LINK-YOU-JUST-COPIED
cd FORKED-REPO-NAME
```
Replace all text in upper case with your details.
In my case, it would be 
```
git clone https://github.com/logiquebox/first-timers-lab.git
cd first-timers-lab
```
Substitute **logiquebox** with your github username
# STEP 3 - CREATE A BRANCH 
Create a branch and make your changes to that branch, this makes it so that each contributor works on a separate branch and only commit to master when their code has been reviewed. 

Enter the follwing code to create a branch.
```
git checkout -b YOUR-BRANCH-NAME
```
Your branch name should be short and descriptive and also, the maintaner might have a convention for naming branches. Which is why, you must have gone through the `CONTRIBUTING.md` file at the beginning.




