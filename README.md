# Part 1: Directions on using Visual Studio Code, Git, and GitHub
- Install git at: https://git-scm.com/downloads

- Install GitHub and create an account: https://github.com/join

- Install Visual Studio Code: https://code.visualstudio.com/download 

- Steps to follow:
  1. **Open Visual Studio Code:**
Open Visual Studio Code on your machine.
  2. **Install Git Extension for Visual Studio Code:**
If you haven't installed the Git extension for Visual Studio Code, you can do this from the Extensions view. Click on the Extensions icon in the Activity Bar on the side of the window (or use the keyboard shortcut Ctrl+Shift+X), search for "Git", and install the one provided by Microsoft.
  3. **Open a Project or Create a New One:**
Open the project you want to connect to GitHub or create a new one.
  4. **Initialize a Git Repository:**
If your project is not already a Git repository, you can initialize one. Open the terminal in Visual Studio Code (Ctrl+ backtick) and run the following commands: `git init`
  5. **Stage and Commit Changes:**
Make changes to your code, and use the following commands to stage and commit your changes:
`git add .`
`git commit -m "your commit message here"`
  6. Create a GitHub Repository:
Go to the GitHub website and create a new repository. Follow the instructions on GitHub to create a new repository.
  7. Link Visual Studio Code to GitHub:
In Visual Studio Code, press Ctrl+Shift+P to open the command palette, then type and select "Git: Initialize Repository." Enter the URL of your GitHub repository when prompted.
  8. Push Changes to GitHub:
After linking the repository, you can push your changes to GitHub. Use the following command in the terminal: `git push origin main`
Now, your Visual Studio Code project is connected to GitHub, and you can manage your code through the Git version control system.


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
