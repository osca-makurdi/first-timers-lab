# Make your first Open Source Contribution 📢
---
The `first-timers-lab` repository is created to serve as starting point for newbies to easily make their very first contribution to open source.



## Prerequisite 
Should be familiar with git or just a basic understanding else check here [Everyday Git](https://git-scm.com/docs/giteveryday)

## What you will learn.
- How to contribute to open source using a git workflow 
- How to collaborate with teams 

**_Without Further Ado, Let's get started_** 🚀

---
# STEP 1 - :fork_and_knife: FORK THIS REPOSITORY 
---
![fork-1](https://user-images.githubusercontent.com/37655600/152127104-183c41b1-a8cb-46da-a165-c73629145d81.PNG)

Fork this repository by clicking on the `Fork` button at the top right corner of this page.

Forking the repository, simply means copying the repository or project to your own github account.

---
# STEP 2 - CLONE THE REPOSITORY 
---
Cloning the repository means downloading the project from github to your local system, so you can make changes.
![clone](https://user-images.githubusercontent.com/37655600/152126142-8e06fc3d-fc62-4bd2-8653-daf0f33a6ad1.PNG)


- To do this, go into the **forked** copy of the repository on your personal Github account and click on the `Code` button 
- Copy the **HTTPS** link, SSH and Github CLI are also available options but we are using HTTP for this example
- Then open your **terminal** and enter the following code 

`git clone PASTE-COPIED-LINK`

Replace all **uppercase** text with your details.

In my case, it would be 

`git clone https://github.com/logiquebox/first-timers-lab.git`

replace **logiquebox** with your github username

---
# STEP 3 - CREATE A BRANCH 
---
Create a branch and make your changes to that branch, this makes it so that each contributor works on a separate branch and only commit to master when their code has been approved. 

Enter the follwing code to create a branch.

`git checkout -b YOUR-BRANCH-NAME`

An Example of this would be;

`git checkout -b my-contribution`

Your branch name should be short and descriptive so be creative and also, the maintainer might have a convention for naming branches. Which is why, it is important that you go through the `CONTRIBUTING.md` file at the beginning.

---
# STEP 4 - MAKE YOUR CHANGES 
---
1. Goto the [Team](https://github.com/logiquebox/first-timers-lab#team) section of the README.md file 
2. **Add your Fullname and twitter handle to the list** 

After Successfully adding and saving your details.
Open up your **terminal** and enter the following commands line by line. 
```
git add README.md 
git commit -m 'added my name and handle'
git push origin YOUR-BRANCH-NAME
```
- `git add` this command adds the file in which changes have been made to the staging area.
- `git commit -m` saves the changes you have made to repo locally with a message.
- `git push origin` uploads the changes you have made to the remote repository (github).

---
# STEP 5 - CREATE A PULL REQUEST
---
Now, immediately after you push your changes to remote, github will prompt you to make a pull request. 
![compare](https://user-images.githubusercontent.com/37655600/152628396-59f4a8d5-4e09-4720-8e94-93025e5b6108.PNG)

- And you make a pull request by clicking on the `Compare & Pull Request` button 

![create PR](https://user-images.githubusercontent.com/37655600/152628440-4e5fffb9-00a0-45a7-b9fc-1af9aefaf314.PNG)

- Then enter a title and description, and again your title should be descriptive. 
- Finally, click on `Create Pull Request`

---

# :100: :muscle: :tada:

---


And, Yay!👏 You have just made your first contribution!!! :tada: 
Just wait for you pull request to be merged.


# Team
---
Add your name and handle here ✍

🟢Ujah Emmanuel [@codeboss_](https://twitter.com/codeboss_)





