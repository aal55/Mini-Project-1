# Gitflow and Git Commands and Terminology

### What is Gitflow?

Gitflow is a branching model for Git. It allows for parallel development, collaboration, release staging area, and support for emergency fixes. 

##### Parallel Development:
Gitflow makes parallel development really easy by isolating new work from finished work. New work is done in feature branches, and is only merged back into main body of code when the creator is happy with the code and thinks its ready for release. 

##### Collaboration:
Feature branches make it easier for developers to collaborate on the same feature and easily see what other collaborators are doing, becasue changes that are made are only the ones to get the feature working.

### Terminology:

Repository: This is your project. It contains all the files and the changes made.

Clone: A copy of the repository that you can download onto your computer.

Fork: A copy of a repository in which a contributor can make changes of their own without messing with the original project.

Branch: It is a duplicate of the original repository which someone can make changes to without affecting the original repository.

Commit: Acts as a save button to track who made changes to what and where in your repository.

Merge: Usually done using a pull request, you can take changes that were made to a secondary branch and combine it to the original repository.

Checkout: The git checkout command lets you navigate between the branches created by git branch.

Push: A command used to upload local repository content to a remote repository.

Pull: A command used to fethc and download repository content from a remote repository to a local repository.

Remote Add: Used to add a remote to a repo, which is a common repository that all team members use to exchange their changes.

Status: A status check lets you know if your commits meet the conditions set for the repository you're contributing to.

Master Branch: The branch where all changes made eventually get merged back into.
