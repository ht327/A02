# Tutorial on Git, GitHub, and WebStorm


## Part 1

### Step 1: Install Git
- On Mac, open Terminal and check if Git is installed with:  
  'git --version'
- If not installed, use:  
  'xcode-select --install'
- On Windows, download Git from: [https://git-scm.com/downloads](https://git-scm.com/downloads)

### Step 2: Create a GitHub Account
- Go to [https://github.com](https://github.com) and sign up.

### Step 3: Create a Repository
- After logging in, click the '+' in the top right corner and select 'New repository'.
- Enter a repository name, make it 'Public', and initialize it with a README file.
- Click 'Create repository'.

### Step 4: Clone the Repository
- On the repository page, click the 'Code' button and copy the HTTPS link.
- Open Terminal (or Command Prompt on Windows) and type:
  'git clone [repository URL]'
- This will create a local copy of the repository on your computer.

### Step 5: Open the Repository in an Editor (WebStorm Example)
- Open WebStorm (or another editor).https://www.jetbrains.com/help/webstorm/meet-webstorm.html
- Choose 'File → Open Project' and select the repository folder.
- Go to 'Preferences → Version Control → Git' and make sure Git is recognized.

### Step 6: Make Changes
- Edit files in your project (for example, update the README.md).
- Save your changes.

### Step 7: Commit and Push
- A 'Commit' records your changes locally.
- A 'Push' uploads your commits to GitHub.
- In WebStorm:
    - Click 'Commit', add a commit message, then select 'Commit and Push'.
- After pushing, your changes will be visible on GitHub.

### Step 8: Pull Updates
- If someone else made changes, use 'Pull' to bring the latest updates from GitHub to your local repository.
- This keeps your project in sync with the remote version.


## Part 2: Glossary

- **Branch**: A separate line of development in a repository.
- **Clone**: A copy of a remote repository stored on your local computer.
- **Commit**: A snapshot of changes saved in the local repository.
- **Fetch**: Downloads changes from the remote repository without merging them.
- **GIT**: A distributed version control system for tracking changes in files.
- **Github**: A cloud-based hosting service for Git repositories that supports collaboration.
- **Merge**: Combines changes from one branch into another.
- **Merge Conflict**: When Git cannot automatically merge changes because of overlapping edits.
- **Push**: Uploads commits from the local repository to the remote repository.
- **Pull**: Fetches changes from a remote repository and merges them into the local branch.
- **Remote**: A version of the repository stored on a server, such as GitHub.
- **Repository**: A storage location for project files and their entire version history.

---

## References
1. GitHub Docs: [https://docs.github.com](https://docs.github.com)
2. JetBrains. *Using Git in WebStorm*: [https://www.jetbrains.com/help/webstorm/using-git-integration.html](https://www.jetbrains.com/help/webstorm/using-git-integration.html)
3. Hendela, A. H. (2025). *Introduction to GitHub and WebStorm* (Course Slides). 
4. https://qiita.com/shinshingodmt/items/637cf9e5c6660509c460#:~:text=%E5%AE%8C%E5%85%A8%E5%88%9D%E5%BF%83%E8%80%85%E5%90%91%E3%81%91Git%E7%94%A8%E8%AA%9E%E9%9B%86%20%23GitHub%20%2D%20Qiita
