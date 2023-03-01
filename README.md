# Phillipe Barreto
## Part 1: Directions on Using Webstorm
1. Install Webstorm and gain a license at https://www.jetbrains.com/community/education/#students
2. Install Git if needed, download at https://git-scm.com/downloads
3. Create a Github account at https://github.com/join
4. Connect Github to Webstorm: Go to system preferences in Webstorm and select Version control Git, then enter the path to git.exe if needed
5. Add Github password to Webstorm: Again go to system preferences, then scroll to System Settings -> Passwords
6. Create a Repository on Github, there will be a + symbol on the top right corner, then choose Create new Repository
7. Once set up, crease a readme file after setting the repository to public
8. Copy(clone) the repository into Webstorm through VCS on project page

### Steps to add files to Git
1. Add information to a file, possibly create a new file
2. Click "Add" on the Add to Git dialog box
3. Commit any changes made. Be sure to add a message
4. Push Changes to the remote repository
5. The new files/information is now on Github!




## Part 2: Glossary
1. **Branch**- A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
2. **Clone**- A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
3. **Commit**- A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
4. **Fetch**- When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.
5. **GIT**- Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
6. **Github**- An Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.
7. **Merge**- Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
8. **Merge Conflict**- A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
9. **Push**- To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
10. **Pull**- Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.
11. **Remote**- This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
12. **Repository**- A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.


### Sources Used:
1. Github Glossary- https://docs.github.com/en/get-started/quickstart/github-glossary
