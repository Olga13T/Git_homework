## Content of Homework

* Create 4 branch
* Create conflict
* Use merge


Repository

…or create a new repository on the command line

echo "# Git_homework" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Olga13T/Git_homework.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/Olga13T/Git_homework.git
git branch -M main
git push -u origin main

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

About pull requests:

Pull requests help you collaborate on code with other people. 
As pull requests are created, they’ll appear here in a searchable and filterable list. 
To get started, you should create a pull request.

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.
 Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.
 You can create pull requests on GitHub.com, with GitHub Desktop, in Codespaces, on GitHub Mobile, and when using GitHub CLI.

After initializing a pull request, you'll see a review page that shows a high-level overview of the changes between your branch (the compare branch) and the repository's base branch. You can add a summary of the proposed changes, review the changes made by commits, add labels, milestones, and assignees, and @mention individual contributors or teams. For more information, see "Creating a pull request."

Once you've created a pull request, you can push commits from your topic branch to add them to your existing pull request. These commits will appear in chronological order within your pull request and the changes will be visible in the "Files changed" tab.

Other contributors can review your proposed changes, add review comments, contribute to the pull request discussion, and even add commits to the pull request. By default, in public repositories, any user can submit reviews that approve or request changes to a pull request. Organization owners and repository admins can limit who is able to give approving pull request reviews or request changes. For more information, see "Managing pull request reviews in your organization" and "Managing pull request reviews in your repository."

You can see information about the branch's current deployment status and past deployment activity on the "Conversation" tab. For more information, see "Viewing deployment activity for a repository."

After you're happy with the proposed changes, you can merge the pull request. If you're working in a shared repository model, you create a pull request and you, or someone else, will merge your changes from your feature branch into the base branch you specify in your pull request. For more information, see "Merging a pull request."

If status checks are required for a repository, the required status checks must pass before you can merge your branch into the protected branch. For more information, see "About protected branches."

You can link a pull request to an issue to show that a fix is in progress and to automatically close the issue when someone merges the pull request. For more information, see "Linking a pull request to an issue."


