# torch

1. Prepare environment
   1. Install Git.
      - Use bash terminal.
      - Install Git for Windows.
        Download the executable installer for Git [here](https://git-scm.com/download/win).
      - Install Git for MacOS.
        - Install Homebrew running the command:
          ```
          /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)
          ```
        - Install Git running the command: `brew install git`
        - Verify your Git version running the command in the bash terminal: `git --version`
   5. Setup global Git configuration.
      Run the commands in bash terminal:
        ```
        git config --global user.name "Your Name"
        git config --global user.email alex@live.com
        git config --global --list
        ```
   6. Additional resources.
      - [Github](https://github.com/)
      - [Atlassian](https://www.atlassian.com/git/tutorials/git-bash)
      - [Homebrew](https://brew.sh/)
      - [MacOS Terminal](https://lifehacker.com/launch-an-os-x-terminal-window-from-a-specific-folder-1466745514)

2. Initializing a Git repository
   1. Create a folder for the project.
   2. Open a terminal inside this folder and run the command: `git init`
   3. Check the repository running: `git status`
   4. Useful Git commands:
      ```
      git status
      git add <filename>
      git add .
      git commit -m "Commit message"
      ```
      Verify and checkout to specific commit:
      ```
      git log
      git log --oneline
      git checkout <commit number>
      git checkout <commit number> <filename>
      ```
      Reset staging area to the last commit: `git reset`
      Discard changes of a specific file and checkout to previous version:
      ```
      git reset HEAD <filename>
      git checkout -- <filename>
      ```
   5. Additional resources:
      - [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
      - [Git Simple Guide](http://rogerdudler.github.io/git-guide/)
      - [Git Cheatsheet](https://gist.github.com/hofmannsven/6814451)
      - [Git & VS Code Integration](https://www.digitalocean.com/community/tutorials/how-to-use-git-integration-in-visual-studio-code)
      - [Git Concepts & Workflow](https://livecodestream.dev/post/git-concepts-and-workflow-for-beginners/)
      - [Understanding Git](https://livecodestream.dev/post/git-concepts-and-workflow-for-beginners/)

3. Install Node & NPM
   1. Prerequisite: Make sure you have installed Git on your machine before you install Node.js.
   2. 