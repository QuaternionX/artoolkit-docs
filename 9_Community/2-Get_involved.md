#Get involved
To get involved there are a few steps you need to do and a few procedures that you should be aware of but happen in the background.

##Check out the source code
1. To contribute to the ARToolKit codebase, no matter if fixing or enhancing a sample app or the ARToolKit codebase itself, you need to have an account on [GitHub](https://github.com/join?source=header-home "Join GitHub").
2. Fork the public https://github.com/artoolkit/artoolkit5.git repository
  - For documentation on how to fork and on how to keep your fork up-to-date with the master see the this documentation https://help.github.com/articles/fork-a-repo/
  - Remember to re-sync against the remote master branch often, keep your changes small, push to remote and generate pull requests often. We want to avoid big bang pull requests. Also `git rebasing` your change set on top of the current master tip is always preferred over merging which may result in merge bubbles.
3. Do your work in whatever branch you want to in your fork.
4. Push to your fork.
5. When your work is done synchronize your branch with the ARToolKit master repository. To do so follow these steps:
	1. Ensure that you have checked out the branch you would like to commit. You can verify this with: `git branch` and switch to your branch with `git checkout [BRANCH_NAME]` if needed.
	2. Get changes from the original repo: `git fetch upstream`
	3. Rebase your changes on top of the latest ARToolKit master changes:  `git rebase upstream/master`
	4. Be prepared that merge conflicts might happen and resolve them.
	5. Commit and push again to your branch in your forked repository.
6. Create a **pull request** to contribute back:
  1. Log-in to you GitHub account 
  2. Select the branch you would like to be merged to the ARToolKit repository
  3. Select the "New pull request" button and ensure that the base is set to **master** and the head is set to _the branch you would like to be merged_.
7. Done, the merge request is now in review state. 

##Review
Once you have published a merge request the ARToolKit-Team receives an email about this request. We will have a look at your changes and (if needed) enter comments to your merge request. You will get notified about those comments by email from GitHub. So please ensure that you check your GitHub emails regularly. If all comments are resolved (if any) your code will be merged into the ARToolKit repository. 
Congratulations you are now a member of the growing ARToolKit-Community. 

**Thanks a lot for your help to grow ARToolKit**
