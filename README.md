# git-workflow-warmup v1.2

The point of this exercise is to "git" accustomed to a feature-branching workflow in git. 


## Getting started

- Get into the team of 3-4 that your instructor assigned you.
- In your group, one person needs to make a new repository on their github, and add the other group members as collaborators.
- While that is happening, someone else needs to create a folder on their machine
    - ```git init```
    - Set up a new remote called 'origin' whose URL points to the repository that was created
    - Create index.html, styles.css, and app.js
    - Once you have permissions to push to the github repo, add, commit, and push.
    - USE GOOD COMMIT MESSAGES
___

## Adding code

- Each person needs to create a feature branch
    - ```git checkout -b branchName```
    - Give your branches names based on the feature you're working on. It's a bit difficult in this scenario, but keep that in mind when creating branches.
- Check the requirements below for what each file needs to contain.
- Your team will split these tasks amongst each other, but files should be edited synchronously.
- When you have completed your tasks push to your branch.
    - Remember the format for git push commands.
    - ```git push remote_name branch_name```
- Once you've pushed, create a pull request from your branch into master.
- Someone else should merge that pull request
___

### Requirements
- The index.html file should have: a header, an image, an unordered list with 5 items, and three empty divs
- The javascript file should target the empty divs, and add whatever you want via the DOM
- The CSS style sheet should style each of these elements that you've created
- Work together to resolve any merge conflicts. Here's a [resource](https://help.github.com/articles/resolving-a-merge-conflict-using-the-command-line/)
