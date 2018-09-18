# git-workflow-warmup v1.1

The point of this exercise is to "git" accustomed to a feature-branching workflow in git. 

Use VS code and the terminal inside of it to deal with merge conflicts in not-vim.

If you have questions about how that works check out the [vs code docs](https://code.visualstudio.com/docs/editor/versioncontrol) 

- Get into a team of 3-4
- Person #1 will create a new repository AND ADD THE OTHER PEOPLE IN THEIR GROUP AS COLLABORATORS
- While person #1 is adding collaborators, person #2 will create folder and ```git init``` inside of it.
- Person #2 will ```git remote add origin URL```
- Person #2 will create an index.html, styles.css, and app.js.
- Person #2 will ```add, commit, and push``` to the repo that person #1 created
- Persons #1,3, and 4 will clone the repo to their computers
- Each person needs to create a feature branch
    - `git checkout -b branchName`
    - Give your branches names based on the feature you're working on
    - Depending on the size of your group, 1 - 2 people should be working on a single file in their respective branches
- The index.html file should have: a header, an image, an unordered list with 5 items, and three empty divs
- The javascript file should target the empty divs, and add whatever you want via the DOM
- The CSS style sheet should style each of these elements that you've created
- Push up to YOUR branch every 7-10 minutes
- Once you've pushed, create a pull request from your branch into master.
- Someone else should merge that pull request
- If you want your local master branch to be updated, ```git checkout master``` and ```git pull origin master```
- DONT FORGET TO COMMIT YOUR WORK BEFORE PULLING
- COMMUNICATE WITH YOUR TEAM
- COMMUNICATION IS V IMPORTANT
