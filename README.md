# Make your first Open Source Contribution 📢
The `first-timers-lab` repository is created to serve as starting point for newbies to easily make their very first contribution to open source.
## Prerequisite 
Should be familiar with git or just a basic understanding else check here [Everyday Git](https://git-scm.com/docs/giteveryday)
## What you will learn.
- How to contribute to open source using a git workflow 
- How to collaborate we teams 

**_Without Further Ado, Let's get started_** 🚀
# STEP 1 - FORK THIS REPOSITORY
![fork-1](https://user-images.githubusercontent.com/37655600/152127104-183c41b1-a8cb-46da-a165-c73629145d81.PNG)

Fork this repository by clicking on the `Fork` button at the top right corner of this page.

Forking the repository, simply means copying the repository or project to your own github account.
# STEP 2 - CLONE THE REPOSITORY 
Cloning the repository means downloading the project from github to your local system, so you can make changes.
![clone](https://user-images.githubusercontent.com/37655600/152126142-8e06fc3d-fc62-4bd2-8653-daf0f33a6ad1.PNG)


- To do this, go into the **forked** repository on your personal Github account and click on the `Code` button 
- Copy the **HTTP** link, SSH and Github CLI are also available options but we are using HTTP for this example
- Then open your **terminal** and enter the following code 

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
An Example is would be;

```
git checkout -b update_README
```

Your branch name should be short and descriptive and also, the maintaner might have a convention for naming branches. Which is why, you must have gone through the `CONTRIBUTING.md` file at the beginning.

# STEP 4 - MAKE YOUR CHANGES 
1. Open the README.md file 
2. Goto the Team section
3. **Add your Fullname and twitter handle to the list** 

After Successfully adding and saving your details.
Open up your **terminal** and add the following commands 
```
git add README.md 
git commit -m 'adds my name and handle'
git push origin YOUR-BRANCH-NAME
```
- `git add` this command adds the file in which changes have been made to the staging area.
- `git commit -m` saves the changes you have made locally with a message.
- `git push origin` uploads the changes you have made to github.

# STEP 5 - CREATE A PULL REQUEST

# Team
Add your name and handle here ✍



