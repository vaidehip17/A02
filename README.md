# Part 1: Directions on using Visual Studio Code


# Part 2: Glossary for GitHub
- **Branch:**
  A branch is a parallel version of a repository. It is contained within the repository but does not affect the primary branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want, you can merge your branch back into the main branch to publish your changes.
- **Clone:**
  A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
- **Commit:**
  A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep a record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
- **Fetch:**
  When you use `git fetch`, you're adding changes from the remote repository to your local working branch without committing them. Fetching allows you to review changes before committing them to your local branch. 
- **Git:**
  Git is an open-source program for tracking changes in text files. It was written by the author of the Linux operating system and is the core technology that GitHub, the social and user interface, is built on top of.
- **GitHub:**
  GitHub provides a service to an entire organization and uses its own identity when performing its function. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks.
- **Merge:**
  Merging takes the changes from one branch (in the same repository or from a fork) and applies them to another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
- **Merge Conflict:**
  A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
- **Push:**
  To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
- **Pull:**
  Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. 
- **Remote:**
  This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
- **Repository:**
  A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation) and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.
