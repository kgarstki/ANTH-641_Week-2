# Week 2: Exercise 1 - GitHub
_This activity was based on the instructions found [here](https://guides.github.com/activities/hello-world/). The concepts and take-aways are aligned with those found in [ODAT chapter 1.3](https://o-date.github.io/draft/book/github-version-control.html), so make sure you read the accompanying text._

### Getting started with GitHub
1. Go [here](https://github.com/) and follow the instructions to start a GitHub account
2. When you have an account, search for "kgarstki" and follow me. 

__Create a Repository in GitHub.__ A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets – anything your project needs. I recommend including a README, or a file with information about your project. GitHub makes it easy to add one at the same time you create your new repository.
1.	When you’re on your GitHub page, go to the upper right corner, next to your avatar or identicon, click + and then select __New repository__.
2.	Name your repository “ANTH 641_Week 2” 
3.	Write a short description
4.	Select __Initialize this repository with a README.__
5.	Click __Create repository__

__Create a Branch.__ Branching is the way to work on different versions of a repository at one time. By default your repository has one branch named master which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master.
When you create a branch off the master branch, you’re making a copy, or snapshot, of master as it was at that point in time. If someone else made changes to the master branch while you were working on your branch, you could pull in those updates.
This diagram shows:
•	The master branch
•	A new branch called feature (because we’re doing ‘feature work’ on this branch)
•	The journey that feature takes before it’s merged into master

Have you ever saved different versions of a file? Something like:
•	story.txt
•	story-joe-edit.txt
•	story-joe-edit-reviewed.txt
Branches accomplish similar goals in GitHub repositories.

To Create a New Branch:
1.	Go to your repository “ANTH 641_Week 2”
2.	Click the drop down at the top of the file list that says __branch: master__
3.	Type a branch name, “readme-edits”, into the new branch text box.  
4.	Select the blue Create branch box or hit “Enter” on your keyboard. 

Now you have two branches, “master” and “readme-edits”. They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

__Make and commit changes.__ Now, you’re on the code view for your readme-edits branch, which is a copy of master. Let’s make some edits.

On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.
1.	Click the README.md file.
2.	Click the  pencil icon in the upper right corner of the file view to edit.
3.	In the editor, write a bit about yourself.
4.	Write a commit message that describes your changes.
5.	Click __Commit changes__ button.

These changes will be made to just the README file on your readme-edits branch, so now this branch contains content that’s different from master.

__Open a Pull Request.__ Now that you have changes in a branch off of master, you can open a pull request. Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished. You can even open pull requests in your own repository and merge them yourself. It’s a great way to learn the GitHub flow before working on larger projects.
1.	Click the __Pull Request__ tab, then from the Pull Request page, click the green __New pull request__ button.
2.	In the __Example Comparisons__ box, select the branch you made, readme-edits, to compare with master (the original).
3.	Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit.
4.	When you’re satisfied that these are the changes you want to submit, click the big green Create Pull Request button.
5.	Give your pull request a title and write a brief description of your changes. Then click on the green Create pull request button. 

__Merge your Pull Request__ In this final step, it’s time to bring your changes together – merging your readme-edits branch into the master branch.
1.	Click the green __Merge pull request__ button to merge the changes into master.
2.	Click __Confirm merge__.
3.	Go ahead and delete the branch, since its changes have been incorporated, with the Delete branch button in the purple box.

You did it!! Review the terms you learned
+ repository: a single folder that holds all of the files and subfolders of your project
+	commit: this means, ‘take a snapshot of the current state of my repository’
+	publish: take my folder on my computer, and copy it and its contents to the web as a repository at github.com/myusername/repositoryname
+	sync: update the web repository with the latest commit from my local folder
+	branch: make a copy of my repository with a ‘working name’
+	merge: fold the changes I have made on a branch into another branch
+	fork: to make a copy of someone else’s repo
+	clone: to copy an online repo onto your own computer
+	pull request: to ask the original maker of a repo to ‘pull’ your changes into their master, original, repository
+	push: to move your changes from your computer to the online repo
+	conflict: when two commits describe different changes to the same part of a file




