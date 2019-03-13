
Exercise: Contributing to an open project using GitHub (the countries exercise)

1. Navigate to the repository: https://github.com/mleverance/2019-03-18-uark-git_collab
2. Click on the Fork button at the top right of the screen to make your own copy. You may be asked to choose where to fork (copy) the repository. Fork it into your own GitHub account. 
3. In your fork of the project, create a new branch. Pull down the Branch indicator and start typing to create a new branch. Name the branch for the change you intend to make, e.g.: edit-countryname (avoid spaces in your branch names!).
4. In your fork, on your new branch, make your intended edit(s). This is a good chance to practice Markdown. Before you commit, you can preview how the file will look by clicking the Preview tab over the file.
5. When you have finished your edits, commit (save) your changes. Be sure to write a good commit message.
6. Ask for the owner of the project to incorporate your changes into the project files by creating a pull request. This slightly confusing terminology basically means you REQUEST that the owner of the original source PULL your changes into their version. Follow these steps:
   - Go back to the Code tab of your forked repository
   - Confirm that you are using the branch that contains your edits. If the Branch indicator says `master` pull it down and change it.
   - Click New Pull Request right beside the branch indicator.
   - Compare the two repositories:
     - Base fork: the original project you forked (in this exercise, kulibraries/2019-01-16-gpn_collaboration)
     - Base: the branch of the base fork (in this exercise, master)
     - Head fork: YOUR fork (copy) of the project
     - Compare: name of branch (in this exercise, should be the name of your new branch, e.g.: edit-countryname)
   - GitHub will indicate whether there are conflicts (there shouldn't be for this exercise). If there are no conflicts, you will see the green Create Pull Request button.
   - Click Create Pull Request
   - By default, your summary is the same as your commit message. Use the box below to explain the changes you made in more detail. This message should give the project owner a good idea of what changes you made and why.
   - Click the green Create Pull Request button at the bottom
7. GitHub will notify you if your pull request is accepted into the project.   

To bring your fork of the repository mleverance/2019-03-18-uark-git_collab up to date with all the pull requests made during the workshop:
1. Go to the Code tab of your fork and switch to the master branch.
2. Find the message below the Branch button, "This branch is __ commits behind mleverance:master" (where __ is a number)
3. Look to the right of this message and find the Pull Request link. Click it.
4. GitHub will likely say "There isn't anything to compare" - this is because GitHub is not comparing the repositories in a way that shows the changes.
5. Under that GitHub message, click the "switching the base" link. This does the following:
   - Changes base fork to your fork of the repository
   - Keeps master as the branch
   - Changes head fork to mleverance/2019-03-18-uark-git_collab
   - Keeps master as the branch
   - As a summary, we are telling GitHub that the repository with the most recent changes is mleverance/2019-03-18-uark-git_collab, and that we want to bring those changes into our fork.
6. GitHub should tell you that these branches can be automatically merged.
7. Click Create Pull Request.
8. Write your pull request message - this is essentially a commit message with a different label.
9. Click Create pull request.
10. You will land in the Pull Requests tab. Scroll down through all the commits that were added to the repository. At the bottom, find the green button "Merge pull request"
11. Add more comments if you like, or just click "Merge pull request".
12. Click "Confirm merge"
13. Go back to your Code tab to see changes to the repository that other people made.
